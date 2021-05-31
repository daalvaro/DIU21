# DIU21
Prácticas Diseño Interfaces de Usuario 2020-21 (Tema: Turismo) 

Grupo: DIU3_BÚHOS.  Curso: 2020/21 
Updated: 15/05/2021

Proyecto: 

> GranadaTour

Descripción: 

> GranadaTour es una aplicación para realizar rutas de carácter cultural recorriendo la ciudad de Granada. La aplicación permite seleccionar una ruta ya preestablecida o crear una propia, seleccionando las actividades que se quieren realizar.

Logotipo: 


![logo](P3/logotipoWeb.png)

Miembros
 * :bust_in_silhouette:  Álvaro Domínguez Aguilar     :octocat:     
 * :bust_in_silhouette:  Laura Ortiz González     :octocat:

----- 

# Proceso de Diseño 

## Paso 1. UX Desk Research & Analisis 

![Método UX](img/Competitive.png) 1.a Competitive Analysis
-----

Hemos analizado las webs de turismo: [Freetour](https://www.freetour.com), [way away](https://www.way-away.es/), [World Travel Guide](https://www.worldtravelguide.net/), [wanderlog](https://www.worldtravelguide.net/), [TripRepublic](https://triprepublic.com/) y [Sygic](https://travel.sygic.com/es). Hemos elegido Sygic como plataforma para analizar en profundidad, ya que esta cuenta tanto con tours prediseñados y fáciles de reservar como con la posibilidad de personalizar unas rutas ya sugeridas o crearlas desde cero; cubriendo así con lo que la mayoría de personas buscan en una página de planificación de viajes.

Para consultar la tabla de comparativas y una breve descripción de cada una de las webs de turismo, pulse [aquí](P1/).

![Método UX](img/Persona.png) 1.b Persona
-----

Hemos creado dos personas ficticias que podrían ser usuarios potenciales de [Sygic](https://travel.sygic.com/es). El primero de ellos es Lionel, un joven al que le gustaría disfrutar de unas vacaciones.

![foto1](P1/lionel_journey.png)

El segundo es Marcos, un hombre sin muchos conocimientos tecnológicos que desearía ir de viaje con su familia al centro de Europa.
 
![foto2](P1/marcos.png)

![Método UX](img/JourneyMap.png) 1.c User Journey Map
----

En los mapas de experiencia de ambos usuarios, se expone la experiencia que han tenido Lionel y Marcos para realizar la reserva del viaje y los problemas que han surgido durante este proceso, como la dificultad de tener que reservar cada una de las actividades por separado y una interfaz no muy amigable para los usuarios que no han utilizado este tipo de páginas web.

- Lionel Huet

![foto3](P1/lionel_journey.png)


- Marcos Lanza Laguna

![foto4](P1/marcos_journey.png)


![Método UX](img/usabilityReview.png) 1.d Usability Review
----
- Enlace al documento:
      Para ver el PDF [pulse aquí](P1/Usability_review.pdf)

- Valoración final: 75
- Comentario sobre la valoración: La página web ha obtenido una calificación de 75 puntos en la revisión de usabilidad, lo que puede considerarse como buena. Entre lo más destacable, incluye un amplio número de filtros que permiten seleccionar todo tipo de actividades y cada actividad va acompañada con información relevante (imágenes, descripción y ubicación en un mapa interactivo). Sin embargo, uno de sus mayores defectos es que es complicada de utilizar si no se tiene experiencia en este tipo de páginas web o conocimientos tecnológicos suficientes, debido a que la interfaz puede resultar confusa para el usuario, además de la dificultad que supone crear una ruta personalizada así como la reserva independiente de cada una de las actividades.


## Paso 2. UX Design  


![Método UX](img/feedback-capture-grid.png) 2.a Feedback Capture Grid / EMpathy map / POV
----

En la malla receptora de información hemos recabado toda la información de los usuarios de la práctica 1 (Lionel y Marcos). En esta malla receptora de información se ha tenido en cuenta las inquietudes/críticas de los usuarios así como las funcionalidades que satisfacían las necesidades y las mejoras que se podría realizar sobre la aplicación.

![foto5](P2/Malla_receptora.png)


![Método UX](img/ScopeCanvas.png) 2.b ScopeCanvas
----

Nuestro proyecto, llamado GranadaTour, consiste en una aplicación para realizar rutas de carácter cultural en la ciudad de Granada. La aplicación permite seleccionar una ruta ya preestablecida o crear una propia, seleccionando las actividades que se quieren realizar.

![foto6](P2/ScopeCanvas.png)


![Método UX](img/Sitemap.png) 2.b Tasks analysis 
-----

| Grupos de usuarios             | Jóvenes | Adultos sin hijos | Adultos con hijos | Ancianos | Agentes de viaje |  
| :------:                       | :------:| :----------------:| :----------------:| :--------| :---------------:|
| Buscar actividades infantiles  |    L    |          L        |          H        |     M    |         H        |
| Utilizar rutas preestablecidas |    L    |          M        |          H        |     H    |         M        |
| Utilizar rutas personalizables |    H    |          M        |          L        |     L    |         M        |
| Accesibilidad                  |    L    |          L        |         M/H       |     H    |         M        |    
| Ofertas                        |    H    |          M        |         M/H       |     L    |         M        |
| Comida incluida                |    L    |          H        |          M        |     H    |         M        |

En la matriz de tareas/usuarios hemos enumerado los distintos perfiles de usuarios que pueden utilizar la página web y las frecuencias con que utilizarían las distintas funcionalidades de dicha web.

![Método UX](img/labelling.png) 2.c IA: Sitemap + Labelling 
----
En el mapa del sitio se presentan todos los elementos que permiten la navegación por las diferentes secciones de la página web, así como una pequeña descripción de cada uno de esos elementos.

- Mapa del sitio

![foto7](P2/Sitemap.png)

- Labelling

| Label                | Scope Note                                                                                                                                  | 
| :------:             | :------------------------------------------------------------------------------------------------------------------------------------------:| 
| Preguntas Frecuentes | Ayuda para el usuario con respuestas a preguntas que han surgido a otro usuario                                                             |
| Contacto             | Forma de contactar con el servicio de atención al cliente, con atención 24h o de 8:00 a 18:00 con un agente                                 |
| Ruta preestablecida  | Acceso directo al sitio web de rutas preestablecidas                                                                                        |
| Ruta personalizada   | Acceso directo al sitio web de rutas personalizadas                                                                                         |
| Reservar             | Acceso al resumen de la ruta preestablecida o a la descripción lugar de una ruta personalizada y a opción de pago para obtener las entradas |
| Añadir               | Permite añadir un lugar/evento a una lista de lugares para formar una ruta personalizada                                                    |
| Página oficial       | Acceso directo a la página oficial a un lugar de alguna ruta      


![Método UX](img/Wireframes.png) 2.d Wireframes
-----

Los wireframes se han diseñado teniendo en cuenta el principal enfoque de nuestro proyecto, permitir la selección de tours predefinidos o crear una ruta propia. En la sección de tours, se obtiene un listado de todos los tours disponibles así como una selección de filtros. Cada uno de estos tours lleva a una página con la descripción general del tour y las actividades en las que se compone así como la opción de reservar dicho tour.

En la sección de rutas personalizable, se dispone un listado de todas las actividades que se pueden añadir a la ruta y un mapa interactivo en el que se puede observar la localización de dicha actividad e información detallada.

Por último, se han diseñado secciones de preguntas frecuentes y contacto para los usuarios que lo necesiten.

Para ver los bocetos [pulse aquí](P2/Bocetos/)


## Paso 3. Mi UX-Case Study (diseño)

![Método UX](img/moodboard.png) 3.a Moodboard
-----

El moodboard se puede observar en el siguiente [enlace](https://app.milanote.com/1Lzdo81SfLJFe1?p=R101J9FhGuJ).

Para el tipo de fuente, buscamos primero una que resaltara con el título así que nos decantamos por Anton; una Sans-Serif utilizada en publicidad. Su forma, aunque llamativa, no es excesivamente atrevida y da una sensación moderna, agradable y fácil de leer en una pantalla. Junto a esta, para complementar, elegimos una Montserrat ya que queríamos darle un toque de actualidad a nuestra página, salir de lo tradicional que es lo que se suele asociar al turismo en Granada.

Para los colores, quisimos mantener la esencia de Granada, el rojo y amarillo que recuerdan a la propia fruta y aportan una sensación de calidez en la página. Asimismo, para contrastar y dar vida a la página utilizamos un verde como color de resalte. Para mantener esa calidez utilizamos versiones pastel de los colores. Además, para favorecer la lectura de la página y la accesibilidad de la misma, utilizamos letra negra sobre fondo blanco.

- ![#f999a2](https://via.placeholder.com/15/f999a2/000000?text=+) `#f999a2` Como color principal. El texto será blanco sobre este color.
- ![#ffc99d](https://via.placeholder.com/15/ffc99d/000000?text=+) `#ffc99d` Como color secundario. El texto será negro sobre este color.
- ![#77c1ad](https://via.placeholder.com/15/77c1ad/000000?text=+) `#77c1ad` Como color de resalte para iconos y botones. El texto será blanco sobre este 

![Método UX](img/landing-page.png)  3.b Landing Page
----

![foto8](P3/LandingPage.png)


![Método UX](img/guidelines.png) 3.c Guidelines
----


Utilizaremos los siguientes patrones:
- Para el rellenado de formularios (en la sección de preguntas o de contacto), se utilizarán diversos patrones:
    - El propio **Contact Forms**, para permitir al usuario contactar con nosotros.
    - **Input Hints**, para ayudar al usuario a saber qué debe escribir en cada cuadro.
    - **Inline Validation**, por si algún cuadro obligatorio no está rellenado o hay información errónea.
     
- Para reservar utilizaremos los siguientes patrones:
    - **Immediate Immersion** (Lazy Signups). Para favorecer la estancia del usuario en la web y disminuir su nivel de malestar, no forzaremos a iniciar sesión hasta que se tenga que reservar un viaje o se quiera guardar la ruta de viaje que se esté construyendo.
    - **Social Login**. Permitiremos iniciar sesión con redes sociales además del correo electrónico, para favorecer la fluidez y comodidad del usuario.
    - **Stepped Form** (Wizards), para orientar al usuario en las diversas etapas de la reserva del viaje.
    - **Morphing Controls**. El botón de añadir y quitar actividad no pueden aparecer a la vez.
    - **Undo**. Para ayudar al usuario si este se equivoca.
    
- Para el Onboarding utilizaremos los siguientes patrones:
    - **Walkthroughs**
    - **Next Steps**
    - **Calls to Action**
    - **Modals**


![Método UX](img/mockup.png)  3.d Mockup
----

En los prototipos se han mejorado los defectos detectados tras la realización  de los wireframes (nombre de las secciones, colocación de los elementos dentro de la página web, etc.). Además, se ha hecho uso de los colores y fuentes de texto previamente seleccionadas, así como de los distintos patrones de diseño para la realización del prototipo de nuestra página web.

Para ver los prototipos, pulse [aquí](P3/Layout/).

Se puede simular el funcionanimento de la web en el siguiente [enlace](https://xd.adobe.com/view/09f4a008-eef8-4fb1-81f1-5673beacad53-5ca7/).


![Método UX](img/caseStudy.png) 3.e ¿My UX-Case Study?
-----

Mediante la realización de este proyecto, hemos aprendido sobre la importancia que tienen las opiniones e inquietudes de los usuarios en el desarrollo de una aplicación web y lo complicado que es ponerse en la piel de éstos. Las entrevistas a estos usuarios, así como las distintas herramientas que hemos utilizado en el desarrollo de estas tres prácticas (como, por ejemplo, la malla receptora de información o la matriz de usuarios/tareas) nos han permitido ir diseñando una aplicación cada vez más completa en lugar de lanzarnos directamente a la implementación de dicha aplicación.

Además, hemos profundizado en las diversas técnicas que se utilizan en la actualidad para llevar a cabo un buen y correcto diseño de una aplicación web.



## Paso 4. Evaluación 


![Método UX](img/ABtesting.png) 4.a Caso asignado
----

Se ha asignado el proyecto ViajesP&P, disponible en el siguiente [enlace](https://github.com/Pedropadilla26/DIU21). ViajesP&P es una aplicación, para dispositivos móviles, de búsqueda y reserva de alojamiento de alquiler turístico con información local de la ciudad del alojamiento. También permite subir un alojamiento turístico a la aplicación.

Se ha comparado esta aplicación con la nuestra, GranadaTour, una web para de rutas turísticas por la ciudad de Granada.



![Método UX](img/usability-testing.png) 4.b User Testing
----

Se han seleccionado 4 personas para realizar la evaluación de usabilidad de ambos proyectos. Las personas #1 y #2 han evaluado GranadaTour, mientras que las personas #3 y #4 lo han hecho con [ViajesP&P](https://github.com/Pedropadilla26/DIU21). Las personas son las siguientes:

  - Un joven estudiante de 19 años, apasionado del senderismo y las actividades al aire libre y un avanzado conocimiento con aplicaciones web.
  - Una administrativa de 50 años que necesita hacer un viaje de negocios y con experiencia intermedia en aplicaciones.
  - Una jubilada de 73 años con poca experiencia en el uso de aplicaciones web a la que le gustaría irse de turismo.
  - Un pintor de 31 años que presenta una minusvalía, al que le gustaría ir de viaje para aprender idiomas.

| #id. usuario | Sexo/edad   | Ocupación      | Rol               | Experiencia internet | Plataforma | TestA/B |
|--------------|-------------|----------------|-------------------|----------------------|------------|---------|
|            1 | Hombre / 19 | Estudiante     | Senderismo        | Avanzada             | Web        | A       |
|            2 | Mujer / 50  | Administrativa | Viaje de negocios | Intermedia           | Web        | A       |
|            3 | Mujer / 73  | Jubilada       | Turismo           | Baja                 | App        | B       |
|            4 | Hombre / 31 | Pintor         | Idiomas           | Intermedia           | App        | B       |


![Método UX](img/Survey.png). 4.c Cuestionario SUS
----

### Cuestionario SUS
|    | PREGUNTAS                                                                                |  1  |  2  |  3  |  4  |
|----|------------------------------------------------------------------------------------------|:---:|:---:|:---:|:---:|
|  1 | Creo que me gustará visitar con frecuencia este website                                  |  3  |  5  |  4  |  2  |
|  2 | Encontré el website innecesariamente complejo                                            |  2  |  2  |  2  |  3  |
|  3 | Pensé que era fácil utilizar este website                                                |  4  |  4  |  4  |  3  |
|  4 | Creo que necesitaría del apoyo de un experto para recorrer el website                    |  1  |  1  |  2  |  3  |
|  5 | Encontré las funciones del website bastante bien integradas                              |  4  |  4  |  4  |  4  |
|  6 | Pensé que había demasiada inconsistencia en el website                                   |  2  |  1  |  1  |  1  |
|  7 | Imagino que la mayoría de las personas aprenderían muy rápidamente a utilizar el website |  3  |  3  |  4  |  3  |
|  8 | Encontré el website muy grande al recorrerlo                                             |  1  |  2  |  2  |  1  | 
|  9 | Me sentí muy confiado en el manejo del website                                           |  4  |  4  |  4  |  3  |
| 10 | Necesito aprender muchas cosas antes de manejarme en el website                          |  1  |  1  |  3  |  2  |
|    |                                                             Valoración final (SUS Score) | 77.5| 82.5| 75  | 62.5|



![Método UX](img/usability-report.png) 4.d Usability Report
----

El informe de usabilidad se puede consultar en el siguiente [enlace](P4/P4_UsabReport_ViajesP&P_doneby_DIU3_BUHOS.pdf).

Los usuarios que han hecho uso de esta aplicación concuerdan en la relativa sencillez en la navegación de ésta, aunque se podrían mejorar algunos aspectos del diseño. Entre lo más destacable, las opciones de accesibilidad (modo daltónico y modo de texto hablado) deberían ir en un menú principal y no en una sección dentro del perfil, ya que podría pasar desapercibido por algunos usuarios. Además, ofrecer más claridad de lo que hace cada icono de la aplicación como, por ejemplo, el engranaje que lleva a la configuración del perfil, ya que algunos usuarios (sobre todo más mayores), podrían no entender la función que lleva a cabo dicho icono.

En cuanto a las funcionalidades, se podría mejorar añadiendo la ubicación del alojamiento mediante la integración de un mapa (por ejemplo, Google Maps) u ofrecer sugerencias de lugares cercanos que se pueden visitar además de las recomendaciones de restaurantes, así como permitir utilizar la aplicación sin tener que registrarse (para ver las ofertas disponibles). Además, ya que puede ser una aplicación un tanto innovadora respecto al resto de aplicaciones dirigidas a reservas de hoteles, su uso puede causar cierta confusión y se recomendaría añadir un tutorial (onboarding) para la aplicación.

En general, la aplicación presenta una usabilidad aceptable, aunque habría que mejorar algunos aspectos del diseño para que pueda ser utilizado por todo tipo de usuarios de una forma cómoda.



## Conclusión final / Valoración de las prácticas

En general, mediante la realización de las prácticas de esta asignatura hemos aprendido la metodología para diseñar una aplciación web y la importancia que tienen los usuarios a la hora de su realización, tanto de sus opiniones como de los problemas que puedan surgir durante el uso de una aplicación. Además, hemos conocido herramientas que nos han ayudado a desarrollar este proyecto y que son ampliamente utilizadas en la actualidad.

