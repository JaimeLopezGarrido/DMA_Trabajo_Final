# DMA_Trabajo_Final
Trabajo Final – Data Mining Avanzado

Este repositorio contiene una serie de ejercicios desarrollados en Python como parte de la materia Data Mining Avanzado, orientados a la aplicación práctica de distintos modelos de aprendizaje automático supervisado. Los trabajos abarcan problemas de series de tiempo, clasificación y regresión, implementando pipelines completos de modelado, validación y evaluación.

El objetivo general es ilustrar, de forma integrada, el uso de técnicas modernas de Machine Learning, poniendo énfasis en la correcta separación de datos, la selección de hiperparámetros y la interpretación de resultados.

Contenidos del repositorio
1. Predicción de Series de Tiempo con LSTM

Se implementa un modelo de redes neuronales recurrentes del tipo LSTM (Long Short-Term Memory) para la predicción de una serie temporal real.
El ejercicio incluye:

Preparación y normalización de la serie temporal.

División temporal estricta en conjuntos de entrenamiento, validación y test.

Generación de ventanas deslizantes (lookback → horizonte).

Entrenamiento de múltiples configuraciones de red (número de capas, neuronas y dropout).

Comparación contra un baseline naïve de persistencia.

Evaluación con métricas estándar y análisis gráfico de resultados.

2. Clasificación

Se desarrolla un problema de clasificación supervisada utilizando distintos algoritmos de Machine Learning.
El flujo de trabajo incluye:

Preprocesamiento de datos.

Entrenamiento de modelos dentro de un pipeline.

Optimización de hiperparámetros mediante GridSearch con validación cruzada.

Evaluación del desempeño sobre un conjunto de test independiente.

3. Regresión

Se aborda un problema de regresión supervisada, comparando distintos modelos predictivos.
El ejercicio contempla:

Separación clara entre entrenamiento y test.

Ajuste de hiperparámetros mediante validación cruzada.

Evaluación con métricas como RMSE y R².

Comparación del rendimiento entre modelos.

Requisitos

Los notebooks están desarrollados en Python y utilizan librerías estándar del ecosistema de ciencia de datos, entre ellas:

NumPy

Pandas

Scikit-learn

TensorFlow / Keras

Matplotlib

En el caso del ejercicio de LSTM, el código incluye una instalación condicional de dependencias, lo que permite ejecutar el notebook en distintos entornos sin configuración previa.

Autoría

Trabajo realizado en el marco de la materia Data Mining Avanzado.
Alumnos: Lucía Pereyra Huertas, Gabriel Martina, Jaime López Garrido, Diego Farfán y Analía Ale.
Docente: Martín Volpacchio.
