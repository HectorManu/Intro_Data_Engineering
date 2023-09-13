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
  - [Modulo 2 exámen Examen 1](#modulo-2-exámen-examen-1)
  - [Resumen y aspectos destacados](#resumen-y-aspectos-destacados)
  - [Descripcion general de los repositorios de datos](#descripcion-general-de-los-repositorios-de-datos)
  - [RDBMS](#rdbms)
  - [No SQL](#no-sql)
  - [Data Warehouses, Data Marts y Data Lakes](#data-warehouses-data-marts-y-data-lakes)
  - [Consideraciones para la elección del repositorio de Datos](#consideraciones-para-la-elección-del-repositorio-de-datos)
  - [ETL, ELT y canalizacioens de Datos](#etl-elt-y-canalizacioens-de-datos)
  - [Plataformas de integración de Datos](#plataformas-de-integración-de-datos)
  - [Herramientas, bases de datos y repositorios de datos de elección](#herramientas-bases-de-datos-y-repositorios-de-datos-de-elección)
  - [Modulo 2 examen 2](#modulo-2-examen-2)
  - [Resumen y aspectos destacados](#resumen-y-aspectos-destacados-1)
  - [Fundamentos del Big Data](#fundamentos-del-big-data)
    - [Hadoop](#hadoop)
    - [Spark](#spark)
    - [Resumen:](#resumen)
    - [Tres tecnologías de código abierto y el papel que juegan en el análisis de](#tres-tecnologías-de-código-abierto-y-el-papel-que-juegan-en-el-análisis-de)
  - [Herramientas de procesamiento de Big Data: Hadoop, HDFS, Hive y Spark](#herramientas-de-procesamiento-de-big-data-hadoop-hdfs-hive-y-spark)
  - [Impacto del Big Data en la Ingeniería de Datos](#impacto-del-big-data-en-la-ingeniería-de-datos)
  - [Resumen y aspectos destacados](#resumen-y-aspectos-destacados-2)
  - [Modlulo 2 examen 3](#modlulo-2-examen-3)

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

## Modulo 2 exámen Examen 1 

1. Herramientas automáticas, frameworks, y procesos del almacenamiento para el proceso de análisis de datos es parte del ecosistema de Ingenería de Datos. ¿Qué papel juegan el rol de datos en este ecosistema? 

- Combinar multiples fuentes de datos en una vista unificada para el acceso de las consultas de los consumidores, consultas y manipulación de datos.

2. Cuál de los formatos de datos es proporcinado comunmente por APIs y servicios web para devolver datos?

- JSON 

3. Cuál es un ejemplo de una base de datos relacional?
- SQL Server

4. Cuál de los siguiente lenguajes es uno de los más pupulares de consultas usado hoy en día?

- SQL

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
* **Almacenes de datos(*data Warehouse*):** Los almacenes de datos son repositorios centralizados de datos que se recopilan de diferentes fuentes. Los almacenes de datos se utilizan para el análisis y la inteligencia empresarial.
* **Grandes almacenes de datos(*big data*):** Los grandes almacenes de datos son repositorios de datos de gran tamaño que se utilizan para el análisis de big data.

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

Las bases de datos NoSQL son un tipo de base de datos que no utiliza el modelo relacional tradicional de filas/columnas/tablas con esquemas fijos. En cambio, utilizan diferentes modelos de datos para almacenar datos de forma flexible y eficiente.

Las bases de datos NoSQL se utilizan cada vez más para aplicaciones modernas que requieren el almacenamiento de grandes volúmenes de datos estructurados, semiestructurados o no estructurados.

Existen cuatro tipos principales de bases de datos NoSQL:

* **Almacenes de valores clave:** almacenan datos como pares clave-valor, donde la clave identifica un único valor. Son adecuados para almacenar datos de sesión de usuario, preferencias de usuario, caché en memoria, etc.
* **Bases de datos de documentos:** almacenan datos como documentos JSON o XML. Son adecuados para almacenar datos de aplicaciones web, datos de comercio electrónico, etc.
* **Bases de datos de columnas:** almacenan datos en columnas, lo que las hace adecuadas para aplicaciones que requieren grandes volúmenes de escrituras, como el almacenamiento de datos de series temporales.
* **Bases de datos de gráficos:** almacenan datos como un gráfico de nodos y relaciones. Son adecuadas para aplicaciones que requieren el análisis de relaciones entre datos, como redes sociales, detección de fraude, etc.

Las bases de datos NoSQL ofrecen una serie de ventajas sobre las bases de datos relacionales tradicionales, entre las que se incluyen:

* **Mayor flexibilidad y escalabilidad:** las bases de datos NoSQL pueden almacenar y manipular datos de forma flexible, lo que las hace adecuadas para aplicaciones que requieren el procesamiento de grandes volúmenes de datos de diferentes tipos.
* **Menor coste:** las bases de datos NoSQL están diseñadas para hardware básico de bajo costo, lo que las hace más asequibles que las bases de datos relacionales tradicionales.

Sin embargo, las bases de datos NoSQL también tienen algunas desventajas, como:

* **Menor compatibilidad con ACID:** la mayoría de las bases de datos NoSQL no ofrecen la misma compatibilidad con ACID que las bases de datos relacionales tradicionales, lo que puede limitar su uso en aplicaciones que requieren transacciones seguras.
* **Menor madurez:** las bases de datos NoSQL son una tecnología relativamente nueva, por lo que puede haber menos documentación y soporte disponibles que para las bases de datos relacionales tradicionales.

En general, las bases de datos NoSQL son una opción adecuada para aplicaciones modernas que requieren el almacenamiento de grandes volúmenes de datos estructurados, semiestructurados o no estructurados.

## Data Warehouses, Data Marts y Data Lakes

Los repositorios de minería de datos son sistemas que almacenan datos para su análisis. Hay tres tipos principales de repositorios de minería de datos:

* **Data Warehouse:** almacenan datos estructurados de múltiples fuentes y los integran en una única fuente de verdad. Los almacenes de datos se utilizan para el análisis de grandes volúmenes de datos.
* **Data Mart:** son subconjuntos de un almacén de datos que se crean para un propósito específico, como el análisis de ventas o el análisis financiero. Los mercados de datos se utilizan para proporcionar a los usuarios los datos que necesitan para tomar decisiones.
* **Data Lake :** almacenan datos en su formato nativo, sin procesar. Los lagos de datos se utilizan para almacenar grandes volúmenes de datos de diferentes fuentes y para permitir a los usuarios explorar los datos para identificar tendencias y patrones.

Los repositorios de minería de datos se pueden implementar en la nube o en las instalaciones. Los repositorios de la nube ofrecen flexibilidad y escalabilidad, mientras que los repositorios en las instalaciones ofrecen mayor control y seguridad.

La elección del repositorio de minería de datos adecuado depende de las necesidades específicas de la organización. Si la organización necesita analizar grandes volúmenes de datos estructurados, un almacén de datos es una buena opción. Si la organización necesita proporcionar a los usuarios los datos que necesitan para tomar decisiones, un mercado de datos es una buena opción. Si la organización necesita almacenar grandes volúmenes de datos de diferentes fuentes y permitir a los usuarios explorar los datos para identificar tendencias y patrones, un lago de datos es una buena opción.

Aquí hay un resumen de las características y aplicaciones de cada tipo de repositorio de minería de datos:

**Almacenes de datos**

* Características:
    * Almacenan datos estructurados
    * Los datos están integrados en una única fuente de verdad
    * Los datos están preparados para el análisis
* Aplicaciones:
    * Análisis de grandes volúmenes de datos
    * Toma de decisiones

**Mercados de datos**

* Características:
    * Son subconjuntos de un almacén de datos
    * Se crean para un propósito específico
    * Los datos están preparados para el análisis
* Aplicaciones:
    * Proporcionar a los usuarios los datos que necesitan para tomar decisiones

**Lagos de datos**

* Características:
    * Almacenan datos en su formato nativo, sin procesar
    * Los datos se pueden almacenar de diversas fuentes
    * Los datos se pueden explorar para identificar tendencias y patrones
* Aplicaciones:
    * Almacenar grandes volúmenes de datos de diferentes fuentes
    * Explorar datos para identificar tendencias y patrones
Sata Warehouses ya están modelados y estructurados para un propósito específico. 

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

> Nota: ¿Big data debe ir en la siguiente tabla?


Características |Data Warehouse | Data lake | Data mart | Big Data
---|---|---|---|---
Propósito|Almacena datos estructurados <br> para análisis y repotes | Almacena datos estructurados, semiestructurados y no estructurados para análisis y aprendizaje automático| Almacenar datos estructurados para análisis y reportes de una unidad de negocio específica | Almacenar grandes cantidades de datos estructurados, semiestructurados y no estructurados 
Tipo de datos|Estructurados | Estructuraod, semiestructurados y no estructurados| Estructurados | Estructurados, semiestructurados y no estructurados
Cantidad de datos | Grander cantidades | Muy grandes cantidades | Pequeñas o grandes cantidades | Muy grandes cantidades
Preprocesamiento | OLAP | ETL | OLAP | ETL
Velocidad | Rápido | Lento | Rápido | Muy Lento
Ejemplos | Bases de datos relacionales, OLTP, OLAP | Sistemas de archivos,, base de datos NoSQL, Hadoop | Bases de datos relacionales, OLAP | Sistemas de archivos, bases de datos NoSQL, Hadoop
Uso de datos | Análisis de negocios|Almacenamiento de datos | Análisis de negocios | Análisis de datos, aprendizaje, automático y otras tareas de inteligencia artificial
___ | Almacena datos en un formato estructurado. Se trata de un repositorio central de datos previamente procesados para llevar a cabo análisis y obtener inteligencia empresarial. | Es un repositorio centra que contiene datos sin procesary y no estructurados. | Almacenamiento útil par alas necesidades de un equipo o una unidad de negocios específico, con finanzas, merkating o ventas. | ---
____ |Varios origenes de de datos|---| Fuentes de datos menos diversas y menor tamaño|---
____ |Se almacenan en varias unidades empresariales. Integran los datos de toda la organización de forma centralizada para los análisis sean completos|---|Se centran en un único asunto y tienen un carácter más descentralizado. Suelen filtrar y resumir la información de otro almacenamiento de datos existente.|---
____ |---|---|---





Podemos observar que la tabla anterior presenta big data pero la comparación no es justa debido a que no es una forma de gestionar los datos y los demás sí son una forma de gestionarlos ya que un data lake es un conjunto de datos no procesado, un data warehouse son datos ya procesados y consultados para elaborar análisis y por último se tiene al data mart que es un conjunto de datos tomado de un data warehouse donde se almacenan datos en específico para análisis de negocio.

Definir el Big data con una fuente de respaldo. 

<br>

> invertir el big data hasta al final para que haga alusión a que se manejarán los datos 

Rol|Análista de datos|Científico de datos|Inteligencia de negocio|Ingeniero en datos
---|---|---|---|---
Responsabilidades|Recolecatar, limpiar y analizar datos para identificar tendencia y patrones.|Desarrollar y aplicar modelso de aprendizaje automático para resolver problemas comerciales| Comprender las necesidades comerciales y traducirlas en soluciones de datos.| Constuir y mantener sistemas de datos
Habilidadees y conocmientos|Matemáticas, estadística, análisi de datos, visualización de datos.|Matemáticas, estadística,d aprendizaje automático, programación.|Negocios, análisis de datos, comunicación.|Programación, arquitectura de datos, gesetión de sistemas.
||---|---|---

## Consideraciones para la elección del repositorio de Datos

Estos factores incluyen:

* El caso de uso: ¿Para qué se utilizará el repositorio de datos?
* El tipo de datos: ¿Los datos son estructurados, semiestructurados o no estructurados?
* Los requisitos de rendimiento: ¿Qué nivel de rendimiento se necesita?
* Los requisitos de almacenamiento: ¿Cuánto espacio de almacenamiento se necesita?
* Los requisitos de seguridad: ¿Cómo se protegerán los datos?
* La compatibilidad: ¿Es compatible el repositorio de datos con los sistemas existentes?
* La escalabilidad: ¿Puede el repositorio de datos escalar para satisfacer las necesidades futuras?

Los profesionales de datos entrevistados recomiendan que las organizaciones tengan una variedad de repositorios de datos para satisfacer sus diferentes necesidades. Por ejemplo, una organización puede utilizar una base de datos relacional para el análisis de datos estructurados, un almacén de documentos para el almacenamiento de datos semiestructurados y un lago de datos para el almacenamiento de datos no estructurados.

También es importante tener en cuenta las habilidades y los costos de las diferentes soluciones. Por ejemplo, una organización que tiene muchos expertos en bases de datos relacionales puede querer elegir una base de datos relacional como su principal repositorio de datos.

En última instancia, la elección del repositorio de datos adecuado depende de las necesidades específicas de la organización.

Aquí hay algunos consejos adicionales para elegir un repositorio de datos:

* Evalúe las necesidades de su organización con cuidado.
* Considere los diferentes tipos de repositorios de datos disponibles.
* Compare los pros y los contras de cada opción.
* Consulte con expertos en datos para obtener ayuda.

## ETL, ELT y canalizacioens de Datos 

* **ETL:** extracción, transformación y carga.
* **ELT:** extracción, carga y transformación.
* **Canalizaciones de datos:** un sistema que abarca todo el recorrido de los datos.

**ETL** es el proceso tradicional de mover datos. Los datos se extraen de una fuente, se transforman en un formato utilizable y se cargan en un destino. Este proceso se puede realizar por lotes o en tiempo real.

**ELT** es una variación del proceso ETL en la que los datos se cargan primero en el destino y luego se transforman. Este enfoque es más adecuado para trabajar con grandes cantidades de datos no estructurados o no relacionales.

**Las canalizaciones de datos** son sistemas que abarcan todo el recorrido de los datos, desde la extracción de la fuente hasta la carga en el destino. Las canalizaciones de datos se pueden diseñar para procesamiento por lotes, transmisión de datos o una combinación de ambos.

Aquí hay un resumen de las ventajas de cada enfoque:

**ETL**

* Ventajas:
    * Es un proceso bien establecido y probado.
    * Se puede utilizar para una amplia gama de aplicaciones.
    * Es relativamente fácil de implementar y mantener.
* Desventajas:
    * Puede ser lento para procesar grandes cantidades de datos.
    * Puede ser difícil de escalar para satisfacer las necesidades cambiantes.

**ELT**

* Ventajas:
    * Es más rápido para procesar grandes cantidades de datos.
    * Es más fácil de escalar para satisfacer las necesidades cambiantes.
    * Es más flexible para análisis exploratorios.
* Desventajas:
    * Puede ser más difícil de implementar y mantener que el ETL.
    * No es adecuado para todos los tipos de aplicaciones.

**Canalizaciones de datos**

* Ventajas:
    * Es el enfoque más flexible para mover datos.
    * Se puede utilizar para una amplia gama de aplicaciones.
    * Es escalable para satisfacer las necesidades cambiantes.
* Desventajas:
    * Es el enfoque más complejo para mover datos.
    * Puede ser más costoso implementar y mantener que el ETL o ELT.

La mejor opción para mover datos depende de las necesidades específicas de la organización.

## Plataformas de integración de Datos 

La integración de datos es el proceso de combinar datos de diferentes fuentes para crear una vista unificada. Esto puede ser necesario para una variedad de propósitos, como análisis, informes y cumplimiento.

Una plataforma de integración de datos es un conjunto de herramientas y servicios que ayudan a las empresas a integrar datos. Las plataformas de integración de datos suelen incluir las siguientes capacidades:

* Conectores y adoptadores para conectarse a una amplia variedad de fuentes de datos
* Arquitectura de código abierto para mayor flexibilidad
* Optimización para el procesamiento por lotes y el streaming de datos
* Soporte para fuentes de Big Data
* Funcionalidades adicionales, como calidad y gobernanza de los datos, cumplimiento y seguridad
* Portabilidad para ejecutarse en la nube o en las instalaciones

Hay muchas plataformas y herramientas de integración de datos disponibles en el mercado, desde herramientas comerciales listas para usar hasta marcos de código abierto.

La integración de datos es una disciplina compleja que requiere una comprensión de las diferentes fuentes de datos, los requisitos de la empresa y las mejores prácticas. Las plataformas de integración de datos pueden ayudar a las empresas a simplificar el proceso de integración de datos y aprovechar los beneficios de los datos integrados.

Aquí hay algunos puntos clave del texto:

* La integración de datos combina datos de diferentes fuentes para crear una vista unificada.
* Una plataforma de integración de datos es un conjunto de herramientas y servicios que ayudan a las empresas a integrar datos.
* Las plataformas de integración de datos suelen incluir las siguientes capacidades:
    * Conectores y adoptadores para conectarse a una amplia variedad de fuentes de datos
    * Arquitectura de código abierto para mayor flexibilidad
    * Optimización para el procesamiento por lotes y el streaming de datos
    * Soporte para fuentes de Big Data
    * Funcionalidades adicionales, como calidad y gobernanza de los datos, cumplimiento y seguridad
    * Portabilidad para ejecutarse en la nube o en las instalaciones
* Hay muchas plataformas y herramientas de integración de datos disponibles en el mercado, desde herramientas comerciales listas para usar hasta marcos de código abierto.
* La integración de datos es una disciplina compleja que requiere una comprensión de las diferentes fuentes de datos, los requisitos de la empresa y las mejores prácticas.

## Herramientas, bases de datos y repositorios de datos de elección

En este video, varios profesionales de datos hablan de las herramientas, bases de datos y repositorios de datos que utilizan en su trabajo.

En general, los profesionales de datos utilizan una combinación de herramientas y tecnologías para realizar sus tareas. Estas herramientas pueden incluir:

* Bases de datos relacionales, como MySQL, PostgreSQL y SQL Server
* Bases de datos NoSQL, como MongoDB, Cassandra y Neo4j
* Herramientas de procesamiento de Big Data, como Apache Spark y Hadoop
* Herramientas de transmisión de datos, como Apache Kafka
* Herramientas de integración de datos, como Talend y Apache Airflow
* Herramientas de análisis de datos, como Tableau y Power BI

Los profesionales de datos también suelen utilizar lenguajes de programación, como Python, R y SQL, para automatizar tareas y crear nuevos procesos.

Algunos de los profesionales que aparecen en el video hablan de sus experiencias específicas con estas herramientas y tecnologías. Por ejemplo, un profesional habla de su trabajo con IBM DB2, un popular sistema de gestión de bases de datos relacionales. Otro profesional habla de su trabajo con Apache Airflow, una herramienta de orquestación de datos de código abierto.

En general, el video proporciona una visión general de las herramientas y tecnologías que utilizan los profesionales de datos en su trabajo. Es una información valiosa para cualquier persona que esté interesada en una carrera en ingeniería de datos.

Aquí hay algunos puntos clave del video:

* Los profesionales de datos utilizan una combinación de herramientas y tecnologías para realizar sus tareas.
* Las bases de datos relacionales, las bases de datos NoSQL y las herramientas de procesamiento de Big Data son herramientas comunes para los profesionales de datos.
* Los profesionales de datos también suelen utilizar lenguajes de programación para automatizar tareas y crear nuevos procesos.

Espero que esto ayude.

## Modulo 2 examen 2 

El termino repositorio de datos se refieere exlusivamente a un RBDMes y a bases de datos NoSQL que se utilizan para coleecionar, organizar y airlar datos para el análisis.

- Falso
  - El termino de repositorios de datos no incluye solamente bases de datos RBDMSes y SQL, esto también incluye Data Warehouses, Data Marts y data lakes

## Resumen y aspectos destacados

## Fundamentos del Big Data

**Las tecnologías de procesamiento de Big Data** proporcionaon formas de trabjaar con grandes conjuntos de datos estructurados y datos semiestructurador y no estructurados para que se pueda derivar valor de big data. 

### Hadoop

- Es una colección de herramientas que proporcionan almacenamiento y procesamiento distribuido de grande datos.
- Un marco de código abierto basado en Java, permite el almacenamiento y procesamiento distribuido de grandes conjuntos de datos en grupos de computadoras.
- Es un sistema distruibuido en el que un nodo es una sola computadora y una colección  de nodos forma un cúmulo.
- Posibilidades de escalar desde un solo nodo a cualquier número de nodos, cada uno de los cules ofrece almacenamiento local y computación.
- Porporciona una solución confiable, escalable y rentable para almacenar datos sin requisitos de formato.

**Usando Hadoop, puedes:**
- Incorporar formatos de datos emergentes, como transmisión de audio, video, sentimiento de las redes sociales y datos de secuncia de clics, junto con datos estructurados, semiestructurados y no estructurados que no tradicionalmente utilizado en un *data Warehouse*.
- Porporcine acceso de autoservicio en tiempo real para todas las partes interesadas.
- Optimice y agilice los costos en un *data warehouse* empresarial mediante la consolidación de datos en la organización y mover datos "fríos", es decir, datos que no se utilizan con frecuencia, a un sistema basado en Hadoop.

Uno de los cuatro componentes principales de **Hadoop** es el sistema de archivos distribuido **Hadoop** o **HDFS**, que es un sistema de almacenamiento para big data que se ejecuta en múltiples hardware básicos conectados a través de una red. 

**HDFS** proporciona almacenamiento de big daa eslable y confiable al divirid archivos en múltiples nodos. 
* Divide archivos grandes en varias computdoras, permitiendo el acceso paralelo a ellos. Por lo tanto, los cálculos pueden ejecutarse en paralelo en cada nodo donde se almacenan los datos.
* También replica bloques de archivoe en diferentes nodos para evitar la pérdida de datos, lo que lo hace tolerante a fallas.
* Recuperación rápida de fallas de hardware, porque **HDFS** admite altas tasas de rendimiento de datos.
* Alojamiento de grandes conjuntos de datos, porque **HDFS** puede escalar a cientos de nodos u computadoras, en un solo grupo.
* Portabilidad, porque **HDFS** es portátil a través de múltiples plataformas de hardware y compatible con una variedad de sistemas operativos subyacentes.



### Spark

**Spark** es un marco de análisis de datos distribuido diseñado para realizar análisis de datos complejos en tiempo real.

### Resumen:

1. **Apache Hadoop:** Se describe como una colección de herramientas que proporciona almacenamiento y procesamiento distribuido de grandes conjuntos de datos en grupos de computadoras. Hadoop puede escalar desde un solo nodo hasta un número ilimitado de nodos, y permite el almacenamiento de datos en diversos formatos, incluyendo datos emergentes como transmisiones de audio, video, redes sociales y datos de secuencia de clics. Proporciona acceso en tiempo real para todas las partes interesadas y ayuda a optimizar los costos de almacenamiento de datos empresariales mediante la consolidación de datos y la gestión de datos "fríos".

2. **Apache Hive:** Se presenta como un almacén de datos construido sobre Hadoop que se utiliza para consultas y análisis de datos. Hive es adecuado para tareas de almacenamiento de datos como ETL, informes y análisis, y ofrece acceso a los datos a través de SQL. Sin embargo, debido a su naturaleza basada en lectura, puede tener una latencia alta y no es ideal para aplicaciones que requieren respuestas rápidas o procesamiento de transacciones.

3. **Apache Spark:** Se describe como un motor de procesamiento de datos de propósito general diseñado para una amplia gama de aplicaciones, incluyendo análisis interactivos, procesamiento de flujos, aprendizaje automático, integración de datos y ETL. Spark aprovecha el procesamiento en memoria para acelerar los cálculos y puede ejecutarse en diversas infraestructuras, incluyendo Hadoop. Ofrece interfaces para varios lenguajes de programación y puede acceder a datos de diversas fuentes, como HDFS y Hive. Su capacidad para procesar datos en streaming rápidamente y realizar análisis complejos en tiempo real es un caso de uso clave.

****

### Tres tecnologías de código abierto y el papel que juegan en el análisis de 

## Herramientas de procesamiento de Big Data: Hadoop, HDFS, Hive y Spark

## Impacto del Big Data en la Ingeniería de Datos

 El Big Data se define mediante las cuatro "V": velocidad, veracidad, volumen y variedad. Esta revolución ha diversificado y enriquecido la ingeniería de datos, ya que las organizaciones recopilan una cantidad cada vez mayor de datos, lo que aumenta la importancia de extraer conocimientos de ellos.

El Big Data ha dado lugar a nuevas tecnologías y productos relacionados con el manejo de grandes volúmenes y variedades de datos, lo que ha generado una gran demanda de profesionales capaces de trabajar eficazmente en la construcción, gestión y análisis de sistemas de Big Data. La aparición del Internet de las cosas (IoT) y las redes sociales ha cambiado la forma en que los datos se ingresan en las bases de datos, lo que ha impulsado la evolución de la ingeniería de datos.

Antes, los sistemas de gestión de bases de datos relacionales (RDBMS) no eran la solución única para todos los tipos de datos. Con la diversidad de fuentes y volúmenes de datos, la ingeniería de datos ha evolucionado significativamente. Los ingenieros de datos han tenido que desarrollar nuevas herramientas y aprender nuevas tecnologías, como Google BigTable, Cassandra, bases de datos basadas en gráficos, Hadoop y MapReduce, para analizar petabytes de datos.


## Resumen y aspectos destacados 

Resumen:

En esta lección, has aprendido lo siguiente:

1. **Big Data:** Se refiere a la gran cantidad de datos que se produce constantemente cada día, generados por personas, herramientas y máquinas. La velocidad, el volumen y la variedad de estos datos han desafiado las herramientas y sistemas utilizados para los datos convencionales, lo que ha llevado al surgimiento de herramientas y plataformas de procesamiento diseñadas específicamente para Big Data. Estas tecnologías de procesamiento de Big Data ayudan a extraer valor de los datos y pueden incluir bases de datos NoSQL, lagos de datos y tecnologías de código abierto como Apache Hadoop, Apache Hive y Apache Spark.

2. **Hadoop:** Es una plataforma que proporciona almacenamiento y procesamiento distribuido de grandes conjuntos de datos en clústeres de computadoras. Uno de sus componentes clave es HDFS, el sistema de archivos distribuido de Hadoop, que se utiliza para almacenar datos a gran escala.

3. **Hive:** Es un software de almacén de datos que permite leer, escribir y gestionar grandes conjuntos de datos.

4. **Spark:** Es un motor de procesamiento de datos de propósito general diseñado para extraer y procesar grandes volúmenes de datos de manera eficiente.

Estas tecnologías son esenciales para abordar los desafíos y las oportunidades que plantea el Big Data en la actualidad, y cada una de ellas desempeña un papel fundamental en el procesamiento y análisis de datos a gran escala.

## Modlulo 2 examen 3

1. ¿qué implica el atributo velocidad en el contexto de Big Data?

La velocidad a la que se acomulan los datos

2. Cuál de las herramientas de procesamiento de de Big data provee un almacenamiento distribuido y procesamiento de Big Data?

Hadoop, es un java-based basado en open-source framework, que permite el almacenamiento distribuido y procesamiento de grander datasets a través de un cluster de computadoras.
