# Visualización con Kepler.gl

Kepler.gl desrrollada por Uber, en u  principio para uso interno, para analizar y visualizar sus propios datos.

Es una aplicación basada en web GL de alto rendimiento y agnóstica de datos para la exploración visual de conjuntos de datos de geolocalización a gran escala. Construido en la parte superior de deck.gl, kepler.gl puede representar millones de puntos que representan miles de viajes y realizar agregaciones espaciales sobre la marcha.

![alt text](img/kepler.png "Kepler GL")


## Ejercicio de visualización con Kepler.gl

!!! tip 
    Queremos ver dónde hay más accidentes

* Descargamos dataset CSV de [OpenData BCN](http://opendata-ajuntament.barcelona.cat/data/ca/dataset/accidents-tipus-gu-bcn)

* Vamos a http://kepler.gl/#/demo 


>  `Añadimos csv`

![alt text](img/step1-kepler.png "add dataset")


> `Add Layer: Type Hexbin`

> `Columns: Latitud Longuitud`

> `Color: Scale Quantize`

> `Hexagon radius 0.1`

> `Coverage 0.75`

![alt text](img/step2-kepler.png "add dataset")

!!!Info 
    Continuamos añadiendo más capas y mapas bases