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
```
