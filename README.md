# Proyecto de Machine Learning: Sistema de Recomendación de Películas

El objetivo de este proyecto es desarrollar un sistema de recomendación de películas mediante el uso de técnicas de Machine Learning. A continuación, se presenta el proceso de desarrollo, las funcionalidades implementadas y la estructura del proyecto.

## Descripción general: 

El sistema de recomendación de películas consta de las siguientes etapas principales:

1.	Extracción, Transformación y Carga (ETL): En esta etapa se lleva a cabo la limpieza de los datos y se aplican las transformaciones necesarias para su posterior procesamiento. Se emplean técnicas de limpieza, normalización y manipulación de datos.

2.	Funcionalidades implementadas:

•	Cantidad de filmaciones por mes: Permite obtener la cantidad de filmaciones estrenadas para cada mes.

•	Cantidad de filmaciones por día: Proporciona el número de filmaciones estrenadas para cada día.

•	Puntuación de una película: Devuelve el puntaje asociado a una película específica.

•	Votos de una película: Muestra la cantidad de votos recibidos por una película.

•	Obtener información de un actor: Permite obtener información acerca de un actor en particular.

•	Obtener información de un director: Proporciona información sobre un director específico.

3.	Análisis Exploratorio de Datos (EDA): En esta etapa se realiza una exploración de los datos y se analiza la relación entre las variables relevantes. Esto contribuye a una mejor comprensión de los datos y a la identificación de patrones o tendencias que puedan influir en el modelo de recomendación.

4.	Modelo de recomendación de películas: En este proyecto se ha implementado un modelo de recomendación de películas basado en técnicas de Machine Learning. El proceso de recomendación consta de los siguientes pasos:

•	Matriz de características: Se ha creado una matriz de características utilizando variables relevantes como géneros, puntaje promedio y elenco de las películas.

•	Cálculo de similitud: Utilizando la matriz de características, se ha calculado la similitud del coseno entre las películas. Esto nos permite medir la similitud entre las películas y determinar cuáles son las más parecidas entre sí.

•	Función de recomendación: Se ha desarrollado una función que toma el título de una película como entrada y devuelve una lista con los títulos de las películas más similares. Esta función utiliza la matriz de similitud y los índices de las películas para identificar las recomendaciones más relevantes.

5.	Función "get" para ampliar las funcionalidades existentes y crear la API: Se ha implementado una función adicional para obtener recomendaciones de películas basadas en las funcionalidades anteriores. Esto permite obtener recomendaciones personalizadas para un usuario específico.

6.	Despliegue de la API: La API se ha desplegado en la plataforma Render para que esté accesible y pueda ser utilizada por los usuarios finales.

7.	Framework utilizado: El desarrollo de la API se ha llevado a cabo utilizando el framework FastAPI, que ofrece una forma rápida y sencilla de construir servicios web basados en Python.

## Estructura del proyecto: 

El proyecto se organiza de la siguiente manera:

•	ETL: Carpeta que contiene los scripts y archivos relacionados con el proceso de extracción, transformación y carga de datos.

•	EDA: Carpeta que contiene los notebooks o scripts utilizados para realizar el análisis exploratorio de datos.

•	Modelo: Carpeta que contiene los archivos relacionados con el modelo de recomendación de películas.

•	API: Carpeta que contiene los archivos necesarios para implementar la API utilizando FastAPI.

•	Despliegue: Carpeta que contiene los archivos y configuraciones necesarios para el despliegue de la API en Render.

## Requisitos y dependencias: 

Para ejecutar este proyecto, se requiere tener instaladas las siguientes dependencias:

•	Python (versión 3.x)
•	Bibliotecas de Python: pandas, numpy, scikit-learn, fastapi, uvicorn
