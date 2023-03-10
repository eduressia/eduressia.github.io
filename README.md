# eduressia.github.io
<br />
Argentina Programa 4.0 CV<br />
Proyecto Curriculum vitae para Argentina Programa 4.0 Etapa 1<br />
Si bien el curso es en español he optado por hacerlo en su totalidad en inglés para hacerlo mas profesional y legible para un programador (para mi al menos es abrumador leer código que está basado en inglés y leer comentarios en otro idioma).<br />
También se sugirió crear una hoja que "escriba toda la información que quiera incluir en el CV, para poder empezar a pensar en qué estructura se le dará al proyecto".<br />
Debido a que no me siento cómodo con esa iniciativa he optado en hacerlo a la inversa, primero hacer el programa y darle forma para luego hacer dicha hoja que sería esta misma.<br />
Muchos programadores caen en la trampa de ponerse a pensar como hacer "el dibujo" de su página web para luego empezar de cero una y otra vez.<br />
Por eso yo trabajo en el sentido contrario, primero creo funciones y/o clases que puedan ser adaptables a cualquier formato para al final dedicarle tiempo al formato definitivo que quiera yo o el cliente con la menor cantidad de modificaciones al código de JS.<br />
Sería algo asi como crear un "Framework" (si esa es la palabra correcta) o un CMS (Content Management System) como blogger o un phpBB (Forum Software)<br />
Es decir:<br />
1.- Crear una función que obtenga los datos aleatorios de una página externa (nombre, dirección, email, etc) a traves de una API<br />
2.- Almacenar esos datos en una base de datos (se creó un objeto y se lo guardó como Json en una sessión del navegador, localStorage)<br />
3.- Segmentar esos datos para crear e-mail, y redes sociales ficticias<br />
4.- Para demostrar esa "flexibilidad" se creó una función para refrescar esos datos y obtener nuevos datos aleatorios con el objetivo de que permita ver la cantidad de caracteres que se puedan necesitar.<br />
5.- Ya teniendo los datos almacenados y viendo que datos son los mas comunes se dio paso al "relleno" y al diseño.<br />
6.- Se buscó una plantilla acorde a lo solicitado, en este caso un Curriculum vitae.<br />
7.- Teniendo en cuenta que es un curso de programación y no de diseño gráfico se respetó el diseño de la plantilla pero teniendo en cuenta que se podrá modificar luego via backend (como se hace en la mayoría de los casos) por eso se mantuvo un diseño claro y consiso con mínimas agrupaciones como los tags div y ul que serían facilmente modificables e identificables por ejemplo con PHP.<br />
8.- Debido a la sugerencia del tutor se realizaron cambios perdiéndose en parte esa estructura y se agregaron los tags segment, aside, etc, creando un serio conflicto en el documento cuando se quiera modificar su aspecto en backend con distintas plantillas y estilos, ya de por sí crea conflicto al ser una página "dinámica", esos tags son mas bien para páginas estáticas anticuadas con forma de "árbol" que tenían una página html distinta para cada link en el menú, ademas para evitar conflictos de intereses se obvió el "footer" con los datos del desarrollador y también para no quitar protagonismo al supuesto titular del CV, o sea, la página está pensada para que otros presenten su CV, si el tipo es programador o diseñador web no va a querer que otro colega ponga su firma en su propio CV.<br />
9.- Luego se dio paso a la segmentación de dicho CV creando un menú que discrimine y ponga en "primer plano" con un click los segmentos mas importantes: experiencia laboral, educación y una página con detalles extendidos menos importantes como el código postal, etc.<br />
10.- Para ello se creó un botón estilo hamburguesa que sea siempre visible y alterne con una X al activarse el menú y lo pueda volver a ocultar a dicho menú.<br />
11.- Se agregó al menu un link que abre un "pop up" que simula un "log in" que al logearse el usuario podría editar el texto de todo o parte del documento pero para eso ya se necesitaría backend para "sanitizar" los formularios.<br />
12.- Si bien se podría haber creado una función (y estaba planeado hacerlo) que edite los campos anónimamente pareció innecesario hacer leer al tutor decenas de líneas de código ya que con el menú, el formulario de log in y la carga de datos aleatoria se demostraron las habilidades de modificar los tags, su contenido y su formato.<br />
13.- Como ya fue mencionado, se agregó un botón al pop up de log in para obtener nuevos datos (solo por diversión para utilizar la función existente).<br />
14.- También se pensó poner un "select" para alternar el idioma de los títulos del menú y los segmentos del documento pero se desechó la idea porque para eso sería ideal hacerlo en Backend con el soporte de plantillas ocultas y tal vez una base de datos (insisto, no vale la pena agregar decenas de líneas de código para demostrar que se aprendió lo ya demostrado menos cuando es algo que en el 99.99% de los casos se maneja en backend con o sin ayuda de Ajax).<br />
15.- Finalmente crear este archivo readme que detalle los pasos mas importantes en el desarrollo del proyecto al mejor estilo "copete" de una nota televisiva que describe la nota a continuación pero se graba al final de la nota.<br />
16.- Lo siento, soy técnico (electromecánico), primero junto las herramientas y recién después reviso la máquina XD.<br />
<br />
Visite el deployment del proyecto en <a href="https://eduressia.github.io/" target="_blank">https://eduressia.github.io/</a><br />