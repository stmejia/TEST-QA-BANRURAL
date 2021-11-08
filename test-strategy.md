CASO #1
DESCRIPCION: Linea #89
El llamado de la constante guessSubmit hacia referencia a una funcion mal escrita por lo que se cambio por la correcta.

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
ESTADO: RESUELTO
RESOLUCIÓN: Se coloco el nombre correcto de la funcion "addeventListener" por "addEventListener".

Se adjunta evidencia de la resolucion: "RESOLUCION.PNG"
TIPO DE PRUEBA REALIZADA: HUMO
AMBIENTE BUG: PRODUCCION


CASO #2
DESCRIPCION: Linea #97
El llamado de la variable resetButton hacia referencia a una funcion mal escrita por lo que se cambio por la correcta.

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
ESTADO: RESUELTO
RESOLUCIÓN: Se coloco el nombre correcto de la funcion "addeventListener" por "addEventListener".

Se adjunta evidencia de la resolucion: "RESOLUCION.PNG"
TIPO DE PRUEBA REALIZADA: HUMO
AMBIENTE BUG: PRODUCCION


CASO #3
DESCRIPCION: Linea #57
No se estaba indicando que tipo de dato que recibe el campo de texto donde el usuario ingresa el numero aleatorio.

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
ESTADO: RESUELTO
RESOLUCION: Se coloco el tipo de dato que recibiría el input en este caso sería un tipo NUMBER.

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
TIPO DE PRUEBA REALIZADA: HUMO
AMBIENTE BUG: PRODUCCION


CASO #4
DESCRIPCION: Linea #48
En la constante de tipo querySelector con el nombre "lowOrHi" hacia falta el punto para hacer referencia a la propiedad.

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
ESTADO: RESUELTO
RESOLUCION: Se colocó el punto al inicio de la propiedad para que la referencia sea válida.

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
TIPO DE PRUEBA REALIZADA: HUMO
AMBIENTE BUG: PRODUCCION


CASO #5
DESCRIPCION: Linea #48
La funcion random estaba mal ya que se estaba multiplicando por 10 y el numero aleatorio correcto es hasta 100 y no se le hacia la suma de 1 para su incremento

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
ESTADO: RESUELTO
RESOLUCION: Se cambio el numero 10 por 100.

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
TIPO DE PRUEBA REALIZADA: HUMO
AMBIENTE BUG: PRODUCCION


CASO #6
DESCRIPCION: Linea #117
La funcion random estaba mal ya no se estaba declarando ni multiplicando por 100 y unicamente se le estaba sumando + 1 

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
ESTADO: RESUELTO
RESOLUCION: Se utilizo la palabra reservada de javascript "let" y se agregó la multiplicacion * 100

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
TIPO DE PRUEBA REALIZADA: HUMO
AMBIENTE BUG: PRODUCCION


CASO #7
DESCRIPCION: Linea #45
El numero de intentos estaba mal, ya que la variable ATTEMPS estaba seteada con 10;

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
ESTADO: RESUELTO
RESOLUCION: Se cambio el valor de la variable ATTEMPS a 10.

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
TIPO DE PRUEBA REALIZADA: HUMO
AMBIENTE BUG: PRODUCCION


CASO #8
DESCRIPCION: Linea #66,#71,#75
Los colores de las alertas no eran correctos según lo indicado en el requerimiento

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
ESTADO: RESUELTO
RESOLUCION: Se cambiaron los valores de los colores para las alertas.

Se adjunta evidencia del caso: "EVIDENCIA.PNG";
TIPO DE PRUEBA REALIZADA: HUMO
AMBIENTE BUG: PRODUCCION


CASO #9
DESCRIPCION: Linea #65, #70
Los mensajes de alerta no coincidian con las validaciones asignadas por lo que se modificaron para su correcto funcionamiento.

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
ESTADO: RESUELTO
RESOLUCION: Se cambiaron los valores del texto según se cumpla cada validacion.

Se adjunta evidencia del caso: "EVIDENCIA.PNG";
TIPO DE PRUEBA REALIZADA: HUMO
AMBIENTE BUG: PRODUCCION

CASO #10
DESCRIPCION: 
Según el requerimiento es necesario contar con una validacion en la que unicamente se permitan ingresar números enteros,
que no incremente los intentos realizados y alerte al usuario, por lo que en las pruebas realizadas este requerimiento no está implementado 
en el desarrollo. 

Se adjunta evidencia del caso: "EVIDENCIA.PNG"
ESTADO: No resuelto
RESOLUCION: Favor validar el requerimiento e implementacion del mismo.

Se adjunta evidencia del caso: "EVIDENCIA.PNG";
TIPO DE PRUEBA REALIZADA: HUMO
AMBIENTE BUG: PRODUCCION