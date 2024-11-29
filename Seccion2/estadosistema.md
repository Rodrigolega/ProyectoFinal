# Leer el estado del sistema (Administrador de tareas y comandos UNIX equivalentes)

Existen varios comandos que permiten monitorear y gestionar el estado del sistema. Estos comandos ayudan a organizar cómo se usan los recursos del dispositivo y son muy útiles para decidir qué procesos o servicios utilizar o detener. A continuación, se describen algunos de los comandos más comunes:

## 1. `top`
Muestra una lista continuamente actualizada de los procesos del sistema, ordenados por actividad de la CPU. Es especialmente útil para identificar qué procesos están consumiendo más recursos.

````
c
top
````
## 2. ps
Proporciona información sobre los procesos en ejecución. Usando diferentes opciones, puedes obtener más detalles sobre cada proceso.

Por ejemplo, para listar todos los procesos con información detallada, puedes usar:
````
ps aux
````
## 3. htop
Es similar a top, pero ofrece una interfaz más amigable con opciones de navegación avanzadas. Antes de usarlo, necesitarás instalarlo.

Para instalarlo en sistemas basados en Debian, usa:
````
c
sudo apt-get install htop
````
y para ejecutarlo:
````
c
htop
````
## 4. df
Muestra información sobre el uso del espacio en disco de los sistemas de archivos montados.

Por ejemplo, para mostrar los datos en un formato legible para humanos:
````
c
df -h
````
## 5. du
Permite visualizar el uso del espacio en disco por directorios y subdirectorios.

Por ejemplo, para ver el tamaño de un directorio específico de forma legible:
````
c
du -h /ruta/del/directorio
````
