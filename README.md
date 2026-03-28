Dashboard en Excel basado en datos de consultas realizadas por pediatras en la Junta Castilla y León - periodo: enero + febrero 2026

El proyecto consiste en un análisis del número de consultas realizadas por pediatras de la Junta de Castilla y León en el año 2026. Está categorizado fundamentalmente por provincia, zona de salud, rango de edad y tipo de atención. La fuente de datos es la siguiente: https://datos.gob.es/es/catalogo/a07002862-actividad-de-pediatria-a-nivel-de-zona-basica-de-salud-2026

El proyecto está realizado íntegramente con la herramienta Microsoft Excel.

La estructura básica seguida es la siguiente:
1.- Importación del ficher en Excel (pestaña "DATOS")
2.- Limpieza de datos: renombrar campos (problema con los acentos), corregir acentos en todos los registros con error de todos los campos salvo "zona basica de salud), columna "sexo" corregidos los campos en blanco por SIN DATO.
3.- El campo EDAD contiene datos de texto (meses) y numérico. Se crea una nueva columna para poder agrupar por rango sin perder información
4.- Realización de tablas dinámicas en la pestaña "Aux" para alimentar big numbers y gráficos del dashboard.
5.- Inclusión en DB de tabla dinámica con el ranking de zonas básicas con mayor número de consultas.

Las principales conclusiones son:
- En CyL los pediatras atiendes una media diaria de casi 5.300 consultas.
- La provincia con mayor número de consultas en el periodo de análisis es Valladolid.
- El rango de edad con mayor número de consultas es el de 7 a 12 años.
- El tipo de atención más utilizado es el presencial.
- De las 5 zonas básicas con mayor número de consultas, 2 están en Valladolid y 1 en Palencia, Burgos y León.

El proyecto queda preparado para ir actualizando el histórico de datos anexando los nuevos periodos en la pestaña "DATOS".

AUTOR: Antonio Linares


