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
>### Insertando una etiqueta de <script></script> en el head.
```html
<!DOCTYPE>
<html>
<head>
	<title></title>
	<script></script>
	
</head>
<body>
</body>
</html>
