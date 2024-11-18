# SEN-Project
## Archivos Json con información acerca del Servicio Eléctrico Nacional en el período del 9 al 22 de octubre

### Datos Extraídos:
- Informacion principal:
    - Fecha
    - Dia
    - URL

- Estimacion:
    - Horario
    - Disponibilidad
    - Demanda Maxima
    - Deficit
    - Pronostico:
        - Afectacion

- Info de los horarios:
    - Mañana:
        - Cantidad de MW para la disponibilidad
        - Demanda prevista para ese horario
        - Totalidad del funcionamiento del SEN
    - Mediodia:
        - Pronostico:
            - Afectacion

- Termoelectricas:
    - Limite en la Generacion Termica
    - Fuera de servicio:
        - Por averias:
            - Nombre de la Unidad
            - Nombre de la CTE
        - Por Mantenimiento:
            - Nombre de la Unidad
            - Nombre de la CTE

- Centrales de Generacion Distribuida:
    - Sin servicio:
            - Cantidad de Centrales de Generacion Distribuida
            - Razon por la que se encuentra sin servicio
            - Cantidad de MW afectados

- Pico:
    - Estimacion:
        - Descripcion de la estimacion
        - Razon por la que estuvieron fuera
        - Cantidad de MW totales

- Maxima afectacion del dia:
    - Cantidad de MW afectados
    - Hora en la que ocurrio
    - Descripcion

- Dia anterior:
    - Descripcion
    - Total de horas en las que se estuvo sin servicio
    - Hora en la que se restablecio
