
## Permisos de Archivos en UNIX: Explicación y Ejemplos con chmod

Los permisos de archivos en UNIX determinan quién puede leer, escribir o ejecutar un archivo o directorio. Cada archivo o directorio tiene permisos asociados para tres categorías de usuarios:
- **Propietario**  
- **Grupo**  
- **Otros**  

### Tipos de Permisos
1. **Lectura (r)**: Permite visualizar el contenido del archivo.  
2. **Escritura (w)**: Permite modificar el contenido del archivo.  
3. **Ejecución (x)**: Permite ejecutar un archivo como programa.  

---

## Comando chmod
El comando **chmod** se usa para cambiar los permisos de un archivo o directorio. Existen dos formas principales de usarlo: **notación simbólica** y **notación numérica**.

### 1. Notación Simbólica
Permite modificar permisos mediante letras (`u` = usuario, `g` = grupo, `o` = otros, `a` = todos).  

**Ejemplo**:
```bash
# Agregar permiso de ejecución para el usuario
chmod u+x archivo.sh

# Quitar permiso de escritura para el grupo
chmod g-w archivo.txt

# Dar permiso de lectura a todos
chmod a+r archivo.txt
```

### 2. Notación Numérica
Representa los permisos con números:
- **Lectura (r)** = 4  
- **Escritura (w)** = 2  
- **Ejecución (x)** = 1  

Los permisos se suman para obtener el valor final:
- `7` = Lectura (4) + Escritura (2) + Ejecución (1)  
- `6` = Lectura (4) + Escritura (2)  
- `5` = Lectura (4) + Ejecución (1)  
- `4` = Solo lectura  

**Ejemplo**:
```bash
# Dar permisos de lectura, escritura y ejecución al usuario, y solo lectura al grupo y otros
chmod 744 archivo.sh

# Dar permisos de lectura y escritura al usuario y al grupo, sin permisos para otros
chmod 660 archivo.txt
```

---

### Ejemplo Práctico
Deseas: 
Que el propietario pueda leer, escribir y ejecutarlo, que el grupo pueda solo ejecutarlo, que otros usuarios no tengan permisos.  
 
Usando notación simbólica:
```bash
chmod u+rwx,g+x,o-rwx script.sh
```
Usando notación numérica:
```bash
chmod 751 script.sh
```

---

### Verificar los Permisos
Puedes verificar los permisos de un archivo usando el comando:
```bash
ls -l archivo
```
-----
