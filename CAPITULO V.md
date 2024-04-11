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







1. **Services Documentation Evidence for Sprint Review.**

El objetivo del primer sprint fue realizar la landing page, por lo tanto aún no se encuentra evidencia del uso de web services.


1. **Software Deployment Evidence for Sprint Review.**

En nuestro primer sprint, concluimos con la creación de nuestra landing page. Las herramienta que se usaron para llevar a cabo esta tarea fueron:

- Git: Un sistema de control de versiones que facilitó la colaboración en la construcción de la página de inicio.
- GitFlow: Un modelo de procesos para gestionar el progreso individual en el desarrollo de la página de inicio.
- GitHub: Una plataforma que sirvió para el desarrollo en equipo, permitiendo almacenar las distintas versiones del proyecto.
- Vercel: Una plataforma destinada a la automatización del alojamiento y lanzamiento de la página de inicio en entornos estáticos.

1. **Team Collaboration Insights during Sprint**

![](https://cdn.discordapp.com/attachments/1077004264792137771/1227885729594736660/image.png?ex=662a08b2&is=661793b2&hm=c5e527477defe9eacadaebcc1ed9a0e57bfa1a25267cd4594a4ebbb475bd3eda&)



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

