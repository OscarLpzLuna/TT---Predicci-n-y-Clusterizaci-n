# TT---Predicción-y-Clusterización


Proyecto 13 del bootcap "Data Analyst" de TripleTen. Desarrollado por Óscar López. 

En este proyecto se ponen en práctica las habilidades adquiridas en el último módulo del bootcamp, considerando las siguientes habilidades:

- Herramientas de programación en Python.
- Preprocesamiento de datos.
- Análisis exploratorio de datos.
- Construcción de un modelo de predicción.
- Identificación de grupos (Clusterización)

Para ello, se realiza el ejercicio de analizar los datos aportados por la cadena de gimnasios "Model Fitness" donde se busca predecir la probabilidad de pérdida de clientes, elaborar retratos de usuarios típicos y analizar los impactos en las pérdidas de clientes, con el fin de identificar grupos objetivo y sugerir estrategias para reducir la rotación y mejorar la interacción con la clientela.

Se usaron las siguientes librerias de Python para el desarrollo de este proyecto:
* Visualización de datos: Matplotlib, Seaborn.
* Procesamiento de datos y análisis exploratorio: Pandas, Numpy, Scipy.
* Predicción y Clusterización: Scikit-Learn

Se realizó la consturcción de dos modelos de predicción basados en Regresión logística y Bosque Aleatorio, al dividir los datos para realizar el entrenamiento y la validación del modelo obtenido, utilizando una proporción de 80/20. Obteniendo una exactitud mayor al 90% en ambos modelos.
La clusterización se realizó creando 5 grupos principales de clientes donde se encontró que el grupo 0 y 4 son los que presentan menores tasas de cancelación, mientras que el grupo 3 tiene la más alta tasa de cancelación media con un 52%.

Descripción de los archivos:

    'gym_churn_us.csv' son los datos suministrados para el desarrollo del análisis.
    'proyecto13.ipynb', Jupyter Notebook con el análsis exploratorio de datos realizado.
