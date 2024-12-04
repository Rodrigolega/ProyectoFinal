## ¿Qué es un proceso?

Un proceso es una instancia en ejecución de un programa que realiza tareas específicas en un sistema operativo. Representa un programa en movimiento, con recursos asignados como memoria, tiempo del procesador y acceso a dispositivos de entrada/salida.

### Características principales:
1. **Estado**: Un proceso puede estar en diferentes estados como *ejecución*, *espera* o *listo*.
2. **Recursos asociados**: Cada proceso tiene su espacio de memoria, identificador único (PID) y acceso controlado a recursos.
3. **Ciclo de vida**: Un proceso pasa por varias etapas: creación, ejecución y finalización.
4. **Multitarea**: En sistemas modernos, múltiples procesos pueden ejecutarse simultáneamente.

### Ejemplo práctico: Matar un proceso

#### En Windows
1. **Listar los procesos y sus PID**:
- Abre la terminal de Windows y ejecuta:
     ```bash
     tasklist
     ```
- Esto mostrará una lista de procesos en ejecución con su nombre y PID.

2. **Matar un proceso usando el PID**:
- Una vez que tengas el PID del proceso que deseas finalizar, usa el comando:
     ```bash
     taskkill /PID <PID_DEL_PROCESO> /F
     ```
