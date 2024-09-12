# Titanic Kaggle

El siguiente reto tiene como objetivo resolver el problema Titanic - Machine Learning from Disaster de Kaggle Competition (https://www.kaggle.com/competitions/titanic/overview) utilizando algoritmos de clasificación.
Para ello, se siguieron 2 etapas principales, pre análisis de los datos y entrenamiento de modelos de Machine Learning. Estos modelos tendrian la tarea principal tarea de predecir que pasajero del Titanic sobrevive o no.

## Propuesta de solución

Como solución para este reto, se implementaron los siguientes algoritmos de clasificación de Machine Learning:
* Regresión logística
* k vecinos cercanos (KNN)
* Máquina de soporte vectorial (SVM)
* Bosque Aleatorio

Esperamos que lo siguientes algoritmos nos ofrezcan una solución acepable para el reto.

## Problematicas encontradas

Algunos de los problemas con los que el equipo se encontro para la realización de este reto fueron:
* **Variables faltantes**. Dentro del dataset para entrenar los modelos nos encontramos con una cantidad significativa de muestras con datos faltantes, fue necesario de emplear técnicas de pre preprocesamiento de datos, como imputación y "feature engineering", para encontrar una forma de llenar estos espacios en blanco.
* **Selección de modelos**. Seleccionar los modelos de aprendizaje correctos para nuestro dataset final requirió de un análisis de no solo de las variables que utilizariamos, sino también de análisis de cada modelo en particular, para saber cual se adaptaria mejor.
* **Análisis correcto de los datos**. Saber que datos, y en que forma estos podrian ayudarnos a entrenar los modelos de manera efectiva requirió tanto de pruebas de distintos conjuntos de datos, así como también de los modelos y los resultados que estos nos arrojaban para cada combinación de datos.


## Link al notebook en Google Colab
https://colab.research.google.com/drive/1EHpNfg4JpJImaHKSaizKowmpR5McNkeb?usp=sharing
