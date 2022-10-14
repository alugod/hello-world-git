# Tamaño de Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines 

Underline 1
-------------

Underline 2
=============

# Formatos  de enfasis

-   formato *italica* de la primer forma.
-   formato _italica_ de la segunda forma.
-   formato **strong o bold** de la primer forma.
-   formato __strong o bold__ de la segunda forma.
-   formato ~~tachado~~ formato normal.
-   aquí podeos usar formato *italica*, pero tambien **bold** y ~~tachado~~.

# Listas
1. Esto es un item de lista ordenada.
2. Esto es un item de lista ordenada.
3. Esto es un item de lista ordenada.
-   Esto es un item de lista desordenada.
-   Esto es un item de lista desordenada.
-   Esto es un item de lista desordenada.

# Links
-   <a href="http://google.com">Esto es un link en HTML</a>
-   [Esto es un link en Markdown](http://google.com)
-   [Esto es un link al index o archivo interno](index.html)

# Imagenes
![Logo Github](github.png)
![Logo Github desde liga](https://www.howtogeek.com/wp-content/uploads/2022/08/github_hero_2.jpg?width=1198&trim=1,1&bg-color=000&pad=1,1)


# Code Snippets
## Codigo en JSON

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
## Codigo en Javascript

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
| Nombre | Apellidos | Documento |
| ------ | --------- | --------- |
| Antonio| Lugo      | 85746385  |
| Tomas  | Ramirez   | 123456    |
| Nombre | Apellidos | Documento |
| Nombre | Apellidos | Documento |
| Nombre | Apellidos | Documento |

# Citas
Esto es un texto referente a una cita que pondremos debajo:
>Esto es una cita.

Para terminar la cita tienes que darle un enter.

>Este es otra cita.

# Lineas Divisoras
Esto es un texto que sera dividido por guiones medios. Tiene que estar separado por un espacio.

---

Esto es otro texto dividido por asteriscos.

***

Esto es otro texto dividido por guiones bajo.

___

# Saltos de Línea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.

-   Lista

