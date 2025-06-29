# TP de Sistemas Inteligentes - USAL

Este repositorio contiene el Trabajo Práctico para la materia de Sistemas Inteligentes de la Universidad del Salvador (USAL). El proyecto se divide en tres partes principales, cada una abordando una tarea de Machine Learning diferente.

## Estructura del Proyecto

- **/datasets**: Contiene un archivo `datasets.zip` con todos los CSV utilizados.
- **/notebooks**: Contiene los Jupyter Notebooks con el código y análisis de cada tarea.
- **/informe**: Contiene los informes en formato .docx que detallan los hallazgos y conclusiones.

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
- **Informe**: `informe/TP Individual - Clasificación.docx`

### Descripción
En este notebook, se realiza una tarea de **clasificación binaria** para predecir si una persona es introvertida o extrovertida. Se aplican técnicas de limpieza de datos, transformación y escalado, y se entrenan y evalúan tres modelos: **Regresión Logística**, **Random Forest** y **K-Nearest Neighbors**.

---

## 2. Regresión (TP Grupal)

- **Notebook**: `notebooks/regresion.ipynb`
- **Dataset**: `datasets/carprices.csv`
- **Informe**: `informe/TP Grupal - Regresión.docx`

### Descripción
Este notebook aborda un problema de **regresión** para predecir el precio de venta de vehículos (MSRP). Se realiza un análisis exploratorio, preprocesamiento y se entrenan varios modelos de regresión para estimar los precios.

---

## 3. Aprendizaje No Supervisado (TP Grupal)

- **Notebook**: `notebooks/unsupervised.ipynb`
- **Dataset**: `datasets/creditcard.csv`
- **Informe**: `informe/TP Grupal - Aprendizaje No Supervisado.docx`

### Descripción
Se explora la **detección de anomalías** en transacciones de tarjetas de crédito. Utilizando **Isolation Forest**, el modelo identifica transacciones fraudulentas sin supervisión previa.
