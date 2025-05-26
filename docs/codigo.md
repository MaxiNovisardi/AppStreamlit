# 🔍 Explorando el Código Fuente

Este documento detalla cómo está organizado el código de **AppStreamlit** y los archivos clave para su funcionamiento.

## 📄 Archivos esenciales

### `app.py`

Este es el archivo principal, donde ocurre toda la acción:

- Se configura la interfaz gráfica con Streamlit  
- Se permite la carga de imágenes del usuario  
- Se ejecuta el motor de RemBG para eliminar el fondo  
- Se muestra el resultado y se ofrece la descarga  

### `requirements.txt`

Contiene los paquetes necesarios para ejecutar el proyecto. Incluye:

- `streamlit` — Para crear la interfaz  
- `rembg` — Inteligencia artificial para la segmentación del fondo  
- `Pillow` — Para el procesamiento de imágenes  

## 📦 Instalación de dependencias

```bash
pip install -r requirements.txt
