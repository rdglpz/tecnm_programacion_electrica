# Examen 2 
Unidad 3 Primos Gemelos. 

Primos gemelos son pares de números primos cuya distancia es de 2 unidades. Por ejemplo, el par (3, 5) son primos gemelos porque son primos y su diferencia es 2. Otros ejemplos son (11, 13) o (41, 43). El número 5 es el único primo que puede pertenecer a dos pares de primos gemelos: (3, 5) y (5, 7).

## Descripción del ejercicio.

Determinar si $n$ y $n+2$ son primos.
 
Escribe un programa que pida al usuario un número entero positivo $n>1$ y determine si este es primo. 

Si no es primo imprimir en consola un mensaje anunciando que $n$ no es primo y por lo tanto no tiene primo gemelo. Finalizar el programa. 50%

Si $n$ es primo entonces calcular si $n+2$ es primo. 

Si $n+2$ no es primo imprimir "n es primo pero n+2 no es primo por lo tanto n no tiene primo gemelo".

Si $n+2$ es primo, imprimir "n es primo y n+2 también es primo por lo tanto son primos gemelos"

Ejemplo:
--caso 1--
Dame un número entero $n>1$: 4
4 no es primo

--caso 2--
Dame un número entero $n>1$: 7
7 es primo
9 no es primo 
Por lo tanto (7,9) no son primos gemelos.

--caso 3--
Dame un número entero $n>1$: 11
11 es primo
13 es primo 
Por lo tanto (11,13) son primos gemelos.



No utilizar ```for(){}```.

Rubrica.


Programa funcionando con while, printf, scanf detectando no primo, primo, primo gemelo (doble bandera) 100%


Alternativa 2 
Programa primo simple con while, printf, scanf 50% salida, primo , no primo. 

--caso 1--
Dame un número entero $n>1$: 4
4 no es primo
--Fin del programa--

--caso 2--
Dame un número entero $n>1$: 7
7 es primo
--Fin del programa--



Para sacar un 70% hacer mas eficiente el algoritmo (reducir el numero de operaciones para calcular si es primo).

--caso 1--
Dame un número entero $n>1$: 4
Con 2 comparaciones se deduce que 4 no es primo
--Fin del programa--

--caso 2--
Dame un número entero $n>1$: 7
Con 2 comparaciones se deduce que 7 es primo
--Fin del programa--

para sacar 90 hacer que el Programa primo simple que nunca termina de pedir numeros n>1. Verificar si es primo hasta que el usuario proporciona una señal de salida (usar vlor centinela) 90.

--caso 1--
Dame un número entero $n>1$: 4
Con 2 comparaciones se deduce que 4 no es primo

Dame un número entero $n>1$: 11
Con 4 comparaciones se deduce que 11 no es primo

Dame un número entero $n>1$: 0
--Fin del programa--










