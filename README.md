# Clasificación de Calidad de Vino con Regresión Logística (PyTorch)

Este proyecto implementa un modelo de **regresión logística en PyTorch** para clasificar la calidad del vino tinto como **BUENA o MALA**, basado en propiedades físico-químicas.

## Reporte completo

El análisis detallado, metodología y resultados se encuentran en el siguiente documento:

`report/informe.pdf`

## Contenido del proyecto

* Análisis exploratorio de datos (EDA)
* Manejo de outliers mediante winzorización
* Selección de características (Pearson + Información Mutua)
* Implementación de regresión logística en PyTorch
* Evaluación con múltiples métricas (Accuracy, F1, AUC, etc.)
* Comparación de 10 experimentos con distintos hiperparámetros

## Resultados principales

* Modelo final: Experimento 9
* AUC (test): **0.8277**
* F1-Score: **0.7650**
* Sin evidencia de overfitting

## Cómo ejecutar

```bash
pip install -r requirements.txt
jupyter notebook
```

## Dataset

Wine Quality Dataset (Kaggle):
https://www.kaggle.com/datasets/yasserh/wine-quality-dataset

## Tecnologías

* Python
* PyTorch
* Pandas / NumPy
* Matplotlib / Seaborn
* Scikit-learn
