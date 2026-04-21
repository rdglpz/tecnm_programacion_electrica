Primos Gemelos. 

Determinar si $n$ y $n+2$ son primos.

 
Escribe un programa que pida un número entero positivo $n>1$ al usuario y determine si este es primo. 

Si no es primo imprimir en consola un mensaje anunciando que $n$ no es primo y por lo tanto no tiene primo gemelo y finalizar el programa.

Si $n$ es primo entonces calcular si $n+2$ es primo.

Si $n+2$ no es primo imprimir "n es primo pero n+2 no es primo por lo tanto n no tiene primo gemelo".

Si $n+2$ es primo, imprimir "n es primo y n+2 también es primo por lo tanto son primos gemelos"


No utilizar ```for(){}```.

Rubrica.


Programa funcionando con while, printf, scanf detectando no primo, primo, primo gemelo (doble bandera) 100%


Programa primo simple con while, printf, scanf 50% salida, primo , no primo. 


Programa primo simple mejorado con while, printf, scanf 70% salida, primo , no primo. 








número primo gemelo e imprimir el par de números primos gemelos. Preguntar si se quiere analizar otro par de números y usar un valor de -1 para decir que no, y cualquier otro para continuar.


```
#include<stdio.h>


int main(){
	
	int primo_a = 1;
	int primo_b = 1;
	int d = 2;
	int n;
	scanf("%d", &n);


	while(d<n){
		
		if(n%d==0){
			primo_a = 0;
			d = n;
		}
		
		d = d + 1;
	}

	if(primo_a == 1){
		/*Existe la posibilidad que tenga un primo gemelo*/
		d = 2;
		while(d<n+2){
			if(n+2%d == 0){
				primo_b=0;
				d = n + 2;
			}
			d = d + 1;

		}		

	
	}
	
	if((primo_a == 1) && (primo_b ==1)){
	    printf("%d y %d son primos gemelos", n, n+2);
	}


}
```