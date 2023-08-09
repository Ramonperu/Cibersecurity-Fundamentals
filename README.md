# CIBERSECURITY FUNDAMENTALS

Bienvenidos a la guía básica, para principiantes, sobre ciberseguridad realizada por Ramon Peinado Ruiz gracias al Curso Básico de Ciberseguridad ofrecido por CCN.

## CONCEPTOS BASICOS

La mejor defensa para prevenir y detectar contratiempos en la utilizacion de las TIC son la concienciación, el sentido común y las buenas prácticas. La implementación de seguridad implica planificacion y estos elementos:

- Análisis de riesgos: Estudiar riesgos y valorar consecuencias de estos
- Gestión de riesgos: Valorar las medidas de proteccion para decidir la mejor solucion
- Gobernanza: Adaptar estas practicas a las medidas de seguridad
- Vigilancia: Observación y adecuacion continua de las medidas de seguridad
- Planes de contingencia: Medidas ante un incidente real de seguridad.

### FACTORES DE LAS AMENAZAS:

En los años recientes, ha aumentando tanto la cantidad como la gravedad de los ataques dirigidos hacia los sistemas de información del Sector Público, así como hacia empresas e instituciones de interés estratégico. Esto incluye aquellas que poseen valiosos activos de propiedad intelectual e industrial, y en términos generales, afecta a diversas entidades y a la población en general.

Aún perduran las prácticas de ciberespionaje, que implican ataques cibernéticos que son iniciados o respaldados por naciones y llevados a cabo ya sea por sus propios agentes o por terceros contratados para tal fin. Estas acciones tienen el propósito constante de obtener información de importancia política, estratégica, de seguridad o económica desde diversas perspectivas.

<img src="/img/1ºimagenn.PNG"  />

#### ATAQUES DIRIGIDOS O (ADVANCED PERSISENT THREAT)

Su objetivo es obtener la máxima cantidad de información relevante de la víctima, con la intención de planificar un ataque altamente eficaz.

<img src="/img/2ºimagenn.PNG"  />

Parámetros: 

- Capacidad de desarrollo: Exploits (Código que se aprovecha de una vulnerabilidad en una aplicación/sistema para provocar un comportamiento no deseado o imprevisto.) y vulnerabilidades utilizadas. 
- Persistencia: Tras reinicios, actualizaciones e incluso actividades de formateo. 
- Cifrado: Métodos de cifrado y fortaleza de claves para intercambiar la información exfiltrada. 
- Técnicas exfiltración: Protocolos utilizados para la extracción de información. 
- Ocultación: Técnicas de rootkit(Herramienta que sirve para ocultar actividades ilegítimas en un sistema. Una vez que ha sido instalado, permite al atacante actuar con el nivel de privilegios del administrador del equipo.) , bootkit utilizadas para ocultarse. 
- Resistencia a ingeniería inversa: Técnicas que dificultan el análisis del código.

------



## DARKWEB O INTERNET PROFUNDA

La web profunda está compuesta de páginas dinámicas donde el contenido se coloca en una base de datos que se proporciona a petición del usuario. 

La principal razón de la existencia de la Internet profunda es la  imposibilidad para los motores de búsqueda (Google, Yahoo!, Bing,  etc.) de encontrar o indexar gran parte de la información existente en  ella. 

Un subconjunto de la Internet profunda solo es accesible utilizando determinados navegadores web. Por ejemplo,TOR, donde los usuarios han de disponer del software de navegación  adecuado para poder acceder a dominios que son inaccesibles desde un navegador convencional. Además, los usuarios han de conocer previamente la dirección a la que han de dirigirse.

Existen herramientas para encontrar dominios de la red de TOR(The Hidden Wiki, Silk Road, Agora...) y buscadores como "Grams"

### RED TOR

Fue un proyecto diseñado e implementado por la Marina de los  Estados Unidos, lanzado en 2002, con el fin de fortalecer las comunicaciones por Internet y  garantizar el anonimato y la privacidad.

TOR permite a los usuarios navegar por la web de forma anónima. Los datos  no viajan de forma directa, sino a través de varios nodos que facilitan  el anonimato de las comunicaciones. Existe un directorio de nodos  intermedios con las claves públicas asociadas para poder establecer  la comunicación cifrada.

TOR se encarga de crear circuitos virtuales compuestos por tres nodos aleatoriamente escogidos de su red. De manera que la  comunicación entre origen, nuestro equipo y el destino, por ejemplo, una web, ha de recorrer los tres  nodos asignados, a través de los cuales la información se transmitirá de forma cifrada.

<img src="/img/3ºimagenn.PNG"  />

### BITCOIN

Bitcoin es una **moneda electrónica cifrada**,  descentralizada, de ordenador a ordenador (peer-to-peer) donde **el control** se realiza, de  forma indirecta, **por los propios usuarios a  través de intercambios P2P**. Se utiliza una  cadena de caracteres criptográficos que se intercambian a través de  billeteras digitales (wallets) entre el usuario y el vendedor (intercambios  P2P), lo que hace que esté **fuera del control de cualquier gobierno,  institución o entidad financiera**.

<img src="/img/4ºimagenn.PNG"  />

**Cada transacción** con bitcoins **se registra** en una gran base de datos llamada “**BlockChain**”. Los **datos se guardan en bloques y cada bloque  nuevo debe contener el hash del bloque anterior**. Por lo tanto, cada  bloque nuevo que se une a la cadena posee todo el historial de la transacción (Estas transacciones son confirmadas por los miners POW Proof of work).

------



## APLICACIONES

Instalar programas puede impactar tanto en el desempeño como en la seguridad de los dispositivos o equipos. Es fundamental preservar la integridad de estos sistemas, por lo que es crucial optar por la instalación exclusiva de software autorizado y suministrado directamente por el fabricante.

Para evitarlo:

- El empleo de software legal ofrece garantía y soporte.
- Certificación del programa para su compatibilidad con el sistema operativo y las demás aplicaciones. 
- Instalación y mantenimiento de parches y actualizaciones de seguridad.
- Considerar la superficie de exposición asociada a los sistemas heredados (legacy), especialmente aquellos que tienen más de una  década de antigüedad por su extremada vulnerabilidad.

- Trabajar habitualmente en el sistema  como usuario sin privilegios, no como  “Administrador”.
- No ejecutar nunca programas de origen  dudoso o desconocido. 
- Si se emplea un paquete de software ofimático  capaz de ejecutar macros, hay que asegurarse  de que esté desactivada su ejecución  automática.

En cuanto a la impresión de documentos, hay que ser  conscientes de que los documentos y transacciones  impresas son susceptibles de violaciones de la seguridad.

### CIFRADO DE DATOS

Cifrar significa convertir texto plano en texto ilegible, evitando que la información sea accesible por terceros no autorizados. Para lo cual, se necesita de un algoritmo de cifrado y la existencia de una clave, que permite realizar el proceso  de transformación de los datos y que debe mantenerse en secreto.

Soluciones:

- Cifrado de disco: Cifra el disco por completo,  de esta manera el sistema operativo se encarga de descifrar la información cuando el usuario la solicita

- Cifrado de carpetas: Cifra a nivel de carpeta. El sistema de cifrado se encargará de cifrar y descifrar la información cuando se utiliza la carpeta protegida.

- Cifrado de documentos: Muestra y permite el acceso al documento solo para los usuarios autorizados, haciendo ilegible el contenido a los no autorizados.

### CORTAFUEGOS O FIREWALLS

Diseñados para bloquear el acceso no autorizado al mismo, pero  permitiendo al mismo tiempo las comunicaciones autorizadas. Como criterio genérico, no se deben permitir las conexiones de fuentes desconocidas. Por tanto, deben bloquear todas las conexiones entrantes y solo permitir aquellas que se indiquen expresamente sobre la base de un conjunto de normas y criterios establecidos

<img src="/img/5ºimagenn.PNG"  />

### APLICACIONES ANTIMALWARE

El malware puede causar daños como eliminar o cambiar archivos, agotar recursos, acceder sin autorización, infectar de forma remota, entre otros. Un buen herramienta antimalware o antivirus debe filtrar contenido malicioso, proteger en correo, navegación y conexiones, analizar dispositivos extraíbles y programar chequeos regulares. 

Los antimalware requieren actualizaciones frecuentes y ser de marcas confiables que combinen diversos métodos de protección como estos:

- Escáner de acceso: permite examinar los archivos cuando son abiertos. 

- Escáner a demanda: análisis en base a un calendario establecido. 

- Escáner de correos electrónicos: en dispositivos de protección de  perímetro o servidores de correo. 

- Control de firmas: permite detectar cambios no legítimos en el  contenido de un archivo. 

- Métodos heurísticos: búsqueda de anomalías en los archivos y  procesos en base a experiencias previas de comportamiento del  malware.

  <img src="/img/6ºimagenn.PNG"  />

  Ejemplo de herramienta antimalware

Solo contar con una aplicación antimalware no basta. Se necesita un enfoque centralizado (cliente-servidor) para salvaguardar todos los puntos finales conectados a la red, como servidores, computadoras de escritorio, laptops y smartphones. Algunos proveedores brindan soluciones de Seguridad en los Puntos Finales que engloban antivirus, cortafuegos y otros programas de seguridad.

### BORRADO SEGURO DE DATOS

Hay aplicaciones que permiten  deshacer el formateo de una unidad existiendo  incluso métodos para recuperar los datos de los discos, aunque estos hayan sido sobrescritos. 

Se requiere sobrescribir los datos utilizando un método de borrado que impida su recuperación. Esto implica realizar múltiples pasadas de escritura en los sectores de almacenamiento. Para simplificar este proceso, es conveniente utilizar una aplicación especializada en eliminación de datos.

En el caso de archivos como fotografías, audio, vídeo y documentos, hay metadatos* que pueden guardar información oculta no visible con la configuración estándar de las aplicaciones. Para acceder a esta información, a menudo se necesita una configuración específica o un software dedicado.

Metadatos: Son datos que proporcionan información adicional sobre otros datos. En el contexto digital, los metadatos son detalles descriptivos o informativos que acompañan a un archivo o conjunto de datos.

------



## NAVEGACION SEGURA

El cliente está identificado en la red a través de una dirección IP (TCP/IP)  y cada vez que se conecta a un sitio web, éste conoce automáticamente  la dirección IP, nombre de máquina, la página de procedencia, etc.  Se produce un intercambio de información que habitualmente no es  visible, donde el navegador web es el que facilita la mayoría de estos  datos.

<img src="/img/7ºimagenn.PNG"  />

Un navegador web permite que se acceda a información aparentemente inofensiva:

<img src="/img/8ºimagenn.PNG"  />

Recomendaciones:

- Acceder únicamente a sitios de confianza. 
- Mantener actualizado el navegador a la última versión disponible del  fabricante. 
- Configurar el nivel de seguridad del navegador según sus preferencias. 
- Descargar los programas desde sitios oficiales para evitar suplantaciones maliciosas. 
- Configurar el navegador para evitar ventanas emergentes.
- Utilizar un usuario sin permisos de “Administrador” para navegar por Internet e impedir la instalación de programas y cambios en los valores del sistema.

- Borrar las “cookies”, los ficheros temporales y el historial cuando se utilicen equipos ajenos para no dejar rastro de la navegación. 
- Desactivar la posibilidad “script” en navegadores web, como Firefox  (NoScript) o Chrome (NotScript), para prevenir la ejecución de los mismos por parte de dominios desconocidos. 
- Se recomienda hacer uso de HTTPS (SSL/TLS) frente a HTTP incluso para aquellos servicios que no manejen información sensible. Algunas  funcionalidades como HSTS y extensiones como HTTPS Everywhere servirán de gran ayuda para garantizar el uso preferente de HTTPS sobre HTTP durante la navegación web. 
- En la medida de lo posible, emplear máquinas virtuales para navegar por Internet

Hay que tener en cuenta que los sistemas de navegación anónima permiten el uso de algunos servicios de Internet, principalmente  los basados en navegación web (http/https), de forma desvinculada de  la dirección IP origen de la comunicación.

- Anonimizadores: Actúan como un filtro entre el navegador y sitio web que  se desea visitar.  Al conectarse al anonimizador, se introduce la URL a visitar y entonces éste se adentra en la red filtrando  cookies, javascripts, etc. 
- Servidores Proxy: Un servidor proxy actúa de pasarela entre la máquina  cliente e Internet. El servidor proxy actúa de intermediario, se encarga  de recuperar las páginas web en lugar del usuario que navega. 
- Túneles de Cifrado: (TOR, VPS y Darknets) Red de “túneles” por las cuales los datos de navegación  debidamente cifrados, atraviesan múltiples nodos hasta  llegar a su destino. 

------



## CORREO ELECTRONICO

El incremento y efectividad de la ingeniería social para engañar a los usuarios por medio de correos electrónicos ha modificado el paradigma de la seguridad corporativa. Actualmente los cortafuegos perimetrales y la securización de los  servicios expuestos a Internet no son contramedidas suficientes para proteger una organización de ataques externos.

Algunas recomendaciones para utilizar el correo electrónico de forma segura:

- No abrir ningún enlace ni descargar ningún fichero adjunto procedente de un correo electrónico que presente cualquier indicio o patrón fuera de lo habitual. 
- No confiar únicamente en el nombre del remitente. El usuario deberá  comprobar que el propio dominio del correo recibido es de confianza.  Si un correo procedente de un contacto conocido solicita información inusual, contacte con el mismo por teléfono u otra vía de comunicación para corroborar la legitimidad del mismo. 
- No habilitar las macros de los documentos ofimáticos incluso si el propio fichero así lo solicita.
- Antes de abrir cualquier fichero descargado desde el correo, hay que  asegurarse de la extensión y no fiarse del icono asociado al mismo.
- No hacer clic en ningún enlace que solicite datos personales o bancarios. 
- Utilizar herramientas de seguridad para mitigar exploits de manera  complementaria al software antivirus.
- Evitar hacer clic directamente en cualquier enlace desde el propio cliente de correo. Si el enlace es desconocido, es recomendable buscar información del mismo en motores de búsqueda como Google o Bing. 
- Utilizar contraseñas robustas para el acceso al correo electrónico. Las  contraseñas deberán ser periódicamente renovadas y si es posible utilizar doble autenticación. 
- Cifrar los mensajes de correo que contengan información sensible.
- Tener siempre actualizado el sistema operativo, las aplicaciones ofimáticas y el navegador (incluyendo los plugins/extensiones instaladas)

------



## VIRTUALIZACION

Se entiende como la recreación de un recurso físico (hardware) o lógico (software), por medio de un hipervisor (hypervisor) que permite su ejecución por más de un entorno al mismo tiempo. Cada entorno virtualizado, conocido como máquina virtual, actúa como una entidad independiente con recursos dedicados, como memoria, procesador y almacenamiento.
<center>
<img src="/img/9ºimagenn.PNG"  />
</center>

El apogeo de la virtualización ha llegado con la utilización de la  nube, donde este sistema de reparto de los recursos se hace casi indispensable. Aunque ya existían múltiples sistemas de muchos fabricantes, el desarrollo y avances de los mismos se han incrementad  de una forma exponencial. Actualmente se puede optar, entre otros, por XenServer de Citrix, VMware ESXi de Dell, VirtualBox de Oracle, Oracle VM Server e Hyper-V de Microsoft

Recomendaciones a la hora de la configuracion del host de maquinas virtuales

- Tener instaladas en el sistema operativo las últimas actualizaciones de seguridad. 
- Tener la última reversión disponible del programa de virtualización. 
- Si es posible, tener al menos un adaptador de red en exclusiva para la  infraestructura de virtualización. 
- Crear un entorno de laboratorio aislado del entorno de producción. 
- Disponer de un grupo de seguridad para gestionar la plataforma de  seguridad. 
- Proteger los dispositivos de almacenamiento en los que guardan los archivos de recursos y de definición de la máquina virtual. 
- Mantener estancos a los administradores de los guest respecto a los de host.

Recomendaciones para la creación del guest;

- Hacer un esquema previo de lo que será la infraestructura de virtualización. 
- Dimensionar la creación de máquinas virtuales a las necesidades reales y a los recursos de hardware disponibles en el host. 
- Cifrar los ficheros de máquinas virtuales, instantáneas y discos duros virtuales destinados al almacenamiento de la plataforma de virtualización. 
- Instalar las últimas actualizaciones de seguridad en cada sistema operativo guest. 
- Valorar la instalación de los agentes de hipervisor, tipo Guest Additions, y en caso de hacerlo, mantenerlos actualizados. 
- Asegurar con antimalware y firewalls todos los sistemas operativo  invitados. 
- Conectar medios de almacenamiento externos solo cuando sea necesario y desactivar tras su uso. 
- Mantener activas solamente las máquinas virtuales imprescindibles. 
- Usar para la conexión con la red corporativa o con Internet una interfaz de red virtual diferenciada que se deberá desactivar cuando no se vaya a utilizar. 
- Cifrar los medios de almacenamiento externos que contengan ficheros de virtualización de respaldo y custodiarlos convenientemente.

------



## SEGURIDAD EN DISPOSITIVOS MOVILES

El aumento de las oportunidades y capacidades de los dispositivos móviles en el presente conlleva también riesgos ampliados para su seguridad.

<img src="/img/10ºimagenn.PNG"  />

Consejos: 

- Establecer un método seguro para desbloquear el terminal, por ejemplo,  utilizando una passphrase robusta.
- Es recomendable eliminar las previsualizaciones de los mensajes y extremar las medidas cuando no se disponga del teléfono al alcance. 
- Deshabilitar las conexiones inalámbricas (WiFi, Bluetooth, etc.) y todas aquellas innecesarias mientras no vayan a utilizarse.
- Mantener actualizado el software del dispositivo y utilizar una configuración de seguridad aprobada por el responsable TIC de la  entidad. 
- Tener cuidado con el acceso y las solicitudes de permisos de las aplicaciones que se ejecuten en el teléfono.
- Ignorar y borrar mensajes (SMS, MMS u otros) de origen desconocido que invitan a descargar contenidos o acceder a sitios web. 
- Activar el acceso mediante PIN a las conexiones Bluetooth y configurar el dispositivo en modo oculto. No aceptar conexiones de dispositivos no conocidos. 
- Descargar aplicaciones únicamente desde las tiendas oficiales. En ningún caso, descargar software de sitios poco fiables y en todo caso solicitar al responsable TIC de la entidad las aplicaciones necesarias. 
- Evitar realizar jailbreaking o rooting del terminal, ya que puede comprometer y reducir considerablemente la seguridad del teléfono a pesar de ser tentador para acceder a aplicaciones o servicios específicos. 
- Utilizar una red privada virtual (VPN) para proteger el tráfico de datos desde el dispositivo móvil hasta la infraestructura de la entidad. Siempre es una buena práctica para evitar la posible monitorización por parte de intrusos. 
- Evitar en lo posible el uso de impresoras, faxes o redes WiFi públicas, como las ofrecidas en hoteles o aeropuertos, salvo que se disponga de las herramientas necesarias para asegurar sus comunicaciones. 
- Muchos teléfonos móviles y cámaras digitales añaden las coordenadas GPS en la información de las imágenes tomadas, por lo que es oportuno limitar la compartición de las imágenes en la red o bien utilizar aplicaciones que eliminen dicha información.
- Separar las comunicaciones personales de las profesionales es una buena práctica de seguridad.
- Implementar la gestión centralizada de dispositivos móviles mediante el empleo de agentes MDM (Mobile Device Management). 
- Para manejar información sensible, utilizar únicamente soluciones aprobadas por el responsable de seguridad TIC de la entidad.
