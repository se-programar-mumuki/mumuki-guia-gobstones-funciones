Como en la definición de `hayBolitasAl` se usa `Mover`, es obvio que hay casos en los cuales podría romperse: basta con posicionar el cabezal en el origen y preguntar si `hayBolitas` de algún color al Oeste.

Pero, ¿no era que las funciones eran **puras** y **no tenían efecto real**? ¿Qué pasa si una función **hace BOOM**?

> Hagamos la prueba: vamos a probar la función `hayBolitasAl` del ejercicio anterior con casos donde no pueda moverse el cabezal. Presioná Enviar y mirá el resultado.