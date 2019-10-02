# Autómata Finito No determinista
Autómata Finito No determista para deteccion de pertencencia en algun lenguaje.

La ui recibe un archivo de texto con los datos del autómata, con el siguiente formato.

<hr>
<p>ARCHIVO:<br>
[Primera linea: Alfabeto] <br>
  Pueden ser letras o numeros, separados por coma, no importa los espacios. Ejemplo: a,b,c <br>
[Segunda linea: Estados] <br>
  Pueden ser letras o numeros, separados por coma, no importa los espacios. Ejemplo: 0,1,2,3 <br>
[Tercera linea: Estado Inicial] <br>
  Ejemplo: <br>
  0 <br>
[Tercera linea: Estado(s) Final(es)] <br>
  Ejemplo: 2,3 <br>
[Tabla de transicion] <br>
  Esta tabla debe ir ordenada de tal forma que cada valor del alfabeto sea una columna y las filas los estados, separados por espacios. Sin poner los <i>headers</i> de la tabla. <br>
  El programa acepta poner cualquier caracter cuando no hay una transición T(a,e)=? Donde aE{alfabeto} y eE{Estados} <br>
  Ejemplo: <br>
  0 - - <br>
  . 2 3 <br>
  ? 3 * <br>
  3 - 1 <br>
[Siguientes lineas] <br>
  El programa sólo lee hasta la linea n, donde n es la cantidad de estados indicados en la segunda linea, por lo que después de la tabla, se puede poner cualquier cosa. </p>
<hr>

Después  de haber ingresado este documento, se mostrará de mejor forma en la UI, y se podrá empezar a ejecutar. 
<h3>Ejecución</h3>
Para la ejecucion se debe ingresar una cadena para comprobar que es válida en base al autómata ingresado. <br>
Se puede ejecutar múltiples veces. <br>
  
