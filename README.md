# Desafio_TelecomeX_Part2_Final_Alura_Oracle_Latam
Aquí finaliza la travesía por ahora de la capacitación de Alura Latam con este último desafío, que es la culminación de todas las habilidades adquiridas previamente.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📊 Predicción de Cancelación de Clientes — TelecomX
📌 Descripción

Este proyecto forma parte del desafío TelecomX (Parte 2) y tiene como objetivo predecir la cancelación de clientes (Churn) en una empresa de telecomunicaciones.

A partir de un dataset con información demográfica, de contratación y de facturación de clientes, se realizaron procesos de exploración, limpieza, balanceo, modelado y evaluación, para finalmente identificar los principales factores que influyen en la pérdida de clientes y proponer estrategias de retención.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📂 Estructura del proyecto

Dataset telecomx_codificado.csv: información de clientes, incluyendo datos demográficos, servicios contratados y gastos.

Desafio_TelecomX_Parte2_Final.ipynb: notebook principal con todo el flujo de trabajo.

README.md: descripción general del proyecto.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🔍 Metodología

Análisis exploratorio de datos (EDA)

Distribución de variables categóricas y numéricas.

Identificación de patrones de churn en función de servicios, facturación y permanencia.

Visualizaciones: histogramas, boxplots, scatterplots, heatmaps.

Preprocesamiento de datos

Conversión de variables categóricas a numéricas (One-Hot Encoding).

Imputación de valores faltantes con media (numéricas) y moda (categóricas).

Balanceo de clases mediante SMOTE para corregir el desbalance entre clientes que cancelaron y los que no.

División de datos

70% entrenamiento / 30% prueba.

Modelado

Modelo sin normalización: Árbol de Decisión.

Modelo con normalización: Regresión Logística.

Comparación de métricas de rendimiento: Accuracy, Precision, Recall, F1-score y Matriz de Confusión.

Evaluación y comparación de modelos

Árbol de Decisión: mejor Accuracy y F1-score.

Regresión Logística: mejor Recall.

Análisis de posibles casos de overfitting y underfitting.

Interpretación de resultados

Análisis de la importancia de las variables.

Identificación de factores clave que influyen en la cancelación.

Propuesta de estrategias de retención.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
📈 Resultados principales

Factores más relevantes para el Churn:

Tiempo de permanencia (tenure).

Tipo de contrato (Contract).

Servicio de internet de fibra óptica (InternetService_Fiber optic).

Gastos mensuales (Charges.Monthly).

Soporte técnico (TechSupport_No).

Rendimiento de modelos:

Árbol de Decisión → Accuracy: 79.3%, F1-score: 79.5%.

Regresión Logística → Accuracy: 76.6%, Recall: 81.0%.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
💡 Estrategias de retención propuestas

Incentivos para clientes con contratos mensuales.

Descuentos o beneficios para clientes con alta facturación mensual.

Promociones para clientes con baja permanencia (< 12 meses).

Campañas de mejora del soporte técnico.

Ofertas y bundles para usuarios de fibra óptica.

Programas de fidelización basados en tiempo de contrato.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🛠 Tecnologías utilizadas

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn)

Jupyter Notebook
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Autor: Martínez García Diego Eduardo

Proyecto desarrollado como parte del desafío de Data Science para TelecomX — Parte 2.
