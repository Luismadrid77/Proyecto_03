# *Accidentes aéreos*

## **Contexto**
La **Organización de Aviación Civil Internacional (OACI)**, organismo de la Organización de las Naciones Unidas, quiere investigar en profundidad los accidentes producidos desde inicios del siglo XX. Para ello, les solicita la elaboración de un informe y un dashboard interactivo que recopile tal información. 

La OACI únicamente cuenta con un dataset sobre datos de accidentes de aviones, pero insta a la consultora de datos -de la que forman parte- que intente cruzar esta información con otras fuentes de su interés. Esto con el objetivo de obtener mayor claridad y consistencia en los fundamentos del estudio.

## *Desarrollo del trabajo*

1.) Realizamos una transfomración del CSV despues de extraerlo de nuestra fuente
+ *a)* Quitamos los valores null
+ *b)* realizamos cambios de tipo de datos de algunas columnas, ejem: a la columna *'fecha'*, se le cambio a tipo datatime
+ *c)* Despues de los datos limpios, pasamos desde python a MYSQL. Creamos la tabla en nuestra base de datos

2.) *Busqueda*

+ Buscamos un dataset que nos adicione información al primer dataset. En nuestro caso buscamos un datasets con los datos mejor proporcionados de los accidentes aéreos.

Importamos todos nuestros dataset a POWER BI y empezamos hacer nuestro analisis
+ Nuestros datasets están relacionados por la cantidad de fallecidos.
+ Creámos un mapa donde nos muestre la ruta de los Operarios
+ Creamos un gráfico de líneas donde se nos muestra la tripulación abordo por año
+ una tarjeta donde nos muestra la cantidad de fallecidos
+ Gráfico de barras aplicadas para ver los accidentes por operador
+ Histograma donde nos muestra los fallecidos por año 
+ Tabla multiple donde nos muestra la ruta, año y cantidad de fallecidos


