Análisis de datos de ruido y alquileres en Barcelona
Descripción
Este proyecto consiste en un análisis de los datos de exposición al ruido y precios de alquiler en los distintos barrios de Barcelona.

Los datos provienen de dos fuentes principales:

Datos de exposición al ruido por barrio disponibles en el portal de datos abiertos del Ayuntamiento de Barcelona
Datos de precios medios de alquiler por barrio disponibles en el portal de datos abiertos del Ayuntamiento de Barcelona
Contenido
El proyecto contiene los siguientes archivos:

2017_poblacio_exposada_ciutat_mapa_estrategic_soroll_bcn_long.csv.csv: datos de exposición al ruido por barrio en formato CSV
2023_lloguer_preu_trim.csv: datos de precios de alquiler por barrio en formato CSV
analisis.ipynb: notebook de Jupyter con el código para el análisis de datos y visualizaciones
README.md: este archivo
Análisis
En el notebook analisis.ipynb se realiza lo siguiente:

Carga y limpieza de datos
Análisis estadístico descriptivo
Visualizaciones para entender la distribución de variables clave
Correlaciones entre variables de ruido y precios de alquiler
Requisitos
Para ejecutar el notebook de Jupyter es necesario tener instalado Python 3 y las siguientes librerías:

pandas
matplotlib
seaborn
Créditos
Este análisis fue realizado por oscar quintana cipres alias 'florinato' como parte del reto de Jump Digital.

Los datos fueron obtenidos del portal de datos abiertos del Ayuntamiento de Barcelona.
https://opendata-ajuntament.barcelona.cat/data/en/dataset/poblacio-exposada-mapa-estrategic-soroll/resource/5bb4138e-5215-43a9-b61e-01e82864180d
https://opendata-ajuntament.barcelona.cat/data/es/dataset/est-mercat-immobiliari-lloguer-mitja-mensual/resource/8148fe53-6bb4-42ca-98df-93e6b723dca9
