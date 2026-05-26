# Análisis exploratorio de alojamientos Airbnb en Barcelona

Este proyecto presenta un análisis exploratorio de datos de alojamientos de Airbnb en la ciudad de Barcelona, con el objetivo de estudiar patrones relacionados con precios, disponibilidad, distribución geográfica y concentración de la oferta turística.

El análisis se desarrolla con Python a partir de un conjunto de datos de alojamientos de Airbnb en Barcelona. A través de procesos de limpieza, transformación, visualización y análisis estadístico, se busca obtener información útil sobre el comportamiento de los alojamientos y su relación con algunas de las principales propuestas de valor de la plataforma.

## Objetivo del proyecto

El objetivo principal es analizar los datos de Airbnb en Barcelona para identificar patrones relevantes sobre la distribución de alojamientos por zonas de la ciudad, la relación entre características del alojamiento y precio, la disponibilidad mensual de las propiedades, la concentración de actividad en determinados distritos y la validación parcial de propuestas de valor asociadas a Airbnb.

## Dataset

El proyecto utiliza el archivo `Airbnb_Barcelona_final_list.csv`.

El dataset contiene información sobre alojamientos de Airbnb en Barcelona, incluyendo variables relacionadas con ubicación, precio, disponibilidad, número de habitaciones, camas, baños, reseñas y características del alojamiento.

## Herramientas utilizadas

Python  
Google Colab  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Statsmodels  
Folium  

## Desarrollo del análisis

El proyecto incluye una primera fase de carga y revisión inicial del dataset, seguida de la limpieza de columnas no relevantes para el análisis y el tratamiento de valores nulos.

Posteriormente, se transforman las variables de latitud y longitud, se filtran los registros correspondientes a Barcelona y se realiza un análisis exploratorio de variables numéricas y categóricas.

También se analizan patrones de disponibilidad, actividad por distrito, correlaciones con la variable precio y una regresión múltiple básica para explorar la relación entre el precio y variables como baños, habitaciones y camas.

Finalmente, se realiza una visualización geográfica de los alojamientos mediante mapas y se elaboran conclusiones orientadas a negocio.

## Principales resultados

El análisis muestra que los alojamientos de Airbnb en Barcelona se concentran principalmente en zonas céntricas y turísticas, como Eixample, Ciutat Vella y Gràcia.

También se observa una relación positiva entre el precio y características físicas del alojamiento, especialmente el número de baños, habitaciones y camas.

Respecto a la disponibilidad, existen alojamientos disponibles durante prácticamente todo el mes, lo que puede indicar una orientación más continua hacia el alquiler turístico, en lugar de un uso únicamente ocasional por parte de anfitriones particulares.

En términos generales, el análisis sugiere que algunas propuestas de valor de Airbnb se cumplen parcialmente, especialmente en zonas turísticas consolidadas, aunque la dispersión del turismo hacia barrios menos céntricos parece limitada.

## Informe del proyecto

Además del notebook, se incluye un informe en PDF con el desarrollo del análisis, visualizaciones y conclusiones principales:

`Proyecto_Airbnb.pdf`

## Nota sobre la ejecución

El proyecto fue desarrollado originalmente en Google Colab.

Si se desea ejecutar el notebook en otro entorno, puede ser necesario ajustar la ruta del archivo CSV según la ubicación local del dataset.

## Archivos principales

`Proyecto_Airbnb.ipynb`  
Notebook con el desarrollo técnico del análisis.

`Proyecto_Airbnb.pdf`  
Informe final del proyecto con visualizaciones y conclusiones.

`Airbnb_Barcelona_final_list.csv`  
Dataset utilizado en el análisis.

## Autora

Paola Albán  

Perfil orientado a Data Analytics, Business Intelligence y Machine Learning aplicado.
