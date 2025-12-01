# PCOS-ML-Analysis
Este repositorio contiene un proyecto completo de análisis de datos y modelado predictivo aplicado al diagnóstico del Síndrome de Ovario Poliquístico (PCOS).

# 🔬 Predicción de PCOS con Machine Learning  
Análisis completo de datos clínicos, evaluación de modelos supervisados y selección del mejor algoritmo para la predicción del Síndrome de Ovario Poliquístico (PCOS).

Este proyecto incluye:
- Limpieza avanzada del dataset  
- Análisis Exploratorio de Datos (EDA)  
- Visualización estadística  
- Aplicación de múltiples modelos de Machine Learning  
- Comparación mediante métricas (Accuracy, F1, AUC, ROC)  
- Modelado matemático y justificación teórica  
- Selección del mejor modelo: **Random Forest**

---

## 📑 Tabla de Contenidos
1. [Descripción del Proyecto](#descripción-del-proyecto)  
2. [Dataset](#dataset)  
3. [Objetivos](#objetivos)  
4. [Tecnologías Utilizadas](#tecnologías-utilizadas)  
5. [Modelos Implementados](#modelos-implementados)  
6. [Resultados](#resultados)  
7. [Estructura del Repositorio](#estructura-del-repositorio)  
8. [Instalación](#instalación)  
9. [Uso](#uso)  
10. [Conclusiones](#conclusiones)  
11. [Contribuciones](#contribuciones)  
12. [Autor](#autor)

---

## 🧬 Descripción del Proyecto
Este proyecto tiene como finalidad desarrollar un análisis completo que permita predecir el diagnóstico de PCOS utilizando técnicas de Machine Learning.  
Para ello se trabajó con un dataset clínico real que incluye variables hormonales, antropométricas y metabólicas.  

El flujo del proyecto abarca:

- Limpieza y preparación de datos  
- Transformación de variables  
- EDA con estadística descriptiva  
- Modelado supervisado y no supervisado  
- Evaluación por métricas diversas  
- Fórmulas matemáticas de los modelos  
- Conclusiones clínicas y computacionales

---

## 📂 Dataset
El dataset contiene información sobre pacientes con y sin PCOS.  
Incluye variables como:

- Edad  
- BMI  
- Relación cintura-cadera  
- Hormona antimülleriana (AMH)  
- Hábitos alimenticios  
- Historial menstrual  
- Marcadores metabólicos  

Se aplicó limpieza rigurosa: imputación, renombrado, eliminación de columnas irrelevantes y detección de outliers.

---

## 🎯 Objetivos
- Realizar un análisis estadístico detallado.
- Probar múltiples modelos de Machine Learning.
- Evaluar métricas clave: Accuracy, F1-Score, ROC/AUC.
- Determinar el modelo óptimo para predecir PCOS.
- Explicar el modelo matemáticamente.
- Documentar todo el proceso en un reporte completo.

---

## 🛠 Tecnologías Utilizadas
- **Python 3**
- **Pandas & NumPy**
- **Matplotlib & Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**
- **Word / Markdown para documentación**

---

## 🤖 Modelos Implementados

### **Modelos Supervisados**
- Regresión Logística  
- Árbol de Decisión  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Naive Bayes  

### **Modelos de Regresión**
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  

### **Modelos No Supervisados**
- K-Means  
- Análisis de Clusters (Método del codo, Silhouette Score)

---

## 📊 Resultados
Tras comparar todos los modelos mediante métricas avanzadas:

- ✔ **Random Forest** obtuvo el mejor desempeño global:  
  - Accuracy ≈ **92%**  
  - Excelente manejo de relaciones no lineales  
  - Robustez contra overfitting  
  - Buen equilibrio entre recall y precision  

- La regresión logística y SVM tuvieron buen rendimiento, pero menor sensibilidad para detectar PCOS.

- Los modelos de regresión se emplearon solo para fines comparativos y no son apropiados para este problema de clasificación.

---

Métodos de optimización

Supuestos estadísticos

Análisis comparativo teórico
