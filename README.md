# Clasificación de Imágenes de COVID-19 con Redes Neuronales Convolucionales

Este repositorio contiene un estudio y la implementación de modelos de **Redes Neuronales Convolucionales (CNN)** para la clasificación automática de imágenes de radiografías de tórax en diferentes categorías, incluyendo **COVID-19**, **NORMAL**, **PNEUMONÍA** y **Lung Opacity**. 

El proyecto utiliza el conjunto de datos *COVID-19 Radiography Dataset* con técnicas de procesamiento de imágenes, aumento de datos y optimización de hiperparámetros para lograr un modelo de clasificación robusto.

---


## 📝 Descripción del Proyecto

La clasificación de radiografías de tórax es una herramienta clave en la detección y diagnóstico de enfermedades respiratorias como el **COVID-19** y la **neumonía**. Mediante el uso de Redes Neuronales Convolucionales (CNN), este proyecto busca:

- Automatizar la clasificación de imágenes en las categorías:
  - **COVID-19**
  - **NORMAL**
  - **PNEUMONÍA**
  - **Lung Opacity**
- Optimizar el rendimiento del modelo mediante técnicas de *data augmentation* y ajustes de hiperparámetros.
- Evaluar el desempeño del modelo con métricas como **precisión**, **recall**, **F1-score** y **matriz de confusión**.

---

## 📊 Conjunto de Datos

Se utilizó el conjunto de datos público **COVID-19 Radiography Dataset**, disponible en [Kaggle](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database). El dataset contiene imágenes clasificadas en cuatro clases: 

- **COVID-19**
- **NORMAL**
- **PNEUMONÍA**
- **Lung Opacity**

---

## 🚀 Instalación y Ejecución

### 1. Clonar el repositorio
```bash
git clone https://github.com/martacuevasr/Clasificacion-de-imagenes-de-COVID-19.git
cd Clasificacion-COVID19
