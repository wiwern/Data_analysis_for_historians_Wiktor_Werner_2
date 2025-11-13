# Data_analysis_for_historians_Wiktor_Werner_2
Repository for a teaching course on **data analysis in historical research** using **Python** and **Jupyter Notebook**.   The course is designed for students in history and the humanities who want to learn how to work with quantitative data in a clear and practical way, without needing advanced mathematical or computer science background. 

# Data Analysis for Historical Research (Python & Jupyter)
# Análisis de datos para la investigación histórica (Python y Jupyter)

Repository for a teaching course on **data analysis in historical research** using **Python** and **Jupyter Notebook**.  
The course is designed for students in history and the humanities who want to learn how to work with quantitative data in a clear and practical way, without needing advanced mathematical or computer science background.

Repositorio del curso de **análisis de datos en la investigación histórica** con **Python** y **Jupyter Notebook**.  
El curso está dirigido a estudiantes de historia y humanidades que quieren aprender a trabajar con datos cuantitativos de forma clara y práctica, sin necesidad de una formación avanzada en matemáticas o informática.

---

## Course overview / Visión general del curso

The course introduces fundamental techniques of data analysis that can be directly applied to historical sources and datasets.

El curso introduce técnicas fundamentales de análisis de datos que pueden aplicarse directamente a fuentes y conjuntos de datos históricos.

The main components are:  
Los componentes principales son:

1. **Descriptive statistics for two variables**  
   - Frequency tables, cross-tabulations, basic measures (mean, median, standard deviation).  
   - Correlation between two variables in historical datasets (e.g. social structure, demography, economy).

   **Estadística descriptiva para dos variables**  
   - Tablas de frecuencia, tablas cruzadas, medidas básicas (media, mediana, desviación estándar).  
   - Correlación entre dos variables en conjuntos de datos históricos (p. ej. estructura social, demografía, economía).

2. **Exploratory Data Analysis (EDA) – two variables and linear regression**  
   - Visual exploration (scatter plots, histograms, boxplots).  
   - Simple linear regression to model relationships between two historical variables.

   **Análisis exploratorio de datos (EDA) – dos variables y regresión lineal**  
   - Exploración visual (diagramas de dispersión, histogramas, boxplots).  
   - Regresión lineal simple para modelar relaciones entre dos variables históricas.

3. **Time series analysis**  
   - Basic time series handling (indexing by date, resampling).  
   - Decomposition (trend, seasonality, residuals), causal impact analysis  
   - Linear regression on time series (trend estimation).
   

   **Análisis de series temporales**  
   - Manejo básico de series temporales (indexación por fecha, remuestreo).  
   - Descomposición (tendencia, estacionalidad, residuos, "momentos causales").  
   - Regresión lineal en series temporales (estimación de tendencias).

4. **Correspondence analysis**  
   - From contingency tables to geometric representations.  
   - Interpreting dimensions and graphical output for categorical historical data (e.g. actors × categories).

   **Análisis de correspondencias**  
   - De tablas de contingencia a representaciones geométricas.  
   - Interpretación de dimensiones y resultados gráficos para datos categóricos históricos (p. ej. actores × categorías).

5. **Graph construction and centrality measures**  
   - Building graphs from historical relations (e.g. people, institutions, concepts).  
   - Basic centrality measures (degree, betweenness, closeness) and their interpretation in historical networks.

   **Construcción de grafos y medidas de centralidad**  
   - Construcción de grafos a partir de relaciones históricas (p. ej. personas, instituciones, conceptos).  
   - Medidas básicas de centralidad (grado, intermediación, cercanía) y su interpretación en redes históricas.

6. **Decision tree algorithms and LASSO regression – analysing dependencies between variables**  
   - Using decision trees to explore non-linear relationships and interactions.  
   - LASSO regression to select relevant variables and study which factors matter most in historical datasets.

   **Algoritmo de árbol de decisión y regresión LASSO – análisis de dependencias entre variables**  
   - Uso de árboles de decisión para explorar relaciones no lineales e interacciones.  
   - Regresión LASSO para seleccionar variables relevantes y estudiar qué factores importan más en los conjuntos de datos históricos.

---


## Format and materials / Formato y materiales

- The core materials are **Jupyter Notebooks** (`.ipynb`) for each module.  
- Example datasets (CSV files) are provided to reproduce the analyses.  
- Students are encouraged to modify the code and adapt the methods to their own research questions.

Los materiales principales son **notebooks de Jupyter** (`.ipynb`) para cada módulo.  
Se incluyen conjuntos de datos de ejemplo (archivos CSV) para reproducir los análisis.  
Se anima a los estudiantes a modificar el código y adaptar los métodos a sus propias preguntas de investigación.

Proposed structure / Estructura propuesta:

```text
notebooks/
- `01_descriptive_statistics.ipynb` – descriptive statistics for two quantitative variables  
- `02_eda_linear_regression.ipynb` – exploratory data analysis (EDA) and simple linear regression  
- `03_time_series_analysis.ipynb` – time series analysis (decomposition and linear trend)  
- `03b_time_series_causal_impact.ipynb` – time series with a user-defined causal moment (CausalImpact)  
- `04_correspondence_analysis.ipynb` – correspondence analysis for two categorical variables



