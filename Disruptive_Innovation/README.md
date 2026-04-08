# Disruptive Innovation Analysis & Simulation

---

> 📈 Modelado, simulación y análisis de datos sobre la teoría de innovación disruptiva aplicada a mercados e indicadores financieros.

---

## Índice

- [Contenido del repositorio](#contenido-del-repositorio)  
- [Archivos principales](#archivos-principales)  
- [Contenido teórico](#contenido-teórico)  
- [Enfoque del repositorio](#enfoque-del-repositorio)  
- [Herramientas utilizadas](#herramientas-utilizadas)  

---

## Contenido del repositorio

Este repositorio explora el concepto de **Innovación Disruptiva**, donde un entrante con menos recursos desafía con éxito a empresas establecidas. El proyecto combina el análisis cualitativo basado en *The Innovator’s Dilemma* con simulaciones en Python para modelar cuotas de mercado y análisis de KPIs financieros en tiempo real.

Se incluyen desarrollos sobre:
- Simulación de trayectorias de desempeño entre **Incumbentes vs. Disruptores**.
- Cálculo y análisis de **KPIs de rentabilidad, liquidez y solvencia**.
- Integración de bases de datos NoSQL (**MongoDB**) para el almacenamiento de activos financieros.
- Modelado de elección de mercado mediante funciones **Softmax**.

---

## Archivos principales

### ✦ Simulaciones y Análisis

| Archivo | Descripción |
|---|---|
| [disruptive_innovation_simulation.ipynb](./disruptive_innovation_simulation.ipynb) | Modelo matemático que simula curvas S de desempeño y market share entre empresas. |
| [KPIs_1.ipynb](./KPIs_1.ipynb) | Dashboard de indicadores financieros (Gross Margin, ROE, Beta) con extracción de datos reales. |
| [MongoDB.ipynb](./MongoDB.ipynb) | Pipeline de datos para conectar, insertar y gestionar documentos financieros en un clúster de MongoDB Atlas. |

---

### ✦ Documentación y Teoría

| Archivo | Descripción |
|---|---|
| [The Innovator’s Dilemma.pdf](./The_Innovators_Dilemma_Clayton_M_Christensen.pdf) | Recurso fundamental sobre la teoría de innovación de Clayton M. Christensen. |
| [README.md](./README.md) | Documentación extendida sobre el impacto de la disrupción en sectores como Fintech y Energía en México. |

---

## Contenido teórico

### 📌 El Dilema del Innovador
Las empresas líderes fracasan no por una mala gestión, sino por ignorar tecnologías disruptivas que inicialmente ofrecen menor desempeño pero evolucionan más rápido que las necesidades del mercado masivo.

---

### 📌 Simulación de Competencia (S-Curves)
Se modela cómo el disruptor entra en nichos de bajo valor y mejora su rendimiento siguiendo una curva sigmoidea, superando eventualmente el rendimiento del incumbente.

---

### 📌 Análisis de KPIs Financieros
Uso de métricas clave para evaluar la salud de las empresas en proceso de disrupción:
- **Margen de Utilidad:** Capacidad de generación de valor.
- **Beta:** Exposición al riesgo de mercado.
- **P/E Ratio:** Valoración relativa del mercado.

---

## Enfoque del repositorio

El contenido está diseñado para:
- Cuantificar teorías de estrategia de negocios mediante **simulación computacional**.
- Gestionar grandes volúmenes de datos financieros en entornos **NoSQL**.
- Analizar casos de estudio reales (Amazon, Mercado Libre, Fintechs) bajo el lente de la innovación.
- Automatizar la captura de datos de mercado para análisis de portafolios disruptivos.

---

## Herramientas utilizadas

<p>
<img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/MongoDB-Atlas-47A248?logo=mongodb&logoColor=white"/>
<img src="https://img.shields.io/badge/PyMongo-Driver-4DB33D?logo=mongodb"/>
<img src="https://img.shields.io/badge/Yahoo_Finance-yfinance-410099?logo=yahoo"/>
<img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-Plotting-11557C"/>
<img src="https://img.shields.io/badge/Jupyter-Interactive_Analysis-F37626?logo=jupyter&logoColor=white"/>
</p>
