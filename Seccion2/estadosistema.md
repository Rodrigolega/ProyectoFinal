10) Leer el estado del sistema (Administrador de tareas y comandos UNIX equivalentes).
hay varios comandos que te ayudan a monitorear y gestionar el estado del sistema, esto con el fin de organizar como se usan los recursos de tu dispositivo, es muy util a la hora de decidir que quieres usar y que no, algunos de los comandos son:

1) top: Muestra una lista continuamente actualizada de los procesos del sistema en orden de actividad de la CPU. Es muy útil para ver qué procesos están consumiendo más recursos.
top

2) ps: Muestra información sobre los procesos que se están ejecutando. Puedes usar diferentes opciones para obtener más detalles.
ps aux

3) htop: Similar a top, pero con una interfaz más amigable y opciones de navegación más avanzadas. Necesitarás instalarlo primero.
sudo apt-get install htop
htop

4) df: Muestra el uso del espacio en disco de los sistemas de archivos montados.
df -h

5) du: Muestra el uso del espacio en disco de los directorios y sus subdirectorios.
du -h /ruta/del/directorio

6) free: Muestra la cantidad de memoria libre y usada en el sistema.
free -h

estos comandos ayudaran al usuario a tener un desempeño mas eficaz de su dispositivo.



