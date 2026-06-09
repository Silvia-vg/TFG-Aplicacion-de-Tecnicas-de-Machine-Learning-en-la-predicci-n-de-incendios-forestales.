# TFG-Aplicacion-de-Tecnicas-de-Machine-Learning-en-la-predicci-n-de-incendios-forestales.
Aplicación de Técnicas de Machine Learning en la Predicción de las Condiciones Meteorológicas Asociadas a Incendios Forestales

Este repositorio contiene el desarrollo práctico de mi Trabajo Fin de Grado (TFG), centrado en la aplicación de técnicas de Machine Learning para la predicción de condiciones meteorológicas asociadas a incendios forestales en la provincia de Huelva (España).

El objetivo principal es analizar la capacidad predictiva de distintos algoritmos de aprendizaje automático para identificar situaciones meteorológicas favorables a la ocurrencia de incendios forestales, contribuyendo así al desarrollo de herramientas de apoyo para la prevención y gestión del riesgo.
# Conjunto de datos
Se ha utilizado información meteorológica procedente de estaciones ubicadas en la provincia de Huelva, junto con registros históricos de incendios forestales.

Las variables empleadas incluyen parámetros meteorológicos como:

- Temperatura
- Humedad relativa
- Velocidad del viento
- Precipitación
- Otras variables derivadas y transformadas

# Metodología

Se han implementado y comparado distintos enfoques de Machine Learning:

- Support Vector Classifier (SVC)
- Random Forest (RF)
- Multi-Layer Perceptron (MLP)
- Técnicas aplicadas
- Entrenamiento utilizando únicamente las variables meteorológicas originales.
- Lag Features: Incorporación de variables retardadas para capturar la dependencia temporal de las condiciones meteorológicas.
- Principal Component Analysis (PCA): Reducción de dimensionalidad para evaluar el impacto de la compresión de información sobre el rendimiento predictivo.

# Optimización de hiperparámetros

Todos los modelos han sido optimizados mediante:

- GridSearchCV
- Validación cruzada
- Selección automática de los mejores hiperparámetros
- Métricas de evaluación

Los modelos se han evaluado utilizando diferentes métricas de clasificación, prestando especial atención a:

- F1-Score
- Precision
- Recall
- Accuracy

Dado el carácter desbalanceado del problema, la métrica principal de comparación ha sido el F1-Score.

# Resultados

Los experimentos muestran el comportamiento de cada algoritmo bajo diferentes configuraciones de preprocesamiento y representación temporal de los datos.

El mejor rendimiento se obtuvo mediante un modelo SVC optimizado con incorporación de variables retardadas (lag features), alcanzando los valores más equilibrados entre precisión y capacidad de detección.


# Tecnologías utilizadas
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- GridSearchCV
- Tensorflow
  
# Autor

Silvia García López

Trabajo Fin de Grado (TFG)

Grado en Física

Universidad de Córdoba
