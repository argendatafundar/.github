## fundar.argendata 

![image](https://github.com/argendata/.github-private/assets/12114624/463008ec-f774-4fba-a847-f82b2240e8df)

# Sobre Argendata
Argendata es un proyecto de gran escala a través del cual [Fundar](https://fund.ar/) apuesta a crear un sitio de referencia en lo que concierne a datos sobre Argentina. En línea con las principales premisas de Fundar, Argendata tiene como objetivo aportar conocimiento e incidir en la conversación pública a partir de la evidencia, generando para tal fin un riguroso proceso para la generación de contenidos y gestión de datos. 

# Sobre los datos

Con el fin de alcanzar altos estándares de calidad de datos, se ha desarrollado un circuito de gestión de la información que se compone de dos procesos principales:  **(a)** aseguramiento de la calidad (_QA_) y **(b)** reproductibilidad del proceso de generación de datos. 

A su vez, las diferentes acciones de la gestión de datos pueden entenderse a partir de su vinculación con el proceso más amplio de generación de contenido de **argendata**. Esto es, por un lado, en la interacción con las y los investigadores durante la etapa de generación de datos, y por otro lado, en la necesidad de estandarizar y armonizar, tanto los datos como los procesos que los generaron. Podés profundizar sobre este tema acá.

En este espacio se disponibiliza las herramientas con las que abordamos cada una de los procesos las tareas antes reseñadas:

## (a) _QA_

### - `main` https://github.com/argendata/main 
Tiene como objetivo principal dar estructura organizativa al proyecto para simplificar los procesos de creación y ejecución de controles sobre los conjuntos de datos. Este programa permite tanto la administración del sistema de archivos compartido como la interacción para el _QA_ entre investigadores y el equipo de datos durante el proceso de generación de datos.

### - `geonomencladores` https://github.com/argendata/geonomencladores 
El repositorio contiene definiciones, código y conjuntos de datos que tienen por objetivo la normalización y herramientas para estandarizar información geográfica del conjunto de datos. 

## (b) Reproductibilidad

### - `etl` https://github.com/argendata/etl 
El proyecto procura la armonización del proceso de generación de datos: **_Explorar, Transformar y Cargar (ETL, por sus siglas en inglés)_**. El flujo de trabajo acá definido procura reducir la fricción de la actualización de datos, automatizando siempre que sea posible los pasos ejecutados por las y los investigadores de cada tópico. Desde la descarga de fuentes crudas, los procesos de limpieza y la generación de conjuntos de datos necesarios para las visualizaciones. 
 
### - `argendataR` https://github.com/argendata/argendataR 
Un paquete de `R` con un conjunto de funciones auxiliares del proceso de _ETL_ que procuran facilitar el flujo de trabajo con fuentes y outputs.

### - `data` https://github.com/argendata/data 
En este repositorio se comparten los datasets definitivos agrupados por tópicos que se disponibilizan para la descarga desde el sitio web de **argendata**. 

### - `data-transformers` https://github.com/argendata/data-transformers 
Biblioteca para `Python` que busca facilitar la escritura, ejecución, reproducibilidad y el versionado del código fuente que se realice para manipular datos estructurados. Forma parte del conjunto de herramientas de **argendata** para el análisis y procesamiento de datos manual-asistido. Tiene como principal objetivo formatear los datos según las necesidades del código utilizado por _Frontend_ para las visualizaciones. 

### - `transformers` https://github.com/argendata/transformers  
En este repositorio se comparten los scripts de `Python` que funcionan como “recetas” para la transformación de recursos de [data] para llevarlos al formato requerido por _Frontend_ para la visualización.  


