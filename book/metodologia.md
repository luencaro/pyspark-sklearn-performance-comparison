# Metodologia

## Flujo general

1. Carga y limpieza de datos.
2. Seleccion de variables numericas y categoricas.
3. Split estratificado train/test.
4. Modelado con Random Forest en dos frameworks.
5. Evaluacion con Accuracy, Precision, Recall, F1 y ROC AUC.

## Preprocesamiento

- Imputacion de faltantes con mediana en variables clave.
- Transformaciones sobre variables sesgadas.
- One-Hot Encoding para categoricas.
- Escalado de variables numericas.

## Comparacion de frameworks

Se compara el rendimiento y el tiempo de ejecucion entre `scikit-learn` y `PySpark`, manteniendo la mayor consistencia posible en hiperparametros y metrica final.
