# Spatial Navigation

## Instalación

Descargue el repositorio e importe los siguientes archivos.

```html
<!DOCTYPE html>
<html>
    <head>
        <mate charest="utf-8" />
        <title>Título Página</title>
	<!-- CSS file import Spatial Navigation -->
	<link rel="stylesheet" type="text/css" href="src/spatialNavigation.css">
    </head>
    <body>
	
        <h1>Hola Mundo!</h1>
	
	<a href="#">Enlace 1</a>
	<a href="#">Enlace 2</a>
	<a href="#">Enlace 3</a>
	<a href="#">Enlace 4</a>
		
	<!-- Polyfill file import Spatial Navigation -->
	<script src="polyfill/spatialNavigationPolyfill.js"></script>
		
	<!-- JS file import Spatial Navigation -->
	<script src="src/spatialNavigation.js"></script>
    </body>
</html>
```

## Configuración

~~~
spatialNavigation.css
~~~

> Para cambiar el borde del recuadro modificar la propiedad outline.
> 
> Para cambiar el color de la letra modificar la propiedad color.
> 
> Para modificar el fondo del elemento modificar la propiedad background.

```
*:focus {
  outline: 3px solid #428bca !important;
  background: yellow !important;
  color: red !important;
}
```

## Ejemplo:

[Spatial Navigation](https://marcos006-dev.github.io/spatialNavigation/)
