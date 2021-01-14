# Cabeceras
# Cabecera h1
## Cabecera h2
### Cabecera h3
#### Cabecera h4
##### Cabecera h5
###### Cabecera h6

# Underline
Underline 1
-----------
Underline 2
===========

# Emphasis
- Formato *Italica* primera forma
- Formato _Italica_ segunda forma
- Formato **bold o strong** primera forma
- Formato __bold o strong__ segunda forma
- Formato ~~tachado~~,forma normal
- Aqui se puede combinar formato *Italico*, **bold** y ~~tachado~~

# Listas
1. Estos es un item de lista ordenana
2. Estos es un item de lista ordenana
3. Estos es un item de lista ordenana
- Estos es un item de lista desordenana
- Estos es un item de lista desordenana

# Links
- <a href="http://www.google.com">Esto es un link Html</a>
- [Esto es un link de Markdown](http://www.google.com)
- [Esto es un link al Index](index.html)

# Imagenes
![Esta es una imagen](https://raw.githubusercontent.com/adam-p/markdown-here/master/src/common/images/icon48.png)

# Code Snippets
Codigo en Json
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
Codigo en Javascript
```JAVASCRIPT
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

