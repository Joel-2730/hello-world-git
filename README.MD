# Version del curso 
Version actual : 1.2.2


# Cabeceras 

# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4 
##### Cabecera H5    
###### Cabecera H6

# Underlines 

Underline 1 
-----------
Underline 2 
======


# Formatos de enfasis 
- formato  *italica* de la primer forma 
- formato  _italica_ de la segunda forma
- formato **bold o strong** de la primer forma 
- formato __bold o strong__ de la segunda  forma 
- formato tachado
-  aqui podmeos usar *formato italico* , pero tambien **bold** y tachado 

# Listas 
1. Esto es un item de lista ordenada
2. Esto es un item de lista ordenada
3. Esto es un item de lista ordenada
- Esto es item de lista desordenada 
- Esto es item de lista desordenada 
- Esto es item de lista desordenada 

# Link
- <a href="http://www.google.com">Esto es un link html</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link en index](index.html)

# Imagenes
![logo github](https://image.flaticon.com/icons/png/512/25/25231.png)

# Code Snnipets 

codigo en JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```
codigo en Javascript

```Javascript
function $initHighlight(block, cls) {
  try {
    if (cls.search(/\bno\-highlight\b/) != -1)
      return process(block, true, 0x0F) +
             ` class="${cls}"`;
  } catch (e) {
    /* handle exception */
  }
  for (var i = 0 / 2; i < classes.length; i++) {
    if (checkCondition(classes[i]) === undefined)
      console.log('undefined');
  }

  return (
    <div>
      <web-component>{block}</web-component>
    </div>
  )
}

export  $initHighlight;
```
# Tablas 
| Nombre | Apellido | Documento |
| ------ | -------- | --------- |
| Maxi   | Burgos   |  1234354  |
| Tomas  |  tompson |   5235432 |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita .

Esto es otro texto que no se realaciona con la cita anterior 
> Esta es otra cita 

# Lineas divisoras 

Esto es un texto que sera dividido por guiones medios 

---
Esto es otro texto dividido por asteriscos


***

Este es otro texto dividido por guiones bajos

___

# Saltos de linea 
Esto es nuestro primer parrafo 

Esto es nuestro segundo  parrafo 

Esto es nuestro tercer   parrafo 
- Lista 






