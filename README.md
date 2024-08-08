# Titanic_Machine_Learning
Modelo de cálculo de la probabilidad de supervivencia de los pasajeros en el Titanic

## Descripción
Este proyecto se enfoca en predecir la supervivencia de los pasajeros del Titanic utilizando un modelo de aprendizaje automático. El objetivo es crear un modelo que pueda predecir si un pasajero sobrevivió o no, basándose en diferentes características como la clase del pasajero, su edad, el género, entre otros factores.

## Estructura del Proyecto
Titanic-Modelo.ipynb: Este archivo Jupyter Notebook contiene el análisis exploratorio de datos, la preparación de los datos y la implementación del modelo de predicción. train.csv: Dataset de entrenamiento que contiene información sobre los pasajeros del Titanic, incluyendo si sobrevivieron o no. test.csv: Dataset de prueba que contiene información similar al de entrenamiento, pero sin la columna de supervivencia. Este archivo se utiliza para evaluar el rendimiento del modelo. gender_submission.csv: Un archivo de ejemplo que muestra el formato esperado para las predicciones en el conjunto de prueba.

## Resultados
El modelo desarrollado alcanza una precisión (accuracy) de 0.6531 en el conjunto de prueba, lo que indica que aproximadamente el 65% de las predicciones fueron correctas. Además, el modelo tiene una sensibilidad de 0.5329, lo que significa que es capaz de identificar correctamente al 53% de los pasajeros que realmente sobrevivieron. Por otro lado, la especificidad es de 0.7218, reflejando que el modelo identifica correctamente al 72% de los pasajeros que no sobrevivieron. Estos resultados sugieren que el modelo es moderadamente preciso, aunque tiene margen para mejorar en la detección de pasajeros que sobrevivieron.

## Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar este proyecto o añadir nuevas funcionalidades, siéntete libre de abrir un issue o enviar un pull request.
