# Backlog
## Historias de arquitectura

| Código    | Descripción                                                                                                                                                                                                                                                                                                                                        | Atributo de calidad  |
|-----------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------|
| HU-LAT-1  | Como cliente, cuando seleccione la opción de búsqueda de parqueaderos dado que el sistema opera normalmente quiero ver los sitios de parqueo disponibles más cercanos para poder seleccionar uno. Esto debe suceder en menos de 5 segundos.                                                                                                        | Latencia             |
| HU-LAT-2  | Como cliente, cuando seleccione la opción de realizar pago de fracción dado que el sistema opera normalmente quiero ver el monto a pagar y los minutos utilizados en pantalla para saber cuánto debo pagar. Esto debe suceder en menos de 2 segundos.                                                                                              | Latencia             |
| HU-LAT-3  | Como cliente corporativo, cuando seleccione la opción dashboard dado que el sistema opera normalmente quiero ver el mapa de mi parqueadero para poder organizar los espacios disponibles. Esto debe suceder en menos de 2 segundos.                                                                                                                | Latencia             |
| HU-LAT-4  | Como cliente, cuando seleccione la opción de registro dado que el sistema opera en hora pico quiero acceder a la pantalla de registro para registrarme en la aplicación. Esto debe suceder en menos de 1 segundo.                                                                                                                                  | Latencia             |
| HU-LAT-5  | Como cliente, cuando seleccione la opción de login dado que el sistema opera normalmente quiero poder ingresar mi usuario y clave para poder ingresar al sistema. Esto debe suceder en menos de 2 segundos.                                                                                                                                        | Latencia             |
| HU-ESC-1  | Como oferente del sistema, quiero almacenar el histórico de los usuarios que han usado mis espacios de parqueo durante un año, para que en caso de un reclamo tenga una evidencia ante cualquier novedad.                                                                                                                                          | Escalabilidad        |
| HU-ESC-2  | Como usuario del sistema, quiero almacenar el histórico de los parqueaderos que he usado durante un año, para poder consultarlos cuando lo desee.                                                                                                                                                                                                  | Escalabilidad        |
| HU-ESC-3  | Como oferente del sistema, quiero almacenar las fotos de mis espacios parqueo, para que los usuarios puedan verlo y decidir si mi espacio les agrada, para que conozcan el espacio que se está ofreciendo.                                                                                                                                         | Escalabilidad        |
| HU-ESC-4  | Como usuarios del sistema, quiero que el sistema responda a todas las solicitudes cuando hay una alta demanda de usuarios, para que el sistema esté disponible en todo momento.                                                                                                                                                                    | Escalabilidad        |
| HU-ESC-5  | Como administrador de la plataforma, quiero almacenar permanente mente la información de mis (Usuarios y Oferentes), para tener un registro y control de todos los actores del sistema.                                                                                                                                                            | Escalabilidad        |
| HU-SEG-1  | Como CTO de NIDOO cuando un atacante externo intente acceder o modificar los datos almacenados en el sistema dado que está funcionando normalmente quiero que se bloquee el acceso no autorizado. Esto debe suceder el 99.99% de las veces.                                                                                                        | Seguridad            |
| HU-SEG-2  | Como usuario del sistema cuando haga login con mis datos en la aplicación dado que está funcionando normalmente quiero ingresar al sistema luego de la verificación de los datos. Esto debe suceder el 99.99% de las veces.                                                                                                                        | Seguridad            |
| HU-SEG-3  | Como usuario propietario de automóvil cuando ingrese al parqueadero con un código de entrada dado que está funcionando normalmente quiero poder ingresar al parqueadero y parquear mi carro siempre que sea un código valido y activo para el parqueadero en cuestión Esto debe suceder el 99.9% de las veces                                      | Seguridad            |
| HU-SEG-4  | Como usuario propietario de automóvil cuando quiera pagar la mensualidad en la aplicación dado que está funcionando normalmente quiero que se documente correctamente y se verifique que la transacción esté aprobada. Esto debe suceder en un plazo máximo de 1 día.                                                                              | Seguridad            |
| HU-SEG-5  | Como usuario propietario de automóvil cuando quiera pagar la tarifa por minutos en la aplicación dado que está funcionando normalmente quiero que se documente correctamente y se verifique que la transacción esté aprobada. Esto debe suceder en un plazo máximo de 15 minutos.                                                                  | Seguridad            |
| HU-DIS-1  | Como usuario con un automóvil, cuando envíe la petición de reserva de un parqueadero dado que se envía desde un dispositivo móvil en condiciones normales de operación, quiero ver la reserva se realice satisfactoriamente. Esto debe suceder el 99,99% de las veces.                                                                             | Disponibilidad       |
| HU-DIS-2  | Como usuario con automóvil, cuando envíe la petición de verificación o consulta de una reserva, dado que se realiza desde un dispositivo móvil en condiciones normales de operación, deseo que la verificación o consulta (Si hay reserva / No hay reserva) se realice satisfactoriamente. Esto debe suceder el 99,99 % de las veces.              | Disponibilidad       |
| HU-DIS-3  | Como usuario con automóvil, cuando envíe la petición de verificación o consulta de una reserva, dado que se realiza desde un computador en condiciones normales de operación, deseo que la verificación o consulta (Si hay reserva / No hay reserva) se realice satisfactoriamente. Esto debe suceder el 99,99 % de las veces.                     | Disponibilidad       |
| HU-DIS-4  | Como persona encargada del parqueadero, cuando envíe la petición de verificación o consulta de una reserva, dado que se realiza desde un dispositivo móvil en condiciones normales de operación, deseo que la verificación o consulta (Si hay reserva / No hay reserva) se realice satisfactoriamente. Esto debe suceder el 99,99 % de las veces.  | Disponibilidad       |
| HU-DIS-5  | Como persona encargada del parqueadero, cuando envíe la petición de verificación o consulta de una reserva, dado que se realiza desde un computador en condiciones normales de operación, deseo que la verificación o consulta (Si hay reserva / No hay reserva) se realice satisfactoriamente. Esto debe suceder el 99,99 % de las veces.         | Disponibilidad       |




## Stakeholders

| Stakeholder                       | Descripción                                                                      |
|-----------------------------------|----------------------------------------------------------------------------------|
| Guardia de seguridad.             | Persona encargada del parqueadero                                                |
|                                   |                                                                                  |
| Desarrollador de software         | Empleado de NIDOO quien programa los requerimientos                              |
|                                   |                                                                                  |
| Cliente: propietario de vehículo  | Ocasional, necesita un parqueadero de vez en cuando                              |
|                                   |                                                                                  |
| Cliente: empresa                  | Necesita muchos parqueaderos                                                     |
|                                   |                                                                                  |
| Oferente: empresa                 | Empresas que tienen muchos parqueaderos disponibles                              |
|                                   |                                                                                  |
| Oferente: parqueadero público     | Empresas de servicio que usan la plataforma como canal para ofrecer su servicio  |
|                                   |                                                                                  |
| Oferente: persona natural         | Tiene un parqueadero disponible en su casa                                       |
|                                   |                                                                                  |
| CEO NIDOO                         | Gerente general de NIDOO                                                         |
| CTO NIDOO                         | Director de tecnología de NIDOO                                                  |
|                                   |                                                                                  |
| Financiero NIDOO                  | Valida regulación de cobros, contaduría                                          |
|                                   |                                                                                  |
| Comercial NIDOO                   | Realiza convenios con parqueaderos y empresas para NIDOO                         |



## Relación de historias de usuario 

| Stakeholder                       | Historias de usuario representativas                                                                                              |
|-----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------|
| Guardia de seguridad              | HU-DIS-4, HU-DIS-5, HU-SEG-3                                                                                                      |
| Desarrollador de software         | HU-ESC-5, HU-SEG-1                                                                                                                |
| Cliente: propietario de vehículo  | HU-ESC-4, HU-ESC-2, HU-DIS-1, HU-DIS-2, HU-DIS-3, HU-SEG-2, HU-SEG-3, HU-SEG-4, HE-SEG-5, HU-LAT-1, HU-LAT-2, HU-LAT-5, HU-LAT-4  |
| Cliente: empresa                  | HU-DIS-1, HU-DIS-2, HU-DIS-3, HU-SEG-4, HU-LAT-1, HU-LAT-2, HU-LAT-5, HU-LAT-4                                                    |
| Oferente: empresa                 | HU-ESC-1, HU-DIS-4, HU-DIS-5, HU-ESC-3, HU-SEG-3, HU-LAT-3                                                                        |
| Oferente: parqueadero público     | HU-DIS-4, HU-DIS-5, HU-SEG-3, HU-LAT-3                                                                                            |
| Oferente: persona natural         | HU-DIS-4, HU-DIS-5, HU-SEG-3, HU-LAT-3                                                                                            |
| CEO NIDOO                         | HU-DIS-1                                                                                                                          |
| CTO NIDOO                         | HU-DIS-1, HU-SEG-1, HU-LAT-1                                                                                                      |
| Financiero NIDOO                  | HU-SEG-4, HU-SEG-5                                                                                                                |
| Comercial NIDOO                   | HU-LAT-1, HU-LAT-3                                                                                                                |



## [Inicio](index.md)