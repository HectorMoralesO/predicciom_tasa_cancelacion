## Predicción de la Tasa de Cancelación de Clientes de Telecomunicaciones

### Introducción

Este proyecto tiene como objetivo desarrollar un modelo de predicción para identificar a los clientes de Interconnect que tienen mayor probabilidad de cancelar su servicio. Al predecir el *churn*, la empresa podrá implementar estrategias de retención proactivas y mejorar la satisfacción del cliente.


### Metodología

* **Carga y Exploración de Datos:** Carga de los datos, análisis descriptivo, visualización y detección de anomalías.
* **Preprocesamiento de Datos:** Manejo de valores faltantes, codificación de variables categóricas y escalado de variables numéricas.
* **Modelado:** Selección de algoritmos (Regresión Logística, Random Forest, XGBoost), entrenamiento y evaluación de modelos.
* **Selección del Mejor Modelo:** Comparación de modelos basados en métricas y elección del modelo óptimo.

### Resultados y Conclusiones

El modelo de **Regresión Logística** se seleccionó como el modelo final debido a su **excelente rendimiento** (AUC-ROC de 0.95 en el conjunto de prueba) y su **interpretabilidad**. A pesar de que el modelo LightGBM obtuvo un mejor rendimiento en el conjunto de entrenamiento, se optó por la Regresión Logística debido a su menor riesgo de sobreajuste y a su capacidad para proporcionar una explicación clara de los factores que influyen en la predicción.
