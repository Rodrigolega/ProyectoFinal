## Comandos adicinonales de Unix

### Uso de Wildcards
Los wildcards son caracteres especiales que permiten hacer coincidir múltiples archivos o directorios.

- **Asterisco (*)**: Coincide con cualquier número de caracteres.
  ```bash
  ls *.txt  # Lista todos los archivos que terminan en .txt
  
- Interrogación (?): Coincide con un solo carácter.
  ```bash
  ls file?.txt  # Coincide con file1.txt, file2.txt

- Corchetes ([ ]): Coincide con cualquier carácter dentro de los corchetes.
  ```bash
  ls file[1-3].txt  # Coincide con file1.txt, file2.txt, file3.txt

---

### Comando rm
El comando rm se usa para eliminar archivos o directorios.

Eliminar un archivo:
  ```bash
rm archivo.txt
```

Eliminar todos los archivos con una extensión específica:
  ```bash
rm *.log  # Elimina todos los archivos .log
```

---

### Comando mv
El comando mv se usa para mover o renombrar archivos o directorios.

Mover un archivo a otro directorio:
  ```bash
mv archivo.txt /ruta/al/nuevo/directorio/
```

Renombrar un archivo:
  ```bash
mv viejo_nombre.txt nuevo_nombre.txt
```

---

### Comando ls
El comando ls se usa para listar archivos y directorios.

Listar todos los archivos en el directorio actual:
  ```bash
ls
```

Listar archivos con detalles adicionales:
  ```bash
ls -l
```

Listar archivos incluyendo archivos ocultos:
  ```bash
ls -a
```

---

### Obtener el peso ordenado de archivos
Para obtener el tamaño de los archivos y ordenarlos por tamaño, puedes usar el comando du junto con sort.

Listar archivos en el directorio actual ordenados por tamaño:
  ```bash
du -sh * | sort -h
```

Listar archivos en todos los subdirectorios ordenados por tamaño:
  ```bash
du -ah . | sort -h
