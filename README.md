# Predictor de Precios de Vuelos 🛫💰

**Trabajo Fin de Grado – Business Analytics, UFV (2024-25)**  
Lucía Ortega – luciaortega1



## Descripción

Este repositorio contiene el código completo de mi Trabajo Fin de Grado, cuyo objetivo es **modelar y predecir el precio de billetes de avión** a partir de variables como aerolínea, origen, destino, antelación, duración, número de escalas y clase (business/economy).  
Se han explorado desde modelos simples (Regresión Lineal Múltiple) hasta ensamblados complejos (Random Forest, XGBoost) y Redes Neuronales, para comparar su rendimiento y seleccionar el más adecuado. Finalmente, el modelo elegido está desplegado en un **dashboard interactivo con Streamlit**.

---

## Contenido del repositorio

```text
├── README.md                        ← Este archivo
├── requirements.txt                 ← Dependencias Python
├── data
│   ├── raw                          ← Datos originales
│   └── processed                    ← Datos limpios y transformados
├── notebooks                        ← Google Colab notebooks
│   ├── 01_Ingenieria_Dato.ipynb     ← Código de Ingeniería del Dato (ETL)
│   ├── 02_Analisis_Dato.ipynb       ← Código de Análisis del Dato (EDA y feature engineering)
│   └── 03_Analisis_Negocio.ipynb    ← Código de Análisis de Negocio (modelado y métricas)
├── src
│   ├── data_preparation.py          ← Funciones de ETL reutilizables
│   ├── models.py                    ← Definición y entrenamiento de modelos
│   ├── train.py                     ← Script de entrenamiento y validación
│   ├── evaluate.py                  ← Cálculo de MAE, RMSE, R²
│   └── utils.py                     ← Funciones auxiliares
├── app.py                           ← Dashboard Streamlit
└── .gitignore
