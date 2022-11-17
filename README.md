# SearchFullArchiveTweepy

In this code I collaborated with an undergraduate thesis for the extraction of tweets from the Twitter API (v1.1 reference) in its historical file using 
python 3.9.7 and the Tweepy v4.4.0 library. 

It was a request with the operators enabled for a premium search v1.1. It is an account with sandbox access with a limit of requests and tweets per month. 

There is a lot of cross information regarding the search full archive and the twitter api, if the code improves over time I will try to update it, 
at the moment it works in order to obtain the tweets. 

------------------------
En este código colaboré con una tesis de pregrado para la extracción de tweets de la API (referencia a la v1.1) de twitter en su archivo histórico mediante 
python 3.9.7 y  la librería Tweepy v4.4.0.

Fue una petición con los operadores habilitados para una busqueda premium v1.1. Es una cuenta con accesos sandbox con límite de peticiones y tweets por mes. 

Hay mucha información cruzada respecto a la búqueda en el archivo histórico y la api de twitter, si con el tiempo se mejora el código intentaré actualizarlo, 
de momento este funciona a efectos de obtener los tweets. 

# Datos de query

Para que correspondiesen los requerimientos seleccionados para el corpus de los tuits a utilizar y los parámetros de búsqueda que ofrece Tweepy, se organizó la petición a la API de Twitter de la siguiente forma:

· **Query**: corresponde a las características específicas de la búsqueda. En este caso se evidencian los siguientes elementos:

    o #YoMeQuedoEnCasa: hashtag seleccionado a buscar dentro de los tuits.

    o lang=”es”: búsqueda de tuits que estuviesen únicamente en español.

    o Point_radius="-34.602730,-58.438790,20km": geolocalización de los tuits en unas coordenadas específicas con un radio que abarcase la Ciudad Autónoma de Buenos Aires y Provincia de Buenos Aires, Argentina.

· **fromDate="202003200000"**: Rango de tiempo en el que se inicia la extracción de tuits, es decir, desde el 20 de marzo del 2020 a las 00:00 horas

· **toDate="202003262359"**: Rango de tiempo en el que termina la extracción de tuits, es decir, hasta el 26 de marzo del 2020 a las 23:59 horas.
