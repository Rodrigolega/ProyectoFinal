## Comandos UNIX para la Administración de Procesos

Los comandos en UNIX para la administración de procesos permiten listar, controlar y administrar los procesos del sistema. 

### 1. `ps`
Muestra información sobre los procesos en ejecución.
- `ps`: Muestra los procesos en ejecución en la terminal actual.
- `ps aux`: Lista todos los procesos del sistema con detalles.
- `ps -ef`: Muestra los procesos en un formato extendido.

### 2. `top`
Proporciona una vista interactiva en tiempo real de los procesos .
- Útil para monitorizar el uso de CPU, memoria y otros recursos.

### 3. `htop`
Similar a `top`, pero con una interfaz más amigable.

### 4. `kill`
Finaliza un proceso utilizando su PID.
- `kill <PID>`: Envía una señal para terminar el proceso con el PID especificado.
- `kill -9 <PID>`: Fuerza la terminación del proceso.

### 5. `pkill`
Mata procesos basándose en su nombre en lugar de su PID.
- `pkill <nombre_del_proceso>`: Termina todos los procesos que coincidan con el nombre dado.

### 6. `bg`
Mueve un proceso detenido al segundo plano para que continúe ejecutándose.
- `bg %<número_del_trabajo>`: Reanuda un trabajo en segundo plano.

### 7. `nice` y `renice`
Ajustan la prioridad de un proceso.
- `nice -n <prioridad> <comando>`: Inicia un proceso con una prioridad específica.
- `renice <prioridad> -p <PID>`: Cambia la prioridad de un proceso en ejecución.

### 8. `nohup`
Permite ejecutar un proceso que continúa funcionando incluso después de cerrar la sesión.
- `nohup <comando> &`: Ejecuta el comando en segundo plano.

### 9. `at` y `cron`
Programan tareas para ejecutarse en el futuro.
- `at <hora>`: Programa un comando para ejecutarse una vez.
- `crontab -e`: Configura tareas periódicas.
