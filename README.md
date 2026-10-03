# 🛒 Análisis de E-Commerce Brasileño - Olist Store

## 📋 Descripción del Proyecto

Análisis exploratorio y predictivo del conjunto de datos público de comercio electrónico brasileño de **Olist Store**, que contiene información de **100,000 pedidos** realizados entre **2016 y 2018** en diversos mercados de Brasil.

## 🎯 Objetivos del Análisis

Este proyecto aborda cinco dimensiones clave del negocio:

1. **🗣️ Análisis de Sentimiento (PLN)** - Procesamiento de lenguaje natural en reseñas de clientes
2. **📈 Predicción de Ventas** - Modelos de series de tiempo (ARIMA) para forecasting
3. **🚚 Rendimiento de Entregas** - Análisis de tiempos y cumplimiento logístico
4. **⭐ Calidad de Productos** - Evaluación por categoría de producto
5. **🎯 Segmentación de Clientes** - Clustering con K-Means para perfiles de compradores

## ️ Tecnologías Utilizadas

- **Lenguaje:** Python 3.x
- **Análisis de datos:** Pandas, NumPy
- **Visualización:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn (KMeans, PCA, StandardScaler)
- **Procesamiento de Lenguaje Natural:** NLTK, TextBlob, WordCloud
- **Series de tiempo:** Statsmodels (ARIMA, seasonal_decompose)

## 📁 Estructura del Proyecto

olist-brazilian-ecommerce-analysis/
├── src/ # Código fuente modular
├── Comercio electrónico brasileño Olist.ipynb # Notebook principal
├── .gitignore # Archivos excluidos del repositorio
└── README.md # Este archivo


## 📥 Datos

Los datasets utilizados provienen de [Kaggle - Brazilian E-Commerce by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce). 


## 📊 Hallazgos Principales

- Olist creció de 0 a ~1M R$/mes entre 2016 y 2018, con un pico en Black Friday
- El 90% de las reseñas son neutrales (sin texto), limitando el análisis cualitativo
- La mayoría de entregas llegan antes de lo estimado, pero existe disparidad regional
- No hay correlación directa entre precio y satisfacción del cliente
- Se identificaron 4 segmentos de clientes: VIP, Insatisfechos, Mayoría y Frecuentes

## 👤 Autor

Jairo Alonso Gualteros Ortiz  
Analista de Datos | https://www.linkedin.com/in/jairo-alonso-gualteros-ortiz-595541b2/ | jairoalonsogualterosortiz@gmail.com