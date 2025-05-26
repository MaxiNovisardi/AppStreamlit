
# 🧽 AppStreamlit - Herramienta para Quitar el Fondo de Imágenes

**AppStreamlit** es una solución web desarrollada con Streamlit, diseñada para eliminar automáticamente el fondo de imágenes utilizando modelos de inteligencia artificial.

## 🎯 ¿Qué ofrece?

Una manera rápida y sencilla de quitar el fondo de una imagen sin recurrir a herramientas de edición complicadas como Photoshop.

## 🔧 Características principales

- Subida de imágenes en formatos populares (.jpg, .png, etc.)  
- Eliminación automática del fondo mediante IA  
- Vista previa del resultado en tiempo real  
- Posibilidad de descargar la imagen final sin fondo  

## 🧐 Tecnologías empleadas

- **Lenguaje:** Python  
- **Framework:** Streamlit  
- **Motor de fondo:** RemBG (IA)  
- **Edición de imagen:** Pillow  

## 📂 Organización del proyecto

```
AppStreamlit/
├── app.py               # Código principal de la aplicación
├── requirements.txt     # Dependencias necesarias
├── media/               # Ejemplos de imágenes
├── logo.png             # Imagen del logo
├── README.md            # Documentación general
└── LICENSE              # Licencia del proyecto (Apache 2.0)
```

## 🚀 Pasos para ejecutar la aplicación

Cloná el repositorio:

```bash
git clone https://github.com/manumagallanes/AppStreamlit.git
cd AppStreamlit
```

Instalá los paquetes necesarios:

```bash
pip install -r requirements.txt
```

Lanzá la app:

```bash
streamlit run app.py
```

Accedé desde tu navegador en: [http://localhost:8501](http://localhost:8501)

## 🖼️ ¿Qué vas a ver?

Una interfaz clara y amigable que te permitirá cargar tu imagen, ver el resultado sin fondo y descargarla en formato `.png`.

## 📜 Licencia

Este proyecto está cubierto por la licencia **Apache 2.0**. Consultá el archivo `LICENSE` para más información.

---

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
```