# Sistema de Reconocimiento Facial

Este proyecto implementa un sistema de reconocimiento facial en Python utilizando la librería `face_recognition` y `OpenCV`. El sistema identifica rostros en tiempo real utilizando la cámara web, compara los rostros con una base de datos predefinida y registra la hora de ingreso de empleados reconocidos.

## Funcionalidades

- **Reconocimiento facial en tiempo real:** Utiliza la cámara web para detectar y reconocer rostros.
- **Registro de empleados:** Codifica las imágenes de los empleados para identificarlos.
- **Registro de ingresos:** Registra la hora de ingreso de los empleados reconocidos en un archivo CSV.

## Uso

### Requisitos

- Python instalado en el sistema.
- Instalar las librerías requeridas ejecutando `pip install numpy opencv-python face-recognition`.

### Configuración

1. Coloca las imágenes de los empleados en la carpeta "Empleados".
2. Ejecuta el script `reconocimiento_facial.py` para iniciar el reconocimiento facial.

### Comandos

El sistema reconocerá los rostros y realizará acciones según la detección:

- Si el rostro no coincide con ningún empleado, mostrará "No coincide con ninguno".
- Si se reconoce un empleado, mostrará su nombre y registrarán su hora de ingreso en el archivo `registro.csv`.

## Estructura del Proyecto

- **Empleados:** Carpeta que contiene las imágenes de los empleados.
- **registro.csv:** Archivo CSV que almacena el registro de ingresos con el nombre del empleado y la hora de ingreso, recuerda formar el tuyo.

