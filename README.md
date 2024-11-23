# Machine Learing 
Los datos están relacionados con campañas de marketing directo de una institución bancaria portuguesa. Las campañas de marketing se basaron en llamadas telefónicas. Muchas veces era necesario más de un contacto con un mismo cliente, para poder acceder si el producto (depósito a plazo bancario) estaría ('sí') o no ('no') suscrito.
bank-additional-full.csv con todos los ejemplos (41188) y 20 entradas, ordenados por fecha (de mayo de 2008 a noviembre de 2010), muy cercano a los datos analizados en [Moro et al., 2014]
Los conjuntos de datos más pequeños se proporcionan para probar algoritmos de aprendizaje automático más exigentes desde el punto de vista computacional (por ejemplo, SVM). El objetivo de la clasificación es predecir si el cliente suscribirá (sí/no) un depósito a plazo (variable y).

Los algoritmos a comparar son Random Forest, Logistic Regression, Support Vector Machine, Decision Tree, Gradient Boosting. El objetivo es determinar cual es el mejor algoritmo para determinar la variable "y".


En Paso 1:


En el preprocesamiento de los datos y data wrangling seguir la siguiente logica




Eliminar duplicados y mostrar descripción de las catacteristicas
Detectar anomalías de para cada una de las variables
Análisis descriptivo por cada variable
Buscar valores nulos, blancos y NA




En Paso 2:


Crear varios modelos para predecir si un cliente tomara o no depósito a plazo
Mostrar importancia de las variables para cada modelo seleccionado
Crear confussion matrix , precisión recall y accuracy
Detectar el mejor modelo usando proceso iterativo (cómo se mostró en clases) no calculando los modelos por separado)
Generar recomendaciones en base a modelo propuesto



