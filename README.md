# Predicción de Default en Préstamos: Lending Club 

Este proyecto constituye el **Proyecto Integrador de Aprendizaje Automático**. El objetivo principal es desarrollar y comparar modelos de clasificación supervisada para predecir el riesgo de impago (default) utilizando el histórico de préstamos de la plataforma Lending Club (2007–2020).

## Objetivo del Proyecto

Construir un modelo de clasificación supervisada para predecir si un préstamo emitido por la plataforma Lending Club resultará en default (1) o será pagado completamente (0). 
El objetivo es comparar el desempeño de los modelos construidos con scikit-learn y PySpark, además de aplicar LIME para interpretar predicciones.

- **Escalabilidad**: Implementación y comparación de modelos usando Scikit-learn (entorno local/single-core) vs. PySpark (entorno distribuido/big data).
- **Rendimiento**: Evaluación de métricas de clasificación para medir la precisión y robustez de las predicciones.
- **Interpretabilidad**: Uso de LIME (Local Interpretable Model-agnostic Explanations) para "abrir la caja negra" del modelo y entender por qué se tomó una decisión específica sobre un crédito.

## Dataset

- **Nombre**: Lending Club Loan Data (2007–2020)
- **Fuente**: [Kaggle Dataset](https://www.kaggle.com/datasets/wordsforthewise/lending-club)
- **Volumen**: +1.3 millones de registros.

**Características clave:**
- **Socioeconómicas**: Ingresos anuales, situación laboral, propiedad de vivienda.
- **Financieras**: Monto del préstamo, tasa de interés, cuota mensual.
- **Historial Crediticio**: Consultas previas, morosidad, ratio de deuda/ingreso (DTI).

## Herramientas

| Herramienta       | Uso Principal                                           |
|-------------------|---------------------------------------------------------|
| Scikit-learn      | Modelado para conjuntos de datos manejables en memoria. |
| PySpark           | Procesamiento distribuido y MLlib para el manejo del dataset completo. |
| LIME              | Explicabilidad local de las predicciones.               |


## Instalación y Uso

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/lending-club-ml.git
   cd lending-club-ml
   pip install -r requirements.txt


**Curso:**  Machine Learning — NRC 1627 
**Docente:** Lihki Rubio
**Integrantes:** Luis Cabarcas · Natalia Frias · Luis Cantillo 