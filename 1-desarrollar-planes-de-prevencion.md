# Desarrollo de planes de prevención y concienciación en ciberseguridad

Esta unidad introduce los principios fundamentales de ciberseguridad, junto con los conceptos y la terminología esenciales en este campo. Se abordan amenazas comunes y se proponen medidas de seguridad para enfrentarlas. Luego, se enfoca en la importancia de involucrar a todo el personal de una organización en la protección cibernética a través de formación y concienciación. Se destaca la necesidad de un plan de prevención que incluya auditorías para evaluar su eficacia y sugerir mejoras pertinentes.

- Definir los principios generales de la organización en materia de ciberseguridad.
- Establecer una normativa de protección del puesto de trabajo.
- Especificar un plan de concienciación de ciberseguridad dirigido al personal empleado y desarrollar su material necesario.
- Realizar una auditoría para verificar el cumplimiento del plan de prevención y concienciación de la organización.

Contenido

- 1.1. Principios generales en materia de ciberseguridad
- 1.2. Normativa de protección del puesto de trabajo
- 1.3. Plan de formación y concienciación en materia de ciberseguridad
- 1.4. Materiales de formación y concienciación
- 1.5. Auditorías internas de cumplimiento en materia de prevención

## Introducción

Para empezar es necesario definir el concepto de ciberseguridad.
En la web Enclave de Ciencia' (https://enclavedeciencia.rae.es/) la definición de ciberseguridad es la siguiente:

> Sistemas de proteccion de los componentes de las infraestructuras de los sistemas de información y comunicaciones ante amenazas cibernéticas.

En relación con la ciberseguridad se encuentra en esta misma web el siguiente término:

> Aplicación de medidas de seguridad para proteger los diferentes componentes de los sistemas de información y comunicaciones de un ciberataque.

Ambos términos engloban lo que comúnmente se conoce como ciberseguridad. Una vez definida esta, parece lógico que el siguiente concepto que se necesita establecer es el de incidente.
Incidente: acontecimiento que ocurre de manera inesperada y que puede alterar el desarrollo normal de algo.

La definición de incidente debe precisarse según el contexto en el que se utilice, en este caso la ciberseguridad:

>Incidente de ciberseguridad: evento imprevisto que puede alterar, comprometer o dañar el funcionamiento de un sistema o la información contenida en él.

Hoy en día la ciberseguridad ya está implantada de manera generalizada en las empresas, organizaciones y gobiernos en mayor o menor medida, y estos últimos se preocupan de que las empresas que operan en sus países estén protegidas en materia de ciberseguridad. Por esta razón se pueden encontrar entidades y normativas gubernamentales sobre ciberseguridad, tales como:

- NIST (National Institute of Standards and Technology): el Instituto Nacional de Estándares y Tecnología de Estados Unidos, dependiente del Departamento de Comercio de EE. UU., brinda ayuda a las empresas a analizar, aa-ministrar y reducir sus riesgos de ciberseguridad para proteger sus sistemas de información y comunicación.
- CISA (Cybersecurity & Infrastructure Security Agency): dependiente del Departamento de Seguridad Nacional de EE.UU. se encarga de gestionar y reducir el riesgo cibernético.
ENISA (European Union Agency for Cybersecurity): es la agencia de la Unión europea para la ciberseguridad encargada de velar por la ciberseguridad en todo el territorio europeo, contribuyendo a la política de seguridad ciberne-tica de los miembros de la Unión e implementando mejoras en el ámbito de las tecnologías de la información y la comunicación.
Y concretamente en España se encuentran las siguientes entidades:
- INCIBE (Instituto Nacional de Ciberseguridad): organización dependiente del
Gobierno español dedicada al desarrollo de la ciberseguridad y de la confianza digital de ciudadanos, profesionales, empresas y, especialmente, de sectores estratégicos.
- CCN (Centro Criptológico Nacional): es el organismo responsable de dar respuesta a diferentes áreas de seguridad en tecnologías de la información, como la normativa, la formación, el desarrollo y la certificación.
- CCN-CERT (Equipo de Respuesta a Incidentes de Ciberseguridad del CCN): es el centro de alerta y respuesta nacional que ayuda a responder de forma rápida y eficiente a los ciberataques y a estar preparado ante las ciberame-nazas.
- ENS (Esquema Nacional de Seguridad): es una normativa de aplicación a todo el sector público y sus proveedores, que tiene por objetivo establecer la política de seguridad en la utilización de medios electrónicos que permitan una protección adecuada de la información.

Muchos de los contenidos de este libro se basan en las recomendaciones recogidas en la web de INCIBE, la cual incluye numerosas publicaciones y guías sobre ciberseguridad en diferentes ámbitos.

## Principios generales en materia de ciberseguridad

En las definiciones anteriores se puede observar que se repite un concepto, información, pero ¿qué se entiende por información cuando se habla de ciberseguridad?

> Información: se puede definir como un conjunto organizado de datos relevantes que se almacenan, procesan y comunican para la adquisición o representación de conocimiento.

![](https://upload.wikimedia.org/wikipedia/commons/4/46/Data_warehouse_overview.JPG)

La información puede encontrarse en diferentes foratitos; digital, escrita o impresa, así como representar una gran variedad de datos; imágenes, textos, numeros, esc. Tanto para organizaciones como para la ciudadanía, la información es un activo muy importante y es necesario implementar medidas de seguridad para protegerla. En este objetivo se enfoca la ciberseguridad, que busca preservar los principios básicos de la información, también conocidos como los principios básicos de la ciberseguridad.

### Principios básicos de la ciberseguridad

Los principios básicos de la ciberseguridad son aquellos elementos que al ponerse en riesgo comprometen la información, así como el buen funcionamiento de los sistemas que la procesan, almacenan o transmiten. Dependiendo de las fuentes consultadas se puede encontrar que estos principios son tres:

- Confidencialidad: garantiza que la información solo será conocida por quien tenga autorización expresa, es decir, nadie tendrá acceso a la información, ya sea accidental o deliberadamente, si no tiene permiso para ello.
- Integridad: esta propiedad asegura que la información no ha sido alterada y es fiable. La información a la que se hace referencia es tanto aquella que se encuentra almacenada como la que es transmitida.
- Disponibilidad: este principio responde a que las personas autorizadas tendrán acceso a la información cuando la requieran.
  
Estos principios se conocen como CIA (Confidentiality, Integrity, Availability).

![](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c5/CIAJMK1209-en.svg/1280px-CIAJMK1209-en.svg.png)

Otras fuentes incluyen dos principios adicionales:
- Autenticación: es la capacidad de verificar la identidad de quien accede a la información.
- No repudio: también conocido como irrenunciabilidad, es un servicio de seguridad que permite demostrar la participación de las partes en una comunicación. Es decir, el emisor no puede negar que realizó el envío porque el destinatario tiene pruebas de ello, y el receptor no puede negar que recibió el mensaje porque el emisor tiene pruebas de la recepción; es lo que se conoce como no repudio en origen, y no repudio en destino, respectivamente.
¿Quê elementos amenazan estos principios? ¿Cómo se pueden proteger? Estos principios son fundamentales, y asegurarlos supondrá implementar protocolos, la imativas de prevención, así como la utilización de tecnologías que ayuden o la implantación de medidas de seguridad.

### Amenaza, vulnerabilidad y riesgo
Antes de continuar con los principios básicos, es necesario definir una serie de conceptos que van a utilizarse a lo largo del libro en multitud de ocasiones porque están directamente relacionados con los incidentes de ciberseguridad. 

Estos conceptos son: 

- Amenaza
- Vulnerabilidad
- Riesgo

Una amenaza se puede definir como una circunstancia no deseada que debe identificarse de antemano para poder tomar decisiones en el caso de que surja.

En la ciberseguridad una **amenaza** se refiere a un potencial ataque malicioso, con el objetivo de obtener acceso no autorizado a un sistema de información, comprometiendo la seguridad del sistema, y llevando a cabo acciones dañinas para la organización. 

Por ejemplo, una amenaza podría ser un ciberdelincuente que quiere acceder a la red wifi de la organización.

En muchas ocasiones estas amenazas se deben a que el sistema en cuestión tiene vulnerabilidades. ¿Y qué es una vulnerabilidad?

La **vulnerabilidad** se refiere a una debilidad o fallo en el diseño, implementación o proceso de un sistema, generado en su origen o debido a una implantación errónea, que puede ser explotado por factores externos. En el contexto de la ciberseguridad la vulnerabilidad se refiere habitualmente a una brecha de seguridad en los componentes del sistema de información (software, hardware o red) que, cuando se explota, tiene un impacto negativo en los principios básicos de ciberseguridad. Las vulnerabilidades pueden ser errores de software, configuraciones incorrectas, controles de seguridad inadecuados e incluso
errores humanos.

Siguiendo con el ejemplo anterior, la vulnerabilidad sería que la red wifi tuviera una contraseña débil, fácil de descubrir.

Una vez descritos los conceptos de amenaza y vulnerabilidad es el momento de definir qué es el riesgo, ya que los tres conceptos están directamente relacionados en ciberseguridad.

El **riesgo** es la posibilidad de que se causen pérdidas o daños a activos de una organización cuando una amenaza explota con éxito una vulnerabilidad. Es decir, en el ejemplo supondría la posibilidad de que el ciberdelincuente descifrara la clave de la red wifi accediendo de esta manera a la red de la organización con la probabilidad de que acceda a información sensible.

[![](https://mermaid.ink/img/pako:eNp9kE1Ow0AMRq8y8qqV2kWTrLJAqtQTUMRqNmbGSSwyHjQ_IKh6Ko7AxZg2DVAW3fn5fbItH8B4S9BCN_o3M2BI6mGnRUvkyNIt9hwTOVSWVEEfHBr--pSlFjRps9iaxK9ebSauZq4mrmeuJ25mbpa_K9R6fadOw87F1pHgB_6X1S1Z35LNtfzpPOZRKOATj2zRns65ZM72nin2Xst16o-CFTgq32BbfnfQopSGNJAjDW0pLYZnDVqOJYc5-f27GGhTyLSC4HM_QNvhGAvlF4uJdox9QHfpHr8Bqi6JWg?type=png)](https://mermaid.live/edit#pako:eNp9kE1Ow0AMRq8y8qqV2kWTrLJAqtQTUMRqNmbGSSwyHjQ_IKh6Ko7AxZg2DVAW3fn5fbItH8B4S9BCN_o3M2BI6mGnRUvkyNIt9hwTOVSWVEEfHBr--pSlFjRps9iaxK9ebSauZq4mrmeuJ25mbpa_K9R6fadOw87F1pHgB_6X1S1Z35LNtfzpPOZRKOATj2zRns65ZM72nin2Xst16o-CFTgq32BbfnfQopSGNJAjDW0pLYZnDVqOJYc5-f27GGhTyLSC4HM_QNvhGAvlF4uJdox9QHfpHr8Bqi6JWg)

Figura 1.2. Relación entre amenaza, vulnerabilidad y riesgo. En teoría no todos los activos tendrán vulnerabilidades, ni todos se verán amenazados; cuando se dan ambas situaciones es cuando se habla de riesgo.

Es importante señalar que el riesgo nunca se puede eliminar por completo, pero se puede gestionar y reducir a un nivel aceptable mediante estrategias y medidas de seguridad, o simplemente se puede asumir si la probabilidad de que ocurra es baja o si la organización decide que no merece la pena implementar las medidas de seguridad para mitigarlo porque el impacto que puede causar en caso de ocurrencia es bajo.

### Amenazas a los principios básicos

En este apartado se presentan algunos de los riesgos que amenazan los tres principios fundamentales de la ciberseguridad:

- La confidencialidad se relaciona con el compromiso de cuentas de usuarios con o sin privilegios, también conocido como escalada de privilegios. Estos privilegios pueden obtenerse de varias formas: ingeniería social, phishing o usando técnicas de fuerza bruta entre otras, todas ellas encaminadas a obtener las credenciales para acceder al sistema.
- La integridad también se ve atacada por la escalada de privilegios, ya que una vez que el ciberdelincuente accede a la información puede alterar su contenido. Pero existen otros riesgos que amenazan la integridad, como puede ser, en el caso de información transmitida, el ataque conocido como man-in-the-middle (hombre en medio) donde el atacante puede manipular la información comunicada sin que el emisor ni el receptor sean conscientes de ello.
- La disponibilidad puede verse afectada, por ejemplo, por el robo de cableado de comunicaciones, lo que impediría la conexión o provocaría congestión del tráfico de red, dificultando el acceso a los sistemas o servicios.

A lo largo del libro se estudian con detalle las diferentes amenazas que están tipificadas.

### Medidas para mantener los principios de ciberseguridad

Una vez vistos ciertos riesgos que amenazan los principios fundamentales de ciberseguridad, se muestran a continuación algunas medidas de seguridad que mitigan estas amenazas:

- Confidencialidad: la educación y la concienciación en ciberseguridad son las medidas fundamentales para prevenir los ataques de ingeniería social, ya que pueden impedir a un ciberdelincuente obtener las credenciales de acceso de un usuario.
- Integridad: para prevenir un ataque de tipo MITM (man-in-the-middle) se pueden implementar varias medidas de seguridad como, por ejemplo, la implementación de protocolos de cifrado como TLS (Transport Layer Security, seguridad de la capa de transporte) o SSL (Secure Sockets Layer, capa de sockets seguros).
- Disponibilidad: en el caso de la amenaza de robo de cableado de comunicaciones, las medidas de seguridad deberán ser principalmente físicas, es decir, elementos que impidan el acceso directo al cableado o a la estancia
donde se encuentra.

Como se ha expuesto en este apartado, las medidas de seguridad para mantener a salvo los principios de seguridad pueden ser de muy diversa índole: formación, hardware, software, elementos de seguridad física, entre otros. A lo largo del libro se explicarán diversos tipos de medidas de seguridad aplicables en ciberseguridad.

![](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f1/Executive_Directors_meeting_Berlin_Wikimedia_Summit_2022%2C_workshop_3.jpg/640px-Executive_Directors_meeting_Berlin_Wikimedia_Summit_2022%2C_workshop_3.jpg)

La concienciación de los empleados y la ciudadanía es una de las más efectivas medidas de seguridad frente a los ataques de ingeniaría social.

### Auditorías 

Las auditorías de seguridad de la información, como cualquier otro proceso de auditoría, verifican el cumplimiento de leyes, estándares o procedimientos propios de la organización, a la vez que sirven para mejorar la calidad de los procesos al identificar lo que no funciona como debería.
El proceso de auditoría facilita la identificación de puntos débiles en los que trabajar posteriormente para la mejora continua de la organización.
En el ámbito de la seguridad de la información, lo habitual es que las organizaciones planteen tanto auditorías internas como externas con una frecuencia predeterminada y que se decide como parte del diseño de lo que se denomina el sistema de gestión de la seguridad de la información en la organización.
Las auditorías internas son realizadas por personal del departamento encargado de la seguridad de la información, que debe ser independiente del departamento de informática o TIC, y que se encarga de comprobar que las medidas de control seleccionadas a partir del análisis de riesgos se están implementando en los sistemas de información en todos los niveles que correspondan. En este caso el personal que realiza la auditoría conoce perfectamente a la organización, así como la arquitectura TIC y los sistemas de información implicados.
Sin embargo, en el caso de las auditorías externas, que son contratadas a un tercero, son personas externas a la organización las que tienen que verificar el cumplimiento. Esto hace que el proceso suela ser más largo y requiera de más dedicación por parte de los responsables de los sistemas de información y de otro personal implicado dentro de la organización, ya que deben transferir el conocimiento de la organización necesario para que se pueda realizar la verificación.



Figura 1.5. Las auditorías externas requieren a recopilación de mucha información desde distintas fuentes y en ellas deben participar aquellas personas que de determinados roles entro de la organización, por lo que suele ser común que se tengan que realizar entrevistas personales en las que se puede requerir información adicional.

Es habitual que las auditorías internas sean más frecuentes que las externas, no solo porque pueden ser más ágiles al ser parte de las funciones del personal de seguridad de la información, sino también porque las externas suponen un esfuerzo extra para el personal de la organización y suelen requerir un presupuesto adicional significativo.

Debido a la cantidad y tipo de información que el tercero recopila sobre la organización, es importante garantizar un acuerdo de confidencialidad por contrato antes de que se lleve a cabo la auditoría externa.

## Normativa de protección del puesto de trabajo

Cuando se trata de regulaciones de ciberseguridad en el lugar de trabajo, los diferentes países tienen leyes y regulaciones específicas para garantizar la protección de la información confidencial y la prevención de amenazas. Algunas de ellas son:

- ISO/IEC 27001: estándar internacional para sistemas de gestión de seguridad de la información. Proporciona un marco para que las organizaciones establezcan, implementen, mantengan y mejoren continuamente sus sistemas de gestión de seguridad de la información, incluidas políticas, procedimientos y controles.

- Reglamento general de protección de datos (GDPR) 3; reglamento de la Unión Europea (UE) que tiene como objetivo proteger los datos personales y la privacidad de los ciudadanos de la UE.

- Ley de protección de datos y garantía de los derechos digitales (LPDGDD)*: ley orgánica española cuyo objetivo es adaptar la normativa española sobre protección de datos al RGPD europeo. Este reglamento establece los requisitos y las responsabilidades en materia de protección de datos en empresas sobre cómo proceder con la información personal, así como los derechos que asisten a usuarios y consumidores.

Es importante que las empresas conozcan y cumplan la legislación en materia de ciberseguridad en el lugar de trabajo, con el objetivo de proteger la información confidencial, mantener la confianza de los clientes y mitigar el riesgo de amenazas.

En numerosas ocasiones los incidentes de ciberseguridad que se producen en las empresas se deben a acciones de los propios empleados, ya sean accidentales o intencionadas. La razón principal es que los usuarios tienen acceso a los sistemas de la empresa y a su información. Este es el motivo por el que se hace tan necesaria una normativa de protección del puesto de trabajo, que no solo protegerá los intereses de las empresas, sino también los de los propios empleados, lo que deriva en que es responsabilidad tanto de las empresas como de los empleados cumplir con esta normativa y tomar las medidas necesarias para garantizar un entorno de trabajo ciberseguro.

### Factores vulnerables en el puesto de trabajo

Como se vio en el Apartado 1.1.2, una vulnerabilidad es una debilidad en uno o varios elementos que pueden verse amenazados por un hecho no deseado que afecte al sistema.

En este apartado se van a analizar los factores vulnerables, es decir, susceptibles de verse afectados por hechos no deseados en el puesto de trabajo dentro del ámbito de la ciberseguridad.

En este punto hay que tener en cuenta que el puesto de trabajo se extiende más allá del lugar físico donde los empleados realizan sus funciones, sobre todo actualmente cuando la conectividad se aplica en cualquier aspecto laboral acompañada de una gran diversidad de dispositivos móviles (ordenadores, portátiles, smartphones, tabletas y los cada vez más populares dispositivos wearables). 

Muchas empresas permiten a los empleados lo que se denomina BYOD (Bring Your Own Device, trae tu propio dispositivo), por lo que deben cerciorarse de que incluso con los dispositivos propiedad de los empleados se cumpla con los controles de seguridad establecidos por la organización.

Figura 1.6. Puesto de trabajo tradicional, compuesto por una mesa con archivador o cajones para los documentos, un ordenador y en algunos casos una impresora. Pero el concepto de puesto de trabajo ha superado esta imagen para traspasar las paredes de la oficina.

Otro aspecto que hay que tener en cuenta es el auge del teletrabajo, que permite a los empleados trabajar desde sus casas para ayudar a la conciliación familiar, como bonificación, para evitar largos desplazamientos o incluso para reducir costes a las empresas, lo que en muchos casos aumenta la productividad. Pero este nuevo paradigma de trabajo también supone la necesidad de implementar medidas adicionales de seguridad.

Entonces cabe hacer una serie de preguntas sobre la actividad y el funcionamiento de la empresa para establecer qué elementos son necesarios proteger.

Algunas de estas preguntas serian:

- ¿Qué tecnologías utiliza la empresa?
- ¿Cómo se realiza el mantenimiento de sus sistemas informáticos?
- ¿Se ha implementado algún sistema de protección en los equipos informaticos?
- ¿Tienen los empleados conocimientos básicos sobre ciberseguridad?
- ¿Existe algún tipo de control de acceso físico a las instalaciones?
- ¿Cómo lleva a cabo la destrucción de documentos, soportes y dispositivos cuando ya no son necesarios?
- ¿Cuánta presencia tiene la empresa en internet (web, redes sociales, etcétera)?
- ¿Se cumple la legislación en materia de protección de datos?
- ¿Quién tiene acceso a la información sensible de la empresa?
- ¿Quién configura los sistemas de información?
- ¿Trabajan los empleados conectándose desde el exterior de las instalaciones?
- ¿Qué dispositivos utilizan los empleados para sus labores en la empresa?
- ¿Esos dispositivos los provee todos la empresa o algunos son propiedad de los empleados?
- ¿Están sus técnicos formados en ciberseguridad?

A partir de estas preguntas y sus posibles respuestas pueden considerarse los factores vulnerables de un puesto de trabajo actualmente:

- Hardware: los dispositivos físicos utilizados en el puesto de trabajo.
- Software: aplicaciones utilizadas para realizar las diferentes tareas.
- Comunicaciones: redes y sistemas de comunicación utilizados durante la realización de las funciones laborales.
- Instalaciones: dependencias físicas de la empresa.
- Datos: tanto aquellos que se tratan de manera digital como en formato físico.
- Personas: como se ha indicado al inicio de este apartado, muchos de los incidentes de ciberseguridad son causados por acciones de los propios empleados, por lo que también se considera un factor vulnerable, y en muchos casos se considera el eslabón más débil de la seguridad.
  
### Riesgos en el puesto de trabajo
El establecimiento de los factores vulnerables del puesto de trabajo forma parte del análisis de riesgos que se debe realizar para conocer a qué peligros está expuesta la organización. Los pasos para realizar un análisis de riesgos son estos:

1. Delimitar los activos que pueden ser objeto de amenazas (alcance del análisis).
2. Seleccionar cuáles de los activos son críticos, es decir, aquellos tan importantes que sus operaciones, reputación o existencia se verían gravemente comprometidas por su pérdida, robo, corrupción o acceso no autorizado.
3. Identificar las principales amenazas que pueden afectar a los activos.
4. Determinar el impacto que pueden tener estas amenazas sobre los activos y la probabilidad de que ocurran.
5. Comprobar las medidas de seguridad implantadas que mitigan las consecuencias o la probabilidad de las amenazas.
6. Finalmente, establecer el riesgo que aún persiste de que los activos estén expuestos a amenazas.
 
En este apartado se presentan algunos de los escenarios de riesgo que pueden producirse en el puesto de trabajo:

#### Escenarios de riesgo relacionados con el hardware:

- Utilización de dispositivos de almacenamiento externos (discos duros externos, pendrives, etc.), que son una forma frecuente de entrada de malware a los sistemas.
- Uso de dispositivos móviles y wearables, que son propensos a robos o pérdidas.
Escenarios de riesgo relacionados con el software
- Instalación de software no autorizado: este acto puede afectar al rendimiento y la seguridad de los equipos causando una infección aunque el sistema
esté protegido.
- Utilización de un paquete de software ofimático capaz de ejecutar macros: a través del código fuente de las macros se pueden realizar acciones no deseadas.
Escenarios de riesgo relacionados con las instalaciones
- No tener control de acceso a dependencias con material sensible (CPD, sala de comunicaciones, archivos, etcétera).
- Confiar en que nadie ajeno va a intentar entrar en las instalaciones cuando
están cerradas.

#### Escenarios de riesgo relacionados con los datos

- Uso de documentos en papel (manuscritos o impresos), los cuales son susceptibles de violaciones de la seguridad si se dejan a la vista.
- Confianza en que el formateo rápido o normal de un disco duro impedirá el acceso a los datos contenidos anteriormente. Actualmente existen aplicaciones que son capaces de recuperar la información formateada o sobrescrita en una unidad de disco.

#### Escenarios de riesgo relacionados con las comunicaciones

- No filtrar las entradas y salidas de la red de comunicaciones, permitiendo que puedan producirse conexiones al sistema de personas no autorizadas.
- Empleo de redes wifi públicas.

#### Escenarios de riesgo relacionados con las personas

- La aplicación de contraseñas por parte de los usuarios presenta varios escenarios de riesgos, como son: configurar contraseñas muy débiles por ser fáciles de recordar, usar la misma contraseña en todos los servicios y webs, o apuntar las contraseñas en papeles o archivos.
- La ingeniería social es cada vez más sofisticada y efectiva, engañando a los usuarios a través del correo electrónico, SMS o llamadas telefónicas.

Dependiendo de la actividad y los recursos de la organización que se estén analizando se pueden encontrar estos y otros escenarios de riesgos; por esta razón el estudio de riesgos debe ser específico para cada organización.

Con el análisis de riesgos se consigue identificar las posibles amenazas e impactos a los cuales está expuesta la organización, así como las vulnerabilidades que pueden ser aprovechadas por los ciberdelincuentes.
Como se ha visto al principio del apartado, el último paso del análisis de riesgos es delimitar el riesgo que se está dispuesto a asumir, y, en función de ello, diseñar una política de seguridad que reúna las medidas que hay que aplicar en el puesto de trabajo.

## Medidas de seguridad

La política de seguridad estará formada por un conjunto de pautas aplicables a los sistemas de la organización y de métodos utilizados para monitorizar su eficacia en la protección de los activos y el cumplimiento por parte de los empleados.

Estas pautas incluyen áreas como la seguridad física, personal, administrativa y de las comunicaciones, es decir, son las medidas de seguridad para proteger todos los activos de una organización. Además, se debe establecer su periodo de validez, los recursos disponibles para su implantación y los objetivos que se pretenden alcanzar.

Las medidas de seguridad se pueden clasificar en:

- Preventivas: son medidas que se toman para evitar o reducir los riesgos de que las amenazas se materialicen.
- Monitorización: son medidas establecidas para supervisar y controlar de manera continua un sistema.
- Correctivas: son medidas que se implementan para restaurar el sistema a su estado anterior después de un incidente de seguridad.

En posteriores unidades del libro se tratarán las medidas de monitorización y correctivas; este apartado se centra en las medidas preventivas, y se muestran clasificadas atendiendo a los escenarios y riesgos vistos en el apartado anterior:

### Medidas de seguridad relacionadas con el hardware:

- Deshabilitar los puertos USB de los equipos para evitar la conexión de pendrives o discos duros externos.
- Proteger el acceso a los dispositivos móviles con funciones de seguridad biométrica como las huellas dactilares o el reconocimiento facial.
- Medidas de seguridad relacionadas con el software:
- Trabajar habitualmente en el sistema como usuario sin privilegios, no como administrador o root, lo que dificultará la instalación de programas y la realización de cambios en la configuración y los valores del sistema.
- Desactivar la ejecución automática de macros en los paquetes de software ofimático.

### Medidas de seguridad relacionadas con las comunicaciones:

- Configurar firewalls (cortafuegos) que bloqueen las conexiones no deseadas al sistema pero permitiendo aquellas legitimadas dentro de la
empresa.
- Utilizar una red privada virtual (VPN) que cree una conexión segura y cifrada entre el dispositivo e internet para obtener una capa adicional de seguridad, incluso en redes wifi públicas.

### Medidas de seguridad relacionadas con las instalaciones:
- Implementar un control de acceso a la sala de servidores, por ejemplo con tarjetas personales codificadas.
- Instalar un sistema de alarma para alertar al personal de seguridad sobre posibles violaciones de seguridad.
- Medidas de seguridad relacionadas con los datos:
- Implantar una política de mesas limpias para que los documentos impresos no se dejen a la vista de personal no autorizado.
- Establecer un procedimiento de borrado de metadatos o datos ocultos mediante herramientas especializadas para minimizar el riesgo de conservar información recuperable en dispositivos desechables.

### Medidas de seguridad relacionadas con las personas:

- Utilizar contraseñas robustas, renovarlas periódicamente y, si es posible, usar un método de autenticación en dos fases (2FA).
- Formar a los empleados sobre la ingeniería social para que no proporcionen datos personales o bancarios, entre otras precauciones que se verán en el siguiente apartado.

Tras establecer las medidas de seguridad necesarias, los responsables de la organización tienen la obligación de informar de ellas a los empleados. Pero es importante destacar que no basta con plasmar estas medidas de seguridad en unos documentos, compartirlos con los empleados y esperar a que estos los lean, comprendan y acaten todo su contenido; es necesario diseñar un plan de formación y concienciación que capacite sobre estas medidas a todos los miembros de la organización.

>ACTIVIDAD PROPUESTA 1.2
>Medidas de seguridad para riesgos en el puesto de trabajo
>Amplía con un nuevo escenario de riesgo cada uno de los tipos vistos en el Apartado 1.2.2, y especifica las medidas de seguridad para cada uno de ellos, como se ha hecho en el Apartado 1.2.3, que pudieran incluirse en una política de seguridad para una empresa.

## Plan de formación y concienciación en materia de ciberseguridad

Una vez implantadas las medidas de seguridad que la organización ha considerado necesarias para mitigar los riesgos a los que está expuesta en materia de ciberseguridad, el siguiente paso es la concienciación y formación de las personas que van a trabajar con los distintos activos y sistemas afectados por esas medidas. Para ello debe establecerse un plan de formación y concienciación que tenga en cuenta a todos los trabajadores: usuarios, técnicos, administradores, gestores, etcétera.

La formación tiene la misión de capacitar al personal para prevenir, mitigar o dar respuesta a las posibles amenazas que puedan afectar al sistema.

La concienciación consiste en garantizar que todos los miembros de la organización están sensibilizados con la importancia de participar activamente en la seguridad de la información e involucrarlos a todos en la puesta en práctica de los distintos controles de seguridad, cada cual al nivel que le corresponda como responsable del uso o mantenimiento de los sistemas de información, mediante el cumplimiento de las políticas de seguridad establecidas.

El plan de formación y concienciación debe tener en cuenta:

- Todo el personal debe recibir una formación y concienciación iniciales:
- La formación estará más orientada al personal técnico que desempeñe funciones directas sobre la seguridad, la configuración de sistemas, el tratamiento de la información, la gestión de incidentes, etc. El resto del personal recibirá una formación básica en técnicas de ciberseguridad y buenas prácticas en el puesto de trabajo.
- La concienciación se hará de manera general para todo el personal de la organización.
- La concienciación y la formación deben refrescarse y actualizarse regularmente:
- La formación debe actualizarse cada vez que se producen cambios en el sistema, ya sean de hardware, software o instalaciones de red, entre otros.
- Es importante refrescar la normativa de seguridad relativa al uso responsable de los sistemas aunque no se produzcan incidentes.

### Criterios para el diseño

El objetivo de este plan es fomentar una cultura de ciberseguridad dentro de la organización y educar a todos los empleados sobre la importancia de la protección de datos, las prácticas seguras y las amenazas potenciales que pueden
comprometer los sistemas y los datos.

Por esta razón hay que tener en cuenta una serie de criterios que garantice que todos los empleados conocen, entienden y cumplen las normas y las medidas de protección en materia de ciberseguridad establecidas, así como los riesgos potenciales asociados al uso inadecuado de la tecnología, de manera que sean capaces de identificar actividades o comportamientos sospechosos, y que los notifiquen al personal especializado para que puedan analizarlos y gestionarlos.

#### Nivel inicial de conocimientos sobre ciberseguridad

Es un hecho que dentro de una organización habrá diferentes niveles de conocimiento sobre medidas de seguridad y buenas prácticas cuando se trabaja con los sistemas. Además se debe tener en cuenta al personal técnico que trabaja con los sistemas de información, que en general tendrá un nivel mayor de conocimientos sobre la seguridad de estos sistemas.
Por esta razón, previo a diseñar el plan de formación y concienciación, es recomendable realizar una evaluación para identificar el nivel existente de conocimiento sobre ciberseguridad entre el personal empleado. De esta manera se podrá elaborar un programa de capacitación que parta de los conocimientos iniciales y cubra las necesidades de concienciación y formación reales. De lo contrario se podría caer en el error de incidir en elementos que los empleados ya tienen interiorizados, lo que haría que el plan fuese tedioso y este hecho podría dificultar su implicación.

#### Roles existentes en la organización
La formación también deberá adaptarse a los diferentes roles y responsabilidades que el personal tiene en la organización, ya que en función de ello variarán
aspectos como:
- Información a la que tienen acceso.
- Sistemas con los que trabajan.
- Procesos que realizan.
- Personas con las que tienen relación laboral.
- Ubicaciones desde las que llevan a cabo sus funciones.

De esta manera, al diseñar la formación se evitará la jerga técnica cuando está dirigida a aquellos empleados que trabajan en otras áreas, que pueda confundir o diluir el mensaje. En estos casos será preferible utilizar términos sencillos que sean accesibles para el personal sin conocimientos tecnológicos.
Las funciones a las que se dedica cada empleado tambien influyen en los contenidos que se van a impartir en la formación, debido a que las amenazas no serán las mismas en todos los ámbitos de la organización.

Figura 1.9. Adaptar la capacitación a los riesgos de seguridad específicos que enfrenta cada rol favorecerá que la formación le sea más relevante y útil.
Tipo de información

Aparte de la información de acceso a los sistemas como contraseñas y credenciales de acceso las empresas disponen de diferentes tipos de información que deben protegerse de las amenazas de ciberseguridad. Aquí se muestran
algunos ejemplos:

- Documentos con datos financieros: las informaciones financieras, como detalles de cuentas bancarias y de crédito, son altamente codiciadas por los ciberdelincuentes.
- Datos procedentes de recursos humanos: estos pueden incluir información personal y sensible de los empleados.
- Información sobre salud: para las organizaciones de atención médica, la confidencialidad, la integridad y la disponibilidad son cruciales.
- Proyectos de infraestructuras críticas: para las empresas que operan en ciertos sectores la información relacionada con infraestructuras críticas es vital y debe protegerse.
- Y, en general, cualquier dato confidencial que la organización tenga almacenado digitalmente o archivado de clientes, proveedores o de la propia organización.

Además, es importante recordar que las organizaciones están obligadas, por la Ley Orgánica de Protección de Datos Personales y Garantía de los Derechos Digitales (LOPD GDD), a garantizar la privacidad de los datos personales de las personas que se los ceden, ya sean usuarios, clientes, empleados o proveedores.

### Servicios disponibles

Los servicios con los que trabaja la organización también hay que tenerlos en cuenta en el plan de concienciación y formación, ya que de algunos de ellos depende lo que se conoce como la identidad digital corporativa. Algunos de estos servicios sensibles podrían ser:

- Páginas web: la web de la empresa no es solo su escaparate online al resto del mundo. En muchos casos desde la página web se accede a otros servicios como:
- Tienda online.
- Acceso de los empleados a la intranet.
- Acceso a la zona de clientes, proveedores, etcétera.

Esto supone una puerta muy tentadora para los ciberdelincuentes, por lo que es vital que todos los miembros de la organización tengan los conocimientos necesarios para protegerla dentro de sus responsabilidades.

- Almacenamiento en la nube: el almacenamiento en la nube ofrece muchos beneficios; sin embargo, también conlleva ciertos riesgos de seguridad como que sus credenciales de acceso se vean comprometidas o que no se cumpla con la normativa de protección de datos personales.
- Redes sociales: la reputación de una entidad puede verse altamente afectada si se filtra información sensible a través de las redes sociales o si secuestran o suplantan el perfil de la organización en las redes sociales.

### Políticas de empresa

Otro aspecto importante que debe tenerse en cuenta a la hora de planificar la formación de la plantilla de una organización es cómo se trabaja en ella. Por ejemplo:

- Trabajo presencial y remoto: dependiendo de cómo acceden los empleados a los sistemas de información de la organización, la formación incluirá líneas de actuación diferentes.
- Dispositivos corporativos o BYOD (Bring Your Own Device): que los dispositivos móviles empleados sean propiedad de la organización, o que se permita que los empleados trabajen con sus propios dispositivos (lo que se conoce como BYOD), también exigirá no solo establecer un protocolo de registro y control de los dispositivos, sino también una concienciación sobre su uso.

### Otras características del negocio

Los programas de concienciación también deben adaptarse a otras peculiaridades de la organización que harán que tengan unas necesidades específicas:

- Tamaño de la organización.
- Ámbito de negocio.
- Horarios y turnos de trabajo.
- Localización y número de sedes.

### Contenidos de la formación

Aunque, como se ha indicado anteriormente, se recomienda partir de los conocimientos previos que ya tengan los empleados, la capacitación comenzará con conceptos básicos, y se profundizará más o menos en función de los resultados de esa evaluación preliminar.

Estos son algunos de los contenidos básicos que se podrían incluir en la formación:

- Utilización de contraseñas seguras y sistemas de doble verificación: instruir a los empleados sobre el uso de las contraseñas dificultará accesos no autorizados.
- Phishing: reconocer correos electrónicos sospechosos que pueden llevar a
revelar credenciales de acceso u otros datos sensibles.
- Peligros de las descargas y utilización de software no autorizado: no se debe permitir software no autorizado en dispositivos corporativos. Este software descargado de fuentes no confiables a menudo puede contener malware, virus o spyware ocultos. Estos programas maliciosos pueden comprometer la seguridad del sistema, robar información confidencial o proporcionar acceso no autorizado.
- Uso apropiado de internet: definir qué está permitido y qué no a la hora de utilizar la red y establecer conexiones en internet para que las actividades realizadas dentro del entorno laboral se hagan de una manera segura.
- Ingeniería social: establecer pautas sobre cómo evitar caer en la manipulación de los ciberdelincuentes que intentarán que les proporcionen información confidencial o personal o que hagan algo que les ayude a acceder a los sistemas de la organización. En muchos casos la ingeniería social estará asociada con el phishing.
- Uso de dispositivos de almacenamiento externo: los dispositivos de almacenamiento externos, como pendrives USB o discos duros externos, pueden presentar ciertos riesgos y peligros, como propagación del malware o perdida o robo de datos, ya que son altamente susceptibles de sufrir daños o extraviarse.
- Políticas de trabajo remoto: el trabajo remoto se ha vuelto cada vez más común y los empleados deben saber cómo hacer para que los accesos sean
seguros y mantener así la integridad de los datos y los sistemas.
- Redes inalámbricas: relacionado con el punto anterior, el trabajo remoto permite a los empleados trabajar desde cualquier lugar, incluso desde localizaciones con redes wifi públicas que pueden ser vulnerables al acceso no autorizado por parte de atacantes si no están protegidas adecuadamente.
- Actualización del software: las actualizaciones de software a menudo incluyen parches de seguridad que solventan vulnerabilidades y protegen contra amenazas potenciales, por lo que la actualización periódica del software ayuda a garantizar que las medidas de seguridad estén al día para proteger mejor los sistemas contra posibles ataques.
- Copias de seguridad: es esencial para la continuidad del negocio formar a los empleados sobre las copias de seguridad periódicas de los datos críticos y sobre el proceso de restauración para garantizar que los datos se puedan recuperar durante un incidente de seguridad.
- Notificación de incidentes: los empleados deben ser conscientes de la importancia de notificar cualquier hecho o actividad sospechosa de la que tengan conocimiento. Esta información permite a los equipos de seguridad responder de manera rápida y efectiva, ayudando a minimizar el impacto del incidente, evitando daños mayores. El plan de concienciación debe asegurar que los empleados conocen los canales de notificación.
- Ley de protección de datos: incluir también educación sobre los aspectos legales de las violaciones de datos, incluidas las sanciones por incumplimiento de las leyes de protección de datos.
- Política de mesa limpia: consiste en tener la mesa de trabajo despejada, solo con lo necesario para trabajar en ese momento y no dejar a la vista información sensible, sobre todo cuando el empleado se ausenta del puesto de trabajo, aunque sea por poco tiempo (Figura 1.10).

## Elaboración de un plan de formación y concienciación

En este apartado se proponen una serie de elementos indispensables para incluir en un plan de formación y concienciación.

### Objetivos

El objetivo general de diseñar un plan de formación y concienciación es fomentar una cultura de ciberseguridad dentro de la organización, es decir, educar a todo el personal empleado sobre la importancia de la protección de datos, las prácticas seguras y las amenazas potenciales que pueden comprometer los sistemas de información. En definitiva, se trata de reducir el número de incidentes.

### Evaluación de las necesidades de formación

Como se ha indicado anteriormente, es importante partir de los conocimientos previos de los empleados; por esta razón es primordial evaluar las necesidades de formación para identificar aquellas áreas de las que se carecen de los conocimientos necesarios y así adaptar el plan a las necesidades específicas de los empleados y asignar los recursos de manera más efectiva.

#### Roles incluidos en el plan de formación y concienciación

Cada empleado tiene un papel que desempeñar para garantizar que la infraestructura de información de la organización permanezca segura, por lo que es importante establecer en el plan los diferentes grupos de empleados, departamentos o roles de usuarios junto con sus funciones y responsabilidades.

En ocasiones, es necesario hacer subdivisiones de los grupos debido a características geográficas, horarias o logísticas. Por ejemplo:

- Si la organización tiene personal comercial trabajando en remoto y personal comercial trabajando en oficina, dentro del grupo comercial puede ser necesario crear un subgrupo «comercial remoto» y otro «comercial oficina» para en el primer grupo hacer formaciones online y para el segundo formación in situ.
- Si la empresa tiene turnos de mañana y tarde para el personal técnico, unificar su formación puede ser complicado; en este caso, también podría hacerse una subdivisión de este grupo para impartir formaciones en distintos tramos horarios que se adapten al horario laboral.

### Contenidos

Notificar a los miembros del personal sobre la situación de seguridad actual de la organización es el primer paso para involucrarlos en la educación sobre ciberseguridad.

Seguidamente se debe formar y concienciar a los empleados sobre los diferentes tipos de amenazas que pueden encontrar durante la realización de sus funciones y las buenas prácticas.

Los contenidos serán los que se han indicado en el Apartado 1.3.2, además de contenidos propios asociados a los activos y servicios de la empresa como los enumerados en el Apartado 1.3.1.

Asociación de roles y contenidos

Como se ha comentado anteriormente, uno de los criterios de diseño es el de los roles existentes en la organización, debido a que cada uno de ellos tendrá diferentes responsabilidades, tareas y necesidades de conocimiento; por esta razón es esencial adaptar el contenido a los roles específicos de los empleados
utilizando lenguaje, ejemplos y escenarios relacionados con el contexto laboral específico de cada rol para mejorar la comprensión y facilitar su aplicación al
día a día. Por ejemplo:

- Los empleados en general pueden recibir información sobre phishing e ingeniería social.
- Al personal técnico, además, se le ofrecerá una formación más avanzada sobre las últimas amenazas, administración de firewalls, prácticas de codificación segura, cifrado, uso de VPN y estrategias de respuesta a incidentes.

### Metodologías formativas

El siguiente apartado consiste en elaborar estrategias viables para alcanzar los objetivos de formación y concienciación. En estas estrategias se indicará:

- El grupo o subgrupo involucrado en la acción formativa.
- Los contenidos que hay que impartir.
- La metodología o sistema de formación: jornadas formativas, correos electrónicos, simulacros de ataques, etcétera.
- El calendario, es decir, se indicará con que periodicidad o en qué momento se llevará a cabo cada iniciativa de concienciación y formación. Como se verá en el próximo ejemplo, no siempre tiene que ser un periodo establecido; en ocasiones, la formación y la concienciación son necesarias por un hecho concreto acontecido.

TABLA PÁGINA 28

Para aplicar estas metodologías se necesitan una serie de materiales de concienciación con la información necesaria sobre los contenidos para ayudar a que la capacitación sea efectiva. Estos materiales se verán con más detalle en el Apartado 1.4.

Evaluación del plan de concienciación

El plan de concienciación y formación debe incluir una evaluación que mida el impacto en el comportamiento de los empleados y la mejora en la seguridad de la organización. Los objetivos de esta evaluación son:

- Comprobar las evidencias del plan.
- Actualizar el plan para que estén contemplados los riesgos en cada momento. En definitiva, inspeccionar si el plan está obteniendo los resultados deseados e identificar los ajustes necesarios.

Esta evaluación podría incluir pruebas para examinar la adquisición de los conocimientos, encuestas de opinión y revisiones para realizar un seguimiento de su cumplimiento.

Es interesante incluir en la evaluación enfoques más prácticos que ayudarán a evaluar cómo se afrontarán escenarios de la vida real. Por ejemplo:

- Campañas de phishing para comprobar si caen en la estafa que les llega por correo electrónico.

- Ataques simulados de ransomware para probar el conocimiento y la preparación de los empleados sobre cómo actuar al enfrentarse a esta situación.

Estas prácticas llevarán asociada una formación para aquellos empleados que han «picado» o no han actuado correctamente. La capacitación no debe ser un evento único, ya que constantemente surgen nuevas amenazas, por lo que el plan de concienciación debe actualizarse y aplicarse periódicamente.

Estos apartados para el plan de formación y concienciación son solo una propuesta, y algunos de los cuales pueden fusionarse o desglosarse en varios apartados. Además, se podrían incluir otros apartados relacionados con los costes previstos o presupuestos asignados al plan de concienciación.

## Materiales de formación y concienciación

Para llevar a cabo la formación y concienciación de los empleados se emplea una serie de materiales que ofrecerán información esencial sobre las amenazas, vulnerabilidades y medidas preventivas de ciberseguridad.

Estos materiales se usan como recursos educativos, algunos durante las fases de formación y concienciación como material didáctico, y otros como recordatorios y refuerzos de los contenidos clave de ciberseguridad. Estos materiales ayudan a reforzar las buenas prácticas y comportamientos en materia de ciberseguridad.

Algunos de los materiales se usarán para momentos concretos de la formación y concienciación, mientras que otros estarán accesibles para que los empleados los consulten cuando sea necesario.

### Tipos de materiales
INCIBE® propone en su kit de concienciación diversos tipos de materiales, como son:

- Pósteres/carteles: estos deben tener un título breve y atractivo que proporcione una comunicación inmediata y una imagen impactante que atraiga al destinatario.
- Presentaciones multimedia: se utilizarán principalmente para las jornadas y formaciones de un tema específico.
- Trípticos: un tríptico es un material de comunicación muy versátil que une la atracción inicial de un póster en su portada y en su interior sintetiza la información que se puede encontrar en una presentación. Además, en su contraportada suele incluir información de contacto.
- Encuestas de satisfacción: consultas a los empleados para recopilar comentarios sobre el plan de formación y concienciación.
- Ataques simulados de malware: utiliza diferentes métodos de entrenamiento, incluida la simulación de ataques. Esto puede ayudar a los empleados a comprender cómo podría ser un ataque real y cómo deberían responder.
- Campañas de simulación de phishing: envío de correos intentando que los empleados «piquen» en la estafa, para probar su conocimiento y preparación ante el phishing.

Los dos últimos pueden usarse tanto en la fase formativa como en la fase de evaluación del plan de concienciación.

ENISA (European Union Agency for Security) que, como se vio anteriormente, es la agencia de la Unión Europea para la ciberseguridad, también dispone de materiales de concienciación en su web,' como vídeos, pósteres, ilustraciones y salvapantallas.

Otros materiales interesantes son las plataformas de entrenamiento contra amenazas, de las cuales hay muchas en internet con recursos tanto de pago
como gratuitos.

Al elaborar los materiales se deben tener en cuenta los contenidos previstos en el plan de formación y concienciación y la información actualizada sobre las amenazas cibernéticas. Sobre este último punto es interesante consultar los boletines que INCIBE publica periódicamente en su web.

Figura 1.11. Propuesta de póster poniendo el foco sobre el peligro de las llamadas telefónicas de ingeniería social, que podría colocarse en las instalaciones de la organización aprovechando la época de Halloween.

Una vez recopilados los materiales que se van a utilizar para el plan de formación y concienciación, estos pueden distribuirse a través de diversos canales como correo electrónico, portales de la intranet corporativa, vídeos en las salas comunes, y carteles y trípticos repartidos por las instalaciones.

La ciberseguridad es un proceso global tanto del ámbito corporativo como del doméstico; quien no navega por páginas inseguras en su casa previsiblemente tampoco lo hará en su puesto de trabajo, por lo que además de estos materiales es interesante ofrecer a los empleados recursos para el autoaprendizaje en ciberseguridad como cursos sobre ciberseguridad personal.

>ACTIVIDAD PROPUESTA 1.4
>Material de concienciación
>Diseña un póster similar a los propuestos por INCIBE para concienciar a los empleados de una empresa sobre contraseñas seguras.

## Auditorías internas de cumplimiento en materia de prevención

Llegados a este punto hay que tener en cuenta que las empresas también deben evaluar periódicamente sus prácticas de ciberseguridad, es decir, revisar si ha sido efectiva la capacitación de los empleados, si están funcionando correctamente las medidas de seguridad implementadas y si se están cumpliendo las regulaciones sobre protección de datos y ciberseguridad. Es lo que se ha descrito anteriormente como evaluación del plan de concienciación.

Una forma de auditar el cumplimiento y la efectividad de las medidas de seguridad y de la formación y concienciación de los empleados es establecer métricas o indicadores de logro. Algunas de estas métricas podrían ser:

- Número de veces que se clica en un enlace de un correo de phishing.
- Frecuencia con la que se cae en un engaño de ingeniería social.
- Número de denuncias sobre posibles incidentes.
- Tasa de participacion en las jornadas y cursos de formación.
- Resultados de las pruebas de los empleados sobre los conocimientos impartidos.
- callicaciones de los certificados oficiales del personal técnico.
- Comparativa del número de incidentes acaecidos antes y después de la puesta en marcha del plan.
- Número de reinstalaciones de sistemas debido a infecciones por malware.

Además de establecer estos indicadores, es importante acotar qué resultados se consideran un logro y cuáles no, ya que estos límites pueden variar según los objetivos y las medidas implementadas. Y en caso de que el logro no sea el esperado habrá que establecer qué medidas se van a tomar al respecto. Otra opción interesante es establecer recompensas o reconocimientos cuando los logros se han alcanzado o se han superado las expectativas.

Por ejemplo, si más del 50% de los empleados hace clic en correos electrónicos de phishing simulados puede indicar que es necesario revisar el programa. Por el contrario, si solo un pequeño porcentaje «pica el anzuelo», puede que solo sea necesario un repaso más personalizado de los conocimientos abordados en el plan de concienciación.

También hay que tener en cuenta que la mejora de los indicadores no tiene que ser necesariamente resultado del cumplimiento de las medidas de seguridad; en algunos casos puede haber otras variables, como una disminución de ciertos tipos de ataques.

La frecuencia de las auditorías dependerá del tamaño y alcance de la organización, así como de los requisitos regulatorios que hay que cumplir por ley como en el caso de la Ley Orgánica 3/2018, de 5 de diciembre, de protección de datos personales y garantía de los derechos digitales.

Con el aumento de ciberataques y filtraciones de datos, es crucial que las empresas desarrollen planes de prevención y concienciación. La concienciación de los empleados sobre la ciberseguridad y la capacitación y actualización sobre las amenazas facilita que puedan actuar de manera efectiva en caso de incidente reduciendo significativamente el impacto de estos sobre los activos financieros y reputacionales de las organizaciones atacadas. Además, estos planes no solo protegen la información sensible y los activos de la empresa, sino que también salvaguardan los datos personales de los empleados y clientes.