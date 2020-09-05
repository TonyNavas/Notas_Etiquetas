# **Etiquetas en HTML**

Las etiquetas en HTML normalmente vienen en pares como ```<p>y</p>```, la primera etiqueta en un par es la etiqueta de inicio, la segunda etiqueta es la etiqueta final

La etiqueta final se escribe como la etiqueta inicial, pero con una barra diagonal insertada antes del nombre de la etiqueta ```<p> Mi primer párrafo </p>```

```
--------------------------------------------
|Apertura |       Contenido      |Cierre   |
|---------|----------------------|---------|
|    <h1> |  Mi primer encabezado|   </h1> |
|    <p>  |  Mi primer parrafo   |   </p>  |
|    <br> |                      |         |
```
## **Algunas etiquetas HTML basicas**
```
<body>    para el contenido
<head>    para información sobre el documento
<div>     división dentro del contenido
<a>       para enlaces
<strong>  para poner el texto en negrita
<br>      para saltos de línea
<H1>…<H6> para títulos dentro del contenido
<img>     para añadir imágenes al documento
<ol>      para listas ordenadas,
<ul>      para listas    desordenadas, <li> para   elementos dentro de la lista
<p>       para parágrafos
<span> para estilos de una parte del texto
```
```<body> </body>``` Indica la parte del cuerpo del contenido de un documento HTML. Es una etiqueta esencial para cualquier documento ya que indica donde empieza el contenido visible del documento.

```<head></head>``` a parte superior del documento HTML, es donde podremos indicar los metadatos: título del documento, hojas de estilos, javaScript, CSS…

```<div> </div>``` Un elemento que es usado mayoritariamente para agrupar otros elementos y actuar como plantilla de otros controles. La etiqueta ```<div>``` nos ayuda a estructurar el documento en secciones.

## **Encabezados**

Los encabezados se definen con las etiquetas ```<h1>``` a ```<h6>```. ```<h1>``` define el encabezado más importante. ```<h6>```define el encabezado menos importante.

**Ejemplo**
```
<h1>Título 1</h1>
<h2>Título 2</h2>
<h3>Título 3</h3>
<h4>Título 4</h4>
<h5>Título 5</h5>
<h6>Título 6</h6>

```
## **Etiquetas para citas HTML**

La etiqueta que define las citas cortas es <q>, por lo general, los navegadores les insertan comillas.

**Ejemplo:**
```
<body>
 <p>El objetivo es: <q>Construir un futuro donde las personas vivan en armonía con la naturaleza.</q></p></body>
```

## **Comentarios**

Las etiquetas de comentarios se utilizan para insertar comentarios en el código fuente HTML. El navegador no muestra comentarios, pero pueden ayudarlo a documentar su código fuente HTML.

**Ejemplo** 
```
<!DOCTYPE html>
<html>
<body>
<!-- Este es un comentario -->
<p>Este es un párrafo.</p>
<!-- Los comentarios no se muestran en el navegador -->
</body>
</html>
```
## **Párrafos**

