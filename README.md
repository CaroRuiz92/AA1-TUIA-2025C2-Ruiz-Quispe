# Trabajo Práctico N°1 – Modelo predictivo de tarifas de Uber  

**Materia:** Aprendizaje Automático 1  
**Carrera:** Tecnicatura en Inteligencia Artificial – FCEIA  
**Entrega:** 23/09/2025

**Estudiantes:** Carolina Ruiz y Rocio Quispe

---

## Descripción

Este proyecto corresponde al **Trabajo Práctico N°1** de la asignatura *Aprendizaje Automático 1*.  
El objetivo principal fue **desarrollar un modelo predictivo de tarifas de Uber**, aplicando técnicas de preprocesamiento de datos, regresión lineal y regularización con la librería `scikit-learn`.  

---

## Dataset

Se utilizó el dataset **`uber_fares.csv`**, que contiene información sobre viajes realizados con Uber en Nueva York.  

**Variables de entrada (features):**  
- `key`: identificador único del viaje.  
- `pickup_datetime`: fecha y hora de inicio.  
- `passenger_count`: número de pasajeros.  
- `pickup_longitude`, `pickup_latitude`: coordenadas de inicio.  
- `dropoff_longitude`, `dropoff_latitude`: coordenadas de destino.  

**Variable de salida (target):**  
- `fare_amount`: tarifa del viaje en USD.  

---

## Pasos realizados

1. **Análisis exploratorio de datos (EDA):**  
   - Revisión de valores faltantes y atípicos.  
   - Histogramas, diagramas de caja y scatterplots.  
   - Matriz de correlación.  

2. **Preprocesamiento:**  
   - Imputación de valores faltantes.  
   - Estandarización / escalado de datos.  
   - Codificación de variables categóricas (si correspondía).  
   - División en **train / test**.  

3. **Modelado:**  
   - Regresión Lineal con `LinearRegression`.  
   - Métodos de gradiente descendiente (`SGDRegressor`).  
   - Regularización: **Lasso**, **Ridge**, **Elastic Net**.  

4. **Evaluación:**  
   - Métricas: R², MSE, RMSE, MAE, MAPE.  
   - Gráficos de **Error vs Iteraciones**.  
   - Gráficos de **residuos**.  
   - Comparación entre modelos.  

5. **Optimización:**  
   - Búsqueda de hiperparámetros en gradiente descendiente y regularización.
   - Conclusiones finales sobre el desempeño de versiones de modelos.

---

