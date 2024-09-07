## Propuesta de Investigación: Tasa de abandono (Churn)
1. #### **Objetivo**:
   Identificar el modelo que mejor se ajuste a los datos y ofrezca la mayor capacidad predictiva para detectar a los clientes con mayor probabilidad de darse de baja (churn) del servicio proporcionado por la empresa.

2. #### **Justificación**:
   Modelos de clasificación óptimos permitirán implementar estrategias de retención más efectivas y reducir significativamente su tasa de abandono, mejorando la retención de clientes y, en consecuencia, sus ingresos y sostenibilidad a largo plazo.

3. #### **Metodología**:
   Se utilizará el conjunto de datos de [Customer Churn Dataset (Kaggle)](https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset). La metodología incluirá:
   
   - **Exploración y preprocesamiento de datos**:
      - Análisis descriptivo
      - Análisis de dispersión y gráficos exploratorios
      - Análisis de correlación
   - **Selección de características y transformación**
      - Basados en el analisis exploratorio se seleccionarán las características más relevantes para el modelo.
      - Se aplicarán técnicas de escalado y transformacion de datos.
   - **Construcción de modelos de machine learning**: Se entrenaran los siguientes modelos de clasificacion:
      - Regresión Logística
      - Árbol de Decisión
      - Árbol de Decisión con optimizacion de hiperparametros
      - Random Forest
      - XGBOOST
      - Red Neuronal
   - **Evaluación del desempeño del modelo**:
      - Sensibilidad (TPR)
      - Especificidad (TNR)
      - Exactitud Balanceada
      - Precisión
      - Recuperación (Recall)
      - F1-score
   - **Conclusiones**
