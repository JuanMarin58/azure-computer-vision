# Azure Computer Vision - Proyecto de Análisis y Detección de Objetos

## Descripción

Este proyecto utiliza el servicio de Azure Computer Vision para analizar imágenes, detectar objetos y generar etiquetas descriptivas.  

Incluye:  
- Código para enviar imágenes a la API y obtener resultados detallados.  
- Visualización de imágenes con bounding boxes y etiquetas.  
- Ejemplos para interpretar los datos y facilitar la toma de decisiones.

Ideal para desarrolladores, ingenieros y equipos que quieran integrar análisis visual avanzado en sus soluciones con tecnología de Microsoft Azure.

---

## Requisitos

- Python 3.7 o superior  
- Librerías: requests, matplotlib, numpy, pillow, python-dotenv  
- Cuenta activa de Azure con servicio Computer Vision y clave de suscripción  

---

## Instalación

1. Clonar este repositorio:

```bash
git clone https://github.com/tu_usuario/azure-computer-vision.git
cd azure-computer-vision
```

2. Instalar dependencias:

```bash
pip install -r requirements.txt
```

---

## Uso

1. Abre el archivo `azure_computer_vision.ipynb` en VS Code, Jupyter Notebook o Jupyter Lab.

2. Instala las librerías necesarias (si no las tienes) con:

```bash
pip install -r requirements.txt
```

3. Ejecuta las celdas del notebook paso a paso para realizar el análisis de imágenes.

4. Dentro del notebook, modifica la variable `imagen_path` para cambiar la imagen que deseas analizar.

---

## Ejemplo de resultados

Al ejecutar el análisis sobre una imagen, el sistema mostrará en consola:

- Los objetos detectados y su confianza.  
- Las etiquetas generales encontradas en la imagen.  

Además, se abrirá una ventana con la imagen y los bounding boxes resaltando los objetos detectados.
