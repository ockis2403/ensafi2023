# Notebooks – ENSAFI 2023

Este directorio contiene los notebooks utilizados en el análisis y
visualización de datos de la Encuesta Nacional sobre Salud Financiera (ENSAFI) 2023.

## Estructura

### Parte A – Extracción de datos (documentación)
**`ensafi_parte_A_extraccion_sql.ipynb`**

Este notebook documenta el proceso de conexión a la base de datos
PostgreSQL y las consultas SQL utilizadas para generar los conjuntos
de datos finales.

- El código está comentado y no está diseñado para ejecutarse.
- Su objetivo es documentar el proceso de construcción de los archivos CSV.
- Las consultas mostradas corresponden a los datos utilizados en las visualizaciones.

### Parte B – Visualización de datos
**`ensafi_parte_B_visualizacion.ipynb`**

Este notebook contiene el flujo completo y ejecutable de:

1. Carga de archivos CSV generados previamente
2. Procesamiento de datos con pandas
3. Construcción de gráficos con matplotlib
4. Exportación de las visualizaciones como imágenes


## Salida

Las imágenes generadas por el notebook de visualización se guardan en
una carpeta del repositorio para facilitar su consulta.
