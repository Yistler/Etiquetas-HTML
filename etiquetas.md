## Etiquetas de html
Esta informacion de etiquetas provienen del libro de html del **Programador X y su Academia X**

[.](https://s3.amazonaws.com/kajabi-storefronts-production/file-uploads/sites/2147489095/themes/2154274426/downloads/3f4ed77-fc1e-aaff-dd06-ad64c685b18d_Academia_X_-_HTML_v1.0.0_.pdf)

quede en la pagina 120

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
<html>abarca toda la informacion dentro del documento sigues despues de doctype hasta el final de todo el documento
    <head>Abarca todas las etiquetas no visibles por el usuario
        <meta charset="UTF-8">Especifica el conjunto de caracteres utilizado en el documento UTF-8
        <meta name="description" content="breve descripcion del contenido"> 
        <meta name="keywords" content="palabras claves, separadas por comas">
        <link rel="stylesheet" href="ruta del documento css">se puede usar con media="print" solo impresoras 
        (screen) para ordenador omitir en otro caso si no especifica por defecto es ALL para todos los dispositivos
        <base href="url de la pagina" target="_blank">URL base para toda los enlaces, en una _blank para q se abra en una nueva pestaña
        <link rel="shortcut icon" href="favicon.icon" type="image/x-icon">agregando un icono a la pagina
        <title> Para darle un titulo a una pagina
        <style>Para agregar estilo al documento dentro del mismo html se usa entonces en el head 
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
        <section id="seccion2">seccion para agregar contenido relacionado gracias al id al dar click al enlace <a> envia a esta seccion
            <p>etiqueta para colocar parrafo
        </section>

        <section id="seccion2">
            <ul> lista  <ol> lista ordena con numeracion
                <li> lista desordenada </li>
            </ul>
            <figure>para contener elementos multimedia
                <img src="hubicacion" alt="descripcion por si no carga la imagen">
                <figcaption>descripcion del elemento al pie de la imagen</figcaption>
            </figure>
            
            <b></b>Se utiliza para mostrar el texto en negrita(solo cambia el texto no aporta nada mas)
            <i></i>Se utiliza para mostrar el texto en cursiva(solo cambia el texto no aporta nada mas)
            <em>enfatizar vuleve el texto(cursiva)</em> Etiqueta semantica ayuda a aportar informacion 
            <strong>fuerte pone el texto en negrita</strong> Etiqueta semantica ayuda a aportar informacion 
            <small>Ejemplo el copyright</small>texto tamaño pequeño etiqueta semantica es un texto de menor importancia
            <s></s>Tacha el texto y ya no es valido o correcto dentro del documento etiqueta semantica
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

    <data>se utiliza para almacenar datos privados dentro de un elemento del DOM esta etiqueta es invisible para el usuario
        es solo para almacenar información y no tiene efectos visuales, para usar esa información, debes usar javascript y hacer uso del valor almacenado en el atributo "value"
        <div id="producto1">
            <h2>Producto</h2>
            <p>$50</p>
            <data value="50" class="precio"></data>
        </div>

    <p>El próximo evento se llevará a cabo el <time datetime="2022-09-12">12 de septiembre de 2022</time></p>
        En este caso, el navegador mostraría "El próximo evento se llevará a cabo el 12 de septiembre de 2022."y el contenido dentro de la etiqueta time es una representación visual de la fecha, mientras que el atributo  datetime contiene la fecha en formato estandarizado  AAAA-MM-DD 
        También se puede usar para mostrar un horario: (datetime="13:30")
    
    <code> en HTML se utiliza para mostrar contenido de código en una página web. El contenido dentro de esta etiqueta se presenta en una fuente mono- espaciada y generalmente se muestra con un aspecto distinto al del texto normal en una página. Y se puede utilizar con la etiqueta <pre> que es similar pero los espacios y tabulaciones son mantenidos en su formato original
    <p>Ejemplo de codigo HTML</p>
    <pre>
        <code>
            &lt;html&gt;
                &lt;head&gt;
                    &lt;title&gt;Example&lt;/title&gt;
                &lt;/head&gt;
            &lt;/html&gt;
        </code>
    </pre>
    <samp>Tambien se usa para codigo solo que para mostrar la salida de un programa ejemplo
        console.log("Hello Word");
    <p>salida del console.log</p>
    <samp>Hello Word</samp>
    <kbd>Ctrl</kbd>+<kbd>S</kbd>se utiliza para un texto que representa entrada de teclado o como introducir un comando (Crtl+s)

   H<sub>2</sub>O Se utiliza para mostrar el texto en su interior como un sudíndice
   ejemplo: la formula del agua 
   x<sup>2</sup> Se utiliza para mostrar el texto en su interior como un superíndice
   ejemplo: X al cuadrado x2
   
   

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

<dfn> en HTML se utiliza para indicar el primer uso o la definición de un término o una frase específica dentro de un párrafo. El navegador suele represen- tar el contenido dentro de esta etiqueta con cursiva

<p>El <abbr title="Organización Mundial de la Salud">OMS</abbr> recomienda el uso de pendejadas</p> abbr se utiliza para indicar una abreviatura ayuda a describir el significado del contenido.

<var> en HTML se utiliza para indicar una variable en el contenido de una página web. Se utiliza principalmente en contenido matemático y científico
</html>
```


