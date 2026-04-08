# Portfolio Theory

---

> 📊 Teoría moderna de portafolios, optimización y análisis cuantitativo del riesgo financiero.

---

## Índice

- [Contenido del repositorio](#contenido-del-repositorio)  
- [Archivos principales](#archivos-principales)  
- [Contenido teórico](#contenido-teórico)  
- [Enfoque del repositorio](#enfoque-del-repositorio)  
- [Herramientas utilizadas](#️herramientas-utilizadas)  

---

## Contenido del repositorio

Este repositorio desarrolla la **Teoría Moderna de Portafolios (Markowitz)**, enfocándose en la relación entre riesgo y rendimiento mediante diversificación y optimización.

Incluye implementación en Python, datasets financieros reales y material visual que permite analizar:

- Frontera eficiente  
- Capital Market Line (CML)  
- Portafolio óptimo (Sharpe Ratio)  
- Métricas de riesgo  
- Simulación de escenarios financieros  

---

## Archivos principales

### ✦ Implementación en Python

| Archivo | Descripción |
|---|---|
| [edhec_risk_kit.py](./edhec_risk_kit.py) | Funciones para análisis financiero, optimización y métricas de riesgo |
| [edhec_risk_kit_oop.py](./edhec_risk_kit_oop.py) | Versión orientada a objetos con DataLoader, RiskAnalytics y PortfolioEngine |

---

### ✦ Notebooks

| Archivo | Descripción |
|---|---|
| [EDHEC_Portfolio_Management_Consolidado.ipynb](./EDHEC_Portfolio_Management_Consolidado.ipynb) | Desarrollo completo de teoría de portafolios y aplicaciones prácticas |

---

### ✦ Datasets financieros

| Archivo | Descripción |
|---|---|
| [BRK-A.csv](./BRK-A.csv) | Precios históricos de Berkshire Hathaway |
| [brka_d_ret.csv](./brka_d_ret.csv) | Retornos diarios de BRK-A |
| [sample_prices.csv](./sample_prices.csv) | Dataset de precios para simulaciones |
| [edhec-hedgefundindices.csv](./edhec-hedgefundindices.csv) | Índices de hedge funds |
| [Portfolios_Formed_on_ME_monthly_EW.csv](./Portfolios_Formed_on_ME_monthly_EW.csv) | Dataset Fama-French (capitalización) |

---

### ✦ Factores Fama-French

| Archivo | Descripción |
|---|---|
| [F-F_Research_Data_Factors.CSV](./F-F_Research_Data_Factors.CSV) | Factores de riesgo clásicos |
| [F-F_Research_Data_Factors_daily.CSV](./F-F_Research_Data_Factors_daily.CSV) | Factores en frecuencia diaria |
| [F-F_Research_Data_Factors_m.csv](./F-F_Research_Data_Factors_m.csv) | Factores mensuales |

---

### ✦ Industrias (Ken French)

| Archivo | Descripción |
|---|---|
| [ind30_m_ew_rets.csv](./ind30_m_ew_rets.csv) | Retornos equal-weight (30 industrias) |
| [ind30_m_nfirms.csv](./ind30_m_nfirms.csv) | Número de empresas |
| [ind30_m_size.csv](./ind30_m_size.csv) | Tamaño promedio |
| [ind30_m_vw_rets.csv](./ind30_m_vw_rets.csv) | Retornos value-weighted |
| [ind49_m_ew_rets.csv](./ind49_m_ew_rets.csv) | Retornos (49 industrias) |
| [ind49_m_nfirms.csv](./ind49_m_nfirms.csv) | Número de empresas |
| [ind49_m_size.csv](./ind49_m_size.csv) | Tamaño promedio |
| [ind49_m_vw_rets.csv](./ind49_m_vw_rets.csv) | Retornos value-weighted |

---

### ✦ Material visual y teórico

| Archivo | Descripción |
|---|---|
| [capital_market_line.png](./capital_market_line.png) | Representación de la CML |
| [efficient_frontier.png](./efficient_frontier.png) | Frontera eficiente |
| [sharpe_portfolio.gif](./sharpe_portfolio.gif) | Portafolio óptimo (Sharpe Ratio) |
| [Cross-Covariance.pdf](./Cross-Covariance.pdf) | Teoría de covarianza entre activos |

---

## Contenido teórico

### 📌 Teoría de Markowitz

Modelo que busca maximizar retorno esperado para un nivel dado de riesgo mediante diversificación.

---

### 📌 Frontera eficiente

Conjunto de portafolios óptimos que dominan a cualquier combinación subóptima.

---

### 📌 Capital Market Line (CML)

Línea que representa los portafolios óptimos al incluir un activo libre de riesgo.

---

### 📌 Sharpe Ratio

Mide el rendimiento ajustado por riesgo y permite identificar el portafolio óptimo.

---

### 📌 Medición de riesgo

Se implementan métricas como:

- Volatilidad  
- VaR  
- CVaR  
- Drawdown  

---

### 📌 Simulación financiera

Uso de modelos como movimiento browniano geométrico para simular trayectorias de precios.

---

## Enfoque del repositorio

El contenido está orientado a:

- Comprender teoría moderna de portafolios  
- Implementar modelos financieros en Python  
- Analizar datasets reales de mercado  
- Optimizar portafolios bajo distintos criterios  
- Evaluar riesgo financiero de forma cuantitativa  

---

## Herramientas utilizadas

<p>
<img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?logo=pandas"/>
<img src="https://img.shields.io/badge/NumPy-013243?logo=numpy"/>
<img src="https://img.shields.io/badge/SciPy-Optimization-blue"/>
<img src="https://img.shields.io/badge/Matplotlib-Visualization-blue"/>
<img src="https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white"/>
</p>

---
