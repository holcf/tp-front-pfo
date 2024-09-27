Práctica Formativa 2
Mejora de contenido
• Incluyan una mayor descripción de sí mismos, de los servicios que ofrecen, etc. Por ejemplo, una sección Qué hago con varios bloques y una sección Sobre mí.
• Tomen ideas de otros portfolios y amplíen su contenido en general. Este porfolio será su carta de presentación al internet y será lo que vean los reclutadores a la hora de ver y examinar sus perfiles. Cuanto más profesional y completo, más chances de destacar.

Mejora de estilos

 • Uso de iconos: Usando font-awesome o la fuente que se prefiera. No hace falta saturar todo de íconos pero estaría bien tener un par, por ejemplo en el botón enviar del formulario, etc.
• Manejo de enlaces con pseudoclases: Se pueden eliminar sus estilos, pero deberían tratarse con a:link, a:visited, a:hover, a:active .
• Usar una lista para el nav : Usaremos dentro de nuestro contenedor nav una lista que mostraremos horizontalmente y que dejaremos a nuestro gusto, no se olviden usar list-style-type si quieren sacar los caracteres de lista.
• Mejorar el estilado de nuestra tabla: Esta deberá mostrar una personalización más allá del estilo por defecto. También deberán usar la siguiente pseudoclase para darle un estilo al fondo de cada fila:
/_ Filas pares _/
tr:nth-child(even) {}
/_ Filas impares _/
tr:nth-child(odd) {}
Ahora que van a incluír una descripción mayor en su web, la tabla simplemente puede listar las tecnologías
que manejan o que pueden llegar a manejar.
• Uso de z-index: Con un uso es suficiente, deben mostrar su conocimiento del z-index en donde ustedes consideren, como ubicar un texto encima de un contenedor.
• Uso de combinadores CSS: Usen en su código varios, combinador desdenciente: div p {} y combinador directo: div > p . De esta manera se podrán evitar usar en exceso ids y clases.
• Manejo de opacidad: Deben mostrar el uso de opacidad en algún elemento de su portafolio. Este puede usarse, por ejemplo, para oscurecer algún fondo y resaltar el texto.

Responsividad
Deberán hacer que su página sea responsiva y recolocar los elementos acorde al tamaño de la pantalla. Su proyecto debe llevar 4 tamaños máximos de pantalla.
/_ Tablet horizontal _/
@media (max-width: 1080px) { }
/_ Tablet vertical _/
@media (max-width: 768px) { }
/_ Mobil 1 _/
@media (max-width: 480px) { }
/_ Mobil 2 _/
@media (max-width: 375px) { }

Recordatorios
• Sean prolijos la estructura de su proyecto, un archivo index.html , otro archivo README.md , una carpeta css con su hoja de estilos css/styles.css y una carpeta assets con sus imagenes assets/img/miimagen.jpg .
• Es importante que sean estrictos y prolijos con los nombres de los ficheros, desde sus archivos html y css hasta sus imagenes.
• Comprueben que tienen bien las rutas, sepan navegar entre carpetas. ../ nos permite retroceder una carpeta atrás. Para avanzar podemos poner directamente el nombre de la carpeta o ./, por ejemplo desde index.html la ruta podría ser css/styles.css o ./css/styles.css . Recurran a la ayuda de navegación que les va tirando Visual Studio Code para encontrar los archivos. Recuerden que cuando
vayan a poner una ruta, fijense desde que carpeta están, si en la raíz o en una carpeta superior y naveguen desde ese lugar.
• Recuerden tener un código limpio, bien comentado y bien indentado. Debe ser limpio, claro y fácil de entender. Separen los distintos bloques de su CSS con caracteres bien distinguidos como por ejemplo:
/_///////////////// AJUSTES GENERALES//////////////////_/
/_********\_\_********Portada************\_\_\_\_************_/
• Incluyan en un archivo README.md donde hagan una pequeña descripción de su proyecto usen # para el título. Este se puede crear por defecto cuando se crea un nuevo repositorio en github.
• No es obligatorio, pero se valorará también incluír una imagen de muestra en nuestro README, este puede ser una captura de pantalla de nuestra web, por ejemplo, sample.png y se puede enlazar en nuestro README como <img src="assets/img/sample.png" alt="porfolio>"

Recursos
• En la web, los tiempos de carga son cruciales, recuerden no subir archivos muy pesados, idealmente menos de 500kb cada imagen. Pueden usar compresores de imagen o herramientas para recortar, comprimir y redimensionar como picresize.
• Documentación Markdown.
• Guía visual flexbox.
