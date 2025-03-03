# mi-primera-pagina
Hola esta es mi primera pagina en HTML, CSS y JavaScript
Taller Introducción Aplicaciones Web 
 
Objetivos del Taller 
 
●	Introducir los conceptos básicos de HTML, CSS y JavaScript de manera accesible. 
●	Ayudar a los estudiantes a familiarizarse con las herramientas y tecnologías web fundamentales. 
●	Desarrollar una comprensión básica de cómo crear y estilizar una página web simple, fomentando el aprendizaje práctico a través de ejercicios guiados. 
Estructura del Taller 
 
El taller está dividido en sesiones teóricas y prácticas, cada una enfocada en aspectos específicos de HTML, CSS y JavaScript. Adicionalmente se debe entregar las solución de los ejercicios prácticos del taller en un repositorio, siguiendo los pasos descritos en la guía. 
Parte Teórica 
1.	¿Qué es HTML y cuál es su función en la web? 
R/ Es el lenguaje estándar utilizado para crear y estructurar páginas web. No es un lenguaje de programación, sino un lenguaje de marcado que define la estructura y el contenido de una página web mediante etiquetas. Define los diferentes elementos de una página, como encabezados, párrafos, listas, tablas, imágenes y enlaces.

2.	¿Qué es una etiqueta HTML y menciona las etiquetas más comunes? 
R/ Una etiqueta HTML es un elemento fundamental del lenguaje HTML que se usa para estructurar y definir el contenido de una página web. Las etiquetas le indican al navegador cómo debe mostrar el contenido, ya sea un texto, una imagen, un enlace o cualquier otro elemento. Las etiquetas generalmente están formadas por una etiqueta de apertura y una etiqueta de cierre, aunque algunas son auto contenidas.

Etiquetas comunes de HTML:

Estructura básica:
<!DOCTYPE html> → Define el tipo de documento.
<html> → Contenedor principal de la página.
<head> → Contiene metadatos y enlaces externos (como hojas de estilo o scripts).
<body> → Contiene todo el contenido visible de la página.
Texto:
<h1> a <h6> → Encabezados (de mayor a menor jerarquía).
<p> → Párrafo.
<br> → Salto de línea.
<strong> → Texto en negrita.
<em> → Texto en cursiva.
<hr> → Línea horizontal divisoria.
 Enlaces e imágenes:
<a href="URL"> → Crea hipervínculos.
<img src="ruta" alt="descripción"> → Inserta imágenes.
Listas:
<ul> → Lista desordenada (con viñetas).
<ol> → Lista ordenada (con números).
<li> → Elemento de lista.
 Tablas:
<table> → Crea una tabla.
<tr> → Fila de la tabla.
<td> → Celda de la tabla.
<th> → Celda de encabezado.
 Formularios:
<form> → Define un formulario.
<input> → Campo de entrada.
<label> → Etiqueta para los campos.
<textarea> → Área de texto grande.
<button> → Botón.
<select> y <option> → Listas desplegables.

3.	¿Que es un atributo de una etiqueta HTML y menciona los más comunes? 
R/ Un atributo en HTML proporciona información adicional sobre una etiqueta y define ciertas propiedades o comportamientos de los elementos.
Los más comunes son:
id → Asigna un identificador único al elemento
class → Agrupa elementos bajo una misma clase para aplicar estilos o scripts
style → Aplica estilos CSS directamente en la etiqueta
title → Muestra un mensaje emergente al pasar el cursor sobre el elemento
href → Define la URL en los enlaces (<a>)
target → Indica cómo abrir el enlace (_blank para nueva pestaña)
src → Especifica la ruta de la imagen o recurso
alt → Texto alternativo si la imagen no carga (importante para accesibilidad)
width y height → Controlan el tamaño de imágenes o elementos
type → Define el tipo de entrada (texto, contraseña, botón, etc.)
      name → Asocia un nombre al campo (útil al enviar formularios)
placeholder → Muestra un texto de sugerencia dentro del campo
value → Define un valor predefinido en campos o botones
required → Hace que el campo sea obligatorio

4.	¿Qué es CSS y cómo se utiliza para el diseño web?  
R/ es un lenguaje utilizado para dar estilo y diseño a las páginas web creadas con HTML. CSS se encarga de su apariencia visual, como colores, tamaños, fuentes, márgenes y posiciones.

5.	¿Qué es una propiedad en CSS y menciona las propiedades más comunes? 
R/ una propiedad define una característica específica que se desea modificar de un elemento HTML, como el color, tamaño, borde, posición o espaciado. Cada propiedad tiene un valor que determina cómo se aplicará el estilo.
Más comunes: 
color → Cambia el color del texto
font-size → Define el tamaño de la fuente
font-family → Especifica la tipografía
text-align → Alinea el texto (left, center, right)
text-decoration → Agrega o quita subrayados o líneas.
font-weight → Ajusta el grosor del texto (normal, bold)
width y height → Controlan el ancho y alto
margin → Define el espacio externo alrededor del elemento
padding → Ajusta el espacio interno entre el contenido y el borde
border → Crea bordes alrededor del elemento
background-color → Cambia el color de fondo
background-image → Coloca una imagen de fondo
opacity → Ajusta la transparencia (de 0 a 1)
display → Controla cómo se muestra un elemento (block, inline, flex, grid)
position → Posiciona elementos (static, relative, absolute, fixed)
z-index → Controla la superposición de elementos
float → Permite alinear elementos a la izquierda o derecha
transition → Añade transiciones suaves entre estados

6.	¿Que es un selector en CSS y cuales tipos existen? 
R/ Un selector es el elemento que se utiliza para "seleccionar" o apuntar a uno o varios elementos HTML a los que se les aplicarán estilos específicos. Básicamente, el selector le dice al navegador qué elementos HTML deben recibir ciertos estilos.
Selectores básicos: 
•	Selector de etiqueta: Aplica estilos a todos los elementos de un tipo específico
p { color: blue; } /* Todos los párrafos serán azules */

•	Selector de clase: Se usa para aplicar estilos a elementos con una clase específica (usa .).
.destacado { font-weight: bold; } /* Elementos con clase "destacado" */
•	Selector de ID: Aplica estilos a un elemento con un ID único (usa #)
#titulo { font-size: 24px; } /* Elemento con id="titulo" */
•	Selector universal (*): Afecta a todos los elementos de la página
* { margin: 0; padding: 0; }
•	Selectores de grupo:
Permiten aplicar los mismos estilos a varios elementos separados por comas.
h1, h2, p { color: gray; }
•	Selectores combinadores:
Descendiente ( ): Selecciona elementos dentro de otro elemento.
div p { color: red; } /* Todos los <p> dentro de <div> */
•	Selectores combinadores:
div p { color: red; } /* Todos los <p> dentro de <div> */
•	Hermano adyacente (+): Selecciona el primer elemento hermano inmediato
h1 + p { color: green; }
•	Seleccionan elementos según sus atributos y valores.
a[href^="https"] { color: green; } /* Enlaces que empiezan con "https" */

Selectores pseudo-clase (:):
•	Se usan para definir estados especiales de los elementos
a:hover { color: red; } /* Cuando el cursor pasa sobre el enlace */
li:first-child { font-weight: bold; } /* Primer hijo de una lista */

Selectores pseudo-elemento (::):
•	Permiten aplicar estilos a partes específicas de un elemento.
p::first-letter { font-size: 2em; } /* Primera letra de cada párrafo */
p::before { content: "✔ "; } /* Añade un símbolo antes del contenido */


7.	¿Qué es JavaScript y cómo añade la interactividad a las páginas web? 
R/ Es un lenguaje de programación interpretado y orientado a objetos que se utiliza principalmente para crear páginas web interactivas. Es uno de los pilares fundamentales del desarrollo web junto con HTML.
JavaScript se ejecuta directamente en el navegador del usuario, permitiendo que la página responda a acciones sin necesidad de recargarla. Aquí te explico cómo:
1.	Manipulación del DOM (Document Object Model):
JavaScript puede acceder y modificar el contenido, estructura y estilo de los elementos HTML.
2.	Eventos del usuario:
Puedes programar reacciones a eventos como clics, movimientos del mouse, teclas presionadas, etc.
3.	Validación de formularios:
JavaScript puede verificar que los datos introducidos por el usuario sean correctos antes de enviarlos.
4.	Creación de animaciones y efectos:
Sin necesidad de librerías externas, puedes crear animaciones simples.

5.	Actualización de contenido sin recargar la página (AJAX):
JavaScript permite realizar peticiones al servidor y actualizar partes de la página de forma dinámica (ej. redes sociales que cargan nuevos posts sin recargar).
6.	Interacción con APIs externas:
Puedes conectar tu página con servicios como mapas, clima o redes sociales usando APIs.

8.	¿Cuáles son los tipos de datos primitivos en Javascript? 
R/ Boolean: Valores booleanos, como true y false 
Number: Valores numéricos, como 42 o 3.14159 
BigInt: Valores enteros con precisión arbitraria, como 9007199254740992n 
String: Secuencias de caracteres que representan un valor de texto, como "Hola" 
Symbol: Un tipo de dato cuyas instancias son únicas e inmutables 
Null: Una palabra clave especial que denota un valor nulo 
Undefined: Una propiedad de alto nivel cuyo valor no está definido 
Los tipos primitivos son los datos originales de un lenguaje de programación. Son datos que no son un objeto y no tienen métodos. 

9.	¿Cómo funcionan las estructuras de control de flujo como if, else, switch y bucles en Javascript? 
R/ Las estructuras de control de flujo en JavaScript son instrucciones que permiten evaluar condiciones y modificar el flujo de ejecución de un programa. 
Estructuras condicionales 
If: Ejecuta una instrucción si una condición lógica es verdadera 
Else: Ejecuta una instrucción si una condición lógica es falsa 
Else if: Evalúa varias condiciones y ejecuta el bloque de código correspondiente a la primera condición que sea verdadera 
Switch: Compara una expresión con varios valores posibles y ejecuta el bloque de código correspondiente al valor que coincida 

10.	¿Por qué es importante usar nombres significativos para variables y métodos? 
R/Es importante usar nombres significativos para variables y métodos porque facilita la lectura, el mantenimiento y la actualización del código. 

11.	¿Qué es una variable de entorno y por qué son importantes para Javascript o la programación en general? 
R/ Las variables de entorno son valores que se usan para configurar programas y acceder a información relevante. Son importantes para la programación en general porque permiten personalizar el comportamiento de las aplicaciones sin necesidad de modificar el código fuente. 

12.	¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas? 
R/Las herramientas para desarrolladores de Chrome son un conjunto de herramientas que permiten analizar y editar páginas web. Están integradas en el navegador Google Chrome. 
Para acceder a las herramientas para desarrolladores de Chrome, puedes: 
Hacer clic con el botón secundario en una página y seleccionar "Inspeccionar elemento" 
Seleccionar Ver > Desarrollador > Herramientas para desarrolladores 
Utilizar la combinación de teclas "alt+comando+i"


13.	¿Qué se puede hacer en el panel "Elements" de las herramientas de desarrollo? 
R/ Elements. Permite realizar modificaciones sobre el código HTML (panel izquierdo) y CSS (pestaña Styles en el panel derecho) de nuestra página. Al igual que sucede en Console, estos cambios se visualizan al instante. Existe también otra pestaña más denominada Event Listeners donde se muestran todos los eventos accionados, aunque seguramente no necesitaremos hacer uso de ella (casos excepcionales).

14.	¿Cómo se utiliza el panel "Console" de las herramientas de desarrollo y para qué es 
útil? 
R/El panel "Console" de las herramientas de desarrollo se utiliza para ver cómo funcionan los scripts en una página web. También se puede usar para depurar errores, optimizar el rendimiento y probar la compatibilidad. 
Para qué es útil 
•	Ver el funcionamiento de los scripts en una página web 
•	Depurar errores 
•	Optimizar el rendimiento 
•	Probar la compatibilidad 
•	Experimentar con código 
•	Acceder a información del servidor 
•	Cómo abrir la consola 
•	En Chrome, presiona Control + Mayúsculas + J o Comando + Opción + J (Mac) 
Desde el menú de comandos, comienza a escribir Console y ejecuta el comando Show Console.

15.	¿Qué información se puede obtener del panel "Network" y por qué es importante? 
R/Peticiones HTTP/HTTPS:
Muestra todas las solicitudes realizadas al servidor, incluyendo archivos HTML, CSS, JavaScript, imágenes, videos y datos de API.
Detalles de cada solicitud:
Al seleccionar una petición, puedes ver:
•	URL del recurso solicitado.
•	Método HTTP (GET, POST, PUT, DELETE, etc.).
•	Códigos de estado HTTP (200 OK, 404 Not Found, 500 Internal Server Error, etc.).
•	Cabeceras (Headers) de solicitud y respuesta.
•	Cuerpo de la respuesta (Response), especialmente útil para APIs.
•	Parámetros enviados en la URL o en el cuerpo de la solicitud (Payload).
Tiempos de carga (Performance):
Visualiza cuánto tarda cada recurso en cargarse y detecta cuellos de botella.
•	DNS Lookup
•	Tiempo de espera (TTFB - Time To First Byte)
•	Transferencia de datos
•	Tiempo total de carga
Tamaño de los archivos:
Muestra el peso de cada recurso y si está comprimido (ej. usando gzip o brotli).
Errores de red:
Detecta errores de carga, fallos en peticiones API o problemas de CORS (Cross-Origin Resource Sharing).
Filtrado y análisis de tráfico:
Puedes filtrar por tipo de recurso (JS, XHR, CSS, Img, etc.) o por estado para encontrar fallos más rápido.
Monitoreo de llamadas AJAX/Fetch:
Es útil para ver datos devueltos por APIs sin tener que inspeccionar el código.

