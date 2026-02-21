# 🏋️ Model Fitness: Análisis de Churn y Segmentación de Clientes

## 📖 Introducción
La retención de clientes es el desafío número uno para Model Fitness. En este proyecto, analicé los perfiles de los usuarios y desarrollé un modelo de Machine Learning para predecir la probabilidad de que un cliente abandone el gimnasio el próximo mes.

## 📊 Fases del Proyecto

### 1. Análisis Exploratorio de Datos (EDA)
* Identificación de características clave: frecuencia de visitas, edad, tiempo desde el contrato inicial y participación en clases grupales.
* Análisis de promedios y distribuciones para clientes que se quedaron vs. clientes que se fueron.

### 2. Modelado de Clasificación
* Entrené modelos de **Regresión Logística** y **Random Forest** para predecir el *churn*.
* **Resultado:** Logré métricas de exactitud (Accuracy), Precisión y Recall que permiten identificar a los clientes en riesgo con alta fiabilidad.

### 3. Segmentación (Clustering)
* Utilicé un **Dendrograma** para determinar el número óptimo de grupos.
* Apliqué el algoritmo **K-Means** para segmentar a los usuarios en 5 grupos definidos por su comportamiento.



## 💡 Conclusiones y Recomendaciones
* **Clústeres de Riesgo:** Identifiqué grupos específicos con baja frecuencia de asistencia y contratos cortos.
* **Estrategia:** Se recomendó fortalecer el programa de referidos y fomentar las clases grupales, ya que los usuarios que asisten en grupo tienen una tasa de cancelación significativamente menor.

## 🛠️ Stack Tecnológico
* **Python** (Pandas, NumPy)
* **Scikit-learn** (Machine Learning)
* **Seaborn & Matplotlib** (Visualización)
