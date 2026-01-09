# ENSAFI 2023 – Visualización de Datos

Este repositorio contiene el trabajo final del **Módulo III: Visualización de Datos**, basado en la **Encuesta Nacional sobre Salud Financiera (ENSAFI) 2023** del INEGI.

El objetivo del proyecto es analizar la relación entre **ingresos, privaciones económicas y estrés emocional**, y comunicar los hallazgos mediante visualizaciones construidas en Python, siguiendo la rúbrica del curso.

---

## Estructura del proyecto

El trabajo se desarrolló en tres etapas:

### 1. Construcción de la base de datos
A partir de los microdatos originales de la ENSAFI, se construyó una base de datos relacional en PostgreSQL.  
Esta etapa incluye los archivos CSV originales, catálogos, scripts SQL y documentación de apoyo.

### 2. Extracción de datos
Se realizaron consultas SQL para generar dos conjuntos de datos, los cuales fueron exportados como archivos CSV y utilizados posteriormente para las visualizaciones.

### 3. Visualización de datos
Con los datos procesados se elaboraron dos visualizaciones principales:
- Gráfico de barras horizontales apiladas al 100%
- Gráfico de líneas múltiples

Ambas visualizaciones incluyen títulos, subtítulos, escalas, anotaciones, fuente y autoría, conforme a la rúbrica del curso.

---

## Reproducibilidad

Los notebooks están preparados para ejecutarse directamente en **Google Colab**, cargando los datos desde este repositorio, sin necesidad de configurar una base de datos local.

---

## Autoría

**Autor:** Oscar Gutiérrez Leal  
**Fuente de datos:** Encuesta Nacional sobre Salud Financiera (ENSAFI) 2023 – INEGI  
**Fecha:** Enero 2026
