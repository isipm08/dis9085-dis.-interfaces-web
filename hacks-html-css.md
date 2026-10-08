# Hacks HTML
```
existen de H1-H6

<!DOCTYPE html> -- primera línea

! + enter (código html predeterminado)

<html lang="es"> ... </html> -- languaje es -- español

<meta charset="UTF-8"> -- metadatos

<meta name="viewport"content="width=device-width,initial-scale=1"> -- pantalla real

<title>Muestrario</title> -- título de la página principal en el navegador

<link rel="stylesheet" href="style.css"> -- se conectan ambos archivos

<h1>Título</h1> -- existe uno

<p>Párrafo</p>

<a>Te lleva a otro sitio externo</a>

<button type="button">Ver más</button> -- realiza algo en la misma página

<img src="img/silla.jpg" alt="Silla de madera clara con asiento de cuerda"> -- no tiene etiqueta de cierre "src": ruta "alt": descripción

<figure> <img src="..." alt="..."> <figcaption>Silla Wishbone,1949.</figcaption> </figure> -- agregar imagen más pie de foto

<strong>Bold</strong> -- importancia

<em></em> -- énfasis en la lectura

<nav> <ul> <li><a href="#proyectos">Proyectos</a></li></ul> </nav> -- navegación principal

<a href="link">Ver el link (poner lo que dirá el botón)</a>

<ul> //para reconocer el listado
// ol es lista enumerada
-  <li>Lista</li>
-  <li>Lista</li>
-  <li>Lista</li>
<ul/>

<main> ... </main> -- contenido principal

<section id="materiales"><h2>Materiales</h2> ... </section> -- al presionarla te dirige a la página

<article class="tarjeta"> <h3>Lino</h3><p>...</p> </article> -- contenido que te dirige fura de la página

<img src="nombre imagen.formato"alt="descripción imagen (no se verá)">

<etiqueta id="descripción" -- sirve después para los links

!<--comentar-->

<a href=#contexto">Contexto</a></li> -- para ir como a un link directo dentro de la página web, realizarlo en la lista

<div class="grilla"> <article>...</article> ...</div> -- caja génerica tipo block, agrupar elementos por razones de estilos 

<footer> <p>© 2026 Estudio</p></footer> -- final, créditos 
```
## Atributos
```
href -- destino enlace (enlace interno # + id) (otro archivo dentro del proyecto href="") (otro sitio href="https...)

src -- ruta del archivo de imagen (src="img/lino.jpg")

alt -- texto el cual reemplaza la imagen si es que esta no se ve (alt="Telar con hilos de colores")

class -- se combina entre archivos

id -- nombre único página, sirve para los enlaces internos de single page
```
## Estructura general HTML
```
<html>
<head> -- metadatos
</head>
<body>
</body>
</html>
```
```
<body>
<header></header>
<main></main> -- parte importante de la página
<footer></footer> -- permanentemente abajo, contacto, dirección, teléfono 
</body>
```
# Hacks CSS
```
<link rel="stylesheet href="style.css"> -- ponerlo en el index html -- head (para aplicar css)

/* comentario */

rem -- 3rem (todos los lados) 3rem 2rem (arriba y abajo) (lados)

* al principio para aplicar en toda la página

si quiero destacar una frase dentro de un párrafo realizar clase + propiedad -- ej: strong

si quiero modificar un texto solamente

css .nombreclase {
     font-size:
     color:

html
<p class= "nombre clase";

margin: 0; -- elimina márgenes que trae por defecto

font-family: fuente principal -- se escriba una lista, si la 1ra no estáa pasa a la siguiente (font-family: Inter, Arial,sans-serif;)

color: texto general fuente -- (color: #2B2B2B;)

font-size: tamaño texto (font-size: 1.25rem;)

font-weight: grosor texto (font-weight: bold; · font-weight: 600;)

line-height: interlineado (line-height: 1.6;)

text-decoration: subrayado en los enlaces (text-decoration: none;)

background: #000000 fondo navegación

box-sizing: define ancho -- incluye padding y borde (* { box-sizing: border-box; })

width: ancho caja (width: 50%;)

img { max-width: 100%; } -- impide que una imagen sobrepase el contenedor "padre"

div -- bloques de contenido

header { ... }

max-width: 75rem;: ancho máximo para el contenedor del encabezado (max-width: 50rem; · img {max-width: 100%; })

height: alto caja

min-height: alto mínimo

margin: 0 auto;: centra horizontalmente la caja en la pantalla, transparente (margin: 0; · margin: 0 auto; ·
margin-bottom: 1rem;)

padding: 3rem 2rem;: Agrega espacio interno, toma color fondo (arriba/abajo: 3rem, lados: 2rem) (padding: 1rem; · padding:1rem 2rem; · padding: 1rem 2rem 3rem 0;)

border-bottom: 4px solid rgb(196, 111, 7);: pinta una línea divisoria inferior (border: 1px solid #D9D2C5; ·
border-bottom: 4px solid #B08452;)

border-radius: redondea esquinas (border-radius: 10px;)

list-style: viñetas de una lista (list-style: none;)

:hover -- el mouse está sobre el elemento (.boton:hover { background: #B5543C; })

:focus-visible -- escribe junto al hover para que el sitio funcione sin mouse (.boton:hover, .boton:focus-visible { ... })

display: comportamiento caja (display: block; · display: inline-block; · display: flex;)

flex-direction: dirección en que se ordenan los hijos (flex-direction: column;)

justify-content: distribuye hijos a los largo de la dirección principal (justify-content: space-between;)

align.items: alinea a los hijos en vertical (align-items: center;)

gap: espacio entre hijos (gap: 1.5rem;)

flex-wrap: permite que los hijos que no caben pasen a una nueva línea (flex-wrap: wrap;)

flex: se escribe en los hijos, crezcan para repartirse en el espacio (.tarjeta { flex: 1; })


footer -- parte de abajo final
```
