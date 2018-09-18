# Arquitectura
El desarrollo de este proyecto se basa en una arquitectura de microservicios, la cual permite tener componentes pequeños, simples y desacoplados, lo que a su ves permite tener aplicaciones escalables, flexibles y reutilizables.


### Microservicios con contenedores

* Esta decisión de arquitectura permite construir componentes ligeros que procesen un alto volumen transaccional utilizando tecnologías ligeras.

- Beneficios:
    - Autonomía. Si se cae un micro-servicio no se caen los demás.
    - Desempeño al distribuirse la caga a través de los micro-servicios.
    - Uso de contenedores Docker implementando portabilidad, versionamiento e independencia de proveedores
    - Reutilización de componentes
    - Segregación de responsabilidades, en donde cada componente implementa una funcionalidad específica


## Modelo de contexto
    
**FALTA COMPLETAR. porfa revisen la vista de contexto**


## Modelo de dominio del problema  

**FALTA COMPLETAR.**


## Modelo de Componentes
### Vista componentes nivel 0
La siguiente vista de componentes muestra a un alto nivel cada uno de los microservicios y como se dividen en responsabilidades
- **Presentacion:**
Contiene las aplicaciones web y mobile donde estara todo el front del proyecto estas a traves de servicios REST realizan todas las solicitudes al back.

- **API Gateway:**
    - El componente de API gateway es un recurso del tipo plataforma como servicio PaaS que enlaza las apis implementadas en los microservicios.  
    - El api gateway incluye el balanceador de aplicación como servicio enrutando las peticiones al micro servicio más saludable, teniendo en cuenta el uso 
      de recurso de procesador, peticiones por segundo o por la memoria consumida.

- **Componentes de negocio:**
Representa todos los micro servicios encargados de la ejecucion de los procesos de negocio, cada uno con responabilidades definidas:
    
    - Users: Microservicio encargado del manejo de los usuarios del sistema, como creacion, modificacion, administracion.
    - Administrative: Se encarga de toda la parte administrativa de la aplicacion junto con todo el manejo de reportes y el manejo del Dashboard para la            administracion de parqueaderos.
    - Parking bookin: Este microservicio se encarga del core del negocio como busqueda de parqueaderos, solicitud de parqueo etc.
    - Payments: Micro servicio encargado de toda la parte de pagos dentro del sistema, incluye tambien la comunicacion con componentes de pagos externos.

- **Componentes comunes:**
Estos componentes comprenden todo aquello comun dentro de la aplicacion, como temas de notificaciones, acceso a base de datos y autenticacion.

- **Componentes externos:**
Los componentes externos, son todas aquellas aplicaciones interfaces o componentes que estan fuera de la frontera del sistema pero debe existir una comunicacion ya sea de consumo o exposicion.

![Image](views/NIDOO_Components.png)



### Vista componentes nivel 1
La siguiente vista muestra la estructura de un microservicio, la cual se utiliza un estilo en capas, como se muestra en la imagen a continuación:
Esta vista representa el componente **Parking bookin**

![Image](views/NIDOO_Parking_component_layers.png)


## Modelo de Despliegue
La vista a continuacion muestra el despliegue de los microservicios dentro de contenedores Docker los cuales a su ves se encuentran dentro de instancias EC2 en AWS. 
Las aplicaciones front se comunican a traves de un API Gateway el cual usando un balanceador de carga distribuye las peticiones a cada una de las instancias EC2
![Image](views/vista_despliegue_2.png)


## Explicación Arquitectura
**Debemos hacer el video en youtube para luego incrustarlo como este ejemplo**

<iframe width="560" height="315" src="https://www.youtube.com/embed/PliHAP5m0BE" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>



## [Volver](index.md)