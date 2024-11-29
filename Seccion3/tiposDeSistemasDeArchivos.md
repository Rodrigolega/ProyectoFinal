## Tipos de Sistemas de Archivos

Un sistema de archivos es una estructura que organiza y almacena datos en dispositivos de almacenamiento como discos duros, SSDs y unidades USB. 

#### Tipos Comunes de Sistemas de Archivos

| **Sistema de Archivos** | **Descripción**                                                                                       | **Plataforma Común**             |
|--------------------------|-------------------------------------------------------------------------------------------------------|-----------------------------------|
| FAT               | Sistema de archivos antiguo pero ampliamente compatible. Soporta archivos de hasta 4 GB y particiones de 8 TB. | Windows, Linux, macOS            |
| NTFS                | Sistema moderno de Windows que soporta archivos grandes y características avanzadas como permisos y compresión. | Windows                          |
| APFS                | Sistema moderno de archivos de Apple, optimizado para SSDs y con mejor gestión de snapshots y seguridad. | macOS                            |
| Btrfs               | Sistema avanzado de Linux con características como snapshots, compresión y RAID nativo.               | Linux                            |

-----

#### Comparación de Características

|  Característica         |  FAT  |  NTFS  |   APFS  |  Btrfs  |
|---------------------------|---------|----------|-----------|-----------|
| Compatibilidad            | Alta    | Media    | Baja      | Baja      |
| Tamaño máximo de archivo  | 4 GB    | 16 EB    | 8 EB      | 16 EB     |
| Tamaño máximo de volumen  | 8 TB    | 256 TB   | 8 EB      | 16 EB     |
| Journaling (registro)     | No      | Sí       |  Sí       | Sí        |
| Seguridad avanzada        | No      | Sí       |  Sí       | Sí        |

-----

#### Selección del Sistema de Archivos

La elección del sistema de archivos depende del uso y del entorno en el que se empleará:

- *FAT*: Ideal para dispositivos USB o discos externos que requieran alta compatibilidad entre sistemas operativos.
- *NTFS*: Recomendado para discos duros en sistemas Windows con necesidad de seguridad y archivos grandes.
- *APFS*: Óptimo para usuarios de macOS con dispositivos modernos y almacenamiento SSD.
- *exFAT*: Perfecto para compartir datos entre diferentes plataformas con archivos grandes.

-----
