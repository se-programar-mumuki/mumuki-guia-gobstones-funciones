Como vimos, el problema de lo anterior era la falta de **división en subtareas**: la **expresión** que cuenta la cantidad de bolitas que hay en la celda es demasiado **compleja**, y cuesta entender a simple vista que hace eso.

Entonces, lo que nos está faltando es algún mecanismo para poder **darle un nombre** a esa **expresión compleja**; algo análogo a los **procedimientos** pero que sirva para encapsular expresiones. 

La buena noticia es que Gobstones nos permite hacer esto, y la herramienta para ello es definir una **función**, que se escribe así:

```gobstones
function nroBolitasTotal() {
  return (nroBolitas(Azul) + nroBolitas(Negro) + nroBolitas(Rojo) + nroBolitas(Verde))
}
```

> Pegá el código anterior en el editor y observá el resultado.