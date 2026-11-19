Sistema de detección de fatiga y distracción en conductores mediante visión artificial

Descripción

VigilaDriver es un sistema desarrollado en Python que utiliza técnicas de visión artificial para detectar posibles estados de fatiga y distracción en conductores mediante el análisis facial en tiempo real.

El sistema utiliza una cámara para capturar imágenes del rostro y procesarlas mediante herramientas de visión artificial, permitiendo identificar indicadores relacionados con el comportamiento del conductor.

Tecnologías utilizadas

Python 3.11

OpenCV

MediaPipe

NumPy

Flask

Matplotlib

Requisitos previos

Antes de ejecutar el proyecto, es necesario contar con:

Python 3.11 instalado.

Git instalado.

Una cámara web.

Conexión a Internet para instalar las dependencias.

Instalación y configuración

1. Clonar el repositorio

Abrir una terminal y ejecutar:

git clone https://github.com/patito07/Proyecto-INS-600.git

2. Ingresar a la carpeta del proyecto

cd Proyecto-INS-600

3. Crear el entorno virtual

Crear un entorno virtual para instalar las dependencias sin afectar otras instalaciones de Python:

python -m venv venv

4. Activar el entorno virtual

Windows PowerShell:

.\venv\Scripts\Activate.ps1

Si PowerShell bloquea la ejecución de scripts, utilizar:

Set-ExecutionPolicy -Scope Process -ExecutionPolicy RemoteSigned

Después volver a ejecutar:

.\venv\Scripts\Activate.ps1

Windows CMD:

venv\Scripts\activate.bat

Cuando el entorno esté activado, aparecerá (venv) al inicio de la terminal.

5. Actualizar pip

python -m pip install --upgrade pip

6. Instalar las librerías necesarias

Ejecutar:

pip install -r requirements.txt

Este comando instalará las dependencias necesarias para ejecutar VigilaDriver.

7. Ejecutar el sistema

Una vez instaladas las dependencias, ejecutar:

python main.py

Estructura del proyecto

Proyecto-INS-600/
│
├── core/
│   └── Módulos principales del sistema
│
├── VISION/
│   └── Procesamiento y detección facial
│
├── INTERFACES/
│   └── Interfaz y servidor del sistema
│
├── templates/
│   └── Plantillas HTML
│
├── static/
│   └── Archivos estáticos
│
├── main.py
├── requirements.txt
├── README.md
└── .gitignore

La estructura puede variar según los módulos incluidos en el repositorio.

Consideraciones

No es necesario descargar ni subir la carpeta venv.

Cada usuario debe crear su propio entorno virtual.

Se recomienda utilizar Python 3.11 para mantener la compatibilidad de las dependencias.

Es necesario disponer de una cámara para realizar las pruebas de detección.

La carpeta venv está excluida del repositorio mediante .gitignore.

Autor

Proyecto desarrollado como parte de la formación académica de la carrera de Informática Industrial.

Institución: Escuela Industrial Superior Pedro Domingo Murillo
Carrera: Informática Industrial
Proyecto: VigilaDriver
