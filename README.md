# Clasificación y Optimización de Costos Médicos

Este proyecto implementa un flujo completo de Ciencia de Datos para clasificar y predecir si un cliente representará un costo médico alto o bajo/medio para una aseguradora.

## 🚀 Entregables del Proyecto
* **Notebook Principal:** `clasificacion_costos_medicos.ipynb` con todo el pipeline de código.
* **Análisis Exploratorio (EDA):** Identificación de variables críticas (Fumador como predictor principal, interacciones de IMC y Edad).
* **Modelado Base:** Comparación de Regresión Logística, KNN y Árbol de Decisión.
* **Optimización:** Ajuste exhaustivo de hiperparámetros utilizando `GridSearchCV` y `RandomizedSearchCV`.

## 📊 Resultados del Modelo Campeón
* **Modelo Seleccionado:** Árbol de Decisión Optimizado (RandomizedSearchCV)
* **Accuracy en Test:** 93.28%
* **F1-Score (Clase Costo Alto):** 93.00%
* **ROC-AUC:** 0.9379
* **Tag de Liberación:** v1.0.0
