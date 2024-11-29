**Un sistema operativo** Es el software que se encarga de gestionar los funcionamientos básicos de las aplicaciones, además de comunicar al hardware con el software. 

   Es un conjunto de programas informáticos que permite la administración eficaz de los recursos de la computadora.

   **Ejemplos**: Windows, Linux, Mac OS, entre otros.

2. 
| **Nivel**            | **Descripción**                                                                                     |
|----------------------|-----------------------------------------------------------------------------------------------------|
| **En los comienzos**  | Los ordenadores eran programados de forma manual. El primer sistema operativo fue desarrollado, permitiendo que varios usuarios se conectaran a él. |
| **Primer Nivel**      | Inicio del lenguaje de programación FORTRAN, se programa en tarjeta perforada y los sistemas operativos son básicos. Se usaban tarjetas perforadas y los sistemas operativos eran básicos. |
| **Segundo Nivel**     | En los años 60, aumento del rendimiento del procesador. Se introducen los procesos on-line (conexión directa) y off-line (uso de dispositivos más rápidos). El aumento de rendimiento del procesador permitió estos avances. |
| **Tercer Nivel**      | En los 70-80 se crean los sistemas operativos de disco, mejorando almacenamiento y accesibilidad. Los procesadores podían ejecutar múltiples programas, lo que permitió mejorar la accesibilidad y el procesamiento. |
| **Cuarto Nivel**      | Desde los años 80 en adelante, se usan multiprocesadores y se mejoran las conexiones en seguridad. Se introdujeron sistemas operativos con interfaz gráfica (Windows, Linux, Mac OS) y adaptación a nuevos dispositivos como consolas y móviles. |


3. **Los administradores de sistemas** son los profesionistas que se encargan de implementar, configurar, mantener, monitorizar, documentar y asegurar el correcto funcionamiento de un sistema.

   Profesionista que configura y mantiene la red y el sistema de una empresa.

4. 
| **Servicio**                  | **Descripción**                                                     |
|-------------------------------|---------------------------------------------------------------------|
| **Gestión de memoria**         | Mejor aprovechamiento del espacio disponible.                      |
| **Gestión de procesos**        | Control eficaz de los procesos, para un mejor rendimiento.         |
| **Gestión del sistema**        | Control en los sistemas de entrada y salida.                       |
| **Gestión de archivos y directorios** | Para un mejor rendimiento y visualización en cuanto a los datos. |


5. **Dispositivos de entrada y de salida**  
   Los dispositivos mandan o reciben datos en ondas eléctricas:

   - **Dispositivos de entrada**: Son los que reciben estas señales, como teclados o el ratón.
   - **Dispositivos de salida**: Son los que mandan la información al usuario de forma que el usuario lo entienda, como TV, bocinas, etc.
   - **Dispositivos mixtos**: Mandan y reciben señales, como la pantalla táctil de un celular.


6. **Manipulación de archivos y directorios**  
   Variedad de comandos para la manipulación:

| **Comando**   | **Descripción**                                                                                         |
|---------------|---------------------------------------------------------------------------------------------------------|
| **pwd**       | Muestra la ruta donde estás ubicado.                                                                     |
| **ls**        | Lista el contenido del directorio en el que estás.                                                      |
| **cd <directorio>** | Te lleva al directorio (Debe estar dentro del directorio donde estás ubicado).                      |
| **cd ..**     | Te regresa 1 directorio antes.                                                                           |
| **cp**        | Copia ya sea directorios o archivos.                                                                     |
| **mv**        | Mueve de ubicación a los directorios y archivos.                                                         |
| **rm**        | Puede eliminar ya sea directorios o archivos.                                                           |
| **mkdir**     | Crea directorios.                                                                                       |
| **touch**     | Crea archivos.                                                                                          |
| **rmdir**     | Elimina un directorio solo si este está vacío.                                                           |
| **chmod**     | Cambia los permisos de los archivos y directorios.                                                       |
| **grep**      | Busca en archivos las líneas que coincidan con una expresión regular.                                    |
| **cat**       | Muestra el contenido de un archivo.                                                                      |
| **find**      | Encuentra los archivos que coincidan con un criterio específico.                                          |



7. **Comandos UNIX**  

| **Comando**                  | **Descripción**                                                                                 | **Ejemplo**                                              |
|------------------------------|-------------------------------------------------------------------------------------------------|----------------------------------------------------------|
| **cd <folderName>**           | Sirve para cambiar de directorio según se le índice.                                            | `cd Documents/`                                           |
| **history <number>**          | Muestra el historial de comandos escritos en terminal.                                          | `history 10`                                             |
| **rm <fileName>**             | Elimina un archivo con el nombre indicado.                                                      | `rm Tarea1`                                              |
| **rm -r <folderName>**        | Elimina un directorio.                                                                           | `rm -r Tarea1`                                           |
| **vim <fileName>**            | Abre un archivo con el editor vim.                                                               | `vim Tarea1`                                             |
| **touch <fileName>**          | Crea un archivo con el nombre que se le indica.                                                  | `touch Tarea2`                                           |
| **mkdir <folderName>**        | Crea un directorio en la ruta en la que estés.                                                   | `mkdir Materias`                                         |
| **pwd**                       | Se utiliza para saber la ruta en la que estás.                                                  | `pwd`                                                    |
| **ls**                        | Muestra todos los archivos y directorios que se encuentran en esa ruta.                        | `ls`                                                     |
| **ls -la**                    | Agrega información extra e incluye los archivos ocultos.                                         | `ls -la`                                                 |
| **git init**                  | Inicializa un repositorio de git.                                                                | `git init`                                               |
| **git add .**                 | Agrega todos los cambios nuevos que realizamos al repositorio.                                  | `git add .`                                              |
| **git commit -m “mensaje”**   | Guarda un cambio de nuestro repositorio para subirlo a la nube.                                 | `git commit -m “description of the changes”`             |
| **git push**                  | Sube los cambios al repositorio.                                                                 | `git push`                                               |
| **git pull**                  | Actualiza los datos que fueron subidos por colaboradores.                                        | `git pull`                                               |



8. **VIM, introducción y comandos básicos**

VIM es el editor de texto más usado en Linux, la razón son sus capacidades avanzadas gracias a sus distintas funciones que nos brindan un control excepcional en los documentos.

### Modo Comando:

**VIM <archivo>**: Nos permite editar archivos desde la terminal.

#### Comandos dentro del Modo Comando:

- **Modo Inserción**: Tecla `<i>`, nos permite editar la información del archivo.

(Estos comandos siguientes se ejecutan fuera del Modo Inserción)

- **w**: Nos permite guardar el fichero.
- **q**: Nos permite salir de VIM.
- **q!**: Nos permite salir de VIM descartando cambios no guardados.
- **wq**: Guarda el archivo y sale de VIM.
- **u**: Deshace una acción.
- **Ctrl + r**: Rehace una acción.
- **dd**: Borra la línea donde esté el cursor.
- **\ + texto**: Al pulsar `<\>` entra en modo búsqueda y los caracteres que pongas después los buscará.



9. **Administración de la protección y seguridad en un sistema operativo:**

| **#** | **Descripción**                                                                                                                                 |
|-------|--------------------------------------------------------------------------------------------------------------------------------------------------|
| **1** | **Control de acceso**: Autentifica al usuario mediante contraseñas y otros métodos, luego verifica qué recursos tiene disponibles.              |
| **2** | **Gestión de usuarios y grupos**: Administra a los usuarios en grupos, para organizar los recursos de mejor manera.                             |
| **3** | **Seguridad de archivos y directorios**: Los archivos, al igual que los directorios, se les asignan permisos, como de lectura, escritura y ejecución. La información de ambos es encriptada. |
| **4** | **Protección de memoria**: Permite la protección de la memoria de los distintos procesos que puedan llegar a modificarla.                       |
| **5** | **Mecanismos de seguridad**: Uso de la criptografía en los datos para la confidencialidad, se usan varias técnicas para mantener la integridad de los datos. |
| **6** | **Auditoría y monitoreo**: Registro de los eventos ocurridos y un constante monitoreo.                                                         |
| **7** | **Defensa a amenazas externas**: Uso de firewalls, control en las aplicaciones, actualizaciones y parches de seguridad.                         |
| **8** | **Seguridad en redes**: VPN y protocolos para una mejor seguridad en la red.                                                                   |
| **9** | **Gestión de cuentas y políticas de seguridad**: Políticas en las contraseñas y bloqueo de cuentas.                                             |
| **10**| **Respaldo y recuperación ante desastres**.                                                                                                    |
| **11**| **Defensa en profundidad**: Dividiéndola en capas para un mejor control.                                                                       |

