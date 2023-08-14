# CIBERSECURITY FUNDAMENTALS

Bienvenidos a la guía básica, para principiantes, sobre ciberseguridad realizada por Ramon Peinado Ruiz gracias al Curso Básico de Ciberseguridad ofrecido por CCN.

## DECALOGO BASICO DE SEGURIDAD

La cultura de la ciberseguridad, la concienciación del empleado, debe ser uno de los pilares en lo que se asiente la ciberseguridad de cualquier organización. 

<img align="center" src="/img/16ºimagenn.PNG"  />

1. *No abrir ningún enlace ni descargar ningún fichero adjunto procedente de un correo electrónico que presente cualquier indicio o patrón fuera de  lo habitual.* 
2. *Utilizar software de seguridad, herramientas antivirus y antimalware, cortafuegos personales, herramientas de borrado seguro, etc. debe ser algo irrenunciable cuando se utiliza un sistema de las TIC.* 
3. *Limitar la superficie de exposición a las amenazas, no solo hay que implementar medidas de seguridad que protejan el acceso a la  información, sino que hay que determinar los servicios que son  estrictamente necesarios.* 
4. *Cifrar la información sensible, no hay otra alternativa.* 
5. *Utilizar contraseñas adaptadas a la funcionalidad siendo conscientes de que la doble autenticación ya es una necesidad.*  
6. *Hacer un borrado seguro de la información una vez que esta ya no sea necesaria o se vaya a retirar de uso el soporte en cuestión.*
7. *Realizar copias de seguridad periódicas, no existe otra alternativa en caso de infección de código malicioso tipo ransomware, pérdida de datos, averías del hardware de almacenamiento, borrado de  información involuntaria por parte del usuario, etc.*
8. *Mantener actualizadas las aplicaciones y el sistema operativo es la mejor manera de evitar dar facilidades a la potencial amenaza.* 
9. *Revisa regularmente la configuración de seguridad aplicada, los permisos de las aplicaciones y las opciones de seguridad.*

## CONCEPTOS BASICOS

La mejor defensa para prevenir y detectar contratiempos en la utilizacion de las TIC son la concienciación, el sentido común y las buenas prácticas. La implementación de seguridad implica planificacion y estos elementos:

- **Análisis de riesgos**: Estudiar riesgos y valorar consecuencias de estos
- **Gestión de riesgos**: Valorar las medidas de proteccion para decidir la mejor solucion
- **Gobernanza**: Adaptar estas practicas a las medidas de seguridad
- **Vigilancia**: Observación y adecuacion continua de las medidas de seguridad
- **Planes de contingencia**: Medidas ante un incidente real de seguridad.

### FACTORES DE LAS AMENAZAS:

En los años recientes, ha aumentando tanto la cantidad como la gravedad de los ataques dirigidos hacia los sistemas de información del Sector Público, así como hacia empresas e instituciones de interés estratégico. Esto incluye aquellas que poseen valiosos activos de propiedad intelectual e industrial, y en términos generales, afecta a diversas entidades y a la población en general.

Aún perduran las prácticas de ciberespionaje, que implican ataques cibernéticos que son iniciados o respaldados por naciones y llevados a cabo ya sea por sus propios agentes o por terceros contratados para tal fin. Estas acciones tienen el propósito constante de obtener información de importancia política, estratégica, de seguridad o económica desde diversas perspectivas.

<img align="center" src="/img/1ºimagenn.PNG"  />




#### ATAQUES DIRIGIDOS O (ADVANCED PERSISENT THREAT)

Su objetivo es obtener la máxima cantidad de información relevante de la víctima, con la intención de planificar un ataque altamente eficaz.

<img align="center" src="/img/2ºimagenn.PNG"  />

Parámetros: 

- **Capacidad de desarrollo**: Exploits (Código que se aprovecha de una vulnerabilidad en una aplicación/sistema para provocar un comportamiento no deseado o imprevisto.) y vulnerabilidades utilizadas. 
- **Persistencia**: Tras reinicios, actualizaciones e incluso actividades de formateo. 
- Cifrado: Métodos de cifrado y fortaleza de claves para intercambiar la información exfiltrada. 
- **Técnicas exfiltración**: Protocolos utilizados para la extracción de información. 
- Ocultación: Técnicas de rootkit(Herramienta que sirve para ocultar actividades ilegítimas en un sistema. Una vez que ha sido instalado, permite al atacante actuar con el nivel de privilegios del administrador del equipo.) , bootkit utilizadas para ocultarse. 
- **Resistencia a ingeniería inversa**: Técnicas que dificultan el análisis del código.

------



## DARKWEB O INTERNET PROFUNDA

La web profunda está compuesta de páginas dinámicas donde el contenido se coloca en una base de datos que se proporciona a petición del usuario. 

La principal razón de la existencia de la Internet profunda es la  imposibilidad para los motores de búsqueda (Google, Yahoo!, Bing,  etc.) de encontrar o indexar gran parte de la información existente en  ella. 

Un subconjunto de la Internet profunda solo es accesible utilizando determinados navegadores web. Por ejemplo,TOR, donde los usuarios han de disponer del software de navegación  adecuado para poder acceder a dominios que son inaccesibles desde un navegador convencional. Además, los usuarios han de conocer previamente la dirección a la que han de dirigirse.

Existen herramientas para encontrar dominios de la red de TOR(The Hidden Wiki, Silk Road, Agora...) y buscadores como "Grams"

### RED TOR

Fue un proyecto diseñado e implementado por la Marina de los  Estados Unidos, lanzado en 2002, con el fin de fortalecer las comunicaciones por Internet y  garantizar el anonimato y la privacidad.

**TOR permite a los usuarios navegar por la web de forma anónima**. *Los datos no viajan de forma directa, sino a través de varios nodos que facilitan  el anonimato de las comunicaciones*. Existe un directorio de nodos intermedios con las claves públicas asociadas para poder establecer la comunicación cifrada.

**TOR se encarga de crear circuitos virtuales** compuestos por tres nodos aleatoriamente escogidos de su red. De manera que la comunicación entre origen, nuestro equipo y el destino, por ejemplo, una web, **ha de recorrer los tres nodos asignados**, a través de los cuales la información se transmitirá de forma cifrada.

<img align="center" src="/img/3ºimagenn.PNG"  />

### BITCOIN

Bitcoin es una **moneda electrónica cifrada**,  descentralizada, de ordenador a ordenador (peer-to-peer) donde **el control** se realiza, de  forma indirecta, **por los propios usuarios a  través de intercambios P2P**. Se utiliza una  cadena de caracteres criptográficos que se intercambian a través de  billeteras digitales (wallets) entre el usuario y el vendedor (intercambios  P2P), lo que hace que esté **fuera del control de cualquier gobierno,  institución o entidad financiera**.

<img align="center" src="/img/4ºimagenn.PNG"  />

**Cada transacción** con bitcoins **se registra** en una gran base de datos llamada “**BlockChain**”. Los **datos se guardan en bloques y cada bloque  nuevo debe contener el hash del bloque anterior**. Por lo tanto, cada  bloque nuevo que se une a la cadena posee todo el historial de la transacción (Estas transacciones son confirmadas por los miners POW Proof of work).

------



## APLICACIONES

Instalar programas puede impactar tanto en el desempeño como en la seguridad de los dispositivos o equipos. Es fundamental preservar la integridad de estos sistemas, por lo que es crucial optar por la instalación exclusiva de software autorizado y suministrado directamente por el fabricante.

Para evitarlo:

- *El empleo de software legal ofrece garantía y soporte.*
- *Certificación del programa para su compatibilidad con el sistema operativo y las demás aplicaciones.* 
- *Instalación y mantenimiento de parches y actualizaciones de seguridad.*
- *Considerar la superficie de exposición asociada a los sistemas heredados (legacy), especialmente aquellos que tienen más de una década de antigüedad por su extremada vulnerabilidad.*

- *Trabajar habitualmente en el sistema como usuario sin privilegios, no como  “Administrador”.*
- *No ejecutar nunca programas de origen dudoso o desconocido.* 
- *Si se emplea un paquete de software ofimático capaz de ejecutar macros, hay que asegurarse de que esté desactivada su ejecución automática.*

En cuanto a la impresión de documentos, hay que ser conscientes de que los documentos y transacciones impresas son susceptibles de violaciones de la seguridad.

### CIFRADO DE DATOS

Cifrar significa convertir texto plano en texto ilegible, evitando que la información sea accesible por terceros no autorizados. Para lo cual, se necesita de un algoritmo de cifrado y la existencia de una clave, que permite realizar el proceso  de transformación de los datos y que debe mantenerse en secreto.

Soluciones:

- **Cifrado de disco**: Cifra el disco por completo,  de esta manera el sistema operativo se encarga de descifrar la información cuando el usuario la solicita

- **Cifrado de carpetas**: Cifra a nivel de carpeta. El sistema de cifrado se encargará de cifrar y descifrar la información cuando se utiliza la carpeta protegida.

- **Cifrado de documentos**: Muestra y permite el acceso al documento solo para los usuarios autorizados, haciendo ilegible el contenido a los no autorizados.

### CORTAFUEGOS O FIREWALLS

**Diseñados para bloquear el acceso no autorizado** al mismo, pero  **permitiendo al mismo tiempo las comunicaciones autorizadas**. Como criterio genérico, no se deben permitir las conexiones de fuentes desconocidas. Por tanto, deben bloquear todas las conexiones entrantes y solo permitir aquellas que se indiquen expresamente sobre la base de un conjunto de normas y criterios establecidos

<img align="center" src="/img/5ºimagenn.PNG"  />

### APLICACIONES ANTIMALWARE

**El malware puede causar daños como eliminar o cambiar archivos, agotar recursos, acceder sin autorización, infectar de forma remota**, entre otros. **Un buena herramienta antimalware** o antivirus **debe filtrar contenido** malicioso, proteger en correo, navegación y conexiones, analizar dispositivos extraíbles y programar chequeos regulares. 

<img align="center" src="/img/6ºimagenn.PNG"  />

Los antimalware requieren actualizaciones frecuentes y ser de marcas confiables que combinen diversos **métodos de protección** como estos:

- **Escáner de acceso**: permite examinar los archivos cuando son abiertos. 
- **Escáner a demanda**: análisis en base a un calendario establecido. 
- **Escáner de correos electrónicos**: en dispositivos de protección de perímetro o servidores de correo. 
- **Control de firmas**: permite detectar cambios no legítimos en el contenido de un archivo. 
- **Métodos heurísticos**: búsqueda de anomalías en los archivos y procesos en base a experiencias previas de comportamiento del malware.

Solo contar con una aplicación antimalware no basta. Se necesita un enfoque centralizado (cliente-servidor) para salvaguardar todos los puntos finales conectados a la red, como servidores, computadoras de escritorio, laptops y smartphones. Algunos proveedores brindan soluciones de Seguridad en los Puntos Finales que engloban antivirus, cortafuegos y otros programas de seguridad.

### BORRADO SEGURO DE DATOS

**Hay aplicaciones que permiten deshacer el formateo de una unidad** existiendo incluso métodos para recuperar los datos de los discos, aunque estos hayan sido sobrescritos. 

**Se requiere sobrescribir los datos utilizando un método de borrado que impida su recuperación**. Esto implica realizar múltiples pasadas de escritura en los sectores de almacenamiento. **Para simplificar este proceso, es conveniente utilizar una aplicación especializada en eliminación de datos.**

En el caso de archivos como fotografías, audio, vídeo y documentos, hay metadatos* que pueden guardar información oculta no visible con la configuración estándar de las aplicaciones. Para acceder a esta información, a menudo se necesita una configuración específica o un software dedicado.

**Metadatos**: Son detalles descriptivos o informativos que acompañan a un archivo o conjunto de datos.

------



## NAVEGACION SEGURA

El cliente está identificado en la red a través de una dirección IP (TCP/IP) y cada vez que se conecta a un sitio web, éste conoce automáticamente la dirección IP, nombre de máquina, la página de procedencia, etc. **Se produce un intercambio de información que habitualmente no es  visible, donde el navegador web es el que facilita la mayoría de estos datos**.

<img align="center" src="/img/7ºimagenn.PNG"  />

Un navegador web permite que se acceda a información aparentemente inofensiva:

<img align="center" src="/img/8ºimagenn.PNG"  />

Recomendaciones:

- *Acceder únicamente a sitios de confianza.* 
- *Mantener actualizado el navegador a la última versión disponible del  fabricante.* 
- *Configurar el nivel de seguridad del navegador según sus preferencias.* 
- *Descargar los programas desde sitios oficiales para evitar suplantaciones maliciosas.* 
- *Configurar el navegador para evitar ventanas emergentes.*
- *Utilizar un usuario sin permisos de “Administrador” para navegar por Internet e impedir la instalación de programas y cambios en los valores del sistema.*

- *Borrar las “cookies”, los ficheros temporales y el historial cuando se utilicen equipos ajenos para no dejar rastro de la navegación.* 
- *Desactivar la posibilidad “script” en navegadores web, como Firefox  (NoScript) o Chrome (NotScript), para prevenir la ejecución de los mismos por parte de dominios desconocidos.* 
- *Se recomienda hacer uso de HTTPS (SSL/TLS) frente a HTTP incluso para aquellos servicios que no manejen información sensible. Algunas funcionalidades como HSTS y extensiones como HTTPS Everywhere servirán de gran ayuda para garantizar el uso preferente de HTTPS sobre HTTP durante la navegación web.* 
- *En la medida de lo posible, emplear máquinas virtuales para navegar por Internet*

Hay que tener en cuenta que los sistemas de navegación anónima permiten el uso de algunos servicios de Internet, principalmente los basados en navegación web (http/https), de forma desvinculada de la dirección IP origen de la comunicación.

- **Anonimizadores**: Actúan como un filtro entre el navegador y sitio web que se desea visitar. Al conectarse al anonimizador, se introduce la URL a visitar y entonces éste se adentra en la red filtrando cookies, javascripts, etc. 
- **Servidores Proxy**: Un servidor proxy actúa de pasarela entre la máquina cliente e Internet. El servidor proxy actúa de intermediario, se encarga  de recuperar las páginas web en lugar del usuario que navega. 
- **Túneles de Cifrado**: (TOR, VPS y Darknets) Red de “túneles” por las cuales los datos de navegación  debidamente cifrados, atraviesan múltiples nodos hasta llegar a su destino. 

------



## CORREO ELECTRONICO

El incremento y efectividad de la ingeniería social para engañar a los usuarios por medio de correos electrónicos ha modificado el paradigma de la seguridad corporativa. Actualmente los cortafuegos perimetrales y la securización de los servicios expuestos a Internet no son contramedidas suficientes para proteger una organización de ataques externos.

Algunas recomendaciones para utilizar el correo electrónico de forma segura:

- *No abrir ningún enlace ni descargar ningún fichero adjunto procedente de un correo electrónico que presente cualquier indicio o patrón fuera de lo habitual.* 
- *No confiar únicamente en el nombre del remitente. El usuario deberá  comprobar que el propio dominio del correo recibido es de confianza. Si un correo procedente de un contacto conocido solicita información inusual, contacte con el mismo por teléfono u otra vía de comunicación para corroborar la legitimidad del mismo.* 
- *No habilitar las macros de los documentos ofimáticos incluso si el propio fichero así lo solicita.*
- *Antes de abrir cualquier fichero descargado desde el correo, hay que  asegurarse de la extensión y no fiarse del icono asociado al mismo.*
- *No hacer clic en ningún enlace que solicite datos personales o bancarios.* 
- *Utilizar herramientas de seguridad para mitigar exploits de manera complementaria al software antivirus.*
- *Evitar hacer clic directamente en cualquier enlace desde el propio cliente de correo. Si el enlace es desconocido, es recomendable buscar información del mismo en motores de búsqueda como Google o Bing.* 
- *Utilizar contraseñas robustas para el acceso al correo electrónico. Las contraseñas deberán ser periódicamente renovadas y si es posible utilizar doble autenticación.* 
- *Cifrar los mensajes de correo que contengan información sensible.*
- *Tener siempre actualizado el sistema operativo, las aplicaciones ofimáticas y el navegador (incluyendo los plugins/extensiones instaladas)*

------



## VIRTUALIZACION

**Se entiende como la recreación de un recurso físico (hardware) o lógico (software), por medio de un hipervisor (hypervisor) que permite su ejecución por más de un entorno al mismo tiempo**. **Cada** entorno virtualizado, conocido como **máquina virtual, actúa como una entidad independiente con recursos dedicados, como memoria, procesador y almacenamiento**.

<img align="center" src="/img/9ºimagenn.PNG"  />


El apogeo de la virtualización ha llegado con la utilización de la  nube, donde este sistema de reparto de los recursos se hace casi indispensable. Aunque ya existían múltiples sistemas de muchos fabricantes, el desarrollo y avances de los mismos se han incrementad  de una forma exponencial. Actualmente se puede optar, entre otros, por XenServer de Citrix, VMware ESXi de Dell, VirtualBox de Oracle, Oracle VM Server e Hyper-V de Microsoft

Recomendaciones a la hora de la configuracion del host de maquinas virtuales

- *Tener instaladas en el sistema operativo las últimas actualizaciones de seguridad.* 
- *Tener la última reversión disponible del programa de virtualización.* 
- *Si es posible, tener al menos un adaptador de red en exclusiva para la  infraestructura de virtualización.* 
- *Crear un entorno de laboratorio aislado del entorno de producción.* 
- *Disponer de un grupo de seguridad para gestionar la plataforma de  seguridad.* 
- *Proteger los dispositivos de almacenamiento en los que guardan los archivos de recursos y de definición de la máquina virtual.* 
- *Mantener estancos a los administradores de los guest respecto a los de host.*

Recomendaciones para la creación del guest;

- *Hacer un esquema previo de lo que será la infraestructura de virtualización.* 
- *Dimensionar la creación de máquinas virtuales a las necesidades reales y a los recursos de hardware disponibles en el host.* 
- *Cifrar los ficheros de máquinas virtuales, instantáneas y discos duros virtuales destinados al almacenamiento de la plataforma de virtualización.* 
- *Instalar las últimas actualizaciones de seguridad en cada sistema operativo guest.* 
- *Valorar la instalación de los agentes de hipervisor, tipo Guest Additions, y en caso de hacerlo, mantenerlos actualizados.* 
- *Asegurar con antimalware y firewalls todos los sistemas operativo  invitados.* 
- *Conectar medios de almacenamiento externos solo cuando sea necesario y desactivar tras su uso.* 
- *Mantener activas solamente las máquinas virtuales imprescindibles.* 
- *Usar para la conexión con la red corporativa o con Internet una interfaz de red virtual diferenciada que se deberá desactivar cuando no se vaya a utilizar.* 
- *Cifrar los medios de almacenamiento externos que contengan ficheros de virtualización de respaldo y custodiarlos convenientemente.*

------



## SEGURIDAD EN DISPOSITIVOS MOVILES

El aumento de las oportunidades y capacidades de los dispositivos móviles en el presente conlleva también riesgos ampliados para su seguridad.

<img align="center" src="/img/10ºimagenn.PNG"  />

Consejos: 

- *Establecer un método seguro para desbloquear el terminal, por ejemplo,  utilizando una passphrase robusta.*
- *Es recomendable eliminar las previsualizaciones de los mensajes y extremar las medidas cuando no se disponga del teléfono al alcance.* 
- *Deshabilitar las conexiones inalámbricas (WiFi, Bluetooth, etc.) y todas aquellas innecesarias mientras no vayan a utilizarse.*
- *Mantener actualizado el software del dispositivo y utilizar una configuración de seguridad aprobada por el responsable TIC de la entidad.* 
- *Tener cuidado con el acceso y las solicitudes de permisos de las aplicaciones que se ejecuten en el teléfono.*
- *Ignorar y borrar mensajes (SMS, MMS u otros) de origen desconocido que invitan a descargar contenidos o acceder a sitios web.* 
- *Activar el acceso mediante PIN a las conexiones Bluetooth y configurar el dispositivo en modo oculto. No aceptar conexiones de dispositivos no conocidos.* 
- *Descargar aplicaciones únicamente desde las tiendas oficiales. En ningún caso, descargar software de sitios poco fiables y en todo caso solicitar al responsable TIC de la entidad las aplicaciones necesarias.* 
- *Evitar realizar jailbreaking o rooting del terminal, ya que puede comprometer y reducir considerablemente la seguridad del teléfono a pesar de ser tentador para acceder a aplicaciones o servicios específicos.* 
- *Utilizar una red privada virtual (VPN) para proteger el tráfico de datos desde el dispositivo móvil hasta la infraestructura de la entidad. Siempre es una buena práctica para evitar la posible monitorización por parte de intrusos.* 
- *Evitar en lo posible el uso de impresoras, faxes o redes WiFi públicas, como las ofrecidas en hoteles o aeropuertos, salvo que se disponga de las herramientas necesarias para asegurar sus comunicaciones.* 
- *Muchos teléfonos móviles y cámaras digitales añaden las coordenadas GPS en la información de las imágenes tomadas, por lo que es oportuno limitar la compartición de las imágenes en la red o bien utilizar aplicaciones que eliminen dicha información.*
- *Separar las comunicaciones personales de las profesionales es una buena práctica de seguridad.*
- *Implementar la gestión centralizada de dispositivos móviles mediante el empleo de agentes MDM (Mobile Device Management).* 
- *Para manejar información sensible, utilizar únicamente soluciones aprobadas por el responsable de seguridad TIC de la entidad.*

------



## SEGURIDAD EN REDES INALAMBRICAS

Recomendaciones para las redes inalambricas:

- *Cambiar la contraseña de acceso por defecto para la administración del Punto de Acceso.* 
- *Modificar el SSID configurado por defecto no empleando nombres que pudieran identificar a la entidad y que permitan pasar desapercibidos con el entorno.* 
- *Ocultar el identificador SSID al exterior dificulta obtener el nombre de la red, aunque la trazabilidad de los clientes sigue siendo posible con independencia de la ocultación  del SSID.* 
- *Activar el filtrado de direcciones MAC de los dispositivos WiFi para permitir que se conecten a la red los dispositivos con las direcciones MAC especificadas.*
- *Configurar WPA2-AES en el modo de confidencialidad de datos, obteniendo autenticación y cifrado de datos robusto.*
- *Limitar la cobertura WLAN. Una antena multidireccional ubicada en el centro de la casa/oficina es la opción más común.*
- *Desconectar la red cuando no se utilice. Si bien no es práctico hacerlo diariamente, es muy recomendable durante largos períodos de inactividad.* 
- *Desactivar UPnP (Universal Plug and Play) cuando su uso no sea necesario, para evitar que un código dañino de la propia red lo utilice para abrir una brecha en el cortafuegos del router y permitir así que otros atacantes accedan a él.* 
- *Actualizar el “firmware” del router periódicamente, pues muchas de las actualizaciones y parches que se van incorporando afectan a la seguridad.* 
- *Usar direcciones IP estáticas o limitar el número de direcciones reservadas (DHCP) cuando sea posible, para evitar que usuarios no autorizados puedan obtener una dirección IP de la red local.* 
- *Activar el cortafuegos del router, para que solo los usuarios y los servicios autorizados puedan tener acceso a la red.*
- *Activar la opción de registro (login) para el router y analizar periódicamente el historial de accesos.*
- *Es recomendable cambiar el DNS que por defecto trae configurado el router por otro que preserve la privacidad del usuario y mejore su seguridad, por ejemplo, DNSCrypt.*

------

## MENSAJERIA INSTANTANEA

El uso compartido de información personal y la escasa percepción de riesgo que los usuarios tienen han convertido a las aplicaciones de mensajería instantánea en un entorno atractivo para los ciberatacantes, estas son las recomendaciones para evitar ataques dentro de esta mensajeria

- *Mantener el teléfono bloqueado. De esta forma, se reducirá el riesgo si el dispositivo cae en las manos equivocadas.* 
- *Sería recomendable eliminar las previsualizaciones de los mensajes y extremar las medidas cuando no se disponga del teléfono al alcance.* 
- *En la medida de lo posible, se recomienda la configuración de las aplicaciones para solo recibir mensajes de personas autorizadas.* 
- *Desactivar la conectividad adicional del teléfono cuando no se vaya a utilizar, como podría ser la conexión WiFi o Bluetooth, ya que además de reducir el consumo de batería, reduce la posible superficie de  ataque sobre el dispositivo.* 
- *Utilizar aplicaciones de mensajería instantánea cuyo código fuente esté abierto a la comunidad y haya sido revisado. En ese sentido existen alternativas que, además, aseguran la confidencialidad en  las comunicaciones, cifrando el tráfico extremo a extremo (e2e), un ejemplo es Signal*.



------

## REDES SOCIALES

En general, los riesgos asociados a las redes sociales son los mismos que los del resto de actividades y/o servicios en Internet: grandes dificultades para eliminar la información subida, el acceso futuro por  terceros (el derecho a cambiar de opinión es nulo y será muy difícil borrar cualquier opinión, fotografía o vídeo subido a la red) y la dificultad de discernir entre información veraz y propaganda o manipulación. En este punto hay que recordar la importancia que tiene la configuración de seguridad del dispositivo (sistema operativo y navegador) utilizado para conectarse a Internet y, de esta manera, acceder a las redes  sociales.

- *Creación cuidadosa del perfil y la configuración de privacidad. No basarse en la configuración por defecto que proporcionan las plataformas.* 
-  *Reflexión sobre todo lo que se publica y emplear un pseudónimo. Dar por sentado que todo lo que se sube en una red social es permanente, aunque se elimine la cuenta.* 
-  *Para evitar revelar las direcciones de correo de sus amigos, no permita que los servicios de redes sociales examinen su libreta de direcciones de correo.* 
- *Prestar atención a los servicios basados en la localización y la información del teléfono móvil.* 
- *Precaución con los enlaces. Evitar hacer clic en hipervínculos o enlaces de procedencia dudosa.*
-  *Escribir directamente la dirección de su sitio de redes sociales en el navegador para evitar que un sitio falso pueda robar su información personal.*
- *Tener precaución al instalar elementos adicionales en su sitio ya que, en ocasiones, se usan estas aplicaciones para robar información personal.*
- *Revisar la información publicada. Eludir dar excesiva información sobre uno mismo, como su cumpleaños, su ciudad natal, clase del instituto, etc., para evitar que puedan entrar en su cuenta.* 
- *Seguridad de las contraseñas, utilice contraseñas complejas que incluyan números, símbolos y signos de puntuación. Es importante no compartir la misma contraseña para todas las redes sociales ni para el resto de servicios que se utilizan en Internet (empleo de gestores de  contraseñas tipo keepass).* 
- *Incrementar la seguridad en el acceso a la cuenta añadiendo un segundo factor de autenticación (2FA) que impida a un potencial atacante que se haya hecho con la contraseña acceder al servicio.*

------



## IOT "INTERNET OF THINGS"

Se refiere a redes de objetos físicos, artefactos, vehículos, edificios, electrodomésticos, atuendos, implantes, etc. que llevan en su seno componentes electrónicos, software, sensores con conectividad en red que les permite recolectar información para lograr una contextualización de la situación mediante  técnicas de Big Data imposible de realizar por otros medios.

<img align="center" src="/img/12ºimagenn.PNG"  />

El reto se reduce a establecer una base de monitorización y control para reducir la exposición al riesgo y aplicar técnicas inteligentes a la creciente población de dispositivos IoT.

- *Cambiar las contraseñas por defecto de los dispositivos y utilizar contraseñas realmente robustas.* 
- *Mantener actualizados los dispositivos con las últimas versiones disponibles de software y firmware.* 
- *Desactivar toda conectividad remota (con internet) de los dispositivos cuando no sea estrictamente necesaria.* 
- *Mantener abiertos solo aquellos puertos de comunicación que sean realmente necesarios y modificar los puertos de escucha si es posible.* 
- *Si los dispositivos IoT no permiten la configuración de su seguridad, operar con ellos siempre en una red de área local (LAN) detrás de un dispositivo (enrutador) correctamente configurado que sí provea esa  seguridad.*
-  *En la medida de lo posible, asegurar la autenticidad, confidencialidad e integridad en todas las comunicaciones locales (LAN), especialmente si estas se realizan por enlaces radio (WiFi, Bluetooth, etc.).* 
- *Comprobar periódicamente la configuración de seguridad de todos los elementos de la arquitectura IoT y su comunicación con el exterior.*
- *Mantener deshabilitados los componentes no necesarios como pueden ser, según el caso, micrófonos, cámaras de vídeo, etc...* 
- *Comprobar la visibilidad de los dispositivos propios en buscadores de dispositivos IoT como Shodan.*

------



## POLITICA DE SEGURIDAD

La Política de seguridad establece el estado en el que se encuentra la información y los servicios dentro de la entidad y define qué es lo que se desea proteger, así como los correspondientes objetivos de  seguridad proporcionando una base para la planificación de la misma. Describe responsabilidades del usuario y cómo se supervisa la efectividad de las medidas aplicadas. En definitiva, es un conjunto de reglas que se deciden aplicar en las actividades del sistema y a los  recursos de comunicaciones que pertenecen a una organización.

<img align="center" src="/img/11ºimagenn.PNG"  />

Medidas de seguridad:

- **Preventivas**: tienen como objeto reducir el riesgo: 
  - *Protección Física: guardias, control de acceso, protección hardware…*
  - *Medidas Técnicas: cortafuegos, detectores de intrusos, criptografía…*
  - *Medidas Procedimentales: cursos de mentalización, actualización de conocimientos, normas de acceso a la  información, sanciones…* 
- **Análisis**: orientadas a la identificación del riesgo. 
  - *Protección Física: sistemas de vigilancia, detectores de movimiento…*
  - *Medidas Técnicas: control de acceso lógico, sesión de autenticación…*
  - *Medidas Procedimentales: gestión de logs, monitorización de auditoría…* 
- **Correctivas**: se orientan a impedir o reducir el impacto sobre los activos. 
  - *Protección Física: respaldo de fuente de alimentación (SAI)…* 
  - *Medidas Técnicas: programa antivirus, auditorías, respaldo de seguridad…* 
  - *Medidas Procedimentales: planes de contingencia…*

La amenaza más seria para un sistema de información son las personas, por lo que su formación y sensibilización es uno de los objetivos fundamentales.

------



## GOBERNANZA

Se deben establecer los mecanismos de gerencia y gestión de la seguridad, incluyendo soporte a las operaciones, niveles de escalamiento acordes con la clasificación y remediación de incidentes, frecuencia y tipos de notificación, etc. 

En este sentido, es recomendable implantar el denominado SGSI (Sistema de Gestión de la Seguridad de la Información) un conjunto de políticas de administración de la  información, donde se definen, implantan y mantienen un conjunto de procesos para gestionar eficientemente la accesibilidad de la información, buscando asegurar la confidencialidad, integridad y disponibilidad de los activos de información minimizando a la vez los riesgos de seguridad de la información

Consideraciones a tener en cuenta:

- *Revisar y apoyar la implantación del modelo de gobernanza.* 
- *Análisis y adecuación normativa.* 
- *Análisis y gestión de los riesgos asociados a los activos (riesgo residual asumible).* 
- *Análisis y definición de cuadros de mando (medidas e indicadores).*
- *Auditorías de cumplimiento normativo.*
- *Soporte a los órganos de gobierno de la seguridad.* 
- *Seguimiento y mejora del estado y gestión de la seguridad*

------



## GESTION DE LA CONFIGURACION

La implementación efectiva de control de configuración y gestión de software es fundamental, a considerar:

- *Todos los archivos ejecutables y plantillas de documentos  “templates” compartidos deben estar colocados en un directorio de solo lectura.* 
- *Cada usuario debe tener su propio directorio personal en la red con acceso lectura/escritura y restringido para lectura para otros usuarios para prevenir previsibles diseminaciones de software malicioso de la máquina local a la red.* 
- *Los directorios compartidos por varios usuarios es un modo habitual de trabajo, por lo que hay que prevenir la diseminación de posibles infecciones.*

Las contraseñas son el principal mecanismo de autenticación utilizado por las personas en su acceso a los sistemas de información. La seguridad que proporcionan las contraseñas depende, en gran medida, de su confidencialidad, recomendaciones

- *No podrá ser asociada con facilidad a cualquier información relacionada con el usuario de la cuenta.* 
- *Tendrá una longitud mínima de ocho caracteres con diferentes tipos de caracteres tipográficos.* 
- *Cambiar la contraseña periódicamente.* 
- *No compartir las cuentas y contraseñas con otros usuarios.*
- *No anotar las contraseñas en sitios de fácil acceso, ni almacenarlas en ficheros en el ordenador sin ninguna protección.*
- *Limitar la posibilidad de “Recordar Contraseña” que ofrecen algunos navegadores web.*

------



## VIGILANCIA

Con el control de configuración y gestión del software se debe valorar un proceso continuo de análisis de vulnerabilidades, ya sea automático o manual. 

**Análisis de vulnerabilidades automáticas**: Herramientas para la realización de escaneos de vulnerabilidades a infraestructuras y servicios.

**Análisis de vulnerabilidades manuales**: Realización por parte de un grupo de analistas de una revisión periódica de las diferentes aplicaciones, principalmente de las expuestas a Internet, desde las perspectivas de caja negra y caja blanca.

<img align="center" src="/img/13ºimagenn.PNG"  />

Hay que considerar desplegar un bloque de servicios basados en: 

- **Monitorización de seguridad**: Despliegue de sondas de alta capacidad que reciban una copia del tráfico, tanto entrante como saliente en Internet. Tratamiento de los eventos generados por un sistema de información de seguridad y administración de eventos (SIEM). Asimismo, se deben considerar módulos de  aprendizaje automático (Machine Learning) para análisis de eventos y alertas y poder detectar nuevas amenazas.
- **Protección y filtrado de contenido malicioso**: Proteger a los usuarios que navegan en Internet ante este tipo de amenazas. Dispositivos de nueva generación, los cuales cuentan, además de las capacidades tradicionales de los cortafuegos, con prevención de intrusiones y control de aplicaciones.
- **Respuesta a Incidentes**: Servicio avanzado de soporte a la gestión de incidentes mediante profesionales que se podrán coordinar, de forma remota o in situ, con el personal de la entidad con el objeto de realizar análisis forenses, colaborar en la estrategia de mitigación y/o recuperación, etc.
- **Análisis de Vulnerabilidades**: Análisis periódico de vulnerabilidades tanto de forma automatizada como manual. Para ello se aportarán tecnologías de escaneo de sistemas y de aplicaciones web que facilitarán la realización de estas pruebas de forma periódica, tanto automatizada como manual.

------



## CONTINUIDAD DE NEGOCIO/POLITICAS DE RESPALDO

**“Continuidad de Negocio” supone pensar y disponer de un  plan alternativo en caso de que ocurra un desastre en los sistemas TIC de la entidad**.

Asimismo, en la medida de lo posible, se deberían realizar pruebas de los planes de continuidad para confirmar que se encuentran debidamente actualizados y responden de manera eficaz a la a necesidad. 

**Es fundamental realizar copias de respaldo de manera regular para asegurar la integridad/disponibilidad del sistema**. La realización de copias de seguridad implica crear una copia de los datos en un medio diferente del que se encuentran con el fin de que las mismas puedan utilizarse para restaurar la copia original después de una eventual pérdida de datos.

**Tambien es recomendable verificar el correcto funcionamiento de estas copias de seguridad**

<img align="center" src="/img/14ºimagenn.PNG"  />

------



## GESTION DE INCIDENTES

Cuando se produce un incidente de seguridad, es crítico para una entidad disponer de un protocolo eficaz de respuesta que ayude a los equipos de seguridad a minimizar la pérdida o filtración de información, evitar la propagación del incidente o, incluso, la propia interrupción del servicio.

La velocidad con la cual se reconozca, analice y responda al incidente limitará el daño y minimizará el coste de la recuperación.<img align="center" src="/img/15ºimagenn.PNG"  />

La gestión de incidentes de seguridad tendrá en cuenta: 

- *El establecimiento de sistemas de detección y reacción frente a código dañino.*
- *El registro de los incidentes de seguridad que se produzcan y las acciones de tratamiento que se sigan.* 
- *El soporte y coordinación para el tratamiento de vulnerabilidades y la resolución de incidentes de seguridad.* 
- *Proporcionar información sobre vulnerabilidades, alertas y avisos de nuevas amenazas. Incluye la investigación y divulgación de las mejores prácticas sobre seguridad de la información.*
- *La formación al objeto de mejorar las capacidades para la detección y gestión de incidentes.*

Un esquema básico de actuación frente a un ciberincidente puede ser: 

- *La DETECCIÓN de la amenaza, puede ser realizada por la  propia entidad y/o por las sondas desplegadas por el Equipo de Respuesta a Ciberincidentes (CSIRT) de referencia, que generarán el correspondiente aviso.*
- *En caso de confirmarse el ciberincidente, el organismo realizará la notificación formal (por ejemplo, herramienta LUCIA) a la  autoridad competente, a través del CSIRT de referencia, y las acciones de la fase de CONTENCIÓN.*
- *Una vez ERRADICADA la amenaza, la entidad, usando la misma herramienta, notificará a la autoridad competente, a través del CSIRT de referencia, el cierre del ciberincidente.*

------



## BIBLIOGRAFIA y AGRADECIMIENTOS

Esta guía básica no podía haber sido realizada sin la ayuda de este curso:

Curso Básico Ciberseguridad																																																					CCN

Mencionar también la gran ayuda recibida por parte de toda la comunidad de la ciberseguridad y sus foros .

