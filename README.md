# DMA_Trabajo_Final
Trabajo Final – Data Mining Avanzado

Alumnos: Lucía Pereyra Huertas, Gabriel Martina, Jaime López Garrido, Diego Farfán y Analía Ale.
Docente: Martín Volpacchio.

Este repositorio contiene una serie de ejercicios desarrollados en Python como parte de la materia Data Mining Avanzado, orientados a la aplicación práctica de distintos modelos de aprendizaje automático supervisado. Los trabajos abarcan problemas de series de tiempo, clasificación y regresión, implementando pipelines completos de modelado, validación y evaluación.

El objetivo general es ilustrar, de forma integrada, el uso de técnicas modernas de Machine Learning, poniendo énfasis en la correcta separación de datos, la selección de hiperparámetros y la interpretación de resultados.

Contenidos del repositorio
1. Predicción de Series de Tiempo con LSTM ("Ej1_VI.ipynb")

Se implementa un modelo de redes neuronales recurrentes del tipo LSTM (Long Short-Term Memory) para la predicción de una serie temporal real.
El ejercicio incluye:

- Preparación y normalización de la serie temporal.
- División temporal estricta en conjuntos de entrenamiento, validación y test.
- Generación de ventanas deslizantes (lookback → horizonte).
- Entrenamiento de múltiples configuraciones de red (número de capas, neuronas y dropout).
- Comparación contra un baseline naïve de persistencia.
- Evaluación con métricas estándar y análisis gráfico de resultados.

2. Clasificación ("Ej10_Opcion1_Clasificacion.ipynb")

Se desarrolla un problema de clasificación supervisada utilizando distintos algoritmos de Machine Learning.
El flujo de trabajo incluye:

- Preprocesamiento de datos.
- Entrenamiento de modelos dentro de un pipeline.
- Optimización de hiperparámetros mediante GridSearch con validación cruzada.
- Evaluación del desempeño sobre un conjunto de test independiente.

3. Regresión ("Ej10_Opcion1_Regresion.ipynb")

Se aborda un problema de regresión supervisada, comparando distintos modelos predictivos.
El ejercicio contempla:

- Separación clara entre entrenamiento y test.
- Ajuste de hiperparámetros mediante validación cruzada.
- Evaluación con métricas como RMSE y R².
- Comparación del rendimiento entre modelos.

Gracias!
