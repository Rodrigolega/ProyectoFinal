7. Comandos UNIX
(Los comandos sin ejemplos se ponen tal cual estan escritos)

Comandos básicos shell UNIX
cd <folderName> -- Sirve para cambiar de directorio según se le índice.
    Ejemplo: cd Documents/
history <number> -- muestra el historial de comandos escritos en terminal.
    Ejemplo: history 10
rm <fileName> -- Elimina un archivo con el nombre indicado.
    Ejemplo: rm Tarea1
rm -r <folderName> -- Elimina un directorio.
    Ejemplo: rm -r Tarea1
vim <fileName> -- Abre un archivo con el editor vim.
    Ejemplos: vim Tarea1
touch <fileName> -- Crea un archivo con el nombre que se le indica.
    Ejemplo: touch Tarea2
mkdir <folderName> -- Crea un directorio en la ruta en la que estes.
    Ejemplo: mkdir Materias
pwd -- Se utiliza saber la ruta en la que estas.
ls -- muestra todos los archivos y directorios que se encuentran en esa ruta.
ls -la -- Agrega información extra e incluye los archivos ocultos.
git init -- Inicializa un repositorio de git.
git add . -- Agrega todos los cambios nuevos que realizamos al repositorio.
git commit -m “mensaje” -- Guarda un cambio de nuestro repositorio para subirlo a la nube.
    Ejemplo: git commit -m “description of the changes”
git push -- Sube los cambios al repositorio.
git pull -- Actualiza los datos que fueron subidos por colaboradores.