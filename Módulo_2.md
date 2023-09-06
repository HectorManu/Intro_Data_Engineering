# Ecosistema de Ingenería de Datos

**Índice**
- [Ecosistema de Ingenería de Datos](#ecosistema-de-ingenería-de-datos)
  - [Descripción general del ecosistema de Ingenería de datos](#descripción-general-del-ecosistema-de-ingenería-de-datos)
    - [Dos tipos principales de respositorios de datos](#dos-tipos-principales-de-respositorios-de-datos)
    - [¿Qué sigue después de identificar los datos que se requieren?](#qué-sigue-después-de-identificar-los-datos-que-se-requieren)
  - [Tipos de Datos (estructurados, semiestructurados y no estructurados)](#tipos-de-datos-estructurados-semiestructurados-y-no-estructurados)
  - [Comprender diferentes tipos de formatos de archivos (delimitados, CSV, TSV, XML, PDF, XLS y JSON)](#comprender-diferentes-tipos-de-formatos-de-archivos-delimitados-csv-tsv-xml-pdf-xls-y-json)
    - [Archivos de texto delimitados](#archivos-de-texto-delimitados)
  - [Fuentes de Datos (archivos, bases de datos, web, API, flujos)](#fuentes-de-datos-archivos-bases-de-datos-web-api-flujos)
  - [Idiomas para profesionales de datos](#idiomas-para-profesionales-de-datos)
  - [Trabajar con diversas fuentes y tipos de datos](#trabajar-con-diversas-fuentes-y-tipos-de-datos)
  - [Resumen y aspectos destacados](#resumen-y-aspectos-destacados)
  - [Descripcion general de los repositorios de datos](#descripcion-general-de-los-repositorios-de-datos)
  - [RDBMS](#rdbms)
  - [No SQL](#no-sql)
  - [Data Warehouses, Data Marts y Data Lakes](#data-warehouses-data-marts-y-data-lakes)
  - [Consideraciones para la elección del repositorio de Datos](#consideraciones-para-la-elección-del-repositorio-de-datos)
  - [ETL, ELT y canalizacioens de Datos](#etl-elt-y-canalizacioens-de-datos)
  - [Plataformas de integración de Datos](#plataformas-de-integración-de-datos)
  - [Herramientas, bases de datos y repositorios de datos de elección](#herramientas-bases-de-datos-y-repositorios-de-datos-de-elección)
  - [Resumen y aspectos destacados](#resumen-y-aspectos-destacados-1)
  - [Fundamentos del Big Data](#fundamentos-del-big-data)
  - [Herramientas de procesamiento de Big Data: Hadoop, HDFS, Hive y Spark](#herramientas-de-procesamiento-de-big-data-hadoop-hdfs-hive-y-spark)
  - [Impacto del Big Data en la Ingeniería de Datos](#impacto-del-big-data-en-la-ingeniería-de-datos)
  - [Resumen y aspectos destacados](#resumen-y-aspectos-destacados-2)

## Descripción general del ecosistema de Ingenería de datos 

### Dos tipos principales de respositorios de datos
1. Transaccionales 
   1. Los sistemas transaccionales, también conodcidos como sistemas de procesamiento de transacciones o línea (o OLTP), están diseñados para almacenar un gran volumen de datos operativos diarios.
      1. Transacciones bancarias en línea
      2. Transacciones en cajeros automáticos 
      3. Reservas de aerolíneas
      4. Pueden ser relacionales y no relacionales
2. Analíticos
   1. También conocidos como sistemas de procesamiento analítico en línea (OLAP)
   2. Están optimizados para realizar análisis de datos complejos
   3. Incluye bases de datos relacionales y no relacinoales, almacens de datos, ercados de datos, Data lakes y Big Data.

> Nota: El tipo, formato, fuentes de datos y contexto de uso influyen en qué repositorio de datos es ideal.


### ¿Qué sigue después de identificar los datos que se requieren?

Una vez recopilados los datos de fuentes diapares, ese necesario, procesarlos, limipiarlos e integrarlo para que los usuarios puedan acceder a él a través de una única **interfaz**.

Esto lleva **data pipelines**, un conunto de herramientas y procesos que xubren todo el recorrido de los dados desde los sistemas de origen a los de destino.

Los datos se integran dentro de una canalización de datos mediante procesos como Extract-Transform-and-Load
  

## Tipos de Datos (estructurados, semiestructurados y no estructurados)

Los **datos estructurados** son datos que están bien organizados en formatos que se pueden almacenar en bases de datos y se presta a métodos y herramientas de análisis de datos esetándar

Los **datos semiestructurados** son datos que esetán organizados y se basan en metaetiquetas para agruparse y jerarquía.

Los **datos no estructurados** son datos que no están organizados convencionalmente en forma de filas y columnas en un formato particular.

> nota investigar si e historioco de un datawerhouse, y los data lakes
>
> Hacer un cuadro comparativos 
> data lake 
> data werhouse
> big data 
>
> con peros y contras y definiciones 
>

Diferentes soluciones de almacenamiento en la nube.

Características |Data Warehouse | Data lake | Big Data | Data mart
---|---|---|---|---
Propósito|Almacena datos estructurados <br> para análisis y repotes|Almacena datos estructurados, semiestructurados y no estructurados para análisis y aprendizaje automático|Almacenar grandes cantidades de datos estructurados, semiestructurados y no estructurados|Almacenar datos estructurados para análisis y reportes de una unidad de negocio específica
Tipo de datos|Estructurados|Estructurados, semiestructurados y no estructurados|Estructuraod, semiestructurados y no estructurados| Estructurados
Cantidad de datos|Grander cantidades|Muy grandes cantidades|Muy grandes cantidades|Pequeñas o grandes cantidades
Preprocesamiento|OLAP|ETL|ETL|OLAP
Velocidad| Rápido |Lento|Muy Lento |Rápido
Ejemplos|Bases de datos relacionales, OLTP, OLAP|Sistemas de archivos,, base de datos NoSQL, Hadoop|Sistemas de archivos, bases de datos NoSQL, Hadoop|Bases de datos relacionales, OLAP
Uso de datos|Análisis de negocios|Almacenamiento de datos|Análisis de datos, aprendizaje, automático y otras tareas de inteligencia artificial|Análisis de negocios 
___ |Almacena datos en un formato estructurado. Se trata de un repositorio central de datos previamente procesados para llevar a cabo análisis y obtener inteligencia empresarial. | Es un repositorio centra que contiene datos sin procesary y no estructurados. | --- | Almacenamiento útil par alas necesidades de un equipo o una unidad de negocios específico, con finanzas, merkating o ventas. 
____ |Varios origenes de de datos|---|---| Fuentes de datos menos diversas y menor tamaño
____ |Se almacenan en varias unidades empresariales. Integran los datos de toda la organización de forma centralizada para los análisis sean completos|---|---|Se centran en un único asunto y tienen un carácter más descentralizado. Suelen filtrar y resumir la información de otro almacenamiento de datos existente.
____ |---|---|---

<br>


Rol|Análista de datos|Científico de datos|Inteligencia de negocio|Ingeniero en datos
---|---|---|---|---
Responsabilidades|Recolecatar, limpiar y analizar datos para identificar tendencia y patrones.|Desarrollar y aplicar modelso de aprendizaje automático para resolver problemas comerciales| Comprender las necesidades comerciales y traducirlas en soluciones de datos.| Constuir y mantener sistemas de datos
Habilidadees y conocmientos|Matemáticas, estadística, análisi de datos, visualización de datos.|Matemáticas, estadística,d aprendizaje automático, programación.|Negocios, análisis de datos, comunicación.|Programación, arquitectura de datos, gesetión de sistemas.
||---|---|---

## Comprender diferentes tipos de formatos de archivos (delimitados, CSV, TSV, XML, PDF, XLS y JSON)

Comprender los distintos formatos son más adecuados de acuerdo con los requerimientos y rendimiento de la variedad de tipos de datos. 

### Archivos de texto delimitados 

Definición: 

   - Son archivos de texto utilizados para  almacenar datoscomo texto en el que cada línea, o fila, tien valroes separados por un delimitados, cuando un delimitados es una secuencia de uno o más caracteres para especificar el límite entre entidades o valores, pero los delimitadores más comunes son las **comas** (CSV), **tabulación**(TSV), **dos puntos**, **barra vertical** y **espacio**. 

Como profesional de datos, es importante comprender los diferentes tipos y formatos de archivos de datos. Los formatos de archivo estándar incluyen:

* **Formatos de archivos de texto delimitados:** Estos archivos almacenan datos como texto, con cada línea o fila que contiene valores separados por un delimitador, como una coma o una tabulación. Los formatos de archivos de texto delimitados son fáciles de leer y procesar, y se pueden abrir en una variedad de aplicaciones.
* **Hoja de cálculo Microsoft Excel Open XML (XLSX):** Este formato de archivo es utilizado por Microsoft Excel para almacenar hojas de cálculo. Las hojas de cálculo XLSX pueden contener datos en celdas organizadas en filas y columnas.
* **Lenguaje de marcado extensible (XML):** XML es un lenguaje de marcado utilizado para codificar datos. Los archivos XML son legibles tanto por humanos como por máquinas, y son independientes de la plataforma y del lenguaje de programación.
* **Formato de documento portátil (PDF):** PDF es un formato de archivo utilizado para presentar documentos de manera independiente del software, hardware y sistemas operativos. Los archivos PDF se pueden utilizar para almacenar documentos de texto, imágenes, audio y video.
* **Notación de objetos JavaScript (JSON):** JSON es un formato de datos basado en texto utilizado para transmitir datos estructurados a través de la web. Los archivos JSON son fáciles de leer y procesar, y se pueden utilizar con una variedad de lenguajes de programación.

Los formatos de archivo de texto delimitados son una buena opción para datos simples que no requieren una estructura compleja. Las hojas de cálculo XLSX son una buena opción para datos que necesitan ser formateados y organizados. XML es una buena opción para datos que necesitan ser intercambiados entre diferentes sistemas. PDF es una buena opción para documentos que necesitan ser compartidos de manera segura. JSON es una buena opción para datos que necesitan ser transmitidos a través de la web.

Al elegir un formato de archivo de datos, es importante considerar los siguientes factores:

* **El tipo de datos que se almacenarán:** Algunos formatos de archivo son mejores para ciertos tipos de datos que otros. Por ejemplo, los archivos de texto delimitados son una buena opción para datos numéricos, mientras que las hojas de cálculo XLSX son una buena opción para datos de texto y números.
* **La complejidad de los datos:** Algunos formatos de archivo son mejores para datos complejos que otros. Por ejemplo, XML es una buena opción para datos que necesitan ser organizados en una estructura compleja.
* **La necesidad de intercambio de datos:** Algunos formatos de archivo son mejores para el intercambio de datos que otros. Por ejemplo, JSON es una buena opción para datos que necesitan ser transmitidos a través de la web.
* **La necesidad de seguridad:** Algunos formatos de archivo son más seguros que otros. Por ejemplo, PDF es una buena opción para documentos que necesitan ser compartidos de manera segura.

Esperamos que este resumen te ayude a comprender los diferentes tipos y formatos de archivos de datos.

## Fuentes de Datos (archivos, bases de datos, web, API, flujos)

Las fuentes de datos no han sido tan dinámicas y diversas como hoy en día. 

* Los datos almacenados en bases de datos y almacenes de datos pueden utilizarse como fuente de análisis. 
  * Por ejemplo: 
    * Los datos de un sistema de transacciones minoristas se pueden utilizar para analizar las ventas en difernetes regiones, y los datos de un sistema de gestión de relaciones con el cliente se pueden utilizar para hacer proyecciones de ventas.
* Muchos proveedores de datos y sitios web proporcionan API o interfaces de programas de aplicaciones y sitios web.
* Las API entre sus muchas aplicaciones también se utilizan para esxtraer datos de diversas fuentes como bases de datos, dentro y fuera d ela organización.
* El web Scraping puede extraer datos relevantes de fuentes no estructuradas.
* **Los flujos de datos** son otra fuente ampliamente utilizada para agregar flujos constantes de fuentes como instrumentos, dispositivos y aplicaciones de LoT, datos de GPS de automóviles, computadoras, programas, sitios web y publicacioes en redes sociales.


* Aplicaciones pupulares de flujos de datos: 
  * Apache Kafka
  * Apacke Spark Streaming
  * Apache Storm

- Los canales RSS (Really Simple Syndication) son otra fuente de datos pupular.
  - Normalmente utilizada para captura de datos actualizados de foros en línea y sitios de noticias donde lso datos se actualizan de forma continua. 

## Idiomas para profesionales de datos

En este video, se discuten los lenguajes de programación más importantes para los profesionales de los datos. Estos se pueden dividir en tres categorías:

* **Lenguajes de consulta:** se utilizan para acceder y manipular datos en una base de datos. El lenguaje de consulta más popular es SQL.
* **Lenguajes de programación:** se utilizan para desarrollar aplicaciones y controlar el comportamiento de las aplicaciones. Los lenguajes de programación más populares para los profesionales de los datos son Python, R y Java.
* **Lenguajes de secuencias de comandos:** se utilizan para automatizar tareas repetitivas. Los lenguajes de secuencias de comandos más populares son Unix/Linux Shell y PowerShell.

**SQL**

* Es un lenguaje de consulta estructurado diseñado para acceder y manipular información procedente de bases de datos relacionales.
* Se utiliza para realizar operaciones como insertar, actualizar y eliminar registros en una base de datos; crear nuevas bases de datos, tablas y vistas; y escribir procedimientos almacenados.
* Es portable y se puede utilizar independientemente de la plataforma.
* Tiene una sintaxis simple similar al idioma inglés.
* Puede recuperar grandes cantidades de datos de forma rápida y eficiente.
* Se ejecuta en un sistema de intérprete, lo que significa que el código se puede ejecutar tan pronto como se escribe.

**Python**

* Es un lenguaje de programación de alto nivel, de propósito general y de código abierto ampliamente utilizado.
* Es excelente para realizar tareas de alto contenido computacional con grandes cantidades de datos.
* Tiene funciones integradas para casi todos los conceptos utilizados con frecuencia.
* Admite múltiples paradigmas de programación, lo que lo hace adecuado para una amplia variedad de casos de uso.

**R**

* Es un lenguaje y entorno de programación de código abierto para análisis y visualización de datos, aprendizaje automático y estadística.
* Es especialmente conocido por su capacidad para crear visualizaciones convincentes.
* Es un lenguaje de programación de código abierto independiente de la plataforma.
* Se puede combinar con muchos lenguajes de programación, incluido Python.
* Es altamente extensible.
* Facilita el manejo de datos estructurados y no estructurados.
* Tiene bibliotecas que ofrecen gráficos estéticos.
* Puede crear informes y aplicaciones web interactivas.

**Java**

* Es un lenguaje de programación orientado a objetos, basado en clases e independiente de la plataforma.
* Se encuentra entre los lenguajes de programación mejor clasificados que se utilizan en la actualidad.
* Se utiliza en una serie de procesos a través del análisis de datos, incluida la limpieza de datos, importación y exportación de datos, análisis estadístico y visualización de datos.
* Es perfectamente adecuado para proyectos en los que la velocidad es crítica.

**Unix/Linux Shell**

* Es un programa informático escrito para el shell UNIX.
* Es una serie de comandos UNIX escritos en un archivo de texto plano para lograr una tarea específica.
* Es más útil para tareas repetitivas cuya ejecución puede llevar mucho tiempo escribiendo una línea a la vez.
* Se utiliza para manipular archivos, ejecutar programas, tareas de administración del sistema, scripts de instalación y copias de seguridad.

**PowerShell**

* Es una herramienta de automatización multiplataforma y un marco de configuración de Microsoft.
* Está optimizado para trabajar con formatos de datos estructurados, como JSON, CSV, XML y API REST.
* Consiste en un shell de línea de comandos y un lenguaje de secuencias de comandos.
* Está basado en objetos, lo que permite filtrar, ordenar, medir, agrupar y comparar objetos.
* También es una buena herramienta para la extracción de datos, la creación de GUI y la creación de gráficos, paneles e informes interactivos.

En general, los profesionales de los datos deben tener un conocimiento básico de los tres tipos de lenguajes mencionados anteriormente. Esto les permitirá realizar una amplia gama de tareas relacionadas con el análisis de datos, desde la extracción de datos hasta la visualización de datos.

## Trabajar con diversas fuentes y tipos de datos

En este video, varios profesionales de datos hablan de sus experiencias de trabajo con una variedad de fuentes de datos y tipos de datos. Comparten sus desafíos y consejos para trabajar con datos complejos.

Un tema común es que las fuentes de datos pueden ser muy diferentes. Las bases de datos relacionales son una fuente de datos común, pero también hay bases de datos NoSQL, repositorios de big data y formatos de datos propietarios. Los datos también pueden estar en reposo, en transmisión o en movimiento.

Los profesionales de datos deben ser flexibles y capaces de aprender nuevas habilidades para trabajar con diferentes fuentes de datos. También deben ser conscientes de los desafíos específicos de cada tipo de fuente de datos.

Por ejemplo, los datos de registro son no estructurados, lo que puede dificultar su interpretación. Los datos XML pueden ser pesados y requerir mucho procesamiento. Los datos JSON son más eficientes que los XML, pero aún pueden ser difíciles de trabajar.

Los profesionales de datos también deben ser conscientes de los desafíos específicos de cada proyecto. Por ejemplo, un proyecto puede requerir la conversión de datos de un formato a otro. Esto puede ser un desafío si los formatos tienen diferentes requisitos.

En general, los profesionales de datos deben estar preparados para trabajar con una variedad de fuentes de datos y tipos de datos. Deben ser flexibles, adaptables y conscientes de los desafíos específicos que pueden encontrar.

Aquí hay algunos consejos específicos para trabajar con datos complejos:

* **Empieza con una comprensión clara de las necesidades del proyecto.** ¿Qué tipo de datos necesitas? ¿Cómo se utilizarán los datos?
* **Investiga las diferentes fuentes de datos disponibles.** ¿Cuál es el mejor formato para los datos que necesitas?
* **Utiliza herramientas y técnicas adecuadas para trabajar con datos complejos.** Hay muchas herramientas disponibles para ayudarte a trabajar con datos de diferentes tipos.
* **No tengas miedo de pedir ayuda.** Si te encuentras atascado, hay muchos recursos disponibles para ayudarte.

## Resumen y aspectos destacados 

El ecosistema de un ingeniero de datos es un conjunto de herramientas, marcos y procesos que se utilizan para extraer, preparar, analizar y visualizar datos.

Los datos se pueden clasificar según su estructura en datos estructurados, semiestructurados y no estructurados. Los datos estructurados son datos bien organizados que se pueden almacenar en bases de datos relacionales. Los datos semiestructurados son datos parcialmente organizados que pueden almacenarse en bases de datos NoSQL. Los datos no estructurados son datos que no se pueden organizar convencionalmente en filas y columnas.

Los datos se pueden encontrar en una variedad de fuentes, como bases de datos relacionales y NoSQL, API, servicios web, flujos de datos, plataformas sociales y dispositivos sensores.

Una vez que los datos se identifican y recopilan de diferentes fuentes, es necesario almacenarlos en un repositorio de datos para que puedan prepararse para el análisis. El tipo, formato y fuentes de datos influyen en el tipo de repositorio de datos que se puede utilizar.

Los profesionales de datos necesitan una gran cantidad de lenguajes que puedan ayudarlos a extraer, preparar y analizar datos. Estos se pueden clasificar como:

* Lenguajes de consulta, como SQL, utilizados para acceder y manipular datos de bases de datos.
* Lenguajes de programación como Python, R y Java, para desarrollar aplicaciones y controlar el comportamiento de las aplicaciones.
* Lenguajes Shell y Scripting, como Unix/Linux Shell y PowerShell, para automatizar tareas operativas repetitivas.

En resumen, el ecosistema de un ingeniero de datos es un conjunto de herramientas y procesos que ayudan a los profesionales de datos a extraer, preparar, analizar y visualizar datos.

Aquí hay algunos puntos adicionales que se pueden mencionar en el resumen:

* El ecosistema de un ingeniero de datos está en constante evolución, ya que aparecen nuevas tecnologías y métodos de análisis de datos.
* Los ingenieros de datos deben estar al tanto de las últimas tendencias en el campo para poder mantenerse competitivos.
* El ecosistema de un ingeniero de datos puede ser complejo, pero es importante entenderlo para poder utilizar los datos de manera efectiva.

## Descripcion general de los repositorios de datos

Un repositorio de datos es un conjunto de datos que han sido recopilados, organizados y aislados para que puedan usarse para operaciones comerciales o extraerse para informes y análisis de datos. Puede ser una infraestructura de base de datos pequeña o grande con una o más bases de datos que recopilan, administran y almacenan conjuntos de datos.

Los repositorios de datos se pueden clasificar en tres tipos principales:

* **Bases de datos:** Las bases de datos son una colección de datos organizados que se almacenan en un formato tabular. Las bases de datos pueden ser relacionales o no relacionales. Las bases de datos relacionales almacenan datos en filas y columnas, mientras que las bases de datos no relacionales almacenan datos de forma libre.
* **Almacenes de datos:** Los almacenes de datos son repositorios centralizados de datos que se recopilan de diferentes fuentes. Los almacenes de datos se utilizan para el análisis y la inteligencia empresarial.
* **Grandes almacenes de datos:** Los grandes almacenes de datos son repositorios de datos de gran tamaño que se utilizan para el análisis de big data.

Los repositorios de datos desempeñan un papel importante en las organizaciones. Ayudan a las organizaciones a organizar y almacenar datos de forma eficiente, lo que facilita el análisis y la toma de decisiones.

En resumen, los repositorios de datos son conjuntos de datos organizados que se utilizan para almacenar, administrar y analizar datos. Pueden ser grandes o pequeños, y pueden ser relacionales o no relacionales. Los repositorios de datos desempeñan un papel importante en las organizaciones al ayudarlas a organizar y almacenar datos de forma eficiente.

Aquí hay algunos puntos adicionales que se pueden mencionar en el resumen:

* Los repositorios de datos pueden ayudar a las organizaciones a mejorar su eficiencia operativa al proporcionar datos precisos y actualizados.
* Los repositorios de datos pueden ayudar a las organizaciones a tomar mejores decisiones al proporcionar información sobre los patrones y tendencias de los datos.
* Los repositorios de datos pueden ayudar a las organizaciones a identificar nuevas oportunidades de negocio al proporcionar información sobre los clientes y el mercado.

## RDBMS

En resumen, una base de datos relacional es una colección de datos organizada en una estructura de tabla, donde las tablas pueden vincularse o relacionarse en función de datos comunes a cada una.

Las tablas están formadas por filas y columnas, donde las filas son los "registros" y las columnas los "atributos".

Las bases de datos relacionales utilizan un lenguaje de consulta estructurado, o SQL, para consultar datos.

Las bases de datos relacionales tienen una serie de ventajas, como:

* Flexibilidad: se pueden agregar, eliminar o modificar tablas y columnas sin detener la base de datos.
* Redundancia reducida: los datos se almacenan una sola vez, lo que reduce la posibilidad de errores.
* Facilidad de copia de seguridad y recuperación ante desastres: las bases de datos relacionales se pueden exportar e importar fácilmente.
* Cumplimiento de ACID: los datos de la base de datos son precisos y consistentes, incluso en caso de fallos.

Las bases de datos relacionales se utilizan en una variedad de casos de uso, incluidos:

* Procesamiento de transacciones en línea (OLTP): las bases de datos relacionales son adecuadas para aplicaciones que requieren una gran cantidad de transacciones rápidas, como las tiendas en línea.
* Almacenes de datos: las bases de datos relacionales se pueden utilizar para almacenar y analizar datos históricos para inteligencia empresarial.
* Soluciones de IoT: las bases de datos relacionales se pueden utilizar para recopilar y procesar datos de dispositivos IoT.

Las bases de datos relacionales tienen algunas limitaciones, como:

* No funcionan bien con datos semiestructurados o no estructurados.
* Los esquemas y tipos de datos deben ser idénticos para migrar datos entre bases de datos relacionales.
* Las bases de datos relacionales tienen un límite en la longitud de los campos de datos.

A pesar de estas limitaciones, las bases de datos relacionales siguen siendo la tecnología predominante para trabajar con datos estructurados.

## No SQL

## Data Warehouses, Data Marts y Data Lakes

## Consideraciones para la elección del repositorio de Datos

## ETL, ELT y canalizacioens de Datos 

## Plataformas de integración de Datos 

## Herramientas, bases de datos y repositorios de datos de elección

## Resumen y aspectos destacados

## Fundamentos del Big Data

## Herramientas de procesamiento de Big Data: Hadoop, HDFS, Hive y Spark


## Impacto del Big Data en la Ingeniería de Datos

## Resumen y aspectos destacados 
