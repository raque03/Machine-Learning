# Neural Networks & Deep Learning

---

> 🧠 Diseño, implementación y optimización de Redes Neuronales Artificiales para tareas de clasificación y regresión.

---

## Índice

- [Contenido del repositorio](#contenido-del-repositorio)  
- [Archivos principales](#archivos-principales)  
- [Contenido teórico](#contenido-teórico)  
- [Enfoque del repositorio](#enfoque-del-repositorio)  
- [Herramientas utilizadas](#herramientas-utilizadas)  

---

## Contenido del repositorio

Este repositorio se enfoca en los fundamentos y la aplicación práctica de las **Redes Neuronales (ANN)**. Explora desde la arquitectura básica de una neurona hasta la implementación de Perceptrones Multicapa (**MLP**) utilizando frameworks de aprendizaje automático.

Se incluyen experimentos sobre:
- Arquitectura de redes neuronales (capas ocultas, neuronas y sesgo).
- Ajuste de hiperparámetros mediante **GridSearchCV** y **RandomizedSearchCV**.
- Visualización de **regiones de decisión** en problemas de clasificación.
- Impacto de la **regularización L2** y la tasa de aprendizaje (*learning rate*).

---

## Archivos principales

### ✦ Notebooks y Scripts

| Archivo | Descripción |
|---|---|
| [Neuronas.ipynb](./Neuronas.ipynb) | Implementación de `MLPClassifier` con búsqueda de hiperparámetros y visualización de regiones de clasificación con Seaborn. |
| [Tiny_nn.ipynb](./Tiny_nn.ipynb) | Exploración interactiva de parámetros (pesos, sesgos) y efectos de la regularización en redes pequeñas. |
| [utils.py](./utils.py) | Funciones auxiliares para la generación de datos sintéticos y visualización de fronteras de decisión. |

---

## Contenido teórico

### 📌 Perceptrón Multicapa (MLP)
Es una arquitectura de red neuronal feedforward que consta de una capa de entrada, una o más capas ocultas y una capa de salida. Utiliza algoritmos de retropropagación (**Backpropagation**) para el entrenamiento.

---

### 📌 Optimización de Hiperparámetros
Uso de técnicas avanzadas para encontrar la configuración óptima del modelo:
- **Grid Search:** Búsqueda exhaustiva sobre un subconjunto específico de parámetros.
- **Random Search:** Selección aleatoria de combinaciones para mayor eficiencia en espacios de búsqueda grandes.

---

### 📌 Regularización y Tuning
Implementación de penalizaciones **L2** para evitar el sobreajuste (*overfitting*) y análisis de cómo la arquitectura (número de neuronas y capas) afecta la capacidad de generalización del modelo.

---

## Enfoque del repositorio

El contenido está orientado a:
- Comprender el funcionamiento matemático de los pesos ($w$) y sesgos ($b$).
- Visualizar cómo una red neuronal "separa" los datos en un espacio N-dimensional.
- Aplicar validación cruzada (**K-Fold**) para asegurar la robustez de los modelos.
- Dominar el flujo de trabajo de entrenamiento y evaluación en Scikit-Learn.

---

## Herramientas utilizadas

<p>
<img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Scikit--Learn-MLP_Classifier-F7931E?logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C"/>
<img src="https://img.shields.io/badge/Seaborn-Statistical_Data_Vis-4C72B0"/>
<img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white"/>
</p>
