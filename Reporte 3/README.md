# Manual de Prácticas Iniciales - Sistemas Operativos

## Objetivos de la Actividad

- Instalar un nuevo Sistema Operativo como alternativa a Windows.
- Aprender el manejo básico de la consola en Ubuntu.
- Introducir a los estudiantes a los conceptos de nube.

Actualmente, la mayoría de los servicios en la nube funcionan con sistemas operativos basados en Linux. Por ello, el enfoque principal de esta actividad es introducir a los estudiantes en el uso de **Ubuntu**.

## ¿Qué es Ubuntu?

Ubuntu es un **sistema operativo de software libre y código abierto**, basado en Debian. Puede ejecutarse en computadoras de escritorio y servidores, con un fuerte enfoque en la facilidad de uso y la experiencia del usuario.

### Características principales:

- **Fácil de usar**
- **Totalmente gratis**
- **Seguro** (no requiere antivirus)
- **Alta personalización**
- **Menores requisitos de sistema**
- **Compatibilidad mejorada y controladores incluidos**

## Instalación de Ubuntu

1. **Descargar Ubuntu**
   - Visita la página oficial: [https://ubuntu.com/download](https://ubuntu.com/download)
   - Descarga la versión adecuada para tu equipo.

2. **Crear un medio de instalación**
   - Graba la imagen ISO en una USB con herramientas como **Rufus** o **balenaEtcher**.

3. **Configurar la BIOS**
   - Arranca desde la USB de instalación.

4. **Instalar Ubuntu**
   - Selecciona "Instalar Ubuntu" y sigue las instrucciones en pantalla.

## Comandos básicos en Ubuntu

### Navegación en la terminal

```bash
pwd   # Muestra la ruta del directorio actual
ls    # Lista los archivos del directorio
cd    # Cambia de directorio
```

### Gestión de archivos y directorios

```bash
mkdir prueba       # Crea un directorio llamado "prueba"
touch archivo.txt  # Crea un archivo vacío
mv archivo.txt prueba/  # Mueve el archivo a la carpeta "prueba"
```

### Gestión de paquetes

```bash
sudo apt update    # Actualiza la lista de paquetes
sudo apt upgrade   # Actualiza los paquetes instalados
sudo apt install apache2  # Instala el servidor Apache2
```

## Simulación de instalación de Apache

1. **Instalar Apache2**
   ```bash
   sudo apt install apache2 -y
   ```

2. **Modificar el archivo de inicio**
   ```bash
   cd /var/www/html/
   sudo nano index.html
   ```
   - Agregar el nombre y número de carnet.

3. **Verificar cambios en el navegador**
   - Acceder a `http://localhost/`.

## Conclusión

Ubuntu es una excelente alternativa a Windows, permitiendo un control avanzado del sistema y facilitando el trabajo en entornos de desarrollo y servidores.


