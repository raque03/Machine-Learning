# Curso Machine Learning

---

> 🤖 Modelos de aprendizaje automático enfocados en regresión, clasificación y reducción de dimensionalidad.

---

## Índice

- [Contenido del repositorio](#contenido-del-repositorio)  
- [Archivos principales](#archivos-principales)  
- [Contenido teórico](#contenido-teórico)  
- [Enfoque del repositorio](#enfoque-del-repositorio)  
- [Herramientas utilizadas](#️herramientas-utilizadas)  

---

## Contenido del repositorio

Este repositorio contiene material práctico y teórico sobre **Machine Learning**, enfocado en la implementación de modelos supervisados, técnicas de regularización y métodos de reducción de dimensionalidad.

Se trabajan ejemplos aplicados utilizando datasets reales, permitiendo entender tanto la teoría como la implementación de modelos como regresión lineal, regresión logística, LDA, PCA y redes neuronales.

El contenido combina notebooks de código con apuntes teóricos detallados en PDF.

---

## Archivos principales

### ✦ Modelos de regresión

| Archivo | Descripción |
|---|---|
| [regresion_01.ipynb](./regresion_01.ipynb) | Introducción a regresión lineal |
| [Ejemplo_de_regresión_múltiple.ipynb](./Ejemplo_de_regresión_múltiple.ipynb) | Implementación de regresión múltiple |
| [Multiple Linear Regression Exercise Solution.ipynb](./MultipleLinearRegressionExerciseSolution.ipynb) | Resolución completa de ejercicio de regresión |
| [Regresión.pdf](./Regresión.pdf) | Fundamentos teóricos de regresión lineal :contentReference[oaicite:0]{index=0} |
| [Regresión_Lineal_Múltiple.pdf](./Regresión_Lineal_Múltiple.pdf) | Desarrollo matemático de regresión múltiple :contentReference[oaicite:1]{index=1} |
| [real_estate_price_size_year.csv](./real_estate_price_size_year.csv) | Dataset para modelos de regresión |
| [advertising.csv](./advertising.csv) | Dataset clásico de regresión |
| [50_Startups.csv](./50_Startups.csv) | Dataset de predicción de ganancias |

---

### ✦ Regularización (Ridge y Lasso)

| Archivo | Descripción |
|---|---|
| [Ridge_Lasso.ipynb](./Ridge_Lasso.ipynb) | Implementación de Ridge y Lasso |
| [Ridge_regresion-1.ipynb](./Ridge_regresion-1.ipynb) | Aplicación práctica de regularización |
| [Ridge Regression and Lasso.pdf](./RidgeRegressionandLasso.pdf) | Desarrollo teórico completo de regularización :contentReference[oaicite:2]{index=2} |

---

### ✦ Clasificación

| Archivo | Descripción |
|---|---|
| [Regresion_logistica.ipynb](./Regresion_logistica.ipynb) | Modelo de clasificación con regresión logística |
| [LDA_01.ipynb](./LDA_01.ipynb) | Implementación de Análisis Discriminante Lineal |
| [LDA_1.pdf](./LDA_1.pdf) | Fundamentos teóricos de LDA |

---

### ✦ Reducción de dimensionalidad

| Archivo | Descripción |
|---|---|
| [PCA_ejemplo.ipynb](./PCA_ejemplo.ipynb) | Ejemplo básico de PCA |
| [PCA_Implementacion.ipynb](./PCA_Implementacion.ipynb) | Implementación paso a paso |
| [PCA y Regresión.ipynb](./PCAyRegresión.ipynb) | Integración de PCA con modelos predictivos |

---

### ✦ Modelos avanzados

| Archivo | Descripción |
|---|---|
| [QDA.ipynb](./QDA.ipynb) | Clasificación con Quadratic Discriminant Analysis |
| [LSTM.ipynb](./LSTM.ipynb) | Introducción a redes neuronales recurrentes |

---

## Contenido teórico

### 📌 Regresión lineal

Modelos que buscan explicar la relación entre variables mediante combinaciones lineales.  
En los apuntes se muestran hipótesis como homocedasticidad, independencia y normalidad de los errores :contentReference[oaicite:3]{index=3}.

---

### 📌 Regresión múltiple

Extensión del modelo lineal a múltiples variables explicativas, resolviendo el sistema mediante mínimos cuadrados y ecuaciones normales :contentReference[oaicite:4]{index=4}.

---

### 📌 Regularización (Ridge y Lasso)

Técnicas que penalizan los coeficientes del modelo para evitar sobreajuste:

- Ridge: penalización L2  
- Lasso: penalización L1 (selección de variables)  

Incluye desarrollo matemático completo y algoritmos de optimización :contentReference[oaicite:5]{index=5}.

---

### 📌 Clasificación

Modelos para predecir clases:

- Regresión logística  
- LDA (reducción de dimensión + clasificación)  
- QDA (fronteras cuadráticas)  

---

### 📌 Reducción de dimensionalidad

PCA permite transformar variables correlacionadas en componentes ortogonales, reduciendo dimensionalidad sin perder información relevante.

---

### 📌 Redes neuronales

Introducción a modelos LSTM para datos secuenciales y series de tiempo.

---

## Enfoque del repositorio

El contenido está orientado a:

- Comprender fundamentos matemáticos del Machine Learning  
- Implementar modelos en Python  
- Analizar datasets reales  
- Comparar distintos enfoques (regresión, clasificación, reducción)  
- Integrar teoría con práctica  

---

## Herramientas utilizadas

<p>
<img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?logo=numpy"/>
<img src="https://img.shields.io/badge/Pandas-150458?logo=pandas"/>
<img src="https://img.shields.io/badge/Scikit--Learn-ML-orange"/>
<img src="https://img.shields.io/badge/Matplotlib-Visualization-blue"/>
<img src="https://img.shields.io/badge/Seaborn-Statistical-blue"/>
<img src="https://img.shields.io/badge/TensorFlow-DeepLearning-orange"/>
<img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white"/>
</p>

---
