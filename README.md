# AFN
Autómata Finito No determista para deteccion de pertencencia en algun lenguaje.

La ui recibe un archivo de texto con los datos del autómata, con el siguiente formato.

<hr>
ARCHIVO:
[Primera linea: Alfabeto] 
  Pueden ser letras o numeros, separados por coma, no importa los espacios. Ejemplo: a,b,c
[Segunda linea: Estados] 
  Pueden ser letras o numeros, separados por coma, no importa los espacios. Ejemplo: 0,1,2,3
[Tercera linea: Estado Inicial] 
  Ejemplo: 
  0
[Tercera linea: Estado(s) Final(es)] 
  Ejemplo: 2,3
[Tabla de transicion] 
  Esta tabla debe ir ordenada de tal forma que cada valor del alfabeto sea una columna y las filas los estados, separados por espacios. Sin poner los <i>headers<i> de la tabla.
  El programa acepta poner cualquier caracter cuando no hay una transición T(a,e)=? Donde aE{alfabeto} y eE{Estados}
  Ejemplo: 
  0 - -
  . 2 3
  ? 3 *
  3 - 1
[Siguientes lineas]
  El programa sólo lee hasta la linea n, donde n es la cantidad de estados indicados en la segunda linea, por lo que después de la tabla, se puede poner cualquier cosa.
<hr>

Después  de haber ingresado este documento, se mostrará de mejor forma en la UI, y se podrá empezar a ejecutar.
<h3>Ejecución</h3>
Para la ejecucion se debe ingresar una cadena para comprobar que es válida en base al autómata ingresado.
Se puede ejecutar múltiples veces.
  
