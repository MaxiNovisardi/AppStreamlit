# Background Removal App

A Streamlit application that allows users to upload an image and automatically remove its background using the [rembg](https://github.com/danielgatis/rembg) library.

## Features

- Upload images (PNG, JPG, JPEG formats supported)
- Automatic background removal
- Download the processed image
- Handles large images with automatic resizing
- Progress indicators for better user experience

## Getting Started

### Prerequisites

- Python 3.8+
- pip

### Installation (Local Python)

1. Clone the repository
```bash
git https://github.com/MaxiNovisardi/AppStreamlit.git
cd BackgroundRemoval
```

2. Create a virtual environment (optional but recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

### Running the App

```bash
streamlit run bg_remove.py
```

The app will be available at http://localhost:8501 in your web browser.

---

## 🐳 Running with Docker

### Requirements

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/)

### Steps

1. Build and run the container:

```bash
docker-compose up --build
```

2. Access the app at:

```
http://localhost:8501
```

The container uses `bg_remove.py` as the entry point and exposes port `8501` for the Streamlit interface.

---

## Usage Guidelines

- Maximum file size: 10MB
- Large images will be automatically resized for processing
- Supported formats: PNG, JPG, JPEG

## License

MIT