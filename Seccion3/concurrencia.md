## Concurrencia

La concurrencia se refiere a la capacidad de un sistema para ejecutar múltiples tareas de manera simultánea o intercalada. Estas tareas pueden ser procesos o hilos que comparten recursos del sistema, como el procesador o la memoria.

Aunque las tareas se ejecutan en paralelo (si hay varios núcleos) o se intercalan rápidamente (en sistemas de un solo núcleo), el objetivo principal es optimizar el uso de los recursos y mejorar la eficiencia general del sistema.

---

### Características principales de la concurrencia

1. **Simultaneidad:** Dos o más tareas pueden progresar al mismo tiempo.
2. **Intercalado:** En sistemas con un solo procesador, las tareas se dividen en pequeños intervalos de tiempo y se ejecutan de manera alternada.

---

### Ejemplo 

Imagina que tienes un procesador y dos tareas, **Tarea A** y **Tarea B**, que deben completarse. En un sistema concurrente, estas tareas se dividen en fragmentos más pequeños y se intercalan en el tiempo, en lugar de completarse una después de la otra.

| **Tiempo** | **CPU ejecuta**          |    
|------------|--------------------------|
| 1 ms       | Fragmento de Tarea A     |
| 2 ms       | Fragmento de Tarea B     |
| 3 ms       | Fragmento de Tarea A     |
| 4 ms       | Fragmento de Tarea B     |

#### Tabla de ejecución en un sistema paralelo

| **Tiempo** | **CPU Núcleo 1**       | **CPU Núcleo 2**       |
|------------|------------------------|------------------------|
| 1 ms       | Fragmento de Tarea A   | Fragmento de Tarea B   |
| 2 ms       | Fragmento de Tarea A   | Fragmento de Tarea B   |
| 3 ms       | Fragmento de Tarea A   | Fragmento de Tarea B   |
| 4 ms       | Fragmento de Tarea A   | Fragmento de Tarea B   |


---
