# Depression and Anxiety on Miscarriages on Twitter

## Introducción
Este proyecto ha sido desarrollado como trabajo de final de máster para el máster de Data Science cursado en la UOC (Universitat Oberta de Catalunya). El objetivo final es analizar si las personas que hablan del aborto espontáneo en Twitter también presentan síntomas de depresión o ansiedad, además de analizar semánticamente los tweets para extraer problemas actuales relacionados con el tema.

## Contibuciones
El proyecto ha sido desarrollado por Laura Planas Simón, con el apoyo de mis tutores: Laia Subirats Maté y Davide Cirillo.

## Estructura del proyecto
El código del proyecto se encuentra en el fichero Jupyter notebook llamado `miscarriage-analysis.ipynb`. En este fichero encontramos el proceso completo para obtener datos de Twitter en streaming, procesar tanto las columnas numéricas como el texto, y a continuación realizar un análisis de sentimiento y una extracción de temas con un modelo LDA. Finalmente también se incluye una exploración de los datos y un apartado de análisis de los resultados obtenidos.

El proyecto contiene datos extraídos de Twitter en dos fechas diferentes: durante el fin de semana posterior al Miscarriage Awareness Day (15 de octubre), y durante una semana aleatoria de octubre/noviembre (del 27/10 al 04/11). El primer dataset será mencionado durante todo el código como "awareness" y el segundo como "streaming".

Los datos obtenidos del proyecto se guardan en 3 puntos:
* Al extraer los datos de Twitter obtenemos 2 ficheros en formato JSON con los tweets en su formato original. Estos ficheros se guardan en la carpeta `json_files`.
* Al realizar la limpieza y tranformación a CSV de los datos se guardan dos ficheros CSV en la carpeta `csv_files/transformation`.
* Por último, después de realizar el análisis de aparición de depresión, análisis de sentimiento y extracción de temas de los tweets, guardamos 2 nuevos ficheros en formato CSV en la carpeta `csv_files/results`.

Actualmente se pueden encontrar en estas carpetas los ficheros obtenidos de la extracción de datos mencionada anteriormente.

