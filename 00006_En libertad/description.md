Queremos definir la función `esLibreCostados()`, que determine si el cabezal tiene libertad para moverse hacia los costados (es decir, Este y Oeste).

Antes que nada, pensemos, ¿de qué **tipo** tiene que ser el valor que retorna nuestra función? Será...

* ... ¿un **color**? No.
* ... ¿un **número**? Tampoco.
* ... ¿una **dirección**? Podría, pero no. Fijate que lo que pide es _"saber si puede moverse"_ y no hacia dónde.
* ... ¿un **booleano**? ¡Sí! :tada: Cómo nos dimos cuenta: lo que está pidiendo tiene pinta de **pregunta** que se responde con sí o no, y eso es exactamente lo que podemos representar con un valor booleano: **Verdadero** o **Falso**.

Pero, ups, hay un problema más; hay que hacer DOS preguntas: ¿se **puede mover** al Este? **Y** ¿se **puede mover** al Oeste?. :fearful:

Bueno, existe el operador `&&` que sirve justamente para eso: toma dos expresiones booleanas y devuelve `True` solo si **ambas** son verdaderas. Si sabés algo de lógica, esto es lo que comunmente se denomina **conjunción** y se lo suele representar con el símbolo ∧.

Por ejemplo, si quisieramos saber si un casillero tiene más de 5 bolitas y el `Rojo` es el color dominante podríamos escribir:

``` gobstones
function esUnCasilleroCargadoConRojoDominante() {
  return (nroBolitasTotal() > 5 && rojoEsDominante())
}
```

> Definí la función `esLibreCostados()` que indique si el cabezal puede moverse tanto al Este como al Oeste.
