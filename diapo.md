---
marp: true
theme: default
class: invert
size: 16:9
style: |
  img {background-color: transparent!important;}
  a:hover, a:active, a:focus {text-decoration: none;}
  header a {color: #ffffff !important; font-size: 30px;}
  footer {color: #148ec8;}
header: '[&#9671;](#1 " ")'
footer: 'Slides by [Chris](http://www.christopherhahne.de)'
---

# Desarrollo de planes de prevención

En este módulo abordaremos los siguientes temas:

- Definir los principios generales de la organización en materia de ciberseguridad.
- Establecer una normativa de protección del puesto de trabajo.
- Especificar un plan de concienciación de ciberseguridad dirigido al personal empleado y desarrollar su material necesario.
- Realizar una auditoría para verificar el cumplimiento del plan de prevención y concienciación de la organización.

---

## Introducción

La definicion de la RAE de ciberseguridad es la siguiente:

> Sistemas de proteccion de los componentes de las infraestructuras de los sistemas de información y comunicaciones ante amenazas cibernéticas.

También encontramos la siguiente definición:

> Aplicación de medidas de seguridad para proteger los diferentes componentes de los sistemas de información y comunicaciones de un ciberataque.

---

La definición de *incidente* es importante para entender la ciberseguridad:

> Acontecimiento que ocurre de manera inesperada y que puede alterar el desarrollo normal de algo.

Una definición en el contexto de ciberseguridad:

> Evento imprevisto que puede alterar, comprometer o dañar el funcionamiento de un sistema o la información contenida en él.

Otra definición importante es la de *información*:

> Conjunto organizado de datos relevantes que se almacenan, procesan y comunican para la adquisición o representación de conocimiento.

---

## Entidades de ciberseguridad

Debido a la importancia de la ciberseguridad, existen entidades que se encargan de regular y establecer normas en este ámbito. Algunas de ellas son:

- **NIST** (EEUU): National Institute of Standards and Technology. Ayuda a empresas a analizar, administrar y reducir riesgos para proteger la información y los sistemas de información y comunicaciones.
- **CISA** (EEUU): Cybersecurity and Infrastructure Security Agency. Protege infraestructuras críticas de ciberamenazas.
- **ENISA** (UE): European Union Agency for Cybersecurity. Ayuda a la UE a ser resistente a los ciberataques.

---

## Entidades nacionales

- **INCIBE** (España): Instituto Nacional de Ciberseguridad. Ayuda a empresas y ciudadanos a protegerse de ciberamenazas.
- **CCN-CERT** (España): Centro Criptológico Nacional. Ayuda a proteger las tecnologías de la información y las comunicaciones.
- **ENS** (España): Esquema Nacional de Seguridad. Establece los principios y requisitos para la protección de la información en las administraciones públicas.

---

## Principios básicos de ciberseguridad

Los principios básicos de la ciberseguridad son aquellos elementos que al ponerse en riesgo comprometen la información, así como el buen funcionamiento de los sistemas que la procesan, almacenan o transmiten. 

Son tres principalmente:

- **Confidencialidad**: solo las personas autorizadas pueden acceder a la información.
- **Integridad**: la información no puede ser modificada sin autorización.
- **Disponibilidad**: la información debe estar disponible cuando se necesite.

---

En estos principios nos referimos a la `información` tanto almacenada como en comunicación.

Se conocen como *CIA* (Confidentiality, Integrity, Availability) o triada de la seguridad de la información.

---

![bg 50%](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c5/CIAJMK1209-en.svg/1280px-CIAJMK1209-en.svg.png)

---

Otras fuentes añaden dos principios más:

- **Autenticación**: verificar la identidad de quien accede a la información.
- **No repudio**: garantizar que una persona no pueda negar una acción realizada. Si el emisor de un mensaje no puede negar haberlo enviado, se dice que no puede repudiarlo.

---

## Amenaza, vulnerabilidad y riesgo

Una **amenaza** es un potencial ataque malicioso, con el objetivo de obtener acceso no autorizado a un sistema de información, comprometiendo la seguridad del sistema, y llevando a cabo acciones dañinas para la organización.

La **vulnerabilidad** se refiere a una debilidad o fallo en el diseño, implementación o proceso de un sistema, generado en su origen o debido a una implantación errónea, que puede ser explotado por factores externos.

El **riesgo** es la posibilidad de que se causen pérdidas o daños a activos de una organización cuando una amenaza explota con éxito una vulnerabilidad.

---

[![](https://mermaid.ink/img/pako:eNp9kE1Ow0AMRq8y8qqV2kWTrLJAqtQTUMRqNmbGSSwyHjQ_IKh6Ko7AxZg2DVAW3fn5fbItH8B4S9BCN_o3M2BI6mGnRUvkyNIt9hwTOVSWVEEfHBr--pSlFjRps9iaxK9ebSauZq4mrmeuJ25mbpa_K9R6fadOw87F1pHgB_6X1S1Z35LNtfzpPOZRKOATj2zRns65ZM72nin2Xst16o-CFTgq32BbfnfQopSGNJAjDW0pLYZnDVqOJYc5-f27GGhTyLSC4HM_QNvhGAvlF4uJdox9QHfpHr8Bqi6JWg?type=png)](https://mermaid.live/edit#pako:eNp9kE1Ow0AMRq8y8qqV2kWTrLJAqtQTUMRqNmbGSSwyHjQ_IKh6Ko7AxZg2DVAW3fn5fbItH8B4S9BCN_o3M2BI6mGnRUvkyNIt9hwTOVSWVEEfHBr--pSlFjRps9iaxK9ebSauZq4mrmeuJ25mbpa_K9R6fadOw87F1pHgB_6X1S1Z35LNtfzpPOZRKOATj2zRns65ZM72nin2Xst16o-CFTgq32BbfnfQopSGNJAjDW0pLYZnDVqOJYc5-f27GGhTyLSC4HM_QNvhGAvlF4uJdox9QHfpHr8Bqi6JWg)

Relación entre amenaza, vulnerabilidad y riesgo. No todos los activos tendrán vulnerabilidades, ni todos se verán amenazados; cuando se dan ambas situaciones es cuando se habla de riesgo.

---

## Eliminación y aceptación del riesgo

El riesgo **nunca** se puede eliminar por completo, pero se puede reducir a un nivel aceptable mediante estrategias y medidas de seguridad.

Se puede asumir que la probabilidad de que suceda es baja, o decidir que no merece la pena implementar las medidas de seguridad para mitigarlo porque su impacto es bajo.

---

## Amenazas de los principios CIA

- La *confidencialidad* se relaciona con el compromiso de cuentas de usuarios con o sin privilegios, también conocido como escalada de privilegios. Las amenazas más comunes son ingeniería social, phishing o usando técnicas de fuerza bruta entre otras, todas ellas encaminadas a obtener las credenciales para acceder al sistema.
- La escalada de privilegios pondrá en riesgo también la *integridad*, ya que el atacante puede alterar la información. Aunque existen otros riesgos como un man-in-the-middle.
- La disponibilidad puede verse afectada, por ejemplo, por el robo de cableado de comunicaciones, o por un ataque de denegación de servicio.

---

## Medidas para mantener los principios CIA

- *Confidencialidad*: la educación y la concienciación en ciberseguridad son las medidas fundamentales para prevenir los ataques de ingeniería social, ya que pueden impedir a un ciberdelincuente obtener las credenciales de acceso de un usuario.
- *Integridad*: Necesidad de implementar medidas de seguridad que permitan detectar y prevenir la alteración de la información. Por ejemplo, una firma digital, encriptado SSL/TLS, o un sistema de control de versiones.
- *Disponibilidad*: en el caso de la amenaza de robo de cableado de comunicaciones, las medidas de seguridad deberán ser principalmente físicas. Para ataques de denegación de servicio, se puede implementar un firewall o un sistema de detección de intrusiones.

---

## Auditorías

Las auditorías de seguridad de la información, como cualquier otro proceso de auditoría, verifican el cumplimiento de leyes, estándares o procedimientos propios de la organización, a la vez que sirven para mejorar la calidad de los procesos al identificar lo que no funciona como debería.

El proceso de auditoría facilita la identificación de puntos débiles en los que trabajar posteriormente para la mejora continua de la organización.

---

### Auditorias internas

Son realizadas por el personal del departamento encargado de la seguridad de la información, que debe ser independiente del departamento de informática o TIC, y que se encarga de comprobar que las medidas de control seleccionadas a partir del análisis de riesgos se están implementando en los sistemas de información en todos los niveles que correspondan. 
En este caso el personal que realiza la auditoría conoce perfectamente a la organización, así como la arquitectura TIC y los sistemas de información implicados.

Son más rápidas y menos costosas que las auditorías externas.

---

### Auditorías externas

Sin embargo, en el caso de las auditorías externas, que son contratadas a un tercero, son personas externas a la organización las que tienen que verificar el cumplimiento. Esto hace que el proceso suela ser más largo y requiera de más dedicación por parte de los responsables de los sistemas de información y de otro personal implicado dentro de la organización.

Es importante garantizar un acuerdo de confidencialidad por contrato antes de que se lleve a cabo la auditoría externa debido a la cantidad y tipo de información que el tercero recopila sobre la organización.

---

Es habitual que las auditorías internas sean más frecuentes que las externas, no solo porque pueden ser más ágiles al ser parte de las funciones del personal de seguridad de la información, sino también porque las externas suponen un esfuerzo extra para el personal de la organización y suelen requerir un presupuesto adicional significativo.

Debido a la cantidad y tipo de información que el tercero recopila sobre la organización, es importante garantizar un acuerdo de confidencialidad por contrato antes de que se lleve a cabo la auditoría externa.

---

## Normativa de protección del puesto de trabajo

Cada país tiene su propia normativa, algunas de las más conocidas son:

- **ISO/IEC 27001**: Establece los requisitos para establecer, implementar, mantener y mejorar un sistema de gestión de la seguridad de la información. Incliyendo políticas, procedimientos, controles y medidas de seguridad.
- **GDPR**: Reglamento General de Protección de Datos. Establece las normas para la protección de datos personales de los ciudadanos de la Unión Europea.
- **LPDGDD**: Ley Orgánica de Protección de Datos y Garantía de los Derechos Digitales. Regula el tratamiento de los datos personales y garantiza los derechos digitales de los ciudadanos.

---

## Factores vulnerables

Veamos algunas debilidades comunes en varios elementos de la organización:

- *Hardware*: los dispositivos físicos utilizados en el puesto de trabajo.
- *Software*: aplicaciones utilizadas para realizar las diferentes tareas.
- *Comunicaciones*: redes y sistemas de comunicación utilizados durante la realización de las funciones laborales.
- *Instalaciones*: dependencias físicas de la empresa.
- *Datos*: tanto aquellos que se tratan de manera digital como en formato físico.
- *Personas*: como se ha indicado al inicio de este apartado, muchos de los incidentes de ciberseguridad son causados por acciones de los propios empleados, por lo que también se considera un factor vulnerable, y en muchos casos se considera el eslabón más débil de la seguridad.

---

## Análisis de riesgos

Los pasos para realizar un análisis de riesgos son:

1. Delimitar los activos que pueden ser vulnerables.
2. Seleccionar activos críticos.
3. Identificar las amenazas que pueden afectar a los activos.
4. Determinar el impacto de las amenazas y la probabilidad de que ocurran.
5. Comprobar las medidas ya existentes.
6. Establecer medidas de control para reducir el riesgo.

---

### Escenarios de riesgo relacionados con hardware

- Utilización de dispositivos de almacenamiento externos
- Uso de dispositivos móviles y wearables, que son propensos a robos o pérdidas.
- Conexión de dispositivos no autorizados a la red de la organización.
- Uso de dispositivos obsoletos o sin actualizaciones de seguridad.

---

### Escenarios de riesgo relacionados con software

- Descarga o instalación de software no autorizado.
- Paquetes ofimaticos que puedan usar macros maliciosas.
- Uso de software sin licencia.
- Uso de software obsoleto o sin actualizaciones de seguridad.
- Uso de software con vulnerabilidades conocidas.
- Uso de software con configuraciones inseguras.
- Uso de software con permisos excesivos.
- Uso de software con acceso a internet sin restricciones.

---

### Escenarios de riesgo relacionados con las instalaciones

- No tener control de acceso a dependencias con material sensible (CPD, salas de servidores, etc.).
- Confiar en que los empleados no dejarán la puerta abierta.
- Confiar en que nadie entrará en dependencias sin autorización.
- Puertos Ethernet accesibles en zonas comunes.
- Falta de control de acceso a la red.

---

### Escenarios de riesgo relacionados con las comunicaciones

- Uso de redes Wi-Fi no seguras.
- Uso de redes Wi-Fi públicas.
- Uso de redes Wi-Fi con contraseñas débiles.
- Uso de redes Wi-Fi con dispositivos no seguros.

---

### Escenarios de riesgo relacionados con los datos

- Uso de datos personales sin autorización.
- Uso de datos personales sin cifrar.
- Uso de datos personales sin control de acceso.
- Uso de documentos en papel, mas propensos a perdidas, robos o accesos no autorizados.

---

### Escenarios de riesgo relacionados con las personas

- Falta de concienciación en ciberseguridad.
- Falta de formación en ciberseguridad.
- Falta de políticas de seguridad.
- Falta de medidas de control de acceso.
- Contraseñas débiles o compartidas.
- Ingeniería social.

---

