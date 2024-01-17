<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
</head>
<body>

<p align='center'>
<img src ="https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png">
<p>

# <h1 align=center> **`PROYECTO INDIVIDUAL Nº2`**</h1> <!-- omit in toc --> 

# <h1 align=center>**`Siniestros Viales`**</h1> <!-- omit in toc --> 

# <h3 align=center>**` Enero de 2024 `**</h2> <!-- omit in toc --> 

# <h2 align=center>**` Miguel Angel Dallanegra Vilches - DATA Part Time 05 `** </h2> <!-- omit in toc --> 


<p align='center'>
<img src = 'https://static.lajornadaestadodemexico.com/wp-content/uploads/2022/08/Siniestros-viales.jpg' height = 500>
<p>


- [Información General](#información-general)
- [Desarrollo](#desarrollo)
- [ETL](#etl)
- [EDA](#eda)
- [Dashboard](#dashboard)
- [Datos Adicionales](#datos-adicionales)
- [Conclusiones](#conclusiones)
- [Contacto](#contacto)

## Información General

Se tiene una base de datos compuesta de dos archivos de Excel que contienen informacion acerca siniestros viales. Uno de los datasets contiene datos de homicidios y el otro posee datos de lesiones, ambos porducidos en accidentes viales en la Ciudad Autonoma de Buenos Aires entre 2016 y 2021. Estos datos fueron obtenidos del dataset de siniestros viales generados, guardados y publicados por la ciudad.

## Desarrollo

El proceso de trabajo consistirá en 3 partes:

- Se deberan extraer y transformar los datos que llegan sin procesar y con errores, los cuales se encuentran en la carpeta [_src](https://github.com/mdallanegra/LAB_PI_02/tree/main/_src).
- Se hará un análisis exploratorio para entender la informacion que contiene la base de datos.
- Finalmente se deberá crear un dashboard en Power Bi para explorar y comprender los datos obtenidos de los dos pasos anteriores y se generaran al menos 2 KPI's con la propuesta de reduccion de los accidentes viales.

## ETL

El proceso de extracción y transformación de los datos consiste en la limpieza, eliminacion de columnas innecesarias, borrando elementos duplicados o vacíos, reordenando sus datos y finalmente almacenados en 2 formatos, uno en .parquet para optimizar el trabajo en el paso EDA y otro en .xlsx para el trabajo en Power Bi pensando en la mejor compatibilidad con el programa.  El trabajo se confeccionó en el archivo notebook [Lab_PI_02.1.ETL.ipynb](https://github.com/mdallanegra/LAB_PI_02/blob/main/Lab_PI_02.1.ETL.ipynb). 

## EDA

En el Análsis Exploratorio de Datos, se realiza el análisis gráfico y estadistico de las diferentes variables y sus combinaciones. Esto será de gran utilidad a la hora de confeccionar una estrategia para reducir los homicidios viales, ya que se analizan diversos factores que pueden ser abordados para trabajar, teniendo en cuenta ubicacion de los siniestros, involucrados en el hecho, horarios, edades, etc.
Este análisis, con todos sus graficos y valores se encuentra en el archivo [Lab_PI_02.2.EDA.ipynb](https://github.com/mdallanegra/LAB_PI_02/blob/main/Lab_PI_02.2.EDA.ipynb).

## Dashboard

En esta parte del trabajo se elabora un dashboard de Power Bi con una serie de analisis gráficos y estadísticos que complementan los KPI's solicitados para poder evaluar la reduccion de los homicidios viales. En uno de los KPI se calcula la reduccion del 10% de la tasa total de siniestros, en el segundo se calcula la reduccion del 7% de la tasa de siniestros en motocicleta y el el tercero se calcula la reduccion de un 15% la tasa de siniestros contra peatones.

## Datos Adicionales

Para complementar el análisis se obtuvieron nuevos datasets que ayudaron en el trabajo de geolocalización y proyeccion poblacional. Todos ellos fueron descargados de [https://data.buenosaires.gov.ar/](https://data.buenosaires.gov.ar/).


__Para Geolocalizacion__
  - Por Barrios: [barrios.geojson](https://github.com/mdallanegra/LAB_PI_02/blob/main/_data/barrios.geojson), obtenido de [https://data.buenosaires.gov.ar/dataset/barrios](https://data.buenosaires.gov.ar/dataset/barrios).

  - Por Comunas: [comunas.geojson](https://github.com/mdallanegra/LAB_PI_02/blob/main/_data/comunas.geojson), obtenido de [https://data.buenosaires.gov.ar/dataset/comunas](https://data.buenosaires.gov.ar/dataset/comunas).

__Para Tasa de Homicidios__
  - Poblacion Proyectada:[PBP_CO1025.xlsx](https://github.com/mdallanegra/LAB_PI_02/blob/main/_data/PBP_CO1025.xlsx), obtenido de [https://data.buenosaires.gob.ar/dataset/estructura-poblacion](https://data.buenosaires.gob.ar/dataset/estructura-poblacion).

## Conclusiones



## Contacto

<p align="left">
<img src="_pics/mail.icns"  height=30><a href="mailto:mdallanegra@icloud.com" class="text-link-next-to-icon"> Correo Electrónico</a>
</p>
<p align="left">
<img src="_pics/linkedin.icns"  height=30><a href="https://www.linkedin.com/in/miguel-angel-dallanegra-vilches-b419b19b/" class="text-link-next-to-icon"> Perfil de LinkedIn</a>
</p>

</body>
</html>