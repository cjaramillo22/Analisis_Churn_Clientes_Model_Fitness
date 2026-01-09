# Análisis de Pérdida de Clientes en Model Fitness

## 📌 Descripción del proyecto
Model Fitness, una cadena de gimnasios, busca desarrollar una estrategia de retención de clientes basada en análisis de datos.  
Este proyecto analiza perfiles de clientes, su comportamiento de uso y características contractuales para identificar patrones asociados a la cancelación (churn) y proponer acciones de retención.

El objetivo principal es predecir la probabilidad de pérdida de clientes, segmentarlos en grupos relevantes y extraer conclusiones accionables para mejorar la interacción con los usuarios.

---

## 🎯 Objetivos
- Predecir la probabilidad de cancelación de clientes para el próximo mes.
- Identificar los factores que más influyen en la pérdida de clientes.
- Construir perfiles de usuarios típicos mediante técnicas de clustering.
- Formular recomendaciones básicas para mejorar la retención y atención al cliente.

---

## 🗂️ Descripción de los datos
El dataset fue proporcionado por Model Fitness y contiene información de clientes del mes anterior a la cancelación.

**Archivo utilizado:**
- `gym_churn_us.csv`

### Variables principales
- `Churn`: indicador de cancelación.
- `gender`, `Age`
- `Near_Location`, `Partner`
- `Promo_friends`, `Phone`
- `Lifetime`
- `Contract_period`, `Month_to_end_contract`
- `Group_visits`
- `Avg_class_frequency_total`
- `Avg_class_frequency_current_month`
- `Avg_additional_charges_total`

---

## 🧪 Metodología

### 1. Análisis exploratorio de datos (EDA)
- Revisión de valores ausentes y estadísticos descriptivos.
- Comparación de medias entre clientes que cancelaron y los que permanecen.
- Visualización de distribuciones y patrones de comportamiento.
- Análisis de correlación entre variables.

### 2. Modelado predictivo
- División de los datos en conjuntos de entrenamiento y validación.
- Entrenamiento de modelos de clasificación:
  - Regresión logística.
  - Bosque aleatorio.
- Evaluación de métricas: accuracy, precision y recall.

### 3. Segmentación de clientes
- Estandarización de variables.
- Análisis jerárquico y visualización mediante dendrograma.
- Clustering con K-means (n = 5).
- Análisis de características promedio y tasa de cancelación por clúster.

---

## 🛠️ Herramientas utilizadas
- Python  
- Pandas  
- Matplotlib / Seaborn  
- Scikit-learn  
- SciPy  
- Jupyter Notebook  

---

## 📊 Resultados y conclusiones
El análisis permitió identificar perfiles de clientes con alta y baja probabilidad de cancelación, así como variables clave asociadas al churn, como la frecuencia de visitas, la duración del contrato y la participación en actividades grupales.

A partir de estos hallazgos, se plantean recomendaciones orientadas a mejorar la retención mediante estrategias segmentadas y acciones preventivas.

---

## 📁 Estructura del repositorio
├── notebooks/

│ └── Analisis Perdida Clientes Model Fitness.ipynb

├── datasets/

│ └── gym_churn_us.csv

└── README.md

---

## 👤 Autor
**Carlos Jaramillo**  
Analista de Datos