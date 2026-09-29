# Clase 05
### Estructura HTML general
```
<html>
<head> -- metadatos
</head>
<body>
</body>
</html>
```
### Body
```
<body>
<header>
</header>
<main> -- parte importante de la página
</main>
<footer> -- permanentemente abajo, contacto, dirección, teléfono 
</footer>
</body>
```
### CSS
- Cascading Style Sheets
- controlar apariencia de los elementos de una página web (color, fondo, tipografía, espaciado, bordes, disposición)
---
**todo es una caja**
- Content (contenido): el texto o la imagen, su tamaño se controla con width y height.

- Padding (relleno): espacio interior entre el contenido y el borde, toma el color de fondo de la caja.

- Border (borde): la línea que rodea la caja, se define con grosor, estilo y color: border: 2px solid #2F3C7E;.

- Margin (margen): espacio exterior que separa la caja de las demás. Es transparente.

### Funcionamiento 
```
**
p{
color (propiedad):red (valor);
}

un elemento, varias propiedades
p{
color: red;
font-size: 1rem;
}

varios elementos, misma propiedad
p,
h1{
color: red;
}
```
### Hacks css
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
font-family: fuente principal
color: texto general fuente
background: #000000 fondo navegación
img { max-width: 100%; } -- impide que una imagen sobrepase el contenedor "padre"
div -- bloques de contenido

header { ... }
max-width: 75rem;: ancho máximo para el contenedor del encabezado 
margin: 0 auto;: centra horizontalmente la caja en la pantalla
padding: 3rem 2rem;: Agrega espacio interno (arriba/abajo: 3rem, lados: 2rem)
border-bottom: 4px solid rgb(196, 111, 7);: pinta una línea divisoria inferior


footer -- parte de abajo final
```

**REM**
- unidad medida relativa -- equivale al tamaño de fuente del elemento raís (html)
- 1 rem = 1 vez el tamaño de fuente raíz

### Código final página
```
/* Basico */
* {
    box-sizing: border-box; /*el ancho incluye padding y borde*/
}

body {
    margin: 0;
    .bree-serif-regular 
  font-family: "Bree Serif", serif;
  font-weight: 400;
  font-style: normal;
  color: #000000;
  background: #E6E6E6;
}

img {
    max-width: 100%;
}

/* Header */

header {
    max-width: 60rem;
    margin: 0 auto;
    padding: 3rem 2rem;
    border-bottom: 4px solid #996F38;
}

h1 {
    margin: 0;
    font-size: 2.5rem;
}

.autor {
    font-size: 1.2rem;
    color: #996F38;
}

/* main (contenido principal) */

main {
    max-width: 60rem;
    margin: 0 auto;
    padding: 3rem 2rem;
}

div {
    margin: 0 0 2rem;
    padding: 1rem;
    background: white;
    border: 1px solid #996F38;
}

section {
    padding: 1.5rem 2rem;
    margin-bottom: 1.5rem;
    background: white;
    border: 1px solid #996F38;
}

h2 {
    margin: 0;
    font-size: 1.5rem;
}

.destacado {
    background: #EDCA93;
    padding: 1rem;
}

.button {
    margin-top: 1;
    padding: 0.75rem 1.5rem;
    background: #996F38;
    color: white;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    text-decoration: none;
}

footer {
    max-width: 60rem;
    margin: 0 auto;
    padding: 3rem 2rem;
}
```  
