## Etiquetas de html
Esta informacion de etiquetas provienen del libro de html del **programador x**
Enlace: copia todo el enlace y pegalo para ver el libro
https://s3.amazonaws.com/kajabi-storefronts-production/file-uploads/sites/2147489095/themes/2154274426/downloads/3f4ed77-fc1e-aaff-dd06-ad64c685b18d_Academia_X_-_HTML_v1.0.0_.pdf

### Secciones en la que se dividira este contenido de etiquetas
* seccion 1
    * **etiquetas del head:**   
    son todas las etiquetas semanticas que agregar informacion al documento o agregan elances externos
* seccion 2 
    * **Etiquetas mas importantes:**   
    Aqui estaran las etiquetas mas relevantas las mas usadas evitando colocar excesos de etiquetas que casi no se usan
* seccion 3 
    * **Etiquetas de poca uso:**   
    son todas las etiquetas que dan forma al documento incluyendo informacion que se lee en la pagina
Las etiquetas que describan la funcion que hace omitire explicarlas ya que seras explicitas

## seccion 1
### etiquetas del head:
```html
<!DOCTYPE html> especifica que sera un documento html5
<html>abarca toda la informacion dentro del documento sigues despues de doctype
    <head>Abarca todas las etiquetas no visibles por el usuario
        <meta charset="UTF-8">Especifica el conjunto de caracteres utilizado en el documento UTF-8
        <meta name="description" content="breve descripcion del contenido"> 
        <meta name="keywords" content="palabras claves, separadas por comas">
        <link rel="stylesheet" href="ruta del documento css">se puede usar con media="print" solo impresoras 
        (screen) para ordenador omitir en otro caso
        <base href="url de la pagina" target="_blank">URL base para toda los enlaces, en una _blank para q se abra en una nueva pentaña
        <link rel="shortcut icon" href="favicon.icon" type="image/x-icon">agregando un icono a la pagina
        <title> Para darle un titulo a una pagina
        <style>Para agregar estilo al documento dentro del mismo html se usa entonces en el head </style>
    </head>




```
## seccion 2
### Etiquetas mas importantes:
```html
<body>contenedor principal para el contenido visible todos los elementos que se desean mostrar deben estar dentro
    <header>encabezado de un documento, pagina o seccion
        <nav>para crear lista de navegacion
            <ul>lista
                <li><a href="enlace">nombra al enlace</a></li>
                <li><a href="index2.html">segunda pagina</a></li>
            </ul>
        </nav>
    </header>

    <main> utilizada para indicar el contenido principal de un documento html
        <a> para agregar enlaces lo puedes colocar dentro de <li>lista
        <nav>para crear lista de navegacion
            <ul>lista
                <li><a href="#seccion1">Seccion 1</a></li>
                <li><a href="#seccion2">Seccion 2</a></li>
            </ul>
        </nav>
        <section id="seccion2">seccion para agregar contenido relacionado
            <p>redirije a esta seccion gracias al id="seccion1"
        </section>

        <section id="seccion2">
            <ul> lista desordenada o <ol> lista ordena con numeracion
                <li> descripcion </li>
            </ul>
            <figure>para contener elementos multimedia
                <img src="hubicacion" alt="descripcion por si no carga la imagen">
                <figcaption>descripcion del elemento al pie de la imagen</figcaption>
            </figure>

            <em>enfatizar vuleve el texto(cursiva)</em>
            <strong>fuerte pone el texto en negrita</strong>
            <small>texto tamaño pequeño texto de menor importancia</small>
            <s>tacha el texto y ya no es valido dentro del documento</s>
            <q>para cita corta o dentro de un texto agrega comillas</q>
            <blockquote>Para bloque de nota se puede usar con <cite></cite></blockquote>
            <cite> para titulo de una obra</cite>

            <hr> inserta una linea horizontal
        </section>

        <article>articulo dentro de una pagina contenido independiente y auto-contenido(entenderse de manera independiente)
            <h1>titulo puede ir de h1 a h6</h1>
        </article>
    </main>

    <footer>Todo el contenido para el pie de pagina
        <address>indicar la informacion de contacto de una entidad o web
    </footer>
</body>
```



## seccion 3
### Etiquetas de poca uso:
```html
<hgroup> para agrupar etiquetas de titulo h1 h2 
<pre> texto preformado para codigo respeta espacios deja el texto tal cual

<dl>lista de
    <dt>termino
    <dd>definicion
</dl>usadas en diccionario ejemplo.

&amp; simbolo &
&copy; simbolo copyright
&ntilde; simbolo ñ
&circledR; R con circulo
&commat; arroba


</html>
```


