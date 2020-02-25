# version del curso
version actual: v1.2.2

# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underline
Underline 1
----------
Underline 2
==========

# formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la segunda forma.
- formato ~~tachado~~, formato normal.
-- aqui podemso usar *formato italico*, pero tambien **bold** y ~~tachado~~
# listas ordenadas
1. esto es un item
2. esto es un item
3. esto es un item
- esto es un item
- esto es un item
- esto es un item
# link
- <a href="http://google.com">esto es un link</a>
- [esto es un link en markdown](http://google.com)
- [esto es un link al index](index.html)

# imagenes
![logo angular](https://s3.amazonaws.com/cdn.wp.m4ecnet/wp-content/uploads/2018/06/05041237/GitHub-logo-2-imagen.jpg)

# code snippets
- [esta es la pagina donde esta la highlight](https://highlightjs.org/static/demo/)
codigo json
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
```
# tablas
| nombre | apellido | lu  |
| ------ | -----    | --- |
| cris   | ballest  | 123 |

# citas
esto es un texto de referencia para un cita
> esto es una cita.

esto es un texto de referencia para un cita
> esto es otra cita.

# lineas divisoras
estos es un texto que sera dividido.

--- 
esto  es otro texto por asteriscos

***
esto es otro por guiones bajos

___

# saltos de lineas
Estos es nuestro 1er salto.

Estos es nuestro 2do salto.

Estos es nuestro 3er salto.

- Lista
