# Organización Semanal - Cristo Vive

Este proyecto es una plantilla HTML para organizar la programación semanal de un evento en la iglesia Cristo Vive. Proporciona una tabla editable donde se pueden ingresar las responsabilidades de los líderes para cada día de la semana.

## Funciones
Selección de mes actual
La selección del mes actual se realiza en la línea 81 del código JavaScript:

javascript
Copy code
var today = new Date();
var todayElement = document.getElementById('today');
todayElement.innerText = today.toLocaleDateString();
Esta parte del código crea un objeto Date para obtener la fecha actual. Luego, se selecciona el elemento HTML con el id today y se establece su contenido como la fecha actual en formato de cadena mediante el método toLocaleDateString().

Edición de celdas
La edición de celdas se implementa en las líneas 34-62 del código JavaScript. Aquí se define la lógica para abrir el cuadro de diálogo modal al hacer clic en una celda, guardar los datos ingresados y actualizar el contenido de la celda seleccionada.

Impresión de la organización semanal
La funcionalidad de impresión se encuentra en las líneas 66-79 del código JavaScript. Al hacer clic en el botón "Imprimir Organización Semanal", se muestra una marca de agua y se invoca la función window.print() para abrir la ventana de impresión del navegador.

Fecha del archivo generado
La fecha del archivo generado se establece en la línea 10 del código JavaScript:

javascript
Copy code
var today = new Date();
var todayElement = document.getElementById('today');
todayElement.innerText = today.toLocaleDateString();
Aquí se utiliza el mismo código que se explicó anteriormente para obtener la fecha actual y mostrarla en el elemento HTML con el id today en el pie de página.

Estas son las principales funciones y características implementadas en tu código HTML. Espero que esta explicación sea clara y te ayude a comprender mejor el funcionamiento de tu proyecto.

### Selección de mes actual

En el título de la página se muestra el mes actual. Esto se logra mediante JavaScript. El código obtiene el mes actual y lo muestra en un elemento HTML utilizando un array de nombres de mes predefinidos.

### Edición de celdas

Las celdas de la tabla son editables al hacer clic en ellas. Al hacer clic en una celda, se abre un cuadro de diálogo modal que permite ingresar los datos correspondientes. Al guardar los datos, se actualiza el contenido de la celda seleccionada.

### Impresión de la organización semanal

Se proporciona un botón "Imprimir Organización Semanal" que permite imprimir la tabla de la organización semanal. Al hacer clic en el botón, se muestra una marca de agua y se abre la ventana de impresión del navegador.

### Fecha del archivo generado

En el pie de página se muestra la fecha en que se generó el archivo. Esto se obtiene mediante JavaScript y se muestra en un elemento HTML.

## Uso

Simplemente abre el archivo `index.html` en tu navegador web y podrás ver la plantilla de organización semanal. Puedes hacer clic en las celdas para editar su contenido y utilizar el botón de impresión para obtener una copia impresa.

## Personalización

Puedes personalizar la plantilla según tus necesidades. Puedes modificar el título, los nombres de los días de la semana, agregar más filas o columnas a la tabla, y ajustar el diseño utilizando CSS.

## Tecnologías utilizadas

- HTML
- CSS
- JavaScript
- Materialize CSS (biblioteca CSS para estilos y componentes)

¡Disfruta utilizando la plantilla de organización semanal para tu evento en la iglesia Cristo Vive!

Todos los derechos reservados por JAIRNAY & Echthigern.


