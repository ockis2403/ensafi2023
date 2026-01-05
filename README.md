# ensafi2023

La Encuesta Nacional sobre Salud Financiera (ENSAFI) 2023 se encuentra disponible en múltiples archivos CSV codificados.

https://www.inegi.org.mx/programas/ensafi/2023/#microdatos

Para este proyecto, los datos fueron integrados en una base de datos PostgreSQL diseñada específicamente para el análisis.

El proceso incluyó:
- Limpieza y estandarización de variables
- Integración de cuatro archivos CSV
- Uso de catálogos oficiales de INEGI
- Consultas SQL para generar las tablas analíticas utilizadas en las visualizaciones


# ENSAFI 2023 - Base de datos PostgreSQL

Este repositorio contiene los elementos minimos para crear la base de datos:

- Scripts SQL para creación de tablas
- Archivos CSV limpios listos para importar
- Diagrama entidad relación (ERD)
  
## Orden de carga 

1. entidad
2. municipio
3. tvivienda
4. thogar
5. tsdem
6. tmodulo


# Notebook

- Archivo de Jupyter con codigo de conexión, consultas sql y creación de gráficos.
