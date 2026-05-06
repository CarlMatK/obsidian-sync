#### paso de parametros por referencia
 
cuando pasamos una variable a una funcion por referencia,
lo que se manda en realidad es la direccion de memoria de la variable
para ello es necesario ocupar una variable especial denominada
##### PUNTERO

(un puntero es una variable que guarda direcciones de memoria, es decir,
que nos dice que posicion de la memoria se encuentra ubicada un valor)
Para declarar punteros en C usamos la siguiente simbologia

Tipo de dato * Nombre de la variable;

Ejemplo:
int *pentero;  -> Es un puntero a un entero
float *sueldo;  -> Es un puntero a un flotante

Para hacer uso de los punteros es necesario ocupar los siguientes oepradores 
*Operador que hace referencia al contenido de la direccion a la que apunte
&Operador que indica la direccion de memoria de una variable

Ejemplo de aplicacion:

```cpp
#include <stdio.h>
// *p contenido de la memoria
// x direccion de memoria donde se guardara

int *p,x;
int main()
{
    printf("Numero: ");
    scanf("%d",&x);
    p = &x; // pasamos la direccion de memoria de n a p
    *p = *p + 1; // alteramos el valor de p usando el puntero para acceder al contenido
    printf("El nuevo valor de x es: %d",x);
    return 0;
}

```

 en este ejemplo 'p' es un puntero de tipo entero y 'x' es una variable de tipo enteo 