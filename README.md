# ML-course
Curso de Machine Learning

## Requisitos
- Git
- Anaconda
- VS Code

## Clonar repositorio
```bash
git clone https://github.com/josefrodrim/ML-course.git

# Machine Learning Course – From Fundamentals to Industrial Practice

Autor: Josef Rodriguez  
Repositorio académico y práctico orientado a formación profesional en Machine Learning con enfoque industrial.

---

# Objetivo del Curso

Este repositorio contiene un programa completo de Machine Learning estructurado en 8 clases, cubriendo:

- Fundamentos teóricos
- Implementación práctica en Python
- Validación formal de modelos
- Enfoque industrial (estabilidad, drift, monitoreo)
- Segmentación estratégica de clientes

El curso combina teoría matemática, código reproducible y aplicación real en datasets abiertos y escenarios tipo banca/industria.

---

# Estructura del Curso

## Clase 01 – Introducción a Machine Learning
Fundamentos conceptuales:
- Qué es Machine Learning
- Tipos de aprendizaje
- Flujo de un proyecto ML
- Train/Test split
- Overfitting vs Underfitting

---

## Clase 02 – Fundamentos ML: Clasificación y Regresión
Notebook:
- Clase_02_Fundamentos_ML_Clasificacion_y_Regresion.ipynb

Contenido:
- Regresión vs Clasificación
- Métricas (MAE, RMSE, R², Accuracy)
- Bias-Variance Tradeoff
- Evaluación correcta de modelos

Dataset:
- dataset_mora.csv

---

## Clase 03 – Masterclass Regresión Lineal y No Lineal
Notebook:
- Clase_03_Masterclass_Regresion_Lineal_NoLineal.ipynb

Modelos:
- OLS
- Ridge
- Lasso
- Elastic Net
- Regresión Polinómica

Enfoque:
- Regularización
- Interpretabilidad
- Minimización del error cuadrático

---

## Clase 04 – Exploratory Data Analysis y Web Scraping
Notebooks:
- Clase_04_EDA.ipynb
- Clase_04_Extraccion_datos_web_scraping.ipynb

Contenido:
- Análisis exploratorio profesional
- Distribuciones y outliers
- Correlaciones
- Extracción de datos con BeautifulSoup
- Parsing HTML

Dataset:
- Datos_abiertos_admision_2021_1_2024_1.csv

---

## Clase 05 – Regresión con Validación Formal
Notebook:
- Clase_05_regresion_vf.ipynb

Contenido:
- Train/Test Split
- Cross Validation
- Time Series Split
- Comparación de modelos
- Feature Engineering

Dataset:
- ridetech_peru_regression_202201_202602.csv

Métricas:
- MAE
- RMSE
- R²

---

## Clase 06 – Clasificación (Modelos Base)
Notebook:
- Clase_06_clasificacion_v1.ipynb

Modelos:
- Regresión Logística
- Árboles de decisión
- Random Forest
- XGBoost
- LightGBM
- CatBoost

Métricas:
- ROC AUC
- Gini
- Matriz de confusión

---

## Clase 07 – Clasificación Avanzada y Estabilidad
Notebook:
- Clase_06_07_clasificacion_vf.ipynb

Enfoque industrial:
- Validación fuera de tiempo (OOT)
- PSI (Population Stability Index)
- Drift
- Selección de variables
- Monitoreo de modelos

Incluye reporte:
- reporte_comite_estabilidad_PSI.pdf

---

## Clase 08 – Clustering y Segmentación Estratégica

Notebooks:
- Clase_08_Clustering.ipynb
- Clase_08_Clustering_VF.ipynb
- Clase_08_Clustering_ABC_RFM.ipynb

Dataset:
- online_retail_II.xlsx

### Parte 1 – Clustering
- KMeans
- Silhouette Score
- Davies-Bouldin
- Calinski-Harabasz

### Parte 2 – Segmentación ABC basada en RFM

Definiciones:

Recency:
R_i = T_ref − max(T_i,t)

Frequency:
F_i = n_i

Monetary:
M_i = sum(Quantity_i,t × Price_i,t)

Score:
RFM_score_i = R*_i + F*_i + M*_i

Segmentación:
- A → Top 20% (alto valor)
- B → 30% intermedio
- C → 50% inferior

Aplicación:
- A: clientes estratégicos
- B: clientes con potencial
- C: clientes de bajo valor

---

# Estructura del Repositorio

data/  
    datasets utilizados en las clases  

diccionario_datos/  
    documentación formal de variables  

papers/  
    papers técnicos de:
    - CatBoost
    - XGBoost
    - LightGBM
    - Random Forest
    - Gradient Boosting  

artifacts_clustering_retail/  
    artefactos generados en clustering  

requirements.txt  
    dependencias del proyecto  

---

# Instalación

Requisitos:

- Python 3.9+
- pip o conda
- Jupyter Notebook

Instalar dependencias:

pip install -r requirements.txt

Ejecutar:

jupyter notebook

---

# Enfoque del Curso

Este repositorio no solo enseña modelos, sino que incorpora:

- Validación robusta
- Control de estabilidad
- Métricas industriales
- Enfoque explicativo
- Buenas prácticas reproducibles

---

# Licencia

Este proyecto se distribuye bajo la licencia incluida en el archivo LICENSE.

---

# Autor

Josef Rodriguez  
Machine Learning | Model Risk | AI Applied  