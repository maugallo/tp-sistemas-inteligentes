# TP de Sistemas Inteligentes - USAL

Este repositorio contiene el Trabajo Práctico para la materia de Sistemas Inteligentes de la Universidad del Salvador (USAL). El proyecto se divide en tres partes principales, cada una abordando una tarea de Machine Learning diferente.

## Estructura del Proyecto

- **/datasets**: Carpeta que se debe crear manualmente y donde se almacenarán los datasets utilizados.
- **/notebooks**: Contiene los Jupyter Notebooks con el código y análisis de cada tarea.
---

## Configuración del Entorno Local

Para poder ejecutar los notebooks en tu máquina local, sigue estos pasos:

### 1. Descomprimir los Datasets

Todos los archivos de datos (`.csv`) se descargan de https://drive.google.com/drive/folders/1HAoXhtUHhzOqoj5T-qR8pzm1K57tJLGc?usp=drive_link.
**Se debe descomprimir el archivo .zip en la raíz de la carpeta `/datasets`** para que los notebooks puedan encontrar los CSVs necesarios.

### 2. Instalar las Dependencias

Este proyecto utiliza un entorno virtual de Python. Para instalar todas las librerías y dependencias necesarias, ejecuta el siguiente comando en tu terminal desde la raíz del proyecto:

```bash
pip install -r requirements.txt
```

Esto leerá el archivo `requirements.txt` y instalará las versiones correctas de las librerías utilizadas.

---

## 1. Clasificación (TP Individual)

- **Notebook**: `notebooks/clasification.ipynb`
- **Dataset**: `datasets/personality.csv`

### Descripción
En este notebook, se realiza una tarea de **clasificación binaria** para predecir si una persona es introvertida o extrovertida. Se aplican técnicas de limpieza de datos, transformación y escalado, y se entrenan y evalúan tres modelos: **Regresión Logística**, **Random Forest** y **K-Nearest Neighbors**.

---

## 2. Regresión (TP Grupal)

- **Notebook**: `notebooks/regresion.ipynb`
- **Dataset**: `datasets/carprices.csv`

### Descripción
Este notebook aborda un problema de **regresión** para predecir el precio de venta de vehículos (MSRP). Se realiza un análisis exploratorio, preprocesamiento y se entrenan varios modelos de regresión para estimar los precios.

---

## 3. Clustering (TP Grupal)

- **Notebook**: `notebooks/clustering.ipynb`
- **Dataset**: `datasets/countries.csv`

### Descripción
Este notebook utiliza un modelo de **aprendizaje no supervisado de clustering** para separar un dataset de países en distintos grupos de acuerdo con las características que analice el modelo.
