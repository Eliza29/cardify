# Cardify

## Descripción:
Cardify es un plugin de jQuery que busca todas las
imágenes y las reemplaza por un nuevo elemento `<figure>` el cual contiene la imagen (`<img>`) y además para que este sea más dinámico al colocar el puntero sobre el elmento se muestra un `<figcaption>`con el texto del atributo `alt` de la imagen.

## Herramientas utilizadas:
* ECMAScript 6
* CSS 
* HTML 5
* Bootstrap

## Instalación

### Global (navegador)

```html

// insertamos el link del plugin en nuestro html. 
<script src="http://code.jquery.com/jquery-3.3.1.min.js"integrity="sha256-FgpCb/KJQlLNfOu91ta32o/NMZxltwRo8QtmkMRdAu8="crossorigin="anonymous"></script>
<script src="../src/index.js"></script>
<script src="../src/app.js"></script>
```

## Uso
```js
// imágenes a ser procesadas.
$('img').cardify();
```
## Ejemplo
```html

// imágenes que necesitan el plugin.
<div class="container">
    <img src="assets/images/front2.jpg" alt="front-end1">
    <img src="assets/images/frontend1.png" alt="front-end2">
    <img src="assets/images/great-frontend.png"alt="front-end3">
    <img src="assets/images/laptop.jpg" alt="laptop">
</div>
```
## Desarrolladoras:

* Elizabeth Segura
* Pamela Rojas