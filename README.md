# 🛢️ Oil Well Profit Prediction

Machine Learning Project

## 📌 Overview

Este proyecto desarrolla un modelo de regresión lineal para predecir el volumen de reservas de petróleo y seleccionar la región más rentable y segura para abrir 200 nuevos pozos, considerando beneficios y riesgos financieros.
El análisis se realiza sobre tres regiones con datos sintéticos de exploración geológica, aplicando machine learning supervisado y bootstrapping para la evaluación de riesgos.

## 🎯 Objectives

Predecir el volumen de reservas por pozo.
Seleccionar los 200 pozos más prometedores por región.
Estimar beneficios bajo restricciones de negocio.
Evaluar riesgos mediante simulación estadística.
Recomendar la región óptima para inversión.

## ⚙️ Tools

Python · Pandas · NumPy · Scikit-learn · SciPy · Jupyter Notebook

## 🤖 Model & Methodology

Modelo: Regresión Lineal
Train / Validation split: 75% / 25%
Métrica: RMSE
Selección: Top 200 pozos con mayor predicción
Evaluación de riesgo: Bootstrapping (1000 muestras)
Criterio: Riesgo de pérdida < 2.5%

## 📊 Key Results

Las tres regiones presentan ganancia esperada positiva.
Región 1:
Mayor ganancia promedio.
Intervalo de confianza del 95% sin pérdidas.
Menor riesgo de pérdida.
Región 0:
Alternativa viable si la Región 1 no es seleccionable.
Región 2:
Menor rentabilidad y mayor riesgo relativo.

## ✅ Conclusion

La Región 1 es la mejor opción para el desarrollo de los 200 pozos, al combinar mayor beneficio promedio y menor riesgo de pérdidas.
Se recomienda considerar adicionalmente la distribución geográfica de pozos con reservas nulas antes de la ejecución del proyecto.
