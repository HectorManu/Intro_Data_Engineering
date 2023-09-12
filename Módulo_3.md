# Ciclo de vida de la Ingenería de Datos

**Índice**

## Factores para la selcción y diseño de un almacen de datos

1. **Tipos de Repositorio:** Se mencionan varios tipos de repositorios de datos, que pueden incluir bases de datos, almacenes de datos, centros de datos, grandes almacenes de datos o lagos de datos. La elección depende de las necesidades y el uso previsto de los datos.

2. **Tipo de Datos:** Se destaca la importancia de considerar el tipo de datos que se desea almacenar, ya sean estructurados, semiestructurados o no estructurados.

3. **Volumen de Datos:** Se aborda la necesidad de elegir un repositorio que pueda manejar grandes volúmenes de datos sin procesar, especialmente en el caso de datos a gran escala o Big Data.

4. **Uso Previsto de los Datos:** El diseño debe adaptarse al uso previsto de los datos, ya sea para sistemas transaccionales que requieren altas velocidades de lectura y escritura o para sistemas analíticos que necesitan tiempos de respuesta rápidos en consultas complejas.

5. **Escalabilidad:** Se discute la importancia de la escalabilidad, es decir, la capacidad del almacén de datos para crecer y adaptarse a las necesidades cambiantes de datos, cargas de trabajo y usuarios.

6. **Normalización:** Se menciona que la normalización, aunque importante para los sistemas transaccionales, puede afectar el rendimiento en sistemas analíticos, por lo que es necesario considerarla cuidadosamente.

7. **Consideraciones de Almacenamiento:** Se abordan los aspectos de rendimiento, disponibilidad, integridad y recuperabilidad de los datos, destacando la importancia de implementar medidas de seguridad y gobernanza de datos desde el principio.

8. **Privacidad y Seguridad:** Se destaca la necesidad de cumplir con regulaciones de privacidad y seguridad de datos como GDPR, CCPA e HIPAA, lo que implica el uso de técnicas de protección de datos y estrategias de privacidad en el diseño del almacén de datos.

## Seguiridad

Se exploran cuatro niveles clave de seguridad:

1. **Seguridad de la Información (Tríada de CIA):** La tríada de la CIA se refiere a la confidencialidad (control de acceso no autorizado), la integridad (validación de recursos no manipulados) y la disponibilidad (acceso de usuarios autorizados cuando sea necesario) de los datos. Estos principios son fundamentales en todas las facetas de la seguridad.

2. **Seguridad Física e Infraestructura:** Para garantizar la seguridad física de la infraestructura que alberga sistemas de TI, se aplican medidas como la autenticación de acceso, vigilancia las 24 horas, fuentes de alimentación redundantes y protección contra rayos. También se considera la ubicación de las instalaciones.

3. **Seguridad de la Red:** La seguridad de la red implica el uso de cortafuegos, control de acceso a la red, segmentación de la red, protocolos de seguridad y sistemas de detección de intrusiones para proteger las redes interconectadas y los datos en tránsito.

4. **Seguridad de la Aplicación:** La seguridad de las aplicaciones se logra mediante prácticas de ingeniería de seguridad, como el modelado de amenazas, el diseño seguro y la codificación segura. También se destacan las pruebas de seguridad para identificar y solucionar problemas antes de la implementación.

5. **Seguridad de Datos:** La seguridad de datos se aplica tanto a los datos en reposo (almacenados) como a los datos en movimiento (transmitidos). Se emplean sistemas de autenticación y autorización, así como cifrado para proteger los datos en reposo. Para los datos en movimiento, se utilizan métodos de cifrado como HTTPS, SSL y TLS.

6. **Gestión del Ciclo de Vida de Datos:** Se enfatiza la importancia de monitorear proactivamente y reaccionar ante violaciones de seguridad a lo largo del ciclo de vida de los datos. Esto requiere visibilidad, integración de procesos de seguridad, vigilancia e inteligencia de seguridad, y un historial de auditoría completo.

7. **Política de Seguridad a Nivel Corporativo:** Se menciona que cada empresa debe tener una política de seguridad a nivel corporativo que garantice la seguridad del negocio y la contribución de todas las partes interesadas a través de sistemas, procesos, políticas, personas y herramientas.

La seguridad en plataformas de datos empresariales es un enfoque multifacético que abarca desde la seguridad física hasta la seguridad de la aplicación y la gestión del ciclo de vida de los datos. La implementación efectiva de medidas de seguridad es esencial para proteger los activos de datos y garantizar el cumplimiento de las regulaciones de seguridad.

## Importancia de la seguridad de los datos 

Varios profesionales de datos destacan la importancia de la seguridad de los datos en el contexto de la ingeniería de datos. Subrayan que la seguridad de los datos es crucial, ya que los datos son un recurso extremadamente valioso en la actualidad. Aquí se resumen los puntos clave:

1. **Recurso Más Valioso:** Se enfatiza que, según la revista The Economist, los datos son considerados el recurso más valioso en el mundo actual, superando incluso al petróleo. Esto subraya la necesidad crítica de asegurar y proteger los datos de una organización.

2. **Responsabilidad de Todos:** La seguridad de datos, gobernanza y cumplimiento no deben ser preocupaciones exclusivas de los ingenieros de datos. Estos aspectos deben integrarse en todos los procesos organizacionales y ser responsabilidad de cada parte de la organización.

3. **Control de Acceso:** Es esencial implementar niveles de seguridad y roles adecuados para garantizar que cada usuario tenga el menor privilegio necesario para realizar sus tareas. Otorgar un exceso de acceso puede aumentar el riesgo de violaciones de datos.

4. **Amenazas Internas:** Se destaca que la mayoría de las amenazas a los datos provienen de dentro de la organización, no de fuentes externas. Es importante estar atento a los accesos no autorizados dentro de la organización y proteger los datos de manera efectiva.

5. **Restauración y Recuperación:** La capacidad de restaurar y recuperar datos es parte integral de la seguridad de los datos. Se considera que la pérdida de datos debido a fallos de hardware es una amenaza significativa para la seguridad de los datos.

En resumen, la seguridad de los datos es esencial para proteger un recurso valioso y evitar consecuencias catastróficas, como violaciones de datos y posibles cierres de empresas. Todos los miembros de la organización deben comprender su papel en la seguridad de los datos, y se deben implementar medidas efectivas para controlar el acceso y prevenir amenazas tanto internas como externas.

## Resumen y aspectos destacados 

1. **Arquitectura de Plataforma de Datos:** Se ha explicado que una plataforma de datos se compone de diversas capas funcionales, que incluyen la capa de recopilación de datos, la capa de integración y almacenamiento de datos, la capa de procesamiento de datos, la capa de análisis e interfaz de usuario, y la capa de canalización de datos. Cada una de estas capas cumple funciones específicas en el procesamiento y entrega de datos.

2. **Almacenamiento de Datos:** Se ha enfatizado la importancia de un repositorio de datos bien diseñado para garantizar la escalabilidad y el rendimiento de un sistema. La elección o diseño del almacén de datos se basa en consideraciones como el tipo de datos, el volumen, el uso previsto y las necesidades de seguridad y gobernanza.

3. **Tríada de CIA:** Se ha presentado la tríada de Confidencialidad, Integridad y Disponibilidad (CIA) como un enfoque fundamental para la seguridad de la información. Estos tres componentes son esenciales para una estrategia efectiva de seguridad en todas las facetas, incluida la infraestructura, la red, las aplicaciones y la seguridad de los datos.


## Modulo 2 Examen 1 

1. Cuál es uno de los paos intrinsecos prte de la capa de integración y almacenamiento de datos de una plataforma de datos

- Transformar y fucionar datos extraidos ya sea de forma logica o física

2. Sistemas de uso de captura transaccional de grander volumens de datos necesitan ser diseñador  para responder en tiempo a consultas complejas

False 

3. cuál es el rol de la detección de intrusos y la prevención de intrusos en el area de seguridad de red?

- Inspecionar el tráfico entrante en busqueda de intentos de intrusión y vulnerabilidades


## Cómo recopilar e importar datos 

1. **SQL (Lenguaje de Consulta Estructurado):** Se presenta SQL como un lenguaje de consulta utilizado para extraer información de bases de datos relacionales. SQL permite especificar qué datos recuperar, de qué tabla, cómo se deben agrupar los registros, la secuencia de resultados y la limitación de resultados.

2. **Consultas en Bases de Datos No Relacionales:** Se menciona que algunas bases de datos no relacionales también se pueden consultar utilizando SQL o herramientas de consulta similares, como CQL para Cassandra y GraphQL para Neo4J.

3. **API (Interfaces de Programación de Aplicaciones):** Se explica que las API son ampliamente utilizadas para extraer datos de diversas fuentes. Estas API se invocan desde aplicaciones que acceden a puntos finales que contienen los datos. Las API también se emplean para la validación de datos.

4. **Raspado Web (Web Scraping):** Se describe el raspado web como una técnica para descargar datos específicos de páginas web según parámetros definidos. Se utiliza para extraer información como texto, imágenes, vídeos y otros contenidos de sitios web.

5. **Canales RSS:** Se mencionan los canales RSS como una fuente para capturar datos actualizados de foros y sitios de noticias en línea donde la información se actualiza continuamente.

6. **Flujos de Datos:** Se explica que los flujos de datos son una fuente importante para recopilar datos en tiempo real de dispositivos, aplicaciones IoT, GPS y redes sociales.

7. **Plataformas de Intercambio de Datos:** Se presenta la idea de plataformas de intercambio de datos que facilitan el intercambio de datos entre proveedores y consumidores. Estas plataformas siguen estándares y protocolos definidos para garantizar la seguridad y la gobernanza de los datos.

8. **Fuentes de Datos Específicas:** Se menciona que existen muchas otras fuentes de datos específicas para diferentes necesidades, como tendencias de marketing, datos demográficos y datos de comportamiento del usuario.

9. **Importación de Datos:** Se aborda la importancia de cargar o importar datos en un repositorio de datos antes de procesarlos y analizarlos. Se mencionan las herramientas ETL (Extract, Transform, Load) y se resalta que diferentes tipos de datos y esquemas pueden requerir herramientas específicas y métodos.

## Data Wrangling


1. **Transformación Estructural:** Esta tarea implica cambiar la forma y el esquema de los datos, especialmente cuando provienen de diversas fuentes con diferentes formatos. Las uniones y sindicatos son transformaciones comunes para combinar datos de múltiples tablas.

2. **Normalización y Desnormalización:** La normalización se utiliza para limpiar bases de datos de datos no utilizados y reducir la redundancia, mientras que la desnormalización se utiliza para combinar datos de varias tablas para consultas más rápidas.

3. **Limpieza de Datos:** Las actividades de limpieza abordan irregularidades en los datos para garantizar un análisis preciso. Se inicia con la detección de problemas, seguida de la inspección mediante la creación de perfiles de datos y visualización. Los problemas comunes incluyen valores faltantes, duplicados, irrelevantes, tipos de datos incorrectos, formatos no estandarizados, errores de sintaxis y valores atípicos.

4. **Valores Faltantes:** Se destacan tres opciones para abordar valores faltantes: filtrar registros, obtener información si es intrínseca al caso de uso o utilizar la imputación basada en estadísticas.

5. **Datos Duplicados:** Los datos duplicados deben eliminarse para evitar resultados sesgados.

6. **Datos Irrelevantes:** Los datos que no son relevantes para el contexto del caso de uso pueden considerarse irrelevantes y eliminarse.

7. **Conversión de Tipos de Datos:** Se necesita para asegurar que los valores se almacenan como el tipo de datos correcto, como números o fechas.

8. **Estandarización de Datos:** Se aplica para asegurarse de que los valores sigan un formato o unidad de medida específicos.

9. **Errores de Sintaxis:** Los errores de sintaxis, como espacios en blanco adicionales, deben corregirse.

10. **Valores Atípicos:** Los valores que difieren significativamente de otros en el conjunto de datos pueden ser incorrectos o necesitar una revisión adicional.

## Herramientas para la manipulación de datos 

1. **Hojas de Cálculo (Excel/Google Sheets):** Estas herramientas ofrecen funciones y fórmulas integradas para identificar problemas, limpiar y transformar datos. También admiten complementos para importar datos de diferentes fuentes y realizar manipulaciones.

2. **OpenRefine:** Es una herramienta de código abierto que permite importar y exportar datos en varios formatos. OpenRefine facilita la limpieza y transformación de datos, además de expandirlos con servicios web y datos externos.

3. **Google DataPrep:** Este servicio en la nube permite explorar, limpiar y preparar datos estructurados y no estructurados de manera visual. Ofrece sugerencias en tiempo real para simplificar el proceso y detecta automáticamente esquemas y anomalías.

4. **Watson StudioIBM Data Refinery:** Disponible a través de IBM Watson Studio o Cloud Pak for Data, esta herramienta facilita la limpieza y transformación de datos con operaciones integradas. También detecta tipos de datos y aplica políticas de gobernanza de datos.

5. **Trifacta Wrangler:** Es un servicio basado en la nube que limpia y transforma datos del mundo real, permitiendo exportarlos a diferentes formatos. Destaca por sus funciones de colaboración en equipo.

6. **Python:** Python ofrece una amplia biblioteca y paquetes para la manipulación de datos. Algunas de las bibliotecas clave incluyen:
   - **Jupyter Notebook:** Una aplicación web de código abierto para la limpieza, transformación y análisis de datos.
   - **Numpy:** Ofrece soporte para matrices multidimensionales y funciones matemáticas de alto nivel.
   - **Pandas:** Facilita operaciones complejas en grandes conjuntos de datos con comandos de una sola línea.

7. **R:** También ofrece bibliotecas específicas para el manejo de datos desordenados, como Dplyr, Data.table y Jsonlite. Estas bibliotecas permiten investigar, manipular y analizar datos de manera efectiva.

La elección de la herramienta adecuada depende de factores específicos, como el tamaño de los datos, las estructuras de datos, las necesidades de limpieza y transformación, la infraestructura disponible, la facilidad de uso y la capacidad de aprendizaje del equipo. Cada herramienta tiene sus propias capacidades y dimensiones que se adaptan a diferentes casos de uso y requisitos.


## Resumen y aspectos destacados

1. **Recopilación de Datos:** Dependiendo de la fuente de datos, existen diversos métodos y herramientas disponibles para recolectar datos. Estos métodos incluyen lenguajes de consulta para bases de datos, APIs, Web Scraping, flujos de datos, fuentes RSS e intercambios de datos.

2. **Data Wrangling (Manipulación de Datos):** Una vez que los datos se han recopilado e importado, el proceso de Data Wrangling entra en juego para preparar los datos para el análisis. Esto implica una amplia gama de transformaciones y actividades de limpieza, que incluyen:
   - Manipulación y combinación estructural de datos mediante uniones y _____.
   - Normalización de datos para eliminar redundancias y datos no utilizados.
   - Desnormalización de datos para facilitar consultas más rápidas.

3. **Actividades de Limpieza de Datos:** El proceso de Data Wrangling también abarca actividades de limpieza que involucran:
   - Elaboración de perfiles de datos para detectar anomalías y problemas de calidad.
   - Visualización de datos mediante métodos estadísticos para identificar valores atípicos.
   - Solución de problemas como valores faltantes, datos duplicados, datos irrelevantes, formatos inconsistentes, errores de sintaxis y valores atípicos.

4. **Herramientas y Software:** Existe una variedad de software y herramientas disponibles para el proceso de manipulación de datos, incluyendo Excel Power Query, Hojas de cálculo, OpenRefine, Google DataPrep, Watson Studio Refinery, Trifacta Wrangler, Python y R. Cada uno de estos tiene sus propias características, fortalezas, limitaciones y aplicaciones específicas.

Estos conceptos y procesos son fundamentales para garantizar que los datos estén en condiciones óptimas para su análisis y que se puedan obtener resultados significativos a partir de ellos.

## Modulo 3 Exámen 2

1. ¿Cómo se recopilan los datus usando aplicación de interfaz de programación o APIs?

La API se invoca desde una aplicación para acceder a laba se datos, servicios web, datos de mercados y otras opciones de datos finales para reunión de los datos

2. ¿Cuál es una de las transformaciones estructurales más cumnes apra la combinación de datos de una o más tablas?

- Joins son uno de las transformaciones de esetructuras usadas para combinar datos de multiples tablas.

3. ¿Qué herramientas le permiten descubrir, limpiar y transformar datos con operaciones incorporadas?

- Watson Studio Refinery, tiene características incorporadas que te permiten descubrir, limpiar, y transformar los datos.



## Consultar y analizar datos 

Se exploraron diversas técnicas de consulta utilizadas para analizar datos en una base de datos. Estas técnicas son fundamentales para comprender mejor los datos y obtener información relevante. Algunas de las técnicas destacadas incluyen:

1. **Contar y Agregar Datos:** Se utiliza la función COUNT() para contar el número de filas o registros en un conjunto de datos y DISTINCT() para contar elementos únicos. También se emplean funciones de agregación como SUM(), AVG() y STDDEV() para obtener información resumida sobre columnas numéricas.

2. **Identificar Valores Extremos:** Se utilizan funciones como MAX() y MIN() para identificar los valores máximos y mínimos en una columna de datos.

3. **Cortar Datos:** La función SLICE() permite recuperar datos basados en condiciones específicas o rangos, como clientes que gastaron entre ciertos montos o viven en áreas específicas.

4. **Clasificar Datos:** La función ORDER BY() se utiliza para organizar los datos en un orden significativo, facilitando la identificación de patrones o tendencias.

5. **Filtrar Patrones:** Se emplea el operador LIKE() para filtrar registros basados en patrones de datos parciales, lo que es útil cuando se busca información que coincide parcialmente con un valor.

6. **Agrupar Datos:** La instrucción GROUP BY se usa para agrupar datos en función de una columna específica, permitiendo el análisis de datos agrupados, como el cálculo de sumas totales por categoría.

Estas técnicas de consulta son aplicables en varios lenguajes de consulta, incluido SQL para bases de datos relacionales, así como en lenguajes de consulta similares utilizados en bases de datos NoSQL como Cassandra CQL y Cypher para Neo4J. Estas herramientas son esenciales para realizar tareas básicas pero cruciales en el análisis de datos.

## Ajuste del rendimiento y solución de problemas 

1. **Canalización de Datos:** Se explicó que las canalizaciones de datos involucran el movimiento de datos desde su origen hasta su destino a través de múltiples sistemas, aplicaciones y procesos. Estas canalizaciones pueden verse afectadas por problemas de rendimiento como la escalabilidad, fallas de la aplicación, problemas de programación y la incompatibilidad de herramientas.

2. **Métricas de Rendimiento:** Se destacaron métricas clave para evaluar el rendimiento de las canalizaciones de datos, como la latencia, fallas, patrones de uso, utilización de recursos y tráfico de datos.

3. **Solución de Problemas de Rendimiento:** Se describió un proceso general para abordar problemas de rendimiento en canalizaciones de datos. Esto implica la recopilación de información sobre el problema, la verificación de las versiones de software y códigos fuente, la revisión de registros y métricas, y la posible reproducción del problema en un entorno de prueba.

4. **Optimización de Bases de Datos:** Se discutieron las métricas de rendimiento que deben monitorearse en las bases de datos, como cortes del sistema, capacidad de uso, ralentización de la aplicación y rendimiento de consultas. Además, se mencionaron las mejores prácticas para optimizar bases de datos, como la planificación de capacidad, la indexación, la partición y la normalización.

5. **Sistemas de Monitoreo y Alerta:** Se presentaron sistemas de monitoreo y alerta que proporcionan visibilidad del rendimiento de sistemas, bases de datos, aplicaciones y canalizaciones de datos en tiempo real. Estos sistemas incluyen herramientas de monitoreo de bases de datos, herramientas de gestión del rendimiento de aplicaciones y herramientas para monitorear el rendimiento de consultas y canalizaciones.

6. **Mantenimiento Preventivo:** Se mencionó la importancia del mantenimiento preventivo, que puede llevarse a cabo en función del tiempo o de condiciones específicas para identificar y abordar problemas antes de que afecten gravemente el rendimiento y la disponibilidad de los sistemas.

## Resumen y aspectos destacados 

## Modulo 3 examen 3

1. En este video, estamos usando una función para ver qué tan distribuido estavan los valores de precio de venta ¿Cuál función se utilizo?

- Standar Deviation

2.  ______________ helps you assess if the size of a workload is slowing down the system.

Monitorear la cantidad de datos que se procesan a travez de la canalización  a la vez que ayuda a evaluar si la carga de trabajo está relentizando el sistema.



## Gobernanza y cumplimiento 

La Gobernanza de Datos es un conjunto de principios, prácticas y procesos destinados a mantener la seguridad, privacidad e integridad de los datos a lo largo de su ciclo de vida. Un marco de gobernanza de datos abarca todos los aspectos del proceso de gestión de datos de una organización, incluyendo tecnologías, bases de datos y modelos de datos.

Las regulaciones de gobernanza de datos buscan principalmente proteger los datos personales y sensibles, que son aquellos que pueden identificar a una persona o contienen información que podría causarle daño, como datos sobre raza, orientación sexual o información genética.

Se mencionan regulaciones específicas como el Reglamento General de Protección de Datos (GDPR) de la Unión Europea y la Ley de Privacidad del Consumidor de California (CCPA) en los Estados Unidos, así como regulaciones específicas para la industria, como HIPAA en el ámbito de la salud, PCI DSS en el comercio minorista y SOX en el sector financiero.

La conformidad (compliance) se refiere a los procesos y procedimientos mediante los cuales una organización se adhiere a las regulaciones y realiza sus operaciones de manera legal y ética. Esto implica establecer controles y verificaciones para cumplir con las regulaciones y mantener un registro auditado de su conformidad.

Las consecuencias de no cumplir con las normas pueden ser severas, incluyendo sanciones financieras, daño a la reputación pública y pérdida de confianza. La conformidad es un proceso continuo que requiere una combinación de personas, procesos y tecnología en constante evolución.

A lo largo del ciclo de vida de los datos, desde la adquisición hasta la retención y eliminación, se deben tener en cuenta consideraciones específicas de gobernanza. Esto incluye la identificación de qué datos se recopilan, cómo se procesan, dónde se almacenan, con quién se comparten y cómo se retienen y eliminan. Se debe mantener un registro auditado de todas estas actividades.

Se mencionan herramientas y tecnologías que ayudan en el cumplimiento de las regulaciones, como la autenticación y el control de acceso, la encriptación y el enmascaramiento de datos, las opciones de alojamiento que cumplen con los requisitos de transferencia internacional de datos, la monitorización y alertas de seguridad, y la eliminación de datos.

En resumen, la gobernanza de datos y la conformidad son esenciales a lo largo del ciclo de vida de los datos, y las herramientas y tecnologías desempeñan un papel crucial en la implementación de un marco de gobernanza eficaz.

## Resumen y aspectos destacados




## Modulo 3 examen 4

1. ¿En qué etapa del ciclo de los datos se establece que proveedores externos tendrían acceso a los datos colectados?

- Data sharing
- 


## DataOps

DataOps, definido por Gartner, es una práctica colaborativa de gestión de datos que se enfoca en mejorar la comunicación, integración y automatización de flujos de datos entre gestores y consumidores de datos en toda una organización. El objetivo de DataOps es lograr una entrega predecible y una gestión de cambios de datos, modelos de datos y artefactos relacionados. Utiliza tecnología para automatizar la entrega de datos con los niveles adecuados de seguridad, calidad y metadatos para mejorar el uso y el valor de los datos en un entorno dinámico.

A medida que los conductos de datos y las infraestructuras de datos se vuelven más complejos y los equipos de datos y consumidores crecen, es necesario tener procesos de desarrollo y colaboración eficientes para gobernar el ciclo de vida de los datos y la analítica. DataOps ayuda a lograr esto mediante la gestión de metadatos, la automatización de flujos de trabajo y pruebas, repositorios de código, herramientas de colaboración y orquestación para gestionar tareas y flujos de trabajo complejos.

La metodología de DataOps consta de tres fases principales: Establecer DataOps, Iterar DataOps y Mejorar DataOps. Estas fases permiten una construcción y despliegue repetibles de análisis y conductos de datos, lo que asegura que los datos utilizados en la toma de decisiones sean relevantes, confiables y rastreables.

Los beneficios de utilizar la metodología de DataOps incluyen la automatización de la gestión de metadatos, la trazabilidad de la línea de datos, la automatización de flujos de trabajo y trabajos en el ciclo de vida de los datos, la optimización de procesos y la creación de una cultura basada en datos en la organización.

En resumen, DataOps es una metodología que ayuda a las organizaciones a mejorar la gestión de datos, hacer que los datos sean más confiables y seguros, y fomentar una cultura basada en datos. También brinda oportunidades de carrera para profesionales de datos, como ingenieros de DataOps, que se enfocan en el ciclo de desarrollo y despliegue de datos y análisis.