# 🛠️ png-to-ico 

Script que convierte automáticamente todos sus archivos `.png` en iconos `.ico` compatibles con entornos Windows.
Este script se desarrolló con el objetivo de automatizar el proceso de creación de ficheros `.ico` evitando tener que pasar por una páginas web para realizar la conversión.

## 🚀 Características
El script `png-to-ico` pretende llevar a cabo las siguientes tareas de forma metódica:

<!-- Imágen generada y exportada con Excalidraw -->
![](/assets/workflow.png)

> Este script genera un directorio `output` dentro de la raíz del proyecto. Por lo que si por ejemplo ud. ha clonado el repositorio en una carpeta llamada `files-png` en la que en su interior se incluyen algunas imágenes en formato png. El script genera un nuevo directorio `files-png/output`, en el que se incluyen todos los `.png` convertidos a `.ico`, mediante esa automatización.

Este conjunto de acciones se puede desarrollar como:
1) 🔍 Escanéar automáticamente todos los `.png` que tenemos en el directorio actual.
2) 💾 Generar todos los `.ico` en un directorio de salida llamado `output` dentro del proyecto.
3) 🧪 (Próximas mejoras) Integración en un paquete instalable vía `pip install png-to-ico`
4) ⚡ (Próximas mejoras) Se podrá utilizar desde línea de comandos.

## 📦 Instalación Repo
Si dispone de una terminal con WSL (muy recomendable), ejecute:
```WSL
# Clonar el repositorio en la raíz
git clone https://github.com/fran-hidalgo/png-to-ico.git

# Instalar dependencias en el entorno virtual para evitar conflictos
setup.sh
```

