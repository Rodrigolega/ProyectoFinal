## Lenguaje de Programación de Bajo Nivel

Un lenguaje de programación de bajo nivel es aquel que se encuentra cerca del lenguaje máquina y permite un control directo sobre el hardware del computador. Estos lenguajes están diseñados para manejar recursos del sistema como memoria, registros, etc.

C, aunque no es tan abstracto como los lenguajes de alto nivel, permite a los programadores trabajar eficientemente y con gran control sobre el hardware, haciéndolo ideal para sistemas operativos, drivers y software donde la optimización es crucial.

-----

#### Ejemplo:

```c
#include <stdio.h>

int main() {
    int a = 5, b = 10;
    int suma = a + b;
    printf("La suma de %d y %d es %d\n", a, b, suma);
    return 0;
}

#En este ejemplo, el programa suma dos números y muestra el resultado.
```
