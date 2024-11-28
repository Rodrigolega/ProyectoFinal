# Localidad Espacial y Temporal

La localidad espacial y temporal se refieren a patrones de acceso a la memoria que pueden ser aprovechados para mejorar el rendimiento del sistema.

## Localidad Temporal
Este principio sugiere que si una ubicación de memoria es accedida en un momento dado, es probable que la misma ubicación sea accedida nuevamente en un futuro cercano. Esto se debe a que los programas tienden a reutilizar datos e instrucciones recientemente utilizados, como en el caso de bucles.

**Ejemplo**:  
Supongamos un bucle que suma los elementos de un arreglo:

```c
for (int i = 0; i < n; i++) {
    sum += array[i];
}

En este caso, la variable sum es accedida repetidamente dentro del bucle, demostrando localidad temporal.
```

## Localidad Espacial

Este principio indica que si una ubicación de memoria es accedida, es probable que las ubicaciones cercanas a ella también sean accedidas pronto. Esto ocurre porque las instrucciones y datos suelen estar organizados de manera secuencial en la memoria, como en el caso de estructuras de datos.

### Ejemplo
```c
for (int i = 0; i < n; i++) {
    sum += array[i];
}

A medida que el índice `i` aumenta, los elementos del arreglo `array` se acceden de forma secuencial, mostrando localidad espacial.
```

