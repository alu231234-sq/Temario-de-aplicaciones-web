## Temario-de-aplicaciones-web
## VERONICA VILLA 
# Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.
 1.-Introducción al desarrollo web
Historia y evolución del desarrollo web: El desarrollo web comenzó a finales de los 80 con Tim Berners-Lee creando la World Wide Web, el primer navegador y servidor, e introduciendo el HTML en 1991 para compartir información. La web evolucionó de un medio estático de texto (Web 1.0) a uno interactivo y social (Web 2.0), incorporando hojas de estilo (CSS) para separar contenido y diseño, y JavaScript para la interactividad. 
<img width="836" height="407" alt="image" src="https://github.com/user-attachments/assets/0228aedb-bf53-40cb-8cb8-3b12f1f72fa8" />

Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA): Las aplicaciones web se clasifican en estáticas (contenido fijo), dinámicas (contenido cambiante y personalizado), Aplicaciones de Página Única (SPA, por sus siglas en inglés) (recargan contenido dentro de una sola página para una experiencia fluida) y Aplicaciones Web Progresivas (PWA, por sus siglas en inglés) (combinan características web y móviles, ofreciendo acceso sin conexión, notificaciones push y experiencia nativa).  

2.Arquitectura de aplicaciones web
Cliente-Servidor: La arquitectura cliente-servidor es un modelo informático donde un programa cliente solicita servicios o recursos a un programa servidor, que los provee.

Arquitectura de tres capas (presentación, lógica, datos): La arquitectura de tres capas es un patrón de diseño de software que organiza una aplicación en tres capas lógicas e independientes: Presentación, que es la interfaz de usuario y maneja la interacción con el usuario; Lógica (o de Negocio), que contiene las reglas de negocio y el procesamiento de datos; y Datos (o de Acceso a Datos), responsable de almacenar y recuperar información de las bases de datos. 

REST y API-first design: REST es un estilo arquitectónico para diseñar servicios web, mientras que API-first design es una metodología de desarrollo que prioriza el diseño de la API antes de la implementación de la aplicación.

3. -Lenguajes y tecnologías fundamentales
HTML, CSS, JavaScript, PHP, MySQL:
1. HTML (HyperText Markup Language)
   <img width="1968" height="1200" alt="image" src="https://github.com/user-attachments/assets/2d28986e-7dd4-4a34-b13f-e38138eab523" />

Propósito:
Es el lenguaje de marcado estándar para la creación de la estructura y el contenido de las páginas web.
 CSS (Cascading Style Sheets)
Propósito:
Se utiliza para definir la presentación y el estilo visual de los elementos HTML.
JavaScript (JS)
Propósito: Aporta interactividad y dinamismo a las páginas web.
PHP (Hypertext Preprocessor)
Propósito: Es un lenguaje de programación del lado del servidor.
MySQL 
Propósito: Es un sistema de gestión de bases de datos relacionales.
4.-Control de versiones
Git y GitHub: Git es un sistema de control de versiones, una herramienta que permite rastrear cambios y gestionar el historial de un proyecto, funcionando de manera local en tu computadora. Por otro lado, GitHub es una plataforma web que utiliza Git para ofrecer un servicio de alojamiento de repositorios en la nube

Flujo de trabajo con ramas (branching, merge, pull requests):Un flujo de trabajo con ramas en control de versiones como Git, como el que se usa en GitHub, permite el desarrollo colaborativo seguro al aislar nuevas funcionalidades en ramas (branches) separadas de la rama principal (main).

# Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web
1.-Diseño e implementación del frontend
<img width="1024" height="455" alt="image" src="https://github.com/user-attachments/assets/f6f292a6-b826-4361-83eb-1b5f3a8695fd" />

Maquetación/Wireframe/Mockup: La maquetación se refiere al proceso de dar estructura y forma a un diseño, utilizando wireframes para el esqueleto funcional y mockups para la representación visual detallada del aspecto final. Los wireframes son bocetos de baja fidelidad que muestran la estructura y la distribución de elementos, priorizando el flujo de usuarios, mientras que los mockups son representaciones estáticas y detalladas del diseño visual, incluyendo colores y tipografías, que simulan el aspecto del producto final. 

API: Una API (interfaz de programación de aplicaciones) es un conjunto de reglas y definiciones que permite que dos aplicaciones de software diferentes se comuniquen entre sí, actuando como un puente para el intercambio de datos y servicios.

2.-Diseño e implementación del backend
Servidor: El diseño e implementación del backend implican la creación de la lógica del lado del servidor, las bases de datos y la infraestructura que dan vida a una aplicación web, Un servidor backend es un programa o sistema informático que ejecuta la lógica principal de una aplicación, gestiona las bases de datos, maneja la seguridad y procesa datos que luego son enviados al frontend

Manejo de peticiones y respuestas HTTP: El manejo de peticiones y respuestas HTTP se basa en un modelo cliente-servidor donde el cliente (por ejemplo, un navegador web) envía una petición a un servidor web solicitando un recurso o acción.

Conexión a bases de datos (MySQL, PostgreSQL, MongoDB): Para conectarse a bases de datos (MySQL, PostgreSQL, MongoDB), se necesitan credenciales como el host, puerto, nombre de usuario y contraseña, además de un cliente o driver compatible con el tipo de base de datos
<img width="225" height="225" alt="image" src="https://github.com/user-attachments/assets/24a5c730-1738-4fab-8f1a-7b2e3bd8830f" />

3.-Bases de datos
 Modelado de datos y relaciones:El modelado de datos es el proceso de crear una representación visual de los datos y sus relaciones para estructurar, almacenar y acceder a la información de manera eficiente.
 
ORM (Object Relational Mapping):Un Object Relational Mapping (ORM) es una técnica de programación que crea una capa de abstracción entre las aplicaciones orientadas a objetos y las bases de datos relacionales, permitiendo a los desarrolladores interactuar con los datos de la base de datos usando el mismo lenguaje de programación que usan para la lógica de la aplicación
CRUD desde el backend:El CRUD (Crear, Leer, Actualizar, Eliminar) es un conjunto de operaciones fundamentales en el backend de una aplicación para gestionar datos persistentes, usualmente a través de una API que interactúa con una base de datos.

4.-Seguridad básica en aplicaciones web
Validación de formularios:La seguridad básica en aplicaciones web incluye la validación de formularios para proteger contra ataques de inyección, validación y escaneo de los datos antes de procesarlos.

Autenticación y autorización :La autenticación verifica que un usuario sea quien dice ser, mientras que la autorización determina qué acciones o recursos ese usuario puede acceder.

# Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional
1. -Integración de frontend y backend
Interfaz de usuario Frontend:La interfaz de usuario (UI) de frontend es la parte de un sitio web o aplicación con la que el usuario interactúa directamente, incluyendo elementos visuales como botones, menús, imágenes y el diseño general, utilizando tecnologías como HTML, CSS y JavaScript.
Manejo de API:El manejo de API (gestión de API o API management) es el proceso de desarrollar, publicar, proteger, monitorizar y analizar las APIs para permitir la comunicación segura y escalable entre diferentes aplicaciones y servicios de software
Proceso de Solicitud y Respuesta de Backend:El proceso de solicitud y respuesta de backend comienza cuando un cliente (navegador o aplicación) envía una solicitud HTTP al servidor. El backend, compuesto por el servidor, la aplicación y la base de datos, procesa esta solicitud validando los datos, ejecutando la lógica de negocio y consultando la base de datos si es necesario.

2.- Almacenamiento en Servidor
Tipos de servidores :Los tipos de servidores varían según su función y la forma en que se alojan o utilizan, incluyendo los servidores web para sitios web, servidores de correo para email, servidores de bases de datos para almacenar datos, servidores proxy como intermediarios, y los servidores virtuales y en la nube que ofrecen flexibilidad y escalabilidad.

Servidores y servicios de hosting :Un servidor es una computadora que provee recursos, mientras que el hosting es el servicio que alquila espacio en un servidor para almacenar archivos de un sitio web y hacerlo accesible en Internet. 

Proveedores de Servicios de Almacenamiento:Los principales proveedores de servicios de almacenamiento son Google Drive, Microsoft OneDrive, Dropbox, iCloud y MEGA, cada uno con características y precios variados para diferentes tipos de usuarios, desde el uso personal hasta necesidades empresariales. También existen otros proveedores más enfocados a empresas como Box y aquellos enfocados en el almacenamiento híbrido y la seguridad como IDrive. 

3.-Optimización y rendimiento
Optimización de recursos (imágenes, scripts):La optimización de recursos, especialmente de imágenes y scripts, consiste en reducir el tamaño de estos archivos para que una página web cargue más rápido y ofrezca una mejor experiencia al usuario
Despliegue de aplicaciones web:El despliegue de aplicaciones web es el proceso de transferir una aplicación desde un entorno de desarrollo a un entorno de producción, volviéndola accesible para los usuarios finales. 

CI/CD básico:CI/CD (Integración Continua/Entrega Continua) es un conjunto de prácticas de DevOps que automatiza la integración, las pruebas y la entrega de código en cada cambio
<img width="1000" height="500" alt="image" src="https://github.com/user-attachments/assets/f33c93c1-a578-4171-8975-aea892fedc97" />


Documentación del proyecto:La documentación de proyectos es la colección de todos los documentos y materiales escritos que describen los objetivos, alcance, presupuesto, riesgos y metodologías de un proyecto. Su propósito es asegurar la transparencia, facilitar la comunicación y la toma de decisiones informadas
