
# Machine Learning Course / Curso de Machine Learning

**Core Stack**

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-013243?logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn&logoColor=white)
![seaborn](https://img.shields.io/badge/seaborn-Statistical%20Plots-4C72B0)

**Advanced / Specialized Stack**

![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-FF6F00?logo=tensorflow&logoColor=white)
![LightGBM](https://img.shields.io/badge/LightGBM-Gradient%20Boosting-02569B)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosted%20Trees-EC1C24)
![CatBoost](https://img.shields.io/badge/CatBoost-Gradient%20Boosting-FFCC00)
![NLTK](https://img.shields.io/badge/NLTK-NLP-76B900)
![spaCy](https://img.shields.io/badge/spaCy-NLP-09A3D5)
![Sentence Transformers](https://img.shields.io/badge/Sentence%20Transformers-Embeddings-5C3EE8)
![FAISS](https://img.shields.io/badge/FAISS-Vector%20Search-3B82F6)
![SHAP](https://img.shields.io/badge/SHAP-Explainability-7C3AED)
![Plotly](https://img.shields.io/badge/Plotly-Interactive%20Viz-3F4F75?logo=plotly&logoColor=white)

![License](https://img.shields.io/badge/License-MIT-green)

**Author / Autor:** Josef Rodriguez

---

## Index / Índice
- [English](#english)
- [Español](#español)
- [Quick Start](#quick-start)
- [Inicio Rápido](#inicio-rápido)
- [Project Assets](#project-assets)
- [Recursos del Proyecto](#recursos-del-proyecto)
- [Contact](#contact)

## Quick Start
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt && jupyter notebook
```

## Inicio Rápido
```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt && jupyter notebook
```

## Project Assets
- Datasets and inputs: [`data/`](data/)
- Research references: [`papers/`](papers/)
- Generated/model artifacts: [`artifacts/`](artifacts/), [`artefactos_reto/`](artefactos_reto/), [`artifacts_clustering_retail/`](artifacts_clustering_retail/), [`fraud_pipeline_artifacts/`](fraud_pipeline_artifacts/)
- Additional data dictionary/materials: [`diccionario_datos/`](diccionario_datos/)

## Recursos del Proyecto
- Datasets e insumos: [`data/`](data/)
- Referencias de investigación: [`papers/`](papers/)
- Artefactos generados/de modelos: [`artifacts/`](artifacts/), [`artefactos_reto/`](artefactos_reto/), [`artifacts_clustering_retail/`](artifacts_clustering_retail/), [`fraud_pipeline_artifacts/`](fraud_pipeline_artifacts/)
- Material adicional y diccionario de datos: [`diccionario_datos/`](diccionario_datos/)

## English

Academic and hands-on repository designed to teach Machine Learning from fundamentals to industrial practice using reproducible Python notebooks. It is also structured as a portfolio of applied ML work across real modeling scenarios.

### Topics covered
- Regression
- Classification
- Clustering
- Forecasting / Time series
- Feature engineering
- Hyperparameter tuning
- Industrial model validation
- Model monitoring and stability

### Typical ML project flow
Data Collection -> Data Cleaning -> EDA -> Feature Engineering -> Model Training -> Hyperparameter Optimization -> Model Evaluation -> Model Validation -> Model Monitoring

### Course at a glance (class | topic | level)
| Class | Main topic | Level |
|---|---|---|
| 02 | Classification & regression fundamentals | Beginner |
| 03 | Linear/non-linear regression (Ridge/Lasso) | Beginner |
| 04 | EDA and web scraping | Beginner |
| 05 | Regression with formal validation | Intermediate |
| 06-07 | Classification and validation | Intermediate |
| 08 | Clustering and customer segmentation | Intermediate |
| 09 | Forecasting / time series | Intermediate |
| 10 | WOE and hyperparameter tuning | Intermediate |
| 11 | Model interpretability/explainability | Intermediate |
| 12 | Inference and productionization | Intermediate |
| 13 | Text analytics and NLP | Intermediate |
| 14A-14C | Transformers, RAG, and LLM usage | Advanced |
| 15-16 | Deep Learning foundations and practice | Advanced |
| Final | Deep Learning vs ML synthesis | Advanced |

### Full notebook map (class by class)
- [`Clase_02_Fundamentos_ML_Clasificacion_y_Regresion.ipynb`](Clase_02_Fundamentos_ML_Clasificacion_y_Regresion.ipynb): Fundamentals of supervised ML for classification and regression.
- [`Clase_03_Masterclass_Regresion_Lineal_NoLineal.ipynb`](Clase_03_Masterclass_Regresion_Lineal_NoLineal.ipynb): Linear and non-linear regression, including Ridge and Lasso.
- [`Clase_04_EDA.ipynb`](Clase_04_EDA.ipynb): Exploratory Data Analysis workflow and data profiling.
- [`Clase_04_Extraccion_datos_web_scraping.ipynb`](Clase_04_Extraccion_datos_web_scraping.ipynb): Data extraction through web scraping.
- [`Clase_05_regresion_vf.ipynb`](Clase_05_regresion_vf.ipynb): Regression modeling with formal validation.
- [`Clase_06_clasificacion_v1.ipynb`](Clase_06_clasificacion_v1.ipynb): Baseline classification models and first evaluation pass.
- [`Clase_06_07_clasificacion_vf.ipynb`](Clase_06_07_clasificacion_vf.ipynb): Advanced classification with stronger validation practices.
- [`Clase_08_Clustering.ipynb`](Clase_08_Clustering.ipynb): Core clustering techniques (for example KMeans).
- [`Clase_08_Clustering_VF.ipynb`](Clase_08_Clustering_VF.ipynb): Clustering validation and quality assessment.
- [`Clase_08_Clustering_ABC_RFM.ipynb`](Clase_08_Clustering_ABC_RFM.ipynb): Customer segmentation using ABC/RFM logic.
- [`Clase_09_Forecasting_vf.ipynb`](Clase_09_Forecasting_vf.ipynb): Forecasting fundamentals for time series.
- [`Clase_10_WOES_HiperparametrosTuning.ipynb`](Clase_10_WOES_HiperparametrosTuning.ipynb): WOE-based feature engineering and hyperparameter tuning.
- [`Clase_11_Interpretabilidad_Explicabilidad_Modelos.ipynb`](Clase_11_Interpretabilidad_Explicabilidad_Modelos.ipynb): Model interpretability and explainability techniques.
- [`Clase_12_inferencia.ipynb`](Clase_12_inferencia.ipynb): Inference workflows for trained models.
- [`Clase_12_Puesta_en_produccion.ipynb`](Clase_12_Puesta_en_produccion.ipynb): Productionization concepts for ML solutions.
- [`Clase_13_analisis_texto.ipynb`](Clase_13_analisis_texto.ipynb): Introductory text analytics workflow.
- [`Clase_13_NLP_1.ipynb`](Clase_13_NLP_1.ipynb): NLP foundations and first applied examples.
- [`Clase_13_NLP_2.ipynb`](Clase_13_NLP_2.ipynb): Extended NLP applications and modeling practice.
- [`Clase_14A_Transformes.ipynb`](Clase_14A_Transformes.ipynb): Transformer-based modeling introduction.
- [`Clase_14B_RAGS.ipynb`](Clase_14B_RAGS.ipynb): Retrieval-Augmented Generation (RAG) concepts and practice.
- [`Clase_14C_LLMS_USO.ipynb`](Clase_14C_LLMS_USO.ipynb): Practical usage patterns for LLMs.
- [`Clase_15_intro_deepLear.ipynb`](Clase_15_intro_deepLear.ipynb): Introduction to deep learning.
- [`Clase_16_deepL.ipynb`](Clase_16_deepL.ipynb): Applied deep learning continuation.
- [`Clase_final_DL_vs_ML.ipynb`](Clase_final_DL_vs_ML.ipynb): Final comparison and synthesis: Deep Learning vs traditional ML.

### Included papers
Located in `papers/`, including:
- CatBoost
- Random Forest
- Gradient Boosting
- LightGBM
- XGBoost

### Setup
```bash
git clone https://github.com/josefrodrim/ML-course.git
cd ML-course
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

### Recommended environment
- Python 3.9+
- Anaconda or Miniconda (optional)
- VS Code
- Jupyter Notebook

---

## Español

Repositorio académico y práctico diseñado para enseñar Machine Learning desde fundamentos hasta aplicaciones industriales mediante notebooks reproducibles en Python. También está estructurado como portafolio de trabajo aplicado en escenarios reales de modelado.

### Temas cubiertos
- Regresión
- Clasificación
- Clustering
- Forecasting / Series de tiempo
- Feature engineering
- Hyperparameter tuning
- Validación industrial de modelos
- Monitoreo y estabilidad de modelos

### Flujo típico de un proyecto de ML
Recolección de datos -> Limpieza de datos -> EDA -> Ingeniería de variables -> Entrenamiento -> Optimización de hiperparámetros -> Evaluación -> Validación -> Monitoreo

### Vista rápida del curso (clase | tema | nivel)
| Clase | Tema principal | Nivel |
|---|---|---|
| 02 | Fundamentos de clasificación y regresión | Inicial |
| 03 | Regresión lineal/no lineal (Ridge/Lasso) | Inicial |
| 04 | EDA y web scraping | Inicial |
| 05 | Regresión con validación formal | Intermedio |
| 06-07 | Clasificación y validación | Intermedio |
| 08 | Clustering y segmentación de clientes | Intermedio |
| 09 | Forecasting / series de tiempo | Intermedio |
| 10 | WOE y ajuste de hiperparámetros | Intermedio |
| 11 | Interpretabilidad/explicabilidad | Intermedio |
| 12 | Inferencia y puesta en producción | Intermedio |
| 13 | Análisis de texto y NLP | Intermedio |
| 14A-14C | Transformers, RAG y uso de LLMs | Avanzado |
| 15-16 | Fundamentos y práctica de Deep Learning | Avanzado |
| Final | Síntesis DL vs ML tradicional | Avanzado |

### Mapa completo del curso (clase por clase)
- [`Clase_02_Fundamentos_ML_Clasificacion_y_Regresion.ipynb`](Clase_02_Fundamentos_ML_Clasificacion_y_Regresion.ipynb): Fundamentos de ML supervisado para clasificación y regresión.
- [`Clase_03_Masterclass_Regresion_Lineal_NoLineal.ipynb`](Clase_03_Masterclass_Regresion_Lineal_NoLineal.ipynb): Regresión lineal y no lineal, incluyendo Ridge y Lasso.
- [`Clase_04_EDA.ipynb`](Clase_04_EDA.ipynb): Flujo de análisis exploratorio de datos y perfilamiento.
- [`Clase_04_Extraccion_datos_web_scraping.ipynb`](Clase_04_Extraccion_datos_web_scraping.ipynb): Extracción de datos mediante web scraping.
- [`Clase_05_regresion_vf.ipynb`](Clase_05_regresion_vf.ipynb): Modelado de regresión con validación formal.
- [`Clase_06_clasificacion_v1.ipynb`](Clase_06_clasificacion_v1.ipynb): Modelos base de clasificación y primera evaluación.
- [`Clase_06_07_clasificacion_vf.ipynb`](Clase_06_07_clasificacion_vf.ipynb): Clasificación avanzada con validación más robusta.
- [`Clase_08_Clustering.ipynb`](Clase_08_Clustering.ipynb): Técnicas centrales de clustering (por ejemplo KMeans).
- [`Clase_08_Clustering_VF.ipynb`](Clase_08_Clustering_VF.ipynb): Validación y evaluación de calidad en clustering.
- [`Clase_08_Clustering_ABC_RFM.ipynb`](Clase_08_Clustering_ABC_RFM.ipynb): Segmentación de clientes con lógica ABC/RFM.
- [`Clase_09_Forecasting_vf.ipynb`](Clase_09_Forecasting_vf.ipynb): Fundamentos de forecasting para series temporales.
- [`Clase_10_WOES_HiperparametrosTuning.ipynb`](Clase_10_WOES_HiperparametrosTuning.ipynb): Ingeniería de variables con WOE y ajuste de hiperparámetros.
- [`Clase_11_Interpretabilidad_Explicabilidad_Modelos.ipynb`](Clase_11_Interpretabilidad_Explicabilidad_Modelos.ipynb): Técnicas de interpretabilidad y explicabilidad de modelos.
- [`Clase_12_inferencia.ipynb`](Clase_12_inferencia.ipynb): Flujos de inferencia para modelos entrenados.
- [`Clase_12_Puesta_en_produccion.ipynb`](Clase_12_Puesta_en_produccion.ipynb): Conceptos de despliegue y puesta en producción de soluciones ML.
- [`Clase_13_analisis_texto.ipynb`](Clase_13_analisis_texto.ipynb): Flujo introductorio de análisis de texto.
- [`Clase_13_NLP_1.ipynb`](Clase_13_NLP_1.ipynb): Bases de NLP y primeros ejemplos aplicados.
- [`Clase_13_NLP_2.ipynb`](Clase_13_NLP_2.ipynb): Extensión de aplicaciones y práctica de modelado NLP.
- [`Clase_14A_Transformes.ipynb`](Clase_14A_Transformes.ipynb): Introducción al modelado con Transformers.
- [`Clase_14B_RAGS.ipynb`](Clase_14B_RAGS.ipynb): Conceptos y práctica de Retrieval-Augmented Generation (RAG).
- [`Clase_14C_LLMS_USO.ipynb`](Clase_14C_LLMS_USO.ipynb): Patrones prácticos de uso de LLMs.
- [`Clase_15_intro_deepLear.ipynb`](Clase_15_intro_deepLear.ipynb): Introducción a Deep Learning.
- [`Clase_16_deepL.ipynb`](Clase_16_deepL.ipynb): Continuación aplicada de Deep Learning.
- [`Clase_final_DL_vs_ML.ipynb`](Clase_final_DL_vs_ML.ipynb): Comparación final y síntesis: Deep Learning vs ML tradicional.

### Papers incluidos
Disponibles en `papers/`, incluyendo:
- CatBoost
- Random Forest
- Gradient Boosting
- LightGBM
- XGBoost

### Instalación
```bash
git clone https://github.com/josefrodrim/ML-course.git
cd ML-course
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

### Entorno recomendado
- Python 3.9+
- Anaconda o Miniconda (opcional)
- VS Code
- Jupyter Notebook

---

## Contact
Josef Rodriguez  
Machine Learning | Model Risk | Applied AI
