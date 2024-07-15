<div align='center'>
<a href="https://argendata.fund.ar">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/080bdfa5-0b90-4d54-855c-314ba2a17214" width="400">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/c9f824b8-1f0c-4974-b3a1-b545018af549" width="400">
    <img src="argendata.fund.ar"></img>
  </picture>
</a>

&nbsp;
&nbsp;
&nbsp;
</div>

<!-- # Sobre Argendata -->
Argendata es un proyecto de gran escala a través del cual [Fundar](https://fund.ar/) apuesta a crear un sitio de referencia en lo que concierne a datos sobre Argentina. En línea con las principales premisas de Fundar, Argendata tiene como objetivo aportar conocimiento e incidir en la conversación pública a partir de la evidencia, generando para tal fin un riguroso proceso para la generación de contenidos y gestión de datos. 

## Sobre los datos

El trabajo de recopilación, gestión y puesta a disposición de datos en Argendata se basa en tres pilares fundamentales que enmarcan las acciones, herramientas y procesos: **transparencia y reproducibilidad, calidad de datos y armonización.**

- **Administración de recursos:** desarrollo y mantenimiento de estándares y programas para facilitar la gestión, control y posprocesamiento de datos elaborados por investigadores, con el objetivo de minimizar la inherente distancia entre procesos de investigación individuales y la necesidad de información armonizada y coherente.

- **Control de calidad y reportes:** programas que permiten realizar consultas sistemáticas sobre la calidad de los datos, dados los estándares definidos por el proyecto.

- **Armonización del código fuente:** gestión de programas y flujos de trabajo para administrar de manera armónica el proceso de generación de datos,  con el objetivo de procurar la reproductibilidad y actualización de los datos en el tiempo.

A su vez, las diferentes acciones de la gestión de datos pueden entenderse a partir de su vinculación con el proceso más amplio de generación de contenido de **argendata**. Esto es, por un lado, en la interacción con las y los investigadores durante la etapa de generación de datos, y por otro lado, en la necesidad de estandarizar y armonizar, tanto los datos como los procesos que los generaron. 

Más concretamente, los datos publicados en Argendata salen de un proceso de trabajo de varias estapas. Estas son: 

- la generación de contenido por parte de investigadores (que incluye la generación de datos, instrucciones o código para su generación y la narrativas asociada a cada item o gráfico)
- la armonización de las instrucciones o código que genera los datos (incluyendo tanto el acceso a fuentes, como el procesamiento de las mismas)
- la transformación de datasets que serán utilizados por el Frontend para generar las visualizaciones.

En este espacio se disponibiliza las herramientas con las que abordamos cada una de los procesos las tareas antes reseñadas:


### - `qa` https://github.com/argendatafundarfundar/main 
Tiene como objetivo principal dar estructura organizativa al proyecto para simplificar los procesos de creación y ejecución de controles sobre los conjuntos de datos. Este programa permite tanto la administración del sistema de archivos compartido como la interacción para el _QA_ entre investigadores y el equipo de datos durante el proceso de generación de datos.

### - `geonomencladores` https://github.com/argendatafundarfundar/geonomencladores 
El repositorio contiene un diccionario de entidades geográficas normalizado para el uso de Argendata.  

### - `etl` https://github.com/argendatafundar/etl 
El proyecto procura la armonización del proceso de generación de datos: **_Explorar, Transformar y Cargar (ETL, por sus siglas en inglés)_**. El flujo de trabajo acá definido procura reducir la fricción de la actualización de datos, automatizando siempre que sea posible los pasos ejecutados por las y los investigadores de cada tópico. Desde la descarga de fuentes crudas, los procesos de limpieza y la generación de conjuntos de datos necesarios para las visualizaciones. 
 
### - `argendataR` https://github.com/argendatafundar/argendataR 
Un paquete de `R` con un conjunto de funciones auxiliares del proceso de _ETL_ que procuran facilitar el flujo de trabajo con fuentes y _outputs_.

### - `data` https://github.com/argendatafundar/data 
En este repositorio se comparten los datasets definitivos agrupados por tópicos que se disponibilizan para la descarga desde el sitio web de **argendata**. 

### - `data-transformers` https://github.com/argendatafundar/data-transformers 
Biblioteca para `Python` que busca facilitar la escritura, ejecución, reproducibilidad y el versionado del código fuente que se realice para manipular datos estructurados. Forma parte del conjunto de herramientas de **argendata** para el análisis y procesamiento de datos manual-asistido. Tiene como principal objetivo formatear los datos según las necesidades del código utilizado por _Frontend_ para las visualizaciones. 

### - `transformers` https://github.com/argendatafundar/transformers  
En este repositorio se comparten los scripts de `Python` que funcionan como “recetas” para la transformación de recursos de [`data`](https://github.com/argendatafundar/data) para llevarlos al formato requerido por _Frontend_ para la visualización.  

<!-- ![image](https://github.com/argendatafundar/.github-private/assets/12114624/463008ec-f774-4fba-a847-f82b2240e8df) -->

<a href="https://www.github.com/argendatafundar">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/user-attachments/assets/84831245-5f04-44d2-81f3-2ac1badf8ada">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/user-attachments/assets/628dd50f-0ebb-40bb-b1be-7f723516dc2c">
    <img src="github.com/argendatafundar"></img>
  </picture>
</a>
