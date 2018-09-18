# Atributos de Calidad
Priorización de los atributos de calidad y de los ASR's


## Priorización de ASRs​
| ​                                      | Disponibilidad​ | Escalabilidad​ | Latencia​ | Seguridad​ |
|----------------------------------------|-----------------|----------------|-----------|------------|
| P1 (Guardia de seguridad)​             | 4​              | 1​             | 2​        | 3​         |
| P2 (Desarrollador de software)​        | 3​              | 2​             | 4​        | 1​         |
| P3 (Cliente: propietario de vehículo)​ | 4​              | 1​             | 3​        | 2​         |
| P4 (Cliente: empresa)​                 | 4​              | 1​             | 3​        | 2​         |
| P5 (Oferente: empresa)​                | 3​              | 1​             | 2​        | 4​         |
| P6 (Oferente: parqueadero público)​    | 3​              | 1​             | 4​        | 2​         |
| P7 (Oferente: persona natural)​        | 2​              | 1​             | 4​        | 3​         |
| P8 (CEO NIDOO)​                        | 2​              | 1​             | 4​        | 3​         |
| P9 (CTO NIDOO)​                        | 1​              | 4​             | 3​        | 2​         |
| P10 (Financiero NIDOO)​                | 2​              | 1​             | 3​        | 4​         |
| P11 (Comercial NIDOO)​                 | 3​              | 1​             | 4​        | 2​         |
| TOTAL​                                 | 31​             | 15​            | 36​       | 28​        |
| Peso (Riesgo)​                         | 3​              | 1​             | 4​        | 2​         |



## Relación de HU con stakeholders​
| stakeholders​                          | Latencia​  4                            | Disponibilidad​ 3             | Seguridad​ 2                            | Escalabilidad​ 1    |
|----------------------------------------|-----------------------------------------|-------------------------------|-----------------------------------------|---------------------|
| P1 (Guardia de seguridad)​             | ​                                       | HU-DIS-4, HU-DIS-5​           | HU-SEG-3​                               | ​                   |
| P2 (Desarrollador de software)​        | ​                                       | ​                             | HU-SEG-1​                               | HU-ESC-5​           |
| P3 (Cliente: propietario de vehículo)​ | HU-LAT-1, HU-LAT-2, HU-LAT-5, HU-LAT-4​ | HU-DIS-1, HU-DIS-2, HU-DIS-3​ | HU-SEG-2, HU-SEG-3, HU-SEG-4, HE-SEG-5​ | HU-ESC-4, HU-ESC-2​ |
| P4 (Cliente: empresa)​                 | HU-LAT-1, HU-LAT-2, HU-LAT-5, HU-LAT-4​ | HU-DIS-1, HU-DIS-2, HU-DIS-3​ | HU-SEG-4​                               | ​                   |
| P5 (Oferente: empresa)​                | HU-LAT-3​                               | HU-DIS-4, HU-DIS-5​           | HU-SEG-3​                               | HU-ESC-1, HU-ESC-3​ |
| P6 (Oferente: parqueadero público)​    | HU-LAT-3​                               | HU-DIS-4, HU-DIS-5​           | HU-SEG-3​                               | ​                   |
| P7 (Oferente: persona natural)​        | HU-LAT-3​                               | HU-DIS-4, HU-DIS-5​           | HU-SEG-3​                               | ​                   |
| P8 (CEO NIDOO)​                        | ​                                       | HU-DIS-1​                     | ​                                       | ​                   |
| P9 (CTO NIDOO)​                        | HU-LAT-1​                               | HU-DIS-1​                     | HU-SEG-1​                               | ​                   |
| P10 (Financiero NIDOO)​                | ​                                       | ​                             | ​                                       | HU-SEG-4, HU-SEG-5​ |
| P11 (Comercial NIDOO)​                 | HU-LAT-1, HU-LAT-3​                     | ​                             | ​                                       | ​                   |
| TOTAL​                                 | 56​                                     | 48​                           | 22​                                     | 7​                  |




## Latencia
| ID ASR​   | Prioridad Stakeholders​ | Prioridad Arquitectos  ​ | decision |
|-----------|-------------------------|--------------------------|----------|
| HU-LAT-1​ | A​                      | M​                       | 2​       |
| HU-LAT-2​ | A​                      | M​                       | 3​       |
| HU-LAT-3​ | M​                      | B​                       | 5​       |
| HU-LAT-4​ | M​                      | B​                       | 4​       |
| HU-LAT-5​ | A​                      | B​                       | 1​       |


## [Inicio](index.md)