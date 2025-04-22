# Descripción 
Estás trabajando como analista para Zuber, una nueva empresa de viajes compartidos que se está lanzando en Chicago. Tu tarea es encontrar patrones en la información disponible. Quieres comprender las preferencias de los pasajeros y el impacto de los factores externos en los viajes.
Al trabajar con una base de datos, analizarás los datos de los competidores y probarás una hipótesis sobre el impacto del clima en la frecuencia de los viajes.

## Objetivo
Para poder llevar acabo nuestro objetivo principal que es analisar patrones con la información disponible para comprender como los factores externos como el clima, impacta en las preferencias de los pasajeros para el año 2017 y mes de noviembre. 

## Metodología
Debemos iniciar con la importación de librerias para poder explorar los datos que disponemos, buscando que los valores sean los adecuados para las columnas, buscando valores duplicados, nulos y de ser necesario crear nuevas variables a partir de los datos para poder profundisar en el analisis. Una vez que terminamos con la corrección de nuestros datos podemos empezar con el análisis de nuestros datos agrupando variables para poder crear gráficas, al igual que podemos filtrar información para obtener información más precisa sobre nuestras variables. Después de analizar nuestros datos podremos obtener conclusiones útiles que nos permitan alcanzar nuestro objetivo.

## Exploración de datos
Para comenzar con la exploración de datos debemos identificar cómo han sido recopilados los datos y de ser necesario cambiar valores en las respectivas columnas, tratar los valores ausentes o duplicados, para poder abrir nuestro archivo debemos importar la librería de pandas para poder mostrar la información y observar cómo esta estructurado el dataframe.

## Conclusión
Finalmente realizamos una prueba de hipótesis para conocer si no existía alguna diferencia en la duración de los viajes realizados los días sábados cuando el clima varía ya sea con buen clima o con un clima lluvioso, al realizar la prueba obtuvimos un valor menor a p=0.05 por lo que rechazamos la hipótesis nula y podemos considerar que si existe diferencia entre la duración del tiempo de viaje en los diferentes climas. 
Al calcular el promedio de duración de viaje para los diferentes climas, podemos observar que en días con un buen clima se realizan en promedio 33 minutos en llegar del barrio Loop al aeropuerto, mientras que cuando hay un mal clima en promedio de tiempo, el viaje se efectúa en 40 minutos, siendo una diferencia de 7 minutos en promedio que dura más el viaje hacia el aeropuerto cuando los días tienen un mal clima. 

### Respuesta al objetivo principal
Por lo que podemos responder a nuestro objetivo principal y decir que los patrones de viaje de los pasajeros se ven afectados con las variaciones de clima, principalmente cuando hay lluvia, esto influye en la duración del viaje ya que es posible que exista inundaciones en el trayecto, accidentes o alguna otra consecuencia que afecte al tráfico de vehículos por lo que la duración en el tiempo del viaje es mayor a los climas donde no hay lluvia.
