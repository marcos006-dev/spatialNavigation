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

###Configuración
Si se desea cambiar el borde del recuadro, el color de la letra o el fondo del elemento en el momento que adquiera el foco.
```
*:focus {
  outline: 3px solid #428bca !important;
  background: yellow !important;
  color: red !important;
}
```