# TFM_dataset_stroke
“Pipeline de aprendizaje automático en R para la predicción de ictus: EDA, preprocesamiento y modelado”

Este repositorio contiene el análisis desarrollado en el Trabajo de Fin de Máster (TFM), cuyo objetivo es construir modelos de aprendizaje automático para la predicción del riesgo de ictus a partir de datos clínicos.

## Estructura del repositorio

* `TFM_stroke.Rmd`: script principal con todo el flujo de análisis
* `data/`: dataset utilizado (`stroke.csv`)
* `figures/`: gráficos generados durante el análisis
* `tables/`: tablas de resultados
* `README.md`: descripción del proyecto

## Metodología

El análisis sigue las siguientes etapas:

1. Análisis exploratorio de datos (EDA)
2. Preprocesamiento:
3. Modelado con distintos algoritmos de aprendizaje automático
4. Validación externa
5. Selección del modelo final

## Reproducibilidad

Para ejecutar el análisis:

1. Clonar o descargar el repositorio desde GitHub
2. En caso de descarga en formato ZIP, descomprimir el contenido antes de abrirlo en RStudio
3. Abrir el archivo `TFM_stroke.Rmd`
4. Ejecutar los chunks en orden

El dataset se encuentra en `data/stroke.csv` y se carga mediante rutas relativas, por lo que es necesario mantener la estructura de carpetas del repositorio.

## Requisitos

* R
* Paquetes principales:

  * tidyverse
  * tidymodels
  * ranger
  * themis
  * kableExtra
  * DT

## Autor
Alejandro Baratas Álvarez

