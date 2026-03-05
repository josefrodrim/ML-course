
Machine Learning Course — From Fundamentals to Industrial Practice

Autor: Josef Rodriguez

Repositorio académico y práctico diseñado para enseñar Machine Learning desde fundamentos hasta aplicaciones industriales mediante notebooks reproducibles en Python.

Este curso cubre el ciclo completo de un proyecto de Machine Learning:

- regresión
- clasificación
- clustering
- forecasting
- feature engineering
- hyperparameter tuning
- validación industrial de modelos
- monitoreo y estabilidad de modelos

------------------------------------------------------------
FLUJO DE UN PROYECTO DE MACHINE LEARNING

Data Collection
↓
Data Cleaning
↓
Exploratory Data Analysis
↓
Feature Engineering
↓
Model Training
↓
Hyperparameter Optimization
↓
Model Evaluation
↓
Model Validation
↓
Model Monitoring

------------------------------------------------------------
ESTRUCTURA DEL CURSO

Clase 02
Clase_02_Fundamentos_ML_Clasificacion_y_Regresion.ipynb
Fundamentos de clasificación y regresión

Clase 03
Clase_03_Masterclass_Regresion_Lineal_NoLineal.ipynb
Regresión lineal, ridge, lasso

Clase 04
Clase_04_EDA.ipynb
Análisis exploratorio de datos

Clase 04
Clase_04_Extraccion_datos_web_scraping.ipynb
Web scraping con Python

Clase 05
Clase_05_regresion_vf.ipynb
Regresión con validación formal

Clase 06
Clase_06_clasificacion_v1.ipynb
Modelos base de clasificación

Clase 06-07
Clase_06_07_clasificacion_vf.ipynb
Clasificación avanzada y validación

Clase 08
Clase_08_Clustering.ipynb
Clustering con KMeans

Clase 08
Clase_08_Clustering_VF.ipynb
Validación de clustering

Clase 08
Clase_08_Clustering_ABC_RFM.ipynb
Segmentación estratégica de clientes

Clase 09
Clase_09_Forecasting_vf.ipynb
Forecasting y series de tiempo

Clase 10
Clase_10_WOES_HiperparametrosTuning.ipynb
Feature engineering y hyperparameter tuning

------------------------------------------------------------
FEATURE ENGINEERING

Técnicas utilizadas:

- agrupación de categorías
- transformaciones de variables
- Weight of Evidence (WOE)
- Information Value (IV)

WOE = ln(%NoEvento / %Evento)

IV = Σ (%NoEvento - %Evento) × WOE

------------------------------------------------------------
HYPERPARAMETER TUNING

Métodos utilizados:

- Grid Search
- Random Search
- Cross Validation

Objetivo:

lambda* = argmax Score(lambda)

------------------------------------------------------------
DATASETS

dataset_mora.csv
Datos_abiertos_admision_2021_1_2024_1.csv
online_retail_II.xlsx
ridetech_peru_regression_202201_202602.csv

------------------------------------------------------------
PAPERS INCLUIDOS

papers/

- CatBoost
- Random Forest
- Gradient Boosting
- LightGBM
- XGBoost

------------------------------------------------------------
INSTALACIÓN

git clone https://github.com/josefrodrim/ML-course.git

cd ML-course

pip install -r requirements.txt

jupyter notebook

------------------------------------------------------------
ENTORNO RECOMENDADO

Python 3.9+
Anaconda o Miniconda
VS Code
Jupyter Notebook

------------------------------------------------------------
AUTOR

Josef Rodriguez
Machine Learning | Model Risk | Applied AI
