# Traffic-Fines-in-Madrid-EDA-Python
EDA (Exploratory Data Analysis) Python

En esta ocasión, trabajaremos con datos sobre "Multas de circulación", es decir, infracciones que han cometido los conductores en la ciudad de Madrid. Toda la información del dataset podemos encontrarla en el siguiente enlace:


https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=fb9a498a6bdb9410VgnVCM1000000b205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default


Como podemos comprobar, los datos llevan publicándose desde 2014, para nuestro análisis, tomaremos el último año completo disponible, en esta ocasión todo 2021. Dentro del último link podemos ver una descripción detallada de la información que contienen los datos, en nuestro caso tenemos información de todas las multas de circulación que el Ayuntamiento de Madrid tramita cada mes. Por motivos referentes a protección de datos las variables informan únicamente de la infracción y está prohibido realizar labores de re-identificación personal de la información de los infractores.


Vemos que los datos disponibles para descarga y consulta están divididos en:


Año, Mes:

    Detalle: Descargar fichero en .csv
    Agrupadas-excluidas: Descargar fichero en .csv


Para nuestro caso de estudio sólo vamos a descargar los archivos con extensión .csv que provengan de la categoría "Detalle" del año 2021.

