1. **Capítulo V: Product Implementation**
   1. **Software Configuration Management.**
      1. **Software Development Environment Configuration**

         A continuación, se ofrecerá una descripción detallada de cada uno de los productos de software utilizados en el proyecto. Esta sección será de gran ayuda para asegurar la colaboración efectiva de los desarrolladores actuales y futuros a lo largo de todo el proceso de desarrollo del proyecto.

         **Project Management**

- ` `Google Meet: <https://meet.google.com/> 

  Se utilizó Google Meet para llevar a cabo reuniones virtuales con los miembros del equipo y proporcionar una plataforma más eficaz para el intercambio de diferentes tipos de contenido, como la visualización conjunta de pantallas, así como la compartición de imágenes, texto y video. Google Meet es accesible desde aplicaciones web, dispositivos móviles y ordenadores de escritorio, ofreciendo una amplia compatibilidad en todas sus variantes. Para hacer uso de la aplicación es imprescindible contar con una cuenta activa.

- Trello: <https://trello.com/home> 

  Utilizamos Trello para la organización y seguimiento de las tareas pendientes, en proceso y completadas. Así se facilita la visibilidad del avance en el desarrollo de las diversas actividades que el equipo tiene en cola. Trello es una aplicación web que funciona con la mayoría de los navegadores actuales y su uso se inicia simplemente con el registro de una cuenta activa.

**Requirement Management**

- Trello: <https://trello.com/home> 

  Para la gestión de requisitos utilizamos Trello, una herramienta que facilita la colaboración en el backlog de forma colectiva y ofrece una interfaz de usuario intuitiva. Además, nos ayuda a tener claridad sobre las prioridades y la dirección estratégica del equipo. Trello es de uso gratuito, aunque es necesario crear una cuenta para poder acceder a sus servicios.

**Product UX/UI Design**

- Miro: <https://miro.com/es/> 

  Miro fue utilizado para la elaboración de los mapas de escenarios(as-is y to-be), proporcionando un enfoque detallado tanto para el mapeo general como para el específico de los segmentos de mercado objetivo. 

- UXpressia: <https://uxpressia.com/> 

  UXpressia nos permitió diseñar y desarrollar representaciones detalladas de nuestros usuarios ideales, ayudando al equipo a visualizar y comprender las necesidades, experiencias, comportamientos y objetivos de los distintos segmentos de nuestra audiencia.

- Figma: <https://www.figma.com/> 

  Figma resultó ser una herramienta esencial en el proceso de diseño, facilitando la elaboración colaborativa de wireframes y mockups.

**Software Development**

- Landing Page

  La landing page se creó utilizando tecnologías estándar como HTML5, CSS3 y JavaScript. Para optimizar la respuesta de diseño y acelerar el desarrollo, se eligió Bootstrap, un framework de CSS muy popular, por su eficiencia y facilidad de uso en la creación de interfaces web responsivas.

**IDE’S de desarrollo**

- **Visual Studio Code:** <https://code.visualstudio.com/> 

  Para la implementación de la landing page, se utilizó Visual Studio Code como el entorno de desarrollo integrado (IDE). Este IDE es ampliamente reconocido por su interfaz intuitiva y funcionalidades que potencian la productividad, como la edición de código, depuración y control de versiones, lo que facilita considerablemente el proceso de desarrollo web.

**Software Testing**

- **Google Lighthouse:  [Lighthouse (google.com)**](https://chromewebstore.google.com/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk)**

  Para verificar la calidad técnica del desarrollo de la landing page, emplearemos Google Lighthouse. Esta herramienta automatiza la evaluación del sitio, ofreciendo una visión clara del rendimiento del producto final. Google Lighthouse es una extensión gratuita compatible con los navegadores que admiten complementos de Google.

**Software Deployment**

- **Vercel: <https://vercel.com/>** 

  El despliegue de la landing page se facilitó mediante la integración del repositorio de GitHub con Vercel. Vercel simplifica el proceso de publicación automática del sitio con cada actualización que se sube al repositorio. Esta plataforma se destaca por su eficiencia en el despliegue continuo y por proporcionar un entorno optimizado para front-end, asegurando una entrega rápida y confiable del contenido web.


**Software Documentation**

- **Google Drive: [Google Drive**](https://www.google.com/intl/es-419_ALL/drive/start/apps.html)**

  Para la gestión inicial de la documentación del proyecto, recurrimos a Google Drive, utilizando específicamente Google Docs y Google Slides. Google Docs nos permitió crear y editar textos de manera colaborativa en tiempo real, mientras que Google Slides fue esencial para la preparación de presentaciones impactantes que resumieran nuestros hallazgos y estrategias. Estas herramientas de Google Drive favorecen la organización y el fácil acceso a la información, además de facilitar la colaboración simultánea de varios usuarios.

- **Lucidchart: <https://www.lucidchart.com>** 

  Utilizamos Lucidchart para crear diagramas UML, lo que nos permitió modelar con claridad la estructura y el diseño de nuestro software. Esta herramienta en línea brinda una plataforma intuitiva y colaborativa para la elaboración de diagramas complejos, facilitando la comunicación visual de las relaciones y procesos del sistema entre el equipo de desarrollo.

- **Structurizr: <https://structurizr.com/>** 

  Para los diagramas de arquitectura C4, elegimos Structurizr. Esta herramienta se especializa en representar la arquitectura de software de manera estructurada y abstracta, permitiéndonos definir y visualizar cómo se compone nuestro sistema en diferentes niveles, desde el nivel más alto de sistema hasta los componentes más detallados.

- **Vertabelo: <https://vertabelo.com/>** 

  En cuanto al diseño y la implementación de bases de datos, nos decantamos por Vertabelo. Esta plataforma de modelado de base de datos en la nube ofrece una interfaz gráfica para diseñar esquemas de bases de datos de manera eficiente, gestionar su estructura y generar el SQL necesario para su implementación, lo que simplificó significativamente este aspecto del proyecto.

1. **Source Code Management**

   Optamos por Github para el manejo de nuestra startup mediante una organización dentro de esta herramienta.

·      **Master Branch**

La Master Branch, también conocido como la rama master, es la rama principal del desarrollo de nuestro proyecto. Aquí se encuentra el desarrollo de la parte que estamos realizando actualmente.

Esta rama la denotamos como ***master***
**


·      **Develop Branch**

La Develop Branch, también conocida como la rama de desarrollo, es el entorno donde se ubican los cambios más recientes realizados por el nuestro equipo de desarrollo. Las actualizaciones realizadas en esta rama siempre serán entregadas en la versión que le sigue.

Esta rama tiene como notación ***develop*** y se crea con el comando el siguiente comando:

Comando de creación: ***gitcheckout -b develop master***



·      **Release Branch**

La Release Branch, también conocida como la rama de lanzamiento, nos permite desarrollar una nueva versión de la aplicación Task Management, al igual que subir las actualizaciones a la Develop Branch y, posteriormente a la Master Branch. En esta rama, también se corrigen los errores de las versiones anteriores.

Su notación es ***release*** y se crea con el siguiente comando:

Comando de creación: ***gitcheckout -b releasedevelop***



·  	**Feature Branch**

La Feature Branch, también conocida como la rama de características, se utiliza para implementar las últimas características y funcionalidades desarrolladas en la aplicación. Estas funcionalidades eventualmente serán implementadas a la Develop Branch.

Su notación es ***feature/[name of feature]*** y su comando de creación es el siguiente:

Comando de creación: ***gitcheckout -b feature/[name of feature]develop***



·      **Hotfix Branch**

La Hotfix Branch, también conocida como la rama de revisiones, se utiliza para solucionar posibles pequeños errores o problemas que, aunque no afectan mucho la experiencia de usuario, siguen siendo pequeños inconvenientes que pueden ser arreglados rápidamente. Esta rama permite solucionar pequeños errores mientras que el resto de los integrantes del equipo se mantienen trabajando en la siguiente versión de la aplicación. Es importante que el contenido de esta rama se derive posteriormente a la Master Branch.

Se denota como ***hotfix*** y su comando de creación es el siguiente:

Comando de creación***: gitcheckout -b hotfix master***


1. **Source Code Style Guide & Conventions**

   Para nuestro proyecto, hemos decidido seguir el Google HTML/CSS Style Guide([Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html)), garantizando así un código claro y coherente que se alinea con las mejores prácticas de la industria. Dentro de las convenciones de esta guía de estilo que adoptaremos se encuentran:

- Utilizar indentación de dos espacios para el HTML y el CSS, lo que contribuye a mantener la legibilidad sin aumentar excesivamente la indentación.
- Mantener la consistencia en la declaración de selectores de CSS, comenzando por los de tipo, seguidos de los ID y, finalmente, los de clase.
- Aplicar nombres descriptivos y breves para las clases, priorizando el guion bajo como separador para garantizar la claridad.
- Incluir comentarios específicos cuando sea necesario explicar el porqué detrás de reglas CSS particulares, especialmente si no son obvias a primera vista.

Para la escritura de código JavaScript en nuestro proyecto, seguiremos el Google JavaScript Style Guide([Google JavaScript Style Guide](https://google.github.io/styleguide/jsguide.html)). Esto asegurará que nuestro código sea uniforme y fácil de mantener. Algunas de las convenciones clave del estilo de Google que implementaremos incluyen:

- Emplear const para declarar variables que no se reasignarán, y let para variables que pueden cambiar, evitando el uso de var para mantener el alcance claro y predecible.
- Usar camelCase para nombrar variables, funciones y métodos, lo que facilita la lectura del código y su identificación.
- Colocar todas las declaraciones de variables al principio de la función o bloque para evitar errores relacionados con el hoisting.
- Limitar el uso de funciones anónimas; en su lugar, usar funciones con nombre para mejorar el stack trace y hacer el código más debuggable.
- Aplicar plantillas de cadena (template strings) para la concatenación, permitiendo una sintaxis más clara y la inclusión de expresiones.

1. **Software Deployment Configuration.**

En esta sección, nos ocuparemos de implementar nuestra página de inicio utilizando el servicio automatizado de Netlify. Con el fin de alcanzar este objetivo, detallaremos los pasos necesarios para realizar el despliegue de manera efectiva.

1. Vinculamos nuestra cuenta de Github a Vercel para darle acceso a todos nuestros repositorios y organizaciones

   ![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.001.png)

1. Creamos un proyecto importando el repositorio que contiene nuestra landing page

   ![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.002.png)

1. **Asignamos un nombre al proyecto, especificamos a vercel cual es la raíz de nuestra landing page y desplegamos.**

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.003.png)

1. **Esperamos a que Vercel despliegue la página** 

   ![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.004.png)

1. **Obtenemos nuestra Landing Page desplegada un link para su visualización: [CropSphere (crop-sphere-landing-page.vercel.app)**](https://crop-sphere-landing-page.vercel.app/)**

   ![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.005.png)**


1. **Product Implementation & Deployment**
   1. **Sprint 1**
      1. **Sprint planning 1**

         A continuación, se detalla el sprint planning número uno, en el que se expondrán las pruebas de planificación y ejecución de la landing page. Además, se mostrarán los progresos del proyecto y los conocimientos adquiridos sobre la colaboración en equipo, obtenidos a través de la utilización de GitHub.

|Sprint#|Sprint 1|
| :- | :- |
|Sprint Planning Background||
|Date|Domingo 7 de abril del 2024|
|Time|19:00|
|Location|Videoconferencia Google Meet|
|Prepared By|AgriSynth Group|
|Attendees|Todo el equipo|
|<p>Sprint n - 0</p><p>Review Summary</p>|Al ser el primer sprint, no hay review summary previo.|
|<p>Sprint n - 1 </p><p>Retrospective Summary</p>|Durante este sprint, nuestro objetivo es desarrollar la landing page utilizando Bootstrap, un framework de estilos que es conocido por todos los miembros del equipo. También se discutirá y definirá el contenido textual de la página y se integrarán los diseños previamente realizados en Figma. Al concluir este sprint, la landing page se publicará mediante Vercel, permitiendo que cualquier usuario pueda acceder y ver la página utilizando el enlace correspondiente.|
|Sprint 1 Velocity|8|
|Sum of Story Points|8|









1. **Sprint Backlog 1**

En esta sección se presentan los tasks realizados durante el actual sprint, acompañadas de una captura del tablero correspondiente y el enlace al tablero en Trello.

**Link del Trello: <https://trello.com/invite/b/TivvG1aQ/ATTI1c57883ea5edd76b34566ceb3166bb584148822A/sprint-1-app-web>** 

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.006.png)

<table><tr><th colspan="2" valign="top"><b>Sprint #</b></th><th colspan="5" valign="top"><b>Sprint 1</b></th></tr>
<tr><td colspan="2" valign="top"><b>User Story</b></td><td colspan="5" valign="top"><b>Work-item / Task</b></td></tr>
<tr><td>ID</td><td>Title</td><td>Id</td><td>Descripción</td><td>Estimación (horas)</td><td>Asignado a:</td><td>Status (pendiente/en proceso/en revisión/hecho)</td></tr>
<tr><td rowspan="2">US01</td><td rowspan="2">Implementación de Barra de navegación</td><td>T1</td><td valign="top">Implementar navbar con logo y diseño responsive</td><td>0\.5h</td><td>Mariana </td><td>hecho</td></tr>
<tr><td>T2</td><td valign="top">Implementar menú desplegable para las secciones</td><td>1h</td><td>Mariana</td><td>hecho</td></tr>
<tr><td rowspan="2">US02</td><td rowspan="2">Logo y Descripción de la Empresa</td><td>T3</td><td valign="top">Implementar hero section</td><td>1h</td><td>David</td><td>hecho</td></tr>
<tr><td>T4</td><td valign="top">Añadir diseño responsive para la hero section</td><td>1h</td><td>David</td><td>hecho</td></tr>
<tr><td rowspan="2">US02</td><td rowspan="2">Logo y Descripción de la Empresa</td><td>T5</td><td valign="top">Implementar about us section con información de visión y misión</td><td>0\.5h</td><td>Marcelo</td><td>hecho</td></tr>
<tr><td>T6</td><td valign="top">Añadir diseño responsive a la section</td><td>0\.5h</td><td>Marcelo</td><td>hecho</td></tr>
<tr><td rowspan="2">US03</td><td rowspan="2">Detalles y Servicios de la empresa</td><td>T7</td><td valign="top">Implementar sección de servicios con 4 ítems resumen.</td><td>1h</td><td>Marcelo</td><td>hecho</td></tr>
<tr><td>T8</td><td valign="top">Añadir diseño responsive.</td><td>2h</td><td>Marcelo</td><td>hecho</td></tr>
<tr><td rowspan="2">US04</td><td rowspan="2">Contacto con un asesor</td><td>T9</td><td valign="top">Implementar form de contacto</td><td>0\.5h</td><td>Piero</td><td>hecho</td></tr>
<tr><td>T10</td><td valign="top">Añadir diseńo responsive a la sección.</td><td>2h</td><td>Piero</td><td>hecho</td></tr>
<tr><td rowspan="2">US05</td><td rowspan="2">Descripción de Planes de suscripción</td><td>T11</td><td valign="top">Diseñar sección de planes que presenta plan asesor y corporativo</td><td>2h</td><td>Eduardo</td><td>hecho</td></tr>
<tr><td>T12</td><td valign="top">Implementar grids y tarjetas de cada plan</td><td>2h</td><td>Eduardo</td><td>hecho</td></tr>
<tr><td rowspan="2">US06</td><td rowspan="2">Compra de planes y suscripción</td><td>T13</td><td valign="top">Diseñar botón de compra dentro de los planes de suscripción</td><td>2h</td><td>Eduardo</td><td>hecho</td></tr>
<tr><td>T14</td><td valign="top">Vincular el botón hacia la aplicación web</td><td>2h</td><td>Eduardo</td><td>hecho</td></tr>
<tr><td rowspan="2">US07</td><td rowspan="2">Implementación de un footer</td><td>T15</td><td valign="top">Implementar footer section</td><td>0\.5h</td><td>Mariana</td><td>hecho</td></tr>
<tr><td>T16</td><td valign="top">Añadir diseño responsive</td><td>0\.5h</td><td>Mariana</td><td>hecho</td></tr>
</table>

1. **Development Evidence for Sprint Review.**

<table><tr><th valign="top"><b>Repository</b></th><th valign="top"><b>Branch</b></th><th valign="top"><b>Commit Id</b></th><th valign="top"><b>Commit Message</b></th><th valign="top"><b>Commit Message Body</b></th><th valign="top"><b>Committed on (Date)</b></th></tr>
<tr><td rowspan="9" valign="top">landing</td><td rowspan="9" valign="top">develop</td><td valign="top">eb02296eb30e22f79e816e1181c82622c51e564f</td><td valign="top">Initial commit</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">92c38ef84e51cc54f1716cc622579bede8b4f6ab</td><td valign="top">initial commit</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">c804ccb2e6f4f08cd40f9642f0756aad72b1c17b</td><td valign="top">add basic index template</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">3b9f05453e5c1f15ece59b07ef1ec5a6e8b4b910</td><td valign="top">add t1 and t2</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">842b2a4f3080fd3149bfbd6dde5e242c4ea77205</td><td valign="top">feat: add section home to landing</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">cc50b26257ab0213f38ee474f0888d713291a887</td><td valign="top">IMPLEMENTED US05, US06, US08 ON THE LANDING PAGE</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">37bacb7b604ef1f2b94c9a76945a448e0a195201</td><td valign="top"><p>Add: User Story 4 Landing page</p><p></p></td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">8107fca1336b3e72ffbc497f63a759311998a79e</td><td valign="top">test: add subscription section from US06</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">014b64f5e077f05e8debd452b345a7ec9ca21b5b</td><td valign="top">fix: indentation and add footer</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
</table>

1. **Testing Suite Evidence for Sprint Review**

<table><tr><th valign="top"><b>Repository</b></th><th valign="top"><b>Branch</b></th><th valign="top"><b>Commit Id</b></th><th valign="top"><b>Commit Message</b></th><th valign="top"><b>Commit Message Body</b></th><th valign="top"><b>Commited on (Date)</b></th></tr>
<tr><td rowspan="11" valign="top"><p>upc-pre-202401-si730-sw53-agrisynth-repor[t](https://github.com/upc-pre-202401-si730-sw53-agrisynth/upc-pre-202401-si730-sw53-agrisynth-report)</p><p></p><p></p></td><td rowspan="11" valign="top">main</td><td valign="top">ecc98d18a139f3a1470a76ce3ca2a1eb78a1892d</td><td valign="top">Doc: Added chapters</td><td valign="top"></td><td valign="top">10/04/2024</td></tr>
<tr><td valign="top">7345794f623f6e0ff2bd8d1ae9a720c432f2f7ae</td><td valign="top">Doc: Update CAPITULO IV</td><td valign="top">Added Landing Page UI Design and 4.5 Web Applications Prototyping</td><td valign="top">10/04/2024</td></tr>
<tr><td valign="top">c55884c54ccd25cfa80fb7e36f6ab44f6558ff46</td><td valign="top">doc: add chapter 1</td><td valign="top"></td><td valign="top">10/04/2024</td></tr>
<tr><td valign="top">a9c64dd233d4cf4edca0a6cdb45759f91da5c6f6</td><td valign="top">fix: corrección doc chapter 1</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">57a088620ec5ee8856f1757bb8b38564d2bcd984</td><td valign="top">doc: add chapter 2 from 2.1 to 2.2.1</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">dd989523cd612e9f40696921917357cc59bfc21c</td><td valign="top">docs: add team names</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">93594a7fc34d90d128ba3c0cce12be97e8bf275c</td><td valign="top">doc: add more items from chapter 2</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">5cedc9a2998dc0934720f42e050edc8f38f608f0</td><td valign="top">doc: start writing chapter 3</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">879dba95315c360326abc434862dccc624d97726</td><td valign="top">doc: add more items in chapter 4</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">628935d7808558c657d97c3c1a2957563b7c18fc</td><td valign="top">feat: add and complete the chapter 4</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
<tr><td valign="top">f5acd29ce449a784ac4fd5836d4c7a7d8f73fcb0</td><td valign="top">Added the Users Stories and Product Backlog</td><td valign="top"></td><td valign="top">11/04/2024</td></tr>
</table>

1. **Execution Evidence for Sprint Review**

   Para esta entrega nuestra startup AgriSynth trabajó en conjunto para el diseño e implementación de la landing page de nuestro producto de software, la cual se centra en la conversación de usuario a cliente, a través de información acerca de nuestro proyecto, los servicios que ofrece y un formulario de contacto directo.

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.007.png)

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.008.png)

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.009.png)

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.010.png)

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.011.png)

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.012.png)

1. **Services Documentation Evidence for Sprint Review.**

El objetivo del primer sprint fue realizar la landing page, por lo tanto aún no se encuentra evidencia del uso de web services.


1. **Software Deployment Evidence for Sprint Review.**

En nuestro primer sprint, concluimos con la creación de nuestra landing page. Las herramienta que se usaron para llevar a cabo esta tarea fueron:

- Git: Un sistema de control de versiones que facilitó la colaboración en la construcción de la página de inicio.
- GitFlow: Un modelo de procesos para gestionar el progreso individual en el desarrollo de la página de inicio.
- GitHub: Una plataforma que sirvió para el desarrollo en equipo, permitiendo almacenar las distintas versiones del proyecto.
- Vercel: Una plataforma destinada a la automatización del alojamiento y lanzamiento de la página de inicio en entornos estáticos.

1. **Team Collaboration Insights during Sprint**

![ref1]

1. **Sprint 2**
   1. **Sprint Planning 2.**

|Sprint#|Sprint 2|
| :- | :- |
|Sprint Planning Background||
|Date|Domingo 23 de abril del 2024|
|Time|19:00|
|Location|Remoto vía Discord|
|Prepared By|AgriSynth Group|
|Attendees|Todo el equipo|
|<p>Sprint n - 0</p><p>Review Summary</p>|La página de inicio fue exitosamente lanzada con Vercel, sin embargo, no se implementan las funcionalidades de cambio de idioma ni la sección de términos y condiciones. Estos elementos se abordarán en el sprint actual.|
|<p>Sprint n - 1 </p><p>Retrospective Summary</p>|Para este sprint, se avanza en el desarrollo del front-end de la aplicación web, añadiendo vistas para la autenticación de usuarios y vistas principales para usuarios reclutadores. También se incluirá la configuración multilingüe utilizando la librería i18n en Vue. Además, se tiene previsto elaborar las secciones de términos de servicio y vídeos sobre el producto y el equipo. Hemos organizado las tareas a través de Trello. Al concluir este sprint, esperamos que la página de inicio esté actualizada y que se disponga de una demostración funcional de la aplicación web desplegada en Netlify, aunque los datos solo se mostrarán cuando el servidor json esté en ejecución.|
|Sprint 1 Velocity|8|
|Sum of Story Points|8|

1. **Sprint Backlog 2.**

|**Sprint #**|**Sprint 2**||||||
| :- | :- | :- | :- | :- | :- | :- |
|**User Story**|**Work-item / Task**||||||
|ID|Title|Id|Descripción|Estimación (horas)|Asignado a:|Status (pendiente/en proceso/en revisión/hecho)|
|EP1 / US01|Registro de un nuevo usuario|T1|Implementar un sistema de registro de usuario|4H|Marcelo |hecho|
|EP1 / US02|Acceso de usuarios|T2|Implementar un sistema que permita a los usuarios ingresar al sistema|4H|Marcelo|hecho|
|EP1 / US03|Recuperación de Contraseña|T3|Implementar un sistema que permita al usuario recuperar su contraseña, en caso la pierda|4H|Marcelo|hecho|
|EP2 / US01|Creación de un recurso|T4|Permitir al usuario crear un recurso en la aplicación, para que pueda hacer un seguimiento del mismo|8H|David|hecho|
|EP3 / US03|Edición de un recurso|T7|Implementar un sistema que permita al usuario que editar un recurso que ha creado|4H|Mariana|hecho|
|EP3 / US02|Borrado de recurso|T8|Implementar un sistema que permita al usuario borrar un recurso en caso ya no lo utilice|4H|David|hecho|
|EP4 / US01|Visualizar detalles de Maquinaria|T9|Implementar un dialog de primevue que muestre información detallada de la maquinaria seleccionada|4H|Mariana|hecho|
|EP4 / US02|Visualizar detalles de Terrenos|T10|Implementar dialog de primevue que muestre información más detallada de los terrenos|6H|Piero|hecho|
|EP4 / US03|Alquiler y Compra de Maquinaria o Terreno|T11|Implementar formulario con datos pertinentes a la compra.|8H|<p>Piero /</p><p>Mariana</p>|hecho|
|EP05 / US01|Visualización de Estadísticas de Recursos|T12|Implementar vista de estadística que toma como datos el historial de precios de un producto|8H|David|hecho|
|EP5 / US02|Comparación de Precios de Terrenos y Maquinaria|T13|Implementar tabla que compare precios de terrenos según su selección.|8H|David|hecho|
|EP06 / US01|Creación de grupo de Trabajo|T14|Implementar un dialog que permita el post dentro del db.json|8H|Eduardo|hecho|
|EP06 / US02|Agregar personas al grupo|T15|Implementar botón add member que asigne al grupo.|5H|Eduardo|hecho|
|EP06 / US03|Visualizar los integrantes del grupo|T16|Implementar tabla que cree grupos y muestre integrantes.|4H|Eduardo|hecho|
|EP06 / US04|Eliminar personas del grupo|T17|Implementar un botón que elimine el member dentro del grupo.|4H|Eduardo|hecho|
|EP08 / US02|Ajuste de Datos Personales|T22|Implementar un sistema que permita cambiar sus datos personales|4H|Marcelo|hecho|
|EP08 / US03|Cambio de contraseña|T23|Implementar un sistema que permita al usuario cambiar su contraseña registrada|4H|Marcelo|hecho|

1. **Development Evidence for Sprint Review.**

Repositorio en Github: 

<table><tr><th valign="top"><b>Repository</b></th><th valign="top"><b>Branch</b></th><th valign="top"><b>Commit Id</b></th><th valign="top"><b>Commit Message</b></th><th valign="top"><b>Commit Message Body</b></th><th valign="top"><b>Committed on (Date)</b></th></tr>
<tr><td rowspan="20" valign="top">agrisynth-frontend</td><td rowspan="20" valign="top">DEVELOP</td><td valign="top">efc759fd8fd6b85f5ed5e292caac01995edc48eb</td><td valign="top">chore: add the first structure</td><td valign="top">None</td><td valign="top">Apr 26, 2024</td></tr>
<tr><td valign="top">324e3926c7f11341d1f0b438dc4ee5dc36fd420f</td><td valign="top">docs: update the README.md</td><td valign="top">None</td><td valign="top">Apr 26, 2024</td></tr>
<tr><td valign="top">318b8e5632d2eb7fd636436f2f83cc04929c571e</td><td valign="top">feat: add dependencies</td><td valign="top">None</td><td valign="top">Apr 27, 2024</td></tr>
<tr><td valign="top">5b829a23ff93a32409e56ab1ac24bcb4290750fa</td><td valign="top"><p>add: terrain-card component , terrain.entity and terrain.api created</p><p></p></td><td valign="top">None</td><td valign="top">Apr 27, 2024</td></tr>
<tr><td valign="top">b22532731f262640eae3539e08fdeb8de06662a4</td><td valign="top">update: terrain list component added</td><td valign="top">None</td><td valign="top">Apr 27, 2024</td></tr>
<tr><td valign="top">2a65ff400e389d974de6e4a9e972faa40553a52a</td><td valign="top"><p>update: components</p><p></p></td><td valign="top"><p>The terrain-card and terrain-list components were updated, and also terrain.entity</p><p></p></td><td valign="top">Apr 28, 2024</td></tr>
<tr><td valign="top">21886ba7edf1df2baab739950d7e1251888fb119</td><td valign="top"><p>add: dialog boxes added</p><p></p></td><td valign="top">The description, processing and payment dialog box was added for each terrain-card</td><td valign="top">Apr 28, 2024</td></tr>
<tr><td valign="top">170ef82c47dd336eb43c480def307f395d54860e</td><td valign="top">update: css update</td><td valign="top">None</td><td valign="top">Apr 29, 2024</td></tr>
<tr><td valign="top">f471b66a985dbd0eb0e25fe80022e6125214ba53</td><td valign="top">update: language component changed</td><td valign="top">None</td><td valign="top">Apr 29, 2024</td></tr>
<tr><td valign="top">f21b3d3354bcf66ebfe835766d5e21f05305f4e4</td><td valign="top">update: input text dialog updated</td><td valign="top">None</td><td valign="top">Apr 30, 2024</td></tr>
<tr><td valign="top">f3021cc5f3c226953fcd6e71efebec6750dc66df</td><td valign="top">update: api updated</td><td valign="top">None</td><td valign="top">Apr 30, 2024</td></tr>
<tr><td valign="top">fd2e33829cd07e92678ec73b5b2acf911dd60b81</td><td valign="top"><p>update: terrain-list component</p><p></p></td><td valign="top">None</td><td valign="top">May 3, 2024</td></tr>
<tr><td valign="top">fd2dffd132a9af032004076b2416248dbefbf3d9</td><td valign="top">update: update index.js</td><td valign="top">None</td><td valign="top">May 3, 2024</td></tr>
<tr><td valign="top">52d87190a9249a8b4536147c44c7dae47a76e4d1</td><td valign="top">Update terrain-list.component.vue</td><td valign="top">None</td><td valign="top">May 3, 2024</td></tr>
<tr><td valign="top">b633ed9b0f5afb10c485988f732c355f1b0a02a7</td><td valign="top"><p>Merge pull request #3 from upc-pre-202401-si730-sw53-agrisynth/feature/terrains</p><p></p></td><td valign="top"><p>Feature/terrains</p><p></p></td><td valign="top">May 3, 2024</td></tr>
<tr><td valign="top">8db9a2e590c8e733cb1024bab7fdc6fb04d294cb</td><td valign="top">feat: add the view resources with components</td><td valign="top">None</td><td valign="top">May 3, 2024</td></tr>
<tr><td valign="top">16d05deee4c300ed24f8d4a023c7b8736e1b5b2e</td><td valign="top"><p>Merge pull request #4 from upc-pre-202401-si730-sw53-agrisynth/feature/resources</p><p></p></td><td valign="top">feat: add the view resources with components</td><td valign="top">May 3, 2024</td></tr>
<tr><td valign="top">fb8e7b907c86952b684e1e755abde7cbcee48624</td><td valign="top"><p>feat: add the page machinerys with components</p><p></p></td><td valign="top">None</td><td valign="top">May 3, 2024</td></tr>
<tr><td valign="top">7bdbaf0789c6d4454f2897dbd4018e34d1f52a51</td><td valign="top"><p>Merge pull request #6 from upc-pre-202401-si730-sw53-agrisynth/feature/machinerys</p><p></p></td><td valign="top"><p>feat: add the page machinerys with components</p><p></p></td><td valign="top">May 3, 2024</td></tr>
<tr><td valign="top">9b466dea93637ddb1bb641e54aa5727524df2a7b</td><td valign="top"><p>feat(add): implement feature collaboration in the sidenav bar</p><p></p></td><td valign="top">None</td><td valign="top">May 3, 2024</td></tr>
<tr><td valign="top"></td><td valign="top"></td><td valign="top">a4c82a538edba990dc889ab448bef6299bb48224</td><td valign="top"><p>feat(add): implement css in collaboration page</p><p></p></td><td valign="top">None</td><td valign="top">May 3, 2024</td></tr>
<tr><td valign="top"></td><td valign="top"></td><td valign="top">2d540eeb5a00140ee6429ee0a2577648f1668154</td><td valign="top"><p>Merge pull request #7 from upc-pre-202401-si730-sw53-agrisynth/feature/collaboration</p><p></p></td><td valign="top"><p>Feature/collaboration</p><p></p></td><td valign="top">May 3, 2024</td></tr>
<tr><td valign="top"></td><td valign="top"></td><td valign="top">262c01186cf7763c6ac0f93a66202e19a46610d4</td><td valign="top"><p>feat: added authentications, configuration and support pages</p><p></p></td><td valign="top">None</td><td valign="top">May 3, 2024</td></tr>
<tr><td valign="top"></td><td valign="top"></td><td valign="top">af673e2aa5d217e23ca4e01b577b5508ae65567f</td><td valign="top"><p>Merge pull request #8 from upc-pre-202401-si730-sw53-agrisynth/feature/authentication</p><p></p></td><td valign="top"><p>feat: added authentications, configuration and support pages</p><p></p></td><td valign="top">May 3, 2024</td></tr>
</table>

1. **Testing Suite Evidence for Sprint Review.**

En el alcance del sprint 2 se ha desarrollado el frontend de la aplicación web por lo que no se evidencia testing.

1. **Execution Evidence for Sprint Review.**

En este sprint logramos como primera fase de nuestro producto final, desarrollar nuestra aplicación web usando Vue y PrimeVue, en conjunto con una API hecha con JSON server. 

Muestra de todas  vistas programadas en Vue para este sprint: 

- Pantalla de Login

  ![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.014.png)

- Pantalla de Register

  ![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.015.png)

- Dashboard o pantalla de Terrains

  ![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.016.png)

- Pantalla de Resource Management

  ![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.017.png)

- Pantalla de Machineries

  ![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.018.png)

- Pantalla de Group

  ![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.019.png)

- Pantalla de Suport and help

  ![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.020.png)

- Pantalla de settings

  ![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.021.png)

  - Muestra de la respuesta de nuestra API hecha con JSON server: 

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.022.png)

Enlace del video: 


1. **Services Documentation Evidence for Sprint Review.**

Para este sprint utilizamos los servicios básicos Http en conjunto con Json server que facilitó la construcción de nuestra fake api.

Nuestras variable de entorno serverBasePath que apuntará al puerto 3000:

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.023.png)

Nuestra clase BaseService

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.024.png)

Un ejemplo usando un endpoint:

![](Assets/C5-images/spose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.025.png)

1. **Software Deployment Evidence for Sprint Review.**

Creamos un nuevo site desde un proyecto existente en Github

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.026.png)

Instalamos Netlify en nuestra organización de Github

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.027.png)

Damos acceso a todos nuestros repositorios de nuestra organización.

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.028.png)

Seleccionamos el repositorio del que queremos hacer el new site

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.029.png)

seleccionamos nuestra rama de la que queremos que haga el build

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.030.png)

esperamos y tenemos el link de nuestro aplicación web desplegueda.

![](Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.031.png)

1. **Team Collaboration Insights for Sprint Review**

Durante este sprint, al igual que para el desarrollo de la landing page, para proteger la rama “main” creamos una rama “develop” de la que cada integrante de nuestro grupo creó su propia sub-rama “feature“ para subir un capítulo del reporte siguiendo las convenciones antes señaladas(conventional commit y git flow).
(img de las ramas)

![ref1]

**Conclusiones**

- Nuestro análisis comparativo con los competidores resaltó la necesidad de diferenciarnos claramente en el mercado. Identificamos y destacamos nuestras ventajas competitivas, como la integración de asesoramiento agronómico con tecnología avanzada.
- A través de las entrevistas realizadas, hemos obtenido una comprensión más profunda de las necesidades, desafíos y prioridades de las empresas agrícolas de gran escala.
- Dada la diversidad de empresas agrícolas de gran escala, es crucial que nuestra solución sea adaptable y escalable para satisfacer una variedad de necesidades y contextos operativos. Esto requerirá un enfoque flexible en el diseño y desarrollo de nuestro producto, así como la capacidad de ajustarnos a medida que el mercado evoluciona.
- Las opiniones y comentarios recopilados durante las entrevistas también nos han permitido identificar áreas de mejora potenciales en nuestro enfoque, producto o estrategias de comercialización. Estas áreas pueden incluir aspectos como la personalización de la experiencia del usuario o la integración de funcionalidades adicionales.
- La comunicación y la colaboración entre los diferentes actores del sector agrícola son clave para el éxito de las operaciones a gran escala. Las empresas buscan soluciones que faciliten la comunicación directa entre agricultores, asesores y otros stakeholders, fomentando así la coordinación y el intercambio de información.



**Bibliografía**

- *Pérez, J., & Gómez, M. (2018). Tecnología agrícola y su impacto en la sostenibilidad: Un análisis de casos en América Latina. Revista de Agricultura Sostenible, 10(2), 45-58.*
- *Smith, A. R., & Johnson, B. (2020). Agricultural Technology and Innovation: Improving Efficiency and Sustainability. Journal of Agricultural Science, 25(3), 112-125.*
- *Rodríguez, L. M., & Martínez, E. (2019). Gestión eficiente de recursos agrícolas: un enfoque basado en tecnologías digitales. Revista de Ingeniería Agrícola, 15(1), 78-91.*
- *García, S., & Fernández, P. (2017). Integración de Tecnologías de la Información y Comunicación en la Agricultura: Caso de estudio de una gran empresa agrícola en Perú. Revista Latinoamericana de Agricultura Digital, 5(2), 30-45.*
- *López, R., & González, E. (2016). Impacto de las Tecnologías Digitales en la Productividad Agrícola: Un estudio de caso en una empresa agrícola de Argentina. Revista de Economía Agrícola, 12(3), 67-82.*




**Anexos**

- Video con las entrevistas: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u201923446_upc_edu_pe/Ef7dxCD2PvxJtzA_nHQw3jABskCdcqxvkc09BDq0fDxMyA?e=fnxdY5&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D>
- Product Backlog: <https://trello.com/invite/b/8RJvHxZr/ATTIfd792e4a433c343855fbd42b86ea3c10EF0ACDF1/aplicaciones-web> 
- Landing Page Wireframe y Mock-up: <https://www.figma.com/file/5KPinQgEbux6OZv47qJezq/Landing-Page-Aplicaciones-web?type=design&node-id=0%3A1&mode=design&t=oe2AJnrQrg9Tj3rA-1> 
- Web Applications Wireframes y Mock-up: <https://www.figma.com/file/jaoLACRcU6mUfxjIsSj4Z1/Aplicaciones-Web-Wireframes-y-Mock-up?type=design&node-id=0%3A1&mode=design&t=qRdEdZZ8vVcoJSyc-1> 
- Web Applications Prototyping: <https://upcedupe-my.sharepoint.com/:v:/g/personal/u201923446_upc_edu_pe/ETiSuNru3_VCp4jdSts16XIB__Zeo8wTurh-FBzmHK-ykQ?e=kSLfXo&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D> 
- Class Diagrams: <https://lucid.app/lucidchart/3cd5eaae-f232-4461-8c6d-0d2f66abb3f5/edit?viewport_loc=-8499%2C-3299%2C10921%2C4870%2C0_0&invitationId=inv_9e61d11c-9bbb-4983-bc8b-d3f6c703f606> 
- Database Diagram: <https://drive.google.com/file/d/1UkI6uDxWvgKDRsg5c59VnLGloKkd2G4G/view?usp=sharing> 
- Sprint Backlog 1: <https://trello.com/invite/b/TivvG1aQ/ATTI1c57883ea5edd76b34566ceb3166bb584148822A/sprint-1-app-web> 

**Segmento objetivo: Ingenieros Agrónomos que Asesoran a Agricultores**

- User persona : <https://uxpressia.com/w/DeRZM/p/iE56Q> 
- User Journey Mapping : <https://uxpressia.com/w/DeRZM/m/5td8l> 
- Empathy Mapping: <https://uxpressia.com/w/DeRZM/p/oj8l0> 
- As-is Scenario Mapping: <https://miro.com/welcomeonboard/dDdyWmRYWjB0MHM0dk1GbFQxU3RVdHY2aUpyV2xFSzlzWUtHcGtuOE02bWFSNVRJRXU5aTFsZnVmekdQRWd1dHwzNDU4NzY0NTUxNzYxNjYxMjg2fDI=?share_link_id=176300122658> 
- To-Be Scenario Mapping: <https://miro.com/welcomeonboard/dDdyWmRYWjB0MHM0dk1GbFQxU3RVdHY2aUpyV2xFSzlzWUtHcGtuOE02bWFSNVRJRXU5aTFsZnVmekdQRWd1dHwzNDU4NzY0NTUxNzYxNjYxMjg2fDI=?share_link_id=176300122658> 

**Segmento objetivo: Empresas Agrícolas de Gran Escala**

- User persona: <https://uxpressia.com/w/DeRZM/p/R02Cr> 
- User Journey Mapping: <https://uxpressia.com/w/DeRZM/m/vNTpp> 
- Empathy Mapping: <https://uxpressia.com/w/DeRZM/p/C8egI> 
- As-is Scenario Mapping: <https://miro.com/welcomeonboard/dDdyWmRYWjB0MHM0dk1GbFQxU3RVdHY2aUpyV2xFSzlzWUtHcGtuOE02bWFSNVRJRXU5aTFsZnVmekdQRWd1dHwzNDU4NzY0NTUxNzYxNjYxMjg2fDI=?share_link_id=176300122658> 
- To-Be Scenario Mapping: <https://miro.com/welcomeonboard/dDdyWmRYWjB0MHM0dk1GbFQxU3RVdHY2aUpyV2xFSzlzWUtHcGtuOE02bWFSNVRJRXU5aTFsZnVmekdQRWd1dHwzNDU4NzY0NTUxNzYxNjYxMjg2fDI=?share_link_id=176300122658> 

[ref1]: Assets/C5-images/Aspose.Words.1e69c443-57fa-44d8-8666-d4b246cde8aa.013.png
