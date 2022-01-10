Ejercitemos un poco más esto de las **funciones con procesamiento**.

Te toca programar una nueva versión de `hayBolitasAl` que mire si hay bolitas a cierta distancia de la celda actual. A esta función la vamos a llamar `hayBolitasLejosAl` y recibirá tres parámetros: una **dirección** hacia donde deberá moverse, un **color** por el cual preguntar y una **distancia** que será la cantidad de veces que habrá que moverse.

Por ejemplo: `hayBolitasLejosAl(Norte, Verde, 4)` indica si hay alguna bolita Verde cuatro celdas al Norte de la posición actual.

<table class= "table table-borderless" style="width:100%">
  <thead>
  <tr>
    <th style="text-align: center">Para este tablero devolvería <em>True</em>:</th>
    <th style="text-align: center"></th> 
    <th style="text-align: center">Y para este tablero devolvería <em>False</em>:</th>
  </tr>
  </thead>
  <tbody>
  <tr>
    <td style="text-align: center">  
      <gs-board>
       GBB/1.0
       size 2 5
       cell 0 4 Verde 1
       head 0 0
      <gs-board>
    </td>
    <td style="text-align: center"></td> 
    <td style="text-align: center">
      <gs-board>
       GBB/1.0
       size 2 5
       cell 0 4
       head 0 0
      <gs-board>
    </td>
  </tr>
  <tbody>
</table>

> Definí la función `hayBolitasLejosAl(direccion, color, distancia)`.