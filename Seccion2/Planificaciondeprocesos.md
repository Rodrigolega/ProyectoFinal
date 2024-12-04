## Planificación de Procesos

| Paso | Algoritmo       | Descripción                                                                                   |
|------|-----------------|-----------------------------------------------------------------------------------------------|
| 1    | **FCFS**        | First-Come, First-Served: Los procesos se ejecutan en el orden en que llegan.                 |
| 2    | **Round Robin** | Cada proceso recibe un tiempo fijo para ejecutarse, alternando entre todos los procesos. |
| 3    | **SJF**         | Shortest Job First: El proceso con el menor tiempo de ejecución se selecciona primero.        |

-----

### Ejemplo de FCFS (First-Come, First-Served)

Procesos: P1, P2, P3  
Tiempos de llegada: 0, 2, 4  
Tiempos de ejecución: 5, 3, 1

| Orden | Proceso | Tiempo de Ejecución |
|-------|---------|---------------------|
| 1     | P1      | 0-5                 |
| 2     | P2      | 5-8                 |
| 3     | P3      | 8-9                 |

-----

### Ejemplo de Round Robin

Procesos: P1, P2, P3  
Tiempos de llegada: 0, 1, 2  
Tiempos de ejecución: 5, 3, 1  
Quantum: 2

| Orden | Proceso | Tiempo de Ejecución |
|-------|---------|---------------------|
| 1     | P1      | 0-2                 |
| 2     | P2      | 2-4                 |
| 3     | P3      | 4-5                 |
| 4     | P1      | 5-7                 |
| 5     | P2      | 7-8                 |
| 6     | P1      | 8-9                 |

-----

### Ejemplo de SJF (Shortest Job First)

Procesos: P1, P2, P3  
Tiempos de llegada: 0, 2, 4  
Tiempos de ejecución: 5, 3, 1

| Orden | Proceso | Tiempo de Ejecución |
|-------|---------|---------------------|
| 1     | P3      | 4-5                 |
| 2     | P2      | 5-8                 |
| 3     | P1      | 0-5                 |
