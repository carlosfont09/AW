# AW
## ESTRUCTURA MÍNIMA DE UNA WEB
```html
<!DOCTYPE>
<html>
<head>
	<title></title>
</head>
<body>
</body>
</html>
```
## EXPLICA LAS 3 FORMAS DE USAR EL CSS EN HTML
>## CSS interno: 
### El CSS se añade directamente en la cabecera HTML del documento. 
### EJEMPLO
```html
<!DOCTYPE html>
<html>
<head>
    <title>Título de la página</title>
    <style type="text/css">
        div {
            background:#FFFFFF;
        }
    </style>
</head>
```
>## CSS externo:
### El CSS se añade en la cabecera del HTML, en el bloque <head></head>, de esta forma, los navegadores sabrán que deben aplicar los estilos de este archivo (index.css) al documento HTML actual.
### EJEMPLO
```html
<link rel="stylesheet" type="text/css" href="index.css" />
```
>## CSS inline:
### Aplicar el CSS en las mismas etiquetas con el atributo Style.
### EJEMPLO
```html
<p>¡Hola <span style="color:#FF0000">amigo lector</span>!</p>
```
## CREA UNA LISTA SIN ORDENAR 5 INGREDIENTES DE UNA RECETA DE COCINA
```html
<!DOCTYPE>
<html>
<head>
	<title></title>
</head>
<body>
<ul>
	<li> Peregil </li>
	<li> Limón </li>
	<li> Leche </li>
	<li> 2 Huevos </li>
	<li> Media cucharadita de Sal </li>
</ul>	
</body>
</html>
```
## COMO INTRODUCIR JAVASCRIPT EN HTML
>### Insertando una etiqueta de <script></script> en el head o en el body.
```html
<!DOCTYPE>
<html>
<head>
	<title></title>
	<script> ESTO ES JAVASCRIPT </script>
	
</head>
<body>
	<script> ESTO ES JAVASCRIPT </script>
</body>
</html>
```
## DIFERENCIA ENTRE CLASE E ID
>## CLASE
```html
Una clase es una serie de estilos definidos que se pueden usar muchas veces en cualquier etiqueta HTML.
```
>## ID
```html
La Id es para un elemento único.
```
## CÓDIGO PARA HACER UN ENLACE A OTRA PÁGINA Y QUE ESTA SE ABRA EN UNA NUEVA VENTANA
```html
<!DOCTYPE>
<html>
<head>
	<title></title>
</head>
<body>
	<a href="pagina.html" target="_blank">Título del enlace</a>
</body>
</html>
```
## LAS PSEUDOCLASES
>### Constan de una clave precedida de dos puntos (:) que añadiremos al final del selector para indicar que daremos un estilo a los elementos seleccionados solo cuando estos se encuentren dentro del selector.
>## EJEMPLOS
```html
:active , :any, :checked, :default, :dir(), :disabled
```
## MODELOS DE CAJA CSS
```html
>### Contenido (content): se trata del contenido HTML del elemento (las palabras de un párrafo, una imagen, el texto de una lista de elementos, etc.)
```
```html
>### Relleno (padding): espacio libre opcional existente entre el contenido y el borde.
```
```html
>### Borde (border): línea que encierra completamente el contenido y su relleno.
```
```html
>### Imagen de fondo (background image): imagen que se muestra por detrás del contenido y el espacio de relleno.
```
```html
>### Color de fondo (background color): color que se muestra por detrás del contenido y el espacio de relleno.
```
```html
>### Margen (margin): separación opcional existente entre la caja y el resto de cajas adyacentes.
```
