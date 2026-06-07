# Análisis de Videos en Tendencia de YouTube mediante API

## Descripción del Proyecto

Este proyecto tiene como objetivo obtener y analizar información sobre los videos más populares de YouTube utilizando la API oficial de YouTube Data v3.

A través de Python y Pandas, se realiza la extracción, transformación y análisis de datos relacionados con videos en tendencia, permitiendo explorar métricas de rendimiento y engagement como visualizaciones, "me gusta" y comentarios.

Este trabajo forma parte de mi portafolio de análisis de datos y busca demostrar competencias en la obtención de datos mediante APIs, procesamiento de información y análisis exploratorio.

---

## Objetivos

* Extraer datos de videos en tendencia utilizando la API de YouTube.
* Construir un conjunto de datos estructurado para su análisis.
* Analizar las métricas principales de los videos más populares.
* Identificar patrones relacionados con visualizaciones e interacción de los usuarios.
* Generar una base de datos preparada para futuras visualizaciones y dashboards.

---

## Herramientas Utilizadas

* Python
* Google Colab
* Pandas
* YouTube Data API v3
* Google Cloud Platform
* GitHub

---

## Fuente de Datos

Los datos se obtienen mediante la API oficial de YouTube Data v3.

La consulta realizada recupera los videos más populares de una región específica junto con información descriptiva y estadísticas asociadas.

Entre los datos obtenidos se encuentran:

* Título del video
* Canal creador
* Categoría
* Fecha de publicación
* Cantidad de visualizaciones
* Cantidad de "me gusta"
* Cantidad de comentarios

---

## Proceso de Trabajo

### 1. Extracción de datos

Se establece conexión con la API de YouTube utilizando una clave de acceso generada desde Google Cloud Platform.

### 2. Transformación de datos

Los datos obtenidos en formato JSON son procesados y convertidos en un DataFrame de Pandas para facilitar su análisis.

### 3. Limpieza de datos

Se realizan conversiones de tipos de datos, validaciones y preparación de las variables numéricas.

### 4. Análisis exploratorio

Se exploran indicadores como:

* Videos con mayor cantidad de visualizaciones.
* Canales con mayor presencia entre los videos populares.
* Relación entre visualizaciones, "me gusta" y comentarios.
* Distribución de métricas de engagement.

---

## Estructura del Repositorio

```text
Top-10-Youtube/
│
├── youtube_top10_analysis.ipynb
├── README.md
└── data/
    └── youtube_trending.csv
```

---

## Principales Aprendizajes

Durante el desarrollo de este proyecto se aplicaron conocimientos relacionados con:

* Consumo de APIs.
* Procesamiento de datos en Python.
* Manipulación de datos con Pandas.
* Análisis exploratorio de datos (EDA).
* Automatización de procesos de extracción de información.
* Documentación y presentación de proyectos de análisis de datos.

---

## Próximos Pasos

Las siguientes etapas del proyecto contemplan:

* Incorporar información de múltiples países.
* Automatizar la actualización de los datos.
* Analizar tendencias por categorías de contenido.
* Construir un dashboard interactivo en Looker Studio.
* Generar comparaciones entre regiones y períodos de tiempo.

---

## Autor

**Noelia**

Analista de Datos

Proyecto desarrollado con fines de aprendizaje, práctica y construcción de portafolio profesional.
