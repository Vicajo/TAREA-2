# TAREA-2
[Mapa Control Visitas a Campo](https://vicajo.carto.com/builder/88fc88e2-4d75-479c-b38e-ba3c6e9272e7/embed)

## Cuál es el problema a tratar?

En este caso el problema a tratar corresponde al control de las visitas de supervisión a bases localizadas en el territorio nacional, orientado al registro del responsable de la visita y la fecha.

## Por qué un mapa ayuda a resolverlo?

La empresa que realiza este mapa debe tener control y por lo tanto realizar supervisión de la totalidad de sus bases, con una periodicidad determinada, con el mapa se puede determinar la distribución de las visitas y la frecuencia con las que se hacen.
Descripción de los datos (tipos de geometrías, atributos, sistemas de referencia, urls para descarga de la información, etc)
En este caso se utiliza una geometría de tipo punto que identifica la localización de las bases, pues el área es irrelevante para el objetivo del mapa, y se incluyen los datos de la fecha, el nombre del responsable, el nombre de la base, el municipio y el departamento de esta,

## Descripción del procesamiento realizado a los datos (ejm: transformaciones, filtros, geoprocesamiento, etc)

En este caso fue necesaria la estandarización de la información inicialmente pues las visitas originamente son regitradas por persona y cada columna es una visita adicional, por lo tanto fue estructurada una fila por visita y con el formato de fecha necesario, posteriormente fue activada la característica de tiempo en la capa mediante las propiedades en arcMap.

## Descripción de los métodos / técnicas utilizadas para la visualización.
La visualización de los datos espacial se realizó en puntos por categorías, y otra producto de un análisis que genera agregación de los puntos con una simbología asociada al tamaño proporcional a la cantidad de puntos. Adicionalmente estan las gráficas de barras y la linea de tiempo.
Se deben utilizar dos métodos diferentes para representar los datos.
Cada método debe presentarse en un mapa diferente

## Descripción breve del procedimiento utilizado para publicar los mapas en la web

1. Se ingresa a la página web: carto.com
2. Se inicia sesión con la cuenta previamente creada
3. Se ingresa a Create a table, new table,Importar capas a CARTO.
4. Se ingresa a la opción de comenzar importando un shapefile (que tenemos comprimido en un archivo zip).
5. Seleccionamos el archivo para importarlo.
6. posteriormente click en la pestaña Map para visualizar nuestra capa en el mapa, y establecemos el BaseMap deseado. 
7. En el menú generamos una simbología por responsable de la visita (categorías), establecemos los colorres y el tamaño del circulo deseado.
9. Se adicionan los Widgets deseados, en este caso se adicionó el que permite graficar los datos en un diagrama de barras, y otro para visualizar el tiempo de los datos
10. Finalmente publicamos el mapa en la opción PUBLISH. 

## Ventajas / desventajas / dificultades de la publicación de mapas utilizando herramientas en la nube respecto al software desktop.

Es una herramienta que cuenta con un buen nivel de usabilidad, por lo tanto es muy amigable y rápida para la creación del mapa, pero es posible que se quede corta en cuanto a los Widgets pues opciones como filtros para el usuario final no estan disponibles, por otra parte al generar un análisis esto desaparece la capa original y se pierden las configuraciones realizadas sobre este, como también no permite generar esos análisis en capas temporales.

