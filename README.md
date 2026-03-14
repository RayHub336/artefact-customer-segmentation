# artefact-customer-segmentation
# Desafío Técnico Artefact: Segmentación de Clientes B2C

Este repositorio contiene la resolución del desafío técnico de Data Science para la segmentación de usuarios de un e-commerce utilizando datos de Google Analytics.

## 📌 Estructura del Proyecto
- **`notebooks/`**: Contiene el Jupyter Notebook con el código paso a paso (EDA, preprocesamiento y modelado con K-Means y K-Prototypes).
- **`report/`**: Contiene el informe ejecutivo en PDF con los hallazgos de negocio y recomendaciones.
- **`data/`**: Dataset original utilizado para el análisis.

## 🚀 Cómo ejecutar este proyecto
1. Clona este repositorio.
2. Instala las dependencias necesarias ejecutando: `pip install -r requirements.txt` (Nota: Se requiere la librería `kmodes` para el modelo final).
3. Ejecuta el notebook principal ubicado en la carpeta `notebooks/`.

## 🧠 Enfoque Metodológico
Se implementó un enfoque de **K-Prototypes** para manejar la alta dimensionalidad de variables categóricas (One-Hot Encoding bias) que limitaban al algoritmo tradicional de K-Means, logrando descubrir 5 "Buyer Personas" basados en intención y comportamiento real.
