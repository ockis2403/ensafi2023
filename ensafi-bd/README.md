# Construcción de la base de datos ENSAFI 2023

Este directorio contiene los archivos y materiales utilizados para la construcción de una base de datos relacional a partir de los microdatos originales de la Encuesta Nacional sobre Salud Financiera (ENSAFI) 2023, publicada por el INEGI.

El objetivo de esta base de datos es facilitar la consulta, integración y análisis de la información de la encuesta, particularmente para su uso posterior en ejercicios de visualización de datos.

## Fuente de la información

Los microdatos, catálogos y documentación utilizados en este proyecto fueron descargados directamente del sitio oficial del INEGI:

- Encuesta Nacional sobre Salud Financiera (ENSAFI) 2023  
  https://www.inegi.org.mx/programas/ensafi/2023/#microdatos

Adicionalmente, se utilizó el Catálogo Único de Claves de Áreas Geoestadísticas Estatales, Municipales y Localidades (AGEEML) para la información geográfica.

## Proceso general de construcción

El proceso seguido para construir la base de datos fue el siguiente:

1. **Descarga de microdatos**  
   Se descargaron los archivos CSV originales de la ENSAFI 2023, correspondientes a las distintas secciones de la encuesta.

2. **Descarga de catálogos y documentación**  
   Se obtuvieron los catálogos de variables, el cuestionario de la encuesta y documentación complementaria necesaria para la correcta interpretación y decodificación de las respuestas.

3. **Organización de archivos**  
   Los microdatos, catálogos y documentos se organizaron en carpetas separadas para facilitar su consulta y mantenimiento.

4. **Diseño del modelo de datos (ERD)**  
   A partir de la estructura de los archivos y las claves de identificación proporcionadas por el INEGI, se diseñó un diagrama entidad–relación (ERD) que representa la relación entre vivienda, hogar, sociodemograficas de las personas y cuestionario a la persona seleccionada.

5. **Creación de la base de datos**  
   Se elaboraron scripts SQL para la creación de la base de datos y sus tablas en PostgreSQL, respetando las relaciones y dependencias entre los distintos conjuntos de datos.

6. **Preparación de los archivos CSV**  
   Los archivos CSV fueron revisados y preparados para su carga, manteniendo la estructura original de los datos sin modificar su contenido.

7. **Carga de datos**  
   Los CSV se cargaron en la base de datos siguiendo el orden de dependencia definido por el modelo relacional.

8. **Carga de catálogos seleccionados**  
   Se cargaron catálogos específicos que permiten decodificar y comprender las variables utilizadas en los análisis posteriores.

9. **Validación del modelo**  
   El modelo entidad–relación fue revisado y validado dentro de pgAdmin para asegurar la correcta relación entre tablas y la integridad de los datos.



