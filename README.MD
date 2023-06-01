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
===========

# Formatos de enfasis 

- formato *italica* de la primer forma.
- formato _italiva_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la primer forma.
- formato ~~tachado~~, formato normal.
- aquí podemos usar *formato italico*, pero tambien **bold** y ~~tachado/rayado~~

# Listas
1. Esto es un item de lista ordenada.
1. Esto es un item de lista ordenada.
1. Esto es un item de lista ordenada.
1. Esto es un item de lista ordenada. 

- Esto es un item de lista desordenada
- Esto es un item de lista desordenada
- Esto es un item de lista desordenada

# Links
<a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link al index](index.html)

# Imagenes
![Imagen de Bataman](https://www.lavanguardia.com/files/image_948_465/uploads/2017/04/10/5fa3c6ca21373.jpeg)

# Code Snippets
Codigo en JSON
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
Codigo en JavaScript
```JavaScript
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
JSON
```

# Tablas 
|Nombre    | Apellido |  Fecha    | 
| -----    | -------- | --------- |
| Cesar    | Ortega   | 08/08/92  |
| Alejandro| Burgos   | 01/22/13  |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita:

>Esto es otra cita.

# Lineas Divisoras
Esto es un texto que sera dividido por guines medios.

---
Esto es otro texto dividido por asteriscos.

***

Esto es otro texto dividido por guines bajos.
___


# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista
