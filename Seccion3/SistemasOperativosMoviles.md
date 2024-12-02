## Sistemas Operativos Móviles: Emulador de Android

Un emulador de Android es una herramienta de software que permite simular un dispositivo Android en un computador. Se utiliza para desarrollar, probar y depurar aplicaciones en diferentes versiones y configuraciones de Android sin necesidad de hardware físico.

Es ideal para desarrolladores que no tienen acceso a múltiples dispositivos físicos.  
El emulador puede ser lento en computadoras con recursos limitados.

---

### **Características del Emulador de Android**:

   - Reproduce el comportamiento de un dispositivo Android.

   - Permite probar aplicaciones en diversas versiones del sistema operativo Android, desde las más antiguas hasta las más recientes.

   - Soporte para cámara, GPS, sensores, red, almacenamiento, etc.

-----

### **Ejemplo**:

```java
import android.os.Bundle;
import androidx.appcompat.app.AppCompatActivity;

public class MainActivity extends AppCompatActivity {
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
        System.out.println("¡Hola desde el Emulador de Android!");
    }
}

#Cuando ejecutas esta aplicación en el emulador, verás el mensaje en la consola.
```

-----
