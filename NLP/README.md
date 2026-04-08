
# Natural Language Processing (NLP)

-----

> 🧠 Implementación de técnicas de procesamiento de texto, análisis de sentimientos y modelos avanzados de lenguaje (LSI, LDA y Embeddings).

-----

## Índice

  - [Contenido del repositorio](https://www.google.com/search?q=%23contenido-del-repositorio)
  - [Archivos principales](https://www.google.com/search?q=%23archivos-principales)
  - [Contenido teórico](https://www.google.com/search?q=%23contenido-te%C3%B3rico)
  - [Enfoque del repositorio](https://www.google.com/search?q=%23enfoque-del-repositorio)
  - [Herramientas utilizadas](https://www.google.com/search?q=%23herramientas-utilizadas)

-----

## Contenido del repositorio

Este repositorio contiene una serie de implementaciones prácticas para el análisis de texto. Se exploran desde las etapas iniciales de limpieza (**Stemming** y **Lemmatization**) hasta la clasificación de sentimientos utilizando vectores de palabras y el descubrimiento de temas ocultos mediante modelos probabilísticos.

Incluye ejercicios prácticos de:

  - Normalización de texto y manejo de **Regex** (Expresiones Regulares).
  - Análisis de sentimientos sobre reseñas reales de **Amazon** e **IMDB**.
  - Uso de **Word Embeddings** con la librería **FastText**.
  - Modelado de temas (Topic Modeling) mediante **LSA/LSI** y **LDA**.

-----

## Archivos principales

### ✦ Notebooks de Implementación

| Archivo | Descripción |
|---|---|
| [MNA\_NLP\_FastText\_embeddings.ipynb](https://www.google.com/search?q=./MNA_NLP_FastText_embeddings.ipynb) | Uso de vectores FastText para clasificación multiclase y análisis de sentimientos. |
| [MNA\_NLP\_Actividad\_semanas\_6y7.ipynb](https://www.google.com/search?q=./MNA_NLP_Actividad_semanas_6y7.ipynb) | Implementación de **Topic Modeling** utilizando algoritmos LSI y LDA. |
| [SENTIMENT\_Movies.ipynb](https://www.google.com/search?q=./SENTIMENT_Movies.ipynb) | Análisis de sentimientos detallado aplicado a reseñas de películas de IMDB con visualizaciones (WordClouds). |
| [Stemming\_lemmatization.ipynb](https://www.google.com/search?q=./Stemming_lemmatization.ipynb) | Comparativa entre técnicas de normalización de tokens y reducción a la raíz. |
| [MNA\_NLP\_ejercicios\_complementarios.ipynb](https://www.google.com/search?q=./MNA_NLP_ejercicios_complementarios.ipynb) | Guía práctica sobre manipulación de Strings y búsqueda de patrones con Regex. |

-----

### ✦ Datasets y Recursos

| Archivo | Descripción |
|---|---|
| [amazon5.txt](https://www.google.com/search?q=./amazon5.txt) | Corpus de reseñas de productos de Amazon con etiquetas de polaridad. |
| [imdb5.txt](https://www.google.com/search?q=./imdb5.txt) | Corpus de reseñas de películas de IMDB para entrenamiento de modelos. |
| [embedding\_dict.pkl](https://www.google.com/search?q=./embedding_dict.pkl) | Diccionario serializado de embeddings pre-entrenados para optimización de carga. |

-----

## Contenido teórico

### 📌 Preprocesamiento y Normalización

Reducción de la variabilidad del lenguaje mediante **Stemming** (truncamiento heurístico a raíz) y **Lemmatización** (uso de vocabulario y análisis morfológico para llegar al lema).

-----

### 📌 Word Embeddings

Representación vectorial densa de palabras. A diferencia de Bag-of-Words, los embeddings como **FastText** permiten capturar relaciones semánticas y manejar palabras fuera del vocabulario (OOV) mediante n-gramas de caracteres.

-----

### 📌 Topic Modeling (LSI & LDA)

Extracción automática de temas en colecciones de documentos:

  - **LSI (Latent Semantic Indexing):** Utiliza la descomposición de valores singulares (SVD) para identificar conceptos latentes.
  - **LDA (Latent Dirichlet Allocation):** Modelo probabilístico que asume que cada documento es una mezcla de temas.

-----

### 📌 Sentiment Analysis

Clasificación de texto en categorías de opinión (positivo/negativo). Se implementan flujos desde la limpieza de datos hasta la evaluación con **matrices de confusión** y métricas de desempeño.

-----

## Enfoque del repositorio

El contenido está diseñado para:

  - Dominar el **pipeline completo de NLP**: desde el texto crudo hasta el modelo predictivo.
  - Aplicar algoritmos de **Topic Modeling** para organizar grandes volúmenes de información no estructurada.
  - Utilizar representaciones vectoriales avanzadas para mejorar la precisión en tareas de clasificación.
  - Resolver problemas reales de minería de texto utilizando herramientas estándar de la industria.

-----

## Herramientas utilizadas

<p>
<img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/NLTK-Natural_Language_Toolkit-8DBA2F?logo=python"/>
<img src="https://img.shields.io/badge/Gensim-Topic_Modeling-8A2BE2"/>
<img src="https://img.shields.io/badge/Scikit--Learn-Machine_Learning-F7931E?logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-Visualization-11557C"/>
<img src="https://img.shields.io/badge/WordCloud-Visualization-orange"/>
</p>
