# JavaScript
JavaScript (JS) es un lenguaje de programación utilizado para añadir interactividad a las páginas web. Junto con HTML y CSS, es una de las tres principales tecnologías para la producción de contenido en la Web. Fue creado en 1995 por Brendan Eich, con el fin de dar interactividad a las páginas web leídas con el navegador Netscape. En la actualidad, es utilizado por todos los [principales navegadores web](https://en.wikipedia.org/wiki/Usage_share_of_web_browsers) y en la mayoría de los sitios web.

## Principales características
* Se ejecuta en el cliente (i.e. navegador web).
* Es interpretado.
* Permite el uso de varios paradigmas de programación, incluyendo la [programación orientada a objetos](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Object-oriented_JS).

## ¿Qué puede hacerse con JavaScript?
* Controlar multimedia.
* Reaccionar a "eventos" (ej. presionar un botón).
* Modificar dinámicamente el contenido de una página web.
* Manejar mapas interactivos.
* Y muchas otras cosas más...

## El programa "Hola mundo" en JavaScript
```html
<!DOCTYPE html>
<html lang="es">
    <head>
        <title>Hola mundo</title>
        <meta charset="UTF-8"> 
        <script>
            /* Función que imprime "Hola mundo" */
            function holaMundo () {
                alert("Hola mundo");
            }        
        </script>
    </head>
    <body>
        <button type="button" onclick="holaMundo()">
            Presióneme
        </button>        
    </body>
</html>
```
# Conceptos básicos
## El elemento script de HTML
El elemento [```script```](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/script) se utiliza para incluir código de algún lenguaje de programación, típicamente JavaScript, aunque también usarse con otros lenguajes y sintaxis (ej. [JSON](https://www.json.org/json-en.html)).

```html
<script>
    /* Función que imprime la hilera "Hola mundo" */
    function holaMundo () {
        alert("¡Hola mundo!");
    }        
</script>

<script src="js/misfunciones.js"></script>

<script src="https://maps.googleapis.com/maps/api/js"></script> 

<script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js" integrity="sha512XQoYMqMTK8LvdxXYG3nZ448hOEQiglfqkJs1NOQV44cWnUrBc8PkAOcXy20w0vlaXaVUearIOBhiXZ5V3ynxwA==" crossorigin=""></script>
```

## Sintaxis de JavaScript

### Comentarios
Para varias líneas:
```javascript
/* Este es un
   comentario de
   varias líneas 
*/
```

Para una línea:
```javascript
var i = 1; // contador inicializado en 1       
var j = 2; // contador inicializado en 2 
```




```javascript
```
