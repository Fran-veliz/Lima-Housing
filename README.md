# Predicción de Precios de Casas en Lima (ProyectoV2) 🏡📊

¡Bienvenido al repositorio del **ProyectoV2**!

Este proyecto de ciencia de datos se enfoca en el **análisis predictivo de precios de propiedades residenciales en Lima**. Utilizando datos históricos de casas, implementamos un flujo de trabajo de ciencia de datos que incluye **limpieza y preprocesamiento de datos**, **análisis exploratorio**, **segmentación de propiedades mediante clustering (K-Means)** y el desarrollo de **modelos de regresión (Random Forest)** para estimar precios de viviendas. El objetivo es proporcionar una herramienta predictiva que contribuya a entender las dinámicas del mercado inmobiliario limeño y facilite la toma de decisiones.



## 📝 Descripción Detallada del Proyecto

El **ProyectoV2** es una iniciativa de aprendizaje y aplicación práctica en el campo del análisis de datos y el machine learning. Aborda el desafío de predecir los valores de propiedades inmobiliarias en la vibrante ciudad de Lima, Perú. El proyecto se desarrolla siguiendo una metodología estructurada que abarca desde la ingesta de datos hasta la generación de predicciones:

1.  **Ingesta y Fusión de Datos:** Se combinan y consolidan datos de casas de Lima de diferentes años (específicamente 2019 y 2020) para crear un conjunto de datos robusto y más completo para el análisis.
2.  **Preprocesamiento y Limpieza de Datos:** Se realiza una exhaustiva fase de limpieza para manejar valores nulos, estandarizar nombres de columnas y corregir inconsistencias, asegurando la alta calidad de los datos para el modelado.
3.  **Análisis Exploratorio de Datos (EDA):** A través de visualizaciones y estadísticas descriptivas, se exploran las características de las propiedades, las relaciones entre ellas y las distribuciones de los precios, obteniendo insights valiosos sobre el mercado.
4.  **Agrupación (Clustering) de Propiedades:** Se aplica el algoritmo K-Means para segmentar las propiedades en grupos (clústeres) basados en sus características intrínsecas. Este enfoque permite entrenar modelos de predicción más específicos y precisos para cada tipo de propiedad.
5.  **Modelado Predictivo:** Se desarrollan y entrenan modelos de regresión, específicamente utilizando el algoritmo Random Forest Regressor. Estos modelos aprenden de los datos históricos para establecer relaciones entre las características de las casas y sus precios.
6.  **Generación de Predicciones:** Finalmente, los modelos entrenados se utilizan para predecir los precios de nuevas propiedades, proporcionando estimaciones valiosas para el mercado inmobiliario.



## ✨ Características Principales

* **Fusión de Datos Múltiples:** Combina y procesa datos de `casas_2019.csv` y `casas_2020.csv`.
* **Limpieza de Datos Robusta:** Manejo automatizado de valores ausentes y estandarización de características.
* **Segmentación Inteligente:** Implementación de K-Means para agrupar propiedades y optimizar la predicción.
* **Modelo de Regresión Avanzado:** Uso de Random Forest Regressor para predicciones precisas de precios.
* **Visualizaciones Informativas:** Gráficos que ayudan a entender las distribuciones de datos y correlaciones.
* **Fácilmente Replicable:** El proyecto está contenido en un cuaderno de Colab, facilitando su ejecución.

## 🚀 Tecnologías y Librerías Utilizadas

El proyecto está desarrollado en **Python 3** y hace uso de las siguientes librerías principales:

* **Pandas:** Para la manipulación y análisis eficiente de conjuntos de datos.
* **NumPy:** Para operaciones numéricas fundamentales.
* **Scikit-learn:** Para una amplia gama de tareas de Machine Learning, incluyendo:
    * `StandardScaler` para el escalado de características.
    * `train_test_split` para la división de datos.
    * `KMeans` para el algoritmo de clustering.
    * `RandomForestRegressor` para el modelado de regresión.
    * `silhouette_score` para la evaluación de clústeres.
* **Matplotlib:** Para la creación de gráficos estáticos y personalizables.
* **Seaborn:** Basado en Matplotlib, para generar visualizaciones estadísticas más atractivas.
* **Google Colab:** Entorno de desarrollo interactivo (cuaderno Jupyter) donde se ejecutó y desarrolló el proyecto.

## 📋 Requisitos (requirements.txt)

¡Perfecto! Entiendo que quieres que junte toda la información relevante que hemos discutido sobre tu proyecto de análisis de datos y la presente de manera coherente en un solo bloque de texto Markdown, como un README.md completo.

Aquí tienes el README.md final, integrando la descripción, características, tecnologías, requisitos, instrucciones de uso, estructura de archivos y secciones de contacto/licencia. He utilizado el nombre de repositorio Prediccion-Precios-Casas-Lima como ejemplo, pero recuerda ajustarlo a tu elección final.



