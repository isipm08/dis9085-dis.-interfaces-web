# Clase 09

## JavaScript
- lenguaje programación, corre en el navegador
- reacciones
- comportamiento -- qué pasa cuando realizas algo

### conexión JS a HTML
1. crear archivo: en el index.html crear archivo llamado script.js
2. conectar al HTML: justo antes de cerrar el body escribir <script src="script.js"></script>
3. probar en consola: script.js -- console.log("hola")

### buscar y cambiar elementos
1. buscar elemento: encontrar algo document.querySelector() con los mismos selectores de CSS, lo guardamos en una const para usarlos después
  ``` const titulo = document.querySelector("h1");```

### selectores
- iguales que en css
- etiqueta
- id
- clase
 ```
document.querySelector("h1");
document.querySelector("#boton");
document.querySelector(".tarjeta");
 ```
### cambiar elemento
1. cambiar texto: reemplazar lo que dice el elemento
   
titulo.textContent =
"Hola!"; 

2. cambiar estilo: cambiar propiedad  de CSS

titulo.style.color =
"tomato";

3. agregar clase: sumar clase definida en CSS

titulo.classList.add("activo");

### hacer que pase algo
- evento -- algo que hace la persona
- atento -- addEventListener

```
const boton = document.querySelector("#boton");
const titulo = document.querySelector("h1");

boton.addEventListener("click", function () {
titulo.textContent = "Me hiciste clic!";
});
```


### material complementario

MDN: Javascript

<https://developer.mozilla.org/es/docs/Web/JavaScript>

Manz.dev: Lenguaje JS

<https://lenguajejs.com/javascript/>

W3 Schools: JavaScript Tutorial

<https://www.w3schools.com/js/default.asp>

ENIUN: Curso JavaScript

<https://www.eniun.com/tutorial-javascript-basico/>
