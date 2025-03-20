# Predicción del Clima en Australia con Machine Learning

Este proyecto explora el uso de diferentes modelos de **Machine Learning** para predecir el clima en Australia. Se probaron modelos supervisados y no supervisados con el objetivo de comparar su desempeño y entender mejor sus aplicaciones en problemas de clasificación, regresión y segmentación.

## Objetivo
El objetivo de este trabajo es evaluar qué tipo de modelo de aprendizaje automático es más adecuado para predecir el clima en base a un dataset real, utilizando métricas de evaluación específicas para cada tipo de modelo.

## Modelos Utilizados y Resultados
A continuación, se presentan los modelos utilizados y sus respectivas métricas de desempeño:

| # | Modelo | Tipo | Métrica | Resultado |
|---|----------------------------|---------------|-----------------|------------|
| 1 | Logistic Regression | Clasificación | Accuracy | **0.9891** |
| 2 | Decision Tree Classifier | Clasificación | Accuracy | **1.0000** |
| 3 | Random Forest Classifier | Clasificación | Accuracy | **1.0000** |
| 4 | Linear Regression | Regresión | RMSE | **0.3229** |
| 5 | Decision Tree Regressor | Regresión | RMSE | **0.0000** |
| 6 | Random Forest Regressor | Regresión | RMSE | **0.0000** |
| 7 | KMeans | Segmentación | Silhouette Score | **0.2382** |
| 8 | Agglomerative Clustering | Segmentación | Silhouette Score | **0.1990** |
| 9 | DBSCAN | Segmentación | Silhouette Score | **-0.3510** |

## Contenido del Proyecto
- **`dataset/`** → Contiene el dataset del clima en Australia.
- **`notebooks/`** → Contiene los Jupyter Notebooks con la implementación de los modelos.
- **`src/`** → Código fuente con las funciones utilizadas para preprocesamiento y modelado.
- **`README.md`** → Este archivo, con la documentación del proyecto.

## Tecnologías Utilizadas
- Python
- Pandas y NumPy (Manipulación de datos)
- Scikit-learn (Modelos de Machine Learning)
- Matplotlib y Seaborn (Visualización de datos)

## Notas Finales
Este proyecto fue desarrollado como parte del proceso de aprendizaje en **Ingeniería en Informática en Duoc UC**, sirviendo como una introducción a los modelos de Machine Learning y su evaluación. Aunque no es un estudio profundo, se presenta como un punto de partida en mi camino hacia la **Ciencia de Datos**.
