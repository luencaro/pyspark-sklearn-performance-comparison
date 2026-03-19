# Prediccion de Default en Prestamos: Lending Club

Modelo de clasificacion supervisada para predecir riesgo de impago en prestamos de Lending Club, comparando implementaciones en `scikit-learn` y `PySpark`.

## Informacion del Proyecto

| Campo | Valor |
| --- | --- |
| Curso | Machine Learning - NRC 1627 |
| Docente | Lihki Rubio |
| Integrantes | Luis Cabarcas - Natalia Frias - Luis Cantillo |

## Objetivo

Construir un modelo de clasificacion para predecir si un prestamo termina en:

- `0`: Fully Paid
- `1`: Charged Off

El proyecto compara desempeno predictivo y tiempo de computo entre dos enfoques:

- `scikit-learn` en entorno local.
- `PySpark` con pipeline distribuible.

## Dataset

- **Fuente**: [Kaggle - Lending Club Loan Data](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
- **Periodo**: 2007-2020
- **Volumen**: mas de 1.3 millones de registros

## Estructura del Book

La navegacion esta organizada a partir del mismo notebook principal, dividido en capitulos:

1. Preparacion, EDA y preprocesamiento.
2. Modelado con scikit-learn.
3. Modelado con PySpark y comparacion.
4. Interpretabilidad con LIME y conclusion.

```{note}
Cada capitulo del menu lateral proviene del notebook base y conserva su contenido tecnico.
```
