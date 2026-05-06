#### paso de parametros por referencia
 
cuando pasamos una variable a una funcion por referencia,
lo que se manda en realidad es la direccion de memoria de la variable
para ello es necesario ocupar una variable especial denominada
##### [[PUNTERO]]

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

En este ejemplo 'p' es un puntero de tipo entero y 'x' es una variable de tipo entero.
Al inicio del programa se lee el valor de 'x', para después pasar su dirección de memoria 'p'.
esto ocurre en el momento en el que se dice 'p = &x', una vez que tiene la dirección de 'x', se puede acceder y modificar al contenido p, esto se ejemplifica, cuando se hace:
 *p = *p + 1
Formando como base lo anterior podemos decir que cuando se desea pasar una variable por 
referencia se debe de hacer con un paso o referencia, la cual se indica desde la declaracion de
la función, de este modo cualquier cambio que se haga a la variable que se pase por referencia, tendra efecto en el codigo principal 