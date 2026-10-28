# Sala 5 · El sótano (HTML)

**Compañero/a:** Francisco. User: Francisco-390
**Compañero/a:** Alberto Florido. User: albertofloram05
**Compañero/a:** David Buzón Nogales. User: David89787

## La historia
3-4 líneas.

## La pista
La pista esta al pasar el raton por el pergamino, por las palabras resaltadas de rojo que es 3-5-7, tambien se puede encontrar en negrita leyendo el digrama, pero este es mas dificil de entender


## Diario de investigación
Reto 1 y 2: hemos completado el archivo index.html dentro de VSCode sustituyendo lo que está dentro del <'main'>. Hemos utilizado las etiquetas del ejercicio y hemos mantenido el texto de la actividad.

Reto 3: En index.html he añadido un menú de navegación con nav y una lista de enlaces dentro del header. Los tres primeros enlaces saltan a las secciones de la misma página (#historia, #lista y #pergamino) usando el id de cada una, y el último abre pergamino.html a pantalla completa. También he creado un footer con los créditos y un enlace a Pixabay que se abre en otra pestaña con target="_blank" y rel="noopener noreferrer" para que sea seguro.

Reto 4 y 5: hemos completado la sección cumpliendo con las espectativas del ejercicio. Hemos incluido la lista ordenada y dentro de ella la desordenada. También hemos puesto el <'strong'> para dar énfasis y probado el código en pruebas.html. También se han añadido las imagenes con las descripciones correspondientes y se han cumplido los objetivos de la tarea

Reto 6: He creado pergamino.html, una segunda página con el mismo esqueleto que index.html, enlazada a css/terror.css y con class="pergamino" en el <'body'> para que parezca papel viejo. Dentro puse el diario con las cifras 3, 1 y 7 en <'strong'>. Después la incrusté en index.html con un <'iframe'> que lleva title para que un lector de pantalla sepa qué contiene.

Reto 7: He terminado el pergamino.html con pistas para poder encontrar la contraseña de forma original y divertida, tambien he contestado todo lo que se me preguntaba y corregido todos los fallos y cosas que he encontrado por la pagina

Reto 8: He arreglado los problemas de compilación de la página web index.html y pergamino.html. Luego, he hecho una captura donde se valida el archivo en el validador w3c y he guardado dicha captura en la carpeta docs.

### Reto 1 y 2 · La voz del narrador
- **Pregunta:** ¿strong o b para la palabra que asusta?
- **Fuente:** MDN - <'strong'> y MDN - <'b'>.
- **Lo que dice (con mis palabras):** La etiqueta <'strong'> indica que un texto es importante, mientras que <'b'> sirve para llamar la atención sobre un texto sin indicar que sea más importante.
- **Prueba en pruebas.html:** Probé las etiquetas <'strong'> y <'b'> en dos palabras. Vi que las dos aparecen en negrita, pero tienen significados diferentes.
- **Decisión en mi sala:** Uso <'strong'> en «vigilante nocturno» porque quiero destacar que es una información importante para la historia.
- **Pista de nivel usada:** Ninguna.

### Reto 3 · El mapa del túnel (menú y footer)

- **Pregunta:** ¿Cómo salto a una parte de la misma página? ¿Qué riesgo tiene abrir un enlace en otra pestaña y cómo se evita?
- **Fuente:** MDN · `<a>` (https://developer.mozilla.org/es/docs/Web/HTML/Element/a) y MDN · `<nav>` (https://developer.mozilla.org/es/docs/Web/HTML/Element/nav)
- **Lo que dice (con mis palabras):** Un enlace con `href="#algo"` salta al elemento que tenga `id="algo"`. Para ir a otra página se pone su nombre en el `href`. Con `target="_blank"` el enlace se abre en otra pestaña y, para que esa pestaña no pueda controlar la mía, se añade `rel="noopener noreferrer"`. `<nav>` agrupa el menú y `<footer>` el pie de página.
- **Prueba en pruebas.html:** Cambié `#historia` por `#historiaXX` y el enlace dejó de llevarme a la sección. Al corregirlo volvió a funcionar.
- **Decisión en mi sala:** Uso `<nav>` con una lista de enlaces en el header y un `<footer>` con el enlace a Pixabay abierto en otra pestaña de forma segura.
- **Pista de nivel usada:** ninguna

### Reto 4 · las normas para sobrevivir
- **Pregunta:** ¿Cuándo debe ser una lista ordenada y cuándo no? ¿En qué punto exacto se escribe la lista de dentro para que el validador no dé error?
- **Fuente:** https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements/ol
- **Lo que dice (con mis palabras):** La lista ordenada (ol) sirve para describir instrucciones que se tienen que hacer en un orden determinado. Y la lista desordenada (ul) se usa en listas que simplemente contienen objetos o mensajes los cuales no dependen de su cronología, como la lista de la compra.
- **Prueba en pruebas.html:** He probado toda la sección y he visto en el validador que sí compilaba, pero hay una advertencia de que el encabezado de nivel 2 es recomendable incluirlo tras haber incluido previamente un encabezado de nivel 1.
- **Decisión en mi sala:** uso <'strong'> en "tres páginas marcadas" porque es una frase que debe tener énfasis y es muy importante.
- **Pista de nivel usada:** ninguna.

### Reto 5 · los retratos
- **Pregunta:** ¿Para qué sirve el texto alternativo si la imagen ya se ve ¿Quién lo usa? ¿Qué pasa si la ruta de la imagen está mal? ¿Qué aporta agrupar la imagen y su pie de foto frente a poner un párrafo debajo? ¿Por qué el ancho se escribe sin unidades?
- **Fuente:** https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements/img
- **Lo que dice (con mis palabras):** se pone src y luego el nombre del archivo con su extensión. Si la extensión es equivocada, no se mostrará la imagen, y en su lugar se mostrará la descripción que está puesta en 'alt'.
- **Prueba en pruebas.html:** he probado en pruebas.html las imágenes y no había ningún problema de compilación.
- **Decisión en mi sala:** uso 'alt' en "img src" por si no se ve la imagen, que haya una descripción en la que pueda describirse lo que hay en la imagen.
- **Pista de nivel usada:** ninguna

### Reto 6 (parte 1) · El documento secreto
- **Pregunta:** Qué etiqueta muestra una página dentro de otra?
¿Por qué es obligatorio darle un nombre accesible? ¿Qué oye una persona que usa lector de pantalla si no lo tiene? ¿Qué atributos controlan su tamaño?
- **Fuente:** MDN · atributos globales (https://developer.mozilla.org/es/docs/Web/HTML/Global_attributes)
- **Lo que dice (con mis palabras):** Un atributo global es uno que se puede poner en cualquier etiqueta. `class` sirve para darle un nombre a un elemento y que la hoja de estilos le aplique un aspecto concreto.
- **Prueba en pruebas.html:** Quité `class="pergamino"` del `<body>` y la página perdió el fondo de papel y las letras marrones. Al ponerlo otra vez volvió.
- **Decisión en mi sala:** Copié el esqueleto del paso 1 y cambié el `<title>`, la clase del body y el contenido. Uso `<strong>` en "3", "1" y "7" porque son lo más importante del diario, `<em>` en "sin linterna" para dar énfasis y `<small>` en la última frase porque es una nota aclaratoria.
- **Pista de nivel usada:** ninguna

### Reto 6 (parte 2) · incrustar el pergamino
- **Pregunta:** Qué etiqueta muestra una página dentro de otra?
¿Por qué es obligatorio darle un nombre accesible? ¿Qué oye una persona que usa lector de pantalla si no lo tiene? ¿Qué atributos controlan su tamaño?
- **Fuente:** MDN · `<iframe>` (https://developer.mozilla.org/es/docs/Web/HTML/Element/iframe)
- **Lo que dice (con mis palabras):** `<iframe>` muestra otra página dentro de la actual. Hay que ponerle `title` porque el lector de pantalla lo usa para decir qué hay en el marco; sin él, la persona no sabe qué es. `width` y `height` controlan el tamaño.
- **Prueba en pruebas.html:** Cambié `pergamino.html` por `pergaminoXX.html` en el `src` y el marco salió vacío o con error. Al corregirlo volvió a verse el pergamino.
- **Decisión en mi sala:** Uso `<iframe src="pergamino.html">` con `title="El diario del vigilante"` y tamaño 600x400, dentro de una sección con id `pergamino` para poder enlazarla desde el menú.
- **Pista de nivel usada:** ninguna

### Reto 7 · La pista
- **Pregunta:** ¿se ve a simple vista? ¿un visitante la encuentra en 1 minuto? ¿encaja con lo que espera el programa de 2.º?
- **Fuente:** https://developer.mozilla.org/es/docs/Web/HTML/Element/details y <'abbr'> https://developer.mozilla.org/es/docs/Web/HTML/Reference/Elements/abbr
- **Lo que dice (con mis palabras):** He usado <'p'><'small'><'abbr'><'/abbr'><'/small'><'/p'> ya que asi es mas facil esconder el codigo de una fomra bonita y original que no todo el mundo podra encontrar.
- **Prueba en pruebas.html:** Probe dos opciones para esconder el codigo de la caja fuerte
- **Decisión en mi sala:** Uso <'abbr'> para en el codigo de la caja fuerte porque asi al pasar el raton por encima aparece.
- **Pista de nivel usada:** Ninguna

### Reto 8 · Valida, README y entrega
- **Pregunta:** Para cada error que te dé el validador: ¿qué significa y por qué ocurrió? ¿Qué cambiaste para corregirlo?
- **Fuente:** https://validator.w3.org/
- **Lo que dice (con mis palabras):** el validador sirve para detectar errores de compilación en un archivo html. Una vez que arreglas los errores, el validador te dice que el archivo es capaz de compilar porque no detecta ningún error.
- **Prueba en pruebas.html:** se ha podido comprobar que primero daba algún error, pero por suerte no ha compilado
- **Decisión en mi sala:** uso el validador en "index.html" porque así puedo comprobar si es capaz de compilar.
- **Pista de nivel usada:** ninguna

## Captura
![Sala 5](docs/validado.png)

## Créditos
sotano.png --> pixabay.com
caja.png --> pixabay.com
