Comportamiento de Clientes con Python

Este repositorio contiene el análisis de datos desarrollado durante el Sprint 8, basado en el caso de estudio de NovaRetail+, una plataforma de comercio electrónico con operaciones en Latinoamérica.

El proyecto tiene como propósito identificar qué factores del comportamiento de los clientes están más fuertemente asociados con los ingresos anuales generados, mediante un análisis correlacional de variables relacionadas con la actividad, el consumo y las características de los usuarios.

A través de técnicas estadísticas y herramientas de visualización con Python, se busca identificar relaciones significativas, reconocer posibles correlaciones engañosas y transformar los resultados en recomendaciones útiles para los equipos de Crecimiento y Retención.

📂 Contenido del repositorio

El proyecto utiliza una fuente principal de información:

datasets/novaretail_comportamiento_clientes_2024.csv: Dataset con información del comportamiento de 15,000 clientes de NovaRetail+, incluyendo variables relacionadas con su actividad, características y generación de ingresos.

Descargar dataset

🧠 Objetivo del análisis

Identificar los factores del comportamiento de los clientes que presentan una mayor asociación con los ingresos anuales generados, mediante la aplicación de diferentes técnicas de correlación y análisis estadístico.

🔍 Etapas del análisis

-Exploración de datos: Revisión de dimensiones, tipos de variables, estadísticas descriptivas y calidad de la información.
-Preparación de datos: Validación de variables y preparación de los datos para el análisis estadístico.
-Correlación entre variables numéricas: Evaluación de relaciones lineales y monotónicas mediante diferentes coeficientes de correlación.
-Análisis de variables binarias y numéricas: Identificación de asociaciones entre características de los clientes y sus ingresos anuales.
-Análisis de variables categóricas: Evaluación de asociaciones entre categorías mediante técnicas estadísticas.
-Visualización de resultados: Construcción de scatterplots, heatmaps y gráficos para identificar patrones y relaciones.
-Interpretación de hallazgos: Evaluación de la relevancia de las relaciones encontradas, considerando posibles correlaciones engañosas y limitaciones estadísticas.
-Recomendaciones de negocio: Traducción de los resultados en oportunidades para las estrategias de Crecimiento y Retención.

📘 Cómo reproducir el análisis

Clona o descarga este repositorio.
Abre el notebook S8 Student Version-Project-NovaRetail (2).
Instala las librerías necesarias.
Ejecuta las celdas en orden.
El notebook carga automáticamente el dataset desde /data/ o desde un enlace público, según la configuración del proyecto.

🛠️ Herramientas y tecnologías

-Python: Procesamiento y análisis estadístico.
-Pandas: Exploración, manipulación y preparación de datos.
-NumPy: Operaciones y cálculos numéricos.
-Matplotlib: Visualización de resultados.
-Seaborn: Construcción de heatmaps, scatterplots y gráficos estadísticos.
-Jupyter Notebook: Desarrollo y documentación del análisis.

📈 Resultados del proyecto

Como resultado del análisis se obtiene un reporte de correlación que integra evidencia visual, resultados estadísticos e interpretación de las relaciones identificadas.

El análisis permite reconocer qué variables presentan asociaciones relevantes con los ingresos anuales, así como identificar relaciones entre las características y el comportamiento de los clientes.

Los hallazgos proporcionan información para formular recomendaciones orientadas a fortalecer las estrategias de crecimiento, segmentación y retención de usuarios.

Consideración metodológica: El análisis es de naturaleza exploratoria y correlacional. Las asociaciones identificadas no implican causalidad ni demuestran que una variable provoque cambios en otra.
