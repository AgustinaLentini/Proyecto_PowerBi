## Proyecto_PowerBi
#🏠 Análisis de Datos Airbnb con Power BI 📊

# Descropcion del proyecto: 
En **“Accommodation Analysis in New York City, USA - Airbnb”** se analiza un conjunto de datos de casi 3000 filas y 13 columnas para obtener información relevante sobre las propiedades y los precios, identificar patrones y tendencias en el mercado de alquileres vacacionales y proporcionar recomendaciones para optimizar las estrategias de alquiler, usando varias técnicas de visualización de datos, como mapas de calor, gráficos de barras, gráficos de conteo y KPIs. Ademas, Se identifico las ubicaciones de alquiler mas populares, se comparo grupos de vecindarios y disponibilidad en diferentes vecindarios de acuerdo a los tipos de habitacion y el analicis de vecindarios de uso frecuente en listados de Airbnb.

Para la elaboración del dashboard se realizó un proceso de ETL, que, entre otras tareas, incluía: 

- Limpieza de datos eliminando duplicados, campos vacíos y valores nulos. 
- Generación de tablas de hechos y tabla de dimensiones
- Creación de tabla calendario con lenguaje DAX
- Creación de tabla Medidas y las correspondientes medidas utilizadas (creadas en lenguaje DAX)

# Herramientas tecnológicas implementadas:
- SQL para la consulta de la base de datos y creacion de tablas.
- Excel y Power Query para la lectura y limpieza del datasets.
- Power Point para la creación del diseño del mockup.
- Miro para la creación del diagrama entidad-relación (https://app.diagrams.net/).
- Power BI Desktop para la creación del tablero de control.

# Tableros del proyecto: 

# Home
Carátula del proyecto donde se encuentra una breve descripción del objetivo y varios botones que nos llevan a visualizar el análisis que deseamos.
!(https://drive.google.com/file/d/1mSXMN9k45KHLiDGRmHaCMBKA7BahiWFg/view?usp=sharing)

# Readmi
En esta solapa encontramos información relevante para introducir al usuario al proyecto, tomando conocimiento de la estructura y un glosario que nos da idea del lenguaje a utilizar en este análisis.
!(file:///Users/aguslentini/Desktop/Captura%20de%20pantalla%202023-08-14%20a%20la%28s%29%2015.39.15.png)

# Overview
Se pueden visualizar distintos parámetros generales como TOP 5 y TOP 10 de las propiedades, según los distritos. Asimismo, podemos segmentar los datos de acuerdo a los años, nombre del host, nombre de la propiedad y barrio.
!(file:///Users/aguslentini/Desktop/Captura%20de%20pantalla%202023-08-14%20a%20la%28s%29%2015.41.03.png)

# Property 
Solapa en la que podemos ver la evolución de las propiedades a lo largo de los años, la distribución de las propiedades dentro de cada uno de los distritos y una lista de propiedades donde podemos encontrar datos como el nombre de la propiedad, distrito, promedio del precio por noche el cual si es mayor a 50 dólares la noche se puede visualizar en la lista, caso contrario no, ya que solo se querían tomar aquellos casos donde la noche vale mas o igual a 50 dólares y por último la suma de los días disponibles anualmente por cada propiedad.

!(file:///Users/aguslentini/Desktop/Captura%20de%20pantalla%202023-08-14%20a%20la%28s%29%2015.44.21.png)

# Host 
Se puede visualizar distintas tarjetas con datos como el promedio de precios por noche, el total de días reservados, el total de las reviews y la cantidad total de las veces que el host utilizó Airbnb. Asimismo, se analiza la correlación de los precios con la cantidad de reviews, el número de host por año y una lista con los nombres del host, las propiedades, los distritos y la cantidad de veces que el host utilizó Airbnb.
!(file:///Users/aguslentini/Desktop/Captura%20de%20pantalla%202023-08-14%20a%20la%28s%29%2015.46.05.png)

# District
Datos relevantes como él promedio de precios por distrito, un mapa para ubicar geográficamente los distritos, una tabla donde podemos ver los nombres de las propiedades, barrios a los que pertenecen, el tipo de habitación y un recuento de la cantidad de propiedades, con ello se busca analizar la distribución geográfica de las propiedades y los tipos.
!(file:///Users/aguslentini/Desktop/Captura%20de%20pantalla%202023-08-14%20a%20la%28s%29%2015.47.22.png)

# Room
Análisis del total por cada tipo de habitación y uno general que nos muestra la cantidad de habitaciones sin discriminar por el tipo, por otro lado se analizó el promedio de disponibilidad anual, el promedio mínimo de noches y el promedio del precio por el tipo de habitación. En esta hoja también vamos a encontrar datos como la cantidad de habitaciones por distrito, lo cual se podría traducir en una mayor actividad del alojamiento o menor, según los resultados obtenidos, a través de los segmentadores que se encuentran en la parte superior derecha.

!(file:///Users/aguslentini/Desktop/Captura%20de%20pantalla%202023-08-14%20a%20la%28s%29%2015.48.40.png)

# Archivos: 
[Documentacion del Proyecto ](https://drive.google.com/drive/u/0/folders/1EO4wKs7WedwgACwYF_OhGk7AXOKhcceW)

[Proyecto en Power BI](https://drive.google.com/file/d/1-rDl3PVUaDFI5D07Fd7T-3tNBFaFhMLr/view?usp=drive_link)

# Contacto: 
[Linkedin](https://www.linkedin.com/in/agustina-lentini-494b07129/)




