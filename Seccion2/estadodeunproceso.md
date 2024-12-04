## Estado de un Proceso

El estado de un proceso describe la etapa en la que se encuentra dentro de su ciclo de vida en el sistema operativo. Los estados más comunes son:

| Paso | Estado                | Descripción                                                                                   |
|------|-----------------------|-----------------------------------------------------------------------------------------------|
| 1    | **Nuevo**             | El proceso está siendo creado, pero aún no está listo para ejecutarse.                        |
| 2    | **Listo**             | El proceso está en espera de ser asignado al procesador. Tiene todos los recursos necesarios, excepto el acceso al procesador. |
| 3    | **En ejecución**      | El proceso está siendo ejecutado por el procesador. En sistemas con multitarea, solo un proceso puede estar en ejecución por núcleo en un momento dado. |
| 4    | **Bloqueado o en espera** | El proceso está en pausa mientras espera que se complete un evento externo, como la entrada del usuario o la finalización de una operación de entrada/salida. |
| 5    | **Terminado**         | El proceso ha finalizado su ejecución, ya sea porque completó su tarea o porque fue terminado manualmente. |

