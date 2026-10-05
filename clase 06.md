# Clase 06

## Propiedad display
- cada etiqueta es una caja
- comportamiento por defecto
- nunca usar imágenes tan pequeñas -- 1200-1600px min

### Block
- ocupa todo el ancho y empieza en una línea nueva
```display: block;```

### Inline
- ocupa solo su contenido y fluye con el texto
```display: inline;```

### Inline block
- fluye pero acepta pading y tamaño
```display: inline-block;```

### None 
- desaparece
```display: none;```

---

## Flex box
```
display: flex;
```
- cambia como se ordenan sus hijos
- grilla -- contenedor
- tarjeta -- hijos
```
  .grilla {
display: flex;
}
```
### Flex direction
- **row:** por defecto
```
  .grilla {
display: flex;
flex-direction: row;
}
```
- **column**
```
  .grilla {
display: flex;
flex-direction: column;
}
```
---
- **dos ejes**
1. eje cruzado: align-items
2. eje principal: justify-content
3. repartir el ancho y pasar a otra línea -- entre hijos
```
.grilla {
display: flex;
justify-content: space-between;
align-items: center;
gap: 1.5rem;
}
```
 4. cuando sobra espacio -- se reparten en partes iguales
```
.tarjeta {
flex: 1;
min-width: 12rem; /* ninguna se achica bajo 12rem */
}
```
 5. cuando falta espacio -- pasan a la siguiente línea
```
.grilla {
display: flex;
flex-wrap: wrap;
gap: 1.5rem;
}
```
---
- **justify content:** reparte en el eje principal
  
1. flex-start -- inicio
```     
.grilla {
display: flex;
justify-content: flex-start;
}
```
  2. center -- centro
```
.grilla {
display: flex;
justify-content: center;
}
```
  3. space-between -- uno en cada extremo
```
.grilla {
display: flex;
justify-content: space-between;
}
```
---
- **align-items:** alinea en el eje cruzado
  
1.  stretch -- estiran por defecto
```
.grilla {
display: flex;
justify-content: space-between;
align-items: stretch;
}
```
  2. flex-start -- arriba
```
.grilla {
display: flex;
justify-content: space-between;
align-items: flex-start;
}
```
  3. center -- centro
```
.grilla {
display: flex;
justify-content: space-between;
align-items: center;
}
```


---
## Botones 

### <a> 
- padding vertical se monta sobre las líneas vecinas
```
.boton {
display: inline-block;
padding: 0.75rem 1.5rem;
}
```
### <button> 
- fluye en la línea, pero respeta su padding 
```
button {
padding: 0.75rem 1.5rem;
}
```

## Imágenes
- por defecto queda queda alineada
  
### block + margin auto
- baja a su propia y el margen se reparte a los lados
```
img {
display: block;
max-width: 100%;
height: auto;
}
```
### fill
- estira y deforma por defecto
### contain
cabe completa y deja espacios
### cover 
llena la caja, sin perder proporción

## Pasos
Contenedor display: flex; 

Dirección flex-direction: row | column;

Alinear justify-content x align-itemns

Separar gap: 1.5rem;

Repartir flex: 1; (en los hijos)

## Material complementario

Material de apoyo HTML CSS: https://drive.google.com/drive/folders/1mUIifhxHZzfT4QmuFoPo4L4V3EXAgFqn?ths=true

Flexbox Froggy (juego): https://flexboxfroggy.com/

Flexbox Adventure (juego): https://codingfantasy.com/games/flexboxadventure

Guía sencilla de Flexbox (video tutorial): https://www.youtube.com/watch?v=PSwlAuRbv_A&t=3068s
