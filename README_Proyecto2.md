# 🧠 Proyecto 2 – Aprendizaje de Máquinas

**Curso:** Introducción a la Inteligencia Artificial – Universidad Nacional de Colombia  
**Profesor:** Jaime Alberto Guzmán Luna  
**Grupo:** 1 – Equipo 8  
**Fecha de entrega:** 4 de noviembre de 2025  
**Integrantes:**

- MANUEL ZULETA ARANGO
- PERSONA 2
- PERSONA 3
- PERSONA 4

---

## 🎯 Objetivo General

Desarrollar una aplicación que, a partir de un dataset abierto, implemente y compare diferentes técnicas de **aprendizaje supervisado y no supervisado** para tareas de **clasificación y agrupamiento**.

---

## 🧩 Objetivos Específicos

- Obtener y preparar un dataset con un dominio elegido por el equipo.
- Aplicar técnicas de preprocesamiento: normalización, manejo de outliers y balanceo de clases.
- Implementar algoritmos de **aprendizaje supervisado**: Árboles de Decisión, KNN, SVM y Redes Neuronales.
- Implementar algoritmos de **aprendizaje no supervisado**: K-Means y DBSCAN.
- Evaluar y comparar los modelos usando métricas y curvas ROC/Precision-Recall.
- Visualizar y analizar los resultados obtenidos.

---

## 🧱 Estructura del Proyecto

```
├── data/
│   ├── dataset_original.csv
│   ├── dataset_preprocesado.csv
│   └── ...
├── supervised_learning/
│   ├── decision_tree.py
│   ├── knn.py
│   ├── svm.py
│   └── neural_network.py
├── unsupervised_learning/
│   ├── kmeans.py
│   ├── dbscan.py
│   └── evaluation.py
├── visualizations/
│   ├── plots_supervised.py
│   ├── plots_unsupervised.py
│   └── results/
├── report/
│   ├── documento_diseño.pdf
│   └── figuras/
├── README.md
└── main.ipynb  ← flujo principal del proyecto
```

---

## ⚙️ Requisitos de Software

- Python 3.10 o superior
- Bibliotecas requeridas:
  ```bash
  pip install numpy pandas scikit-learn matplotlib seaborn tensorflow
  ```
- Google Colab (para desarrollo y entrega final)

---

## 🚀 Ejecución del Proyecto

1. **Descargar o clonar** el repositorio.
2. **Abrir `main.ipynb` en Google Colab**.
3. Ejecutar los bloques en orden:
   - Selección y carga del dataset.
   - Preprocesamiento (normalización, balanceo, outliers).
   - Entrenamiento supervisado.
   - Evaluación y visualización de métricas.
   - Entrenamiento no supervisado.
   - Análisis de resultados.

---

## 📊 Resultados Esperados

- Tablas comparativas de métricas (Accuracy, Precision, Recall, F1-score).
- Curvas ROC y Precision-Recall (supervisado).
- Gráficas de Silhouette Score e Inertia (no supervisado).
- Visualizaciones de árboles, fronteras de decisión y clusters.

---

## 🎥 Sustentación

Video tipo _pitch_ (máx. 5 min) con:

- Explicación del problema y del dataset.
- Demostración del sistema funcional.
- Participación de todos los integrantes.  
  📎 **Enlace al video:** [Agregar enlace de YouTube aquí]

---

## 📦 Entrega Final

Subir a **Google Classroom** un archivo:

```
practica2-grupo-XX-equipo-YY.zip
```

Que contenga:

- Documento de diseño (.pdf)
- Código fuente (.ipynb y módulos .py)
- Video pitch (enlace YouTube)

---

## 🧠 Créditos

Trabajo desarrollado por los estudiantes del curso **Introducción a la Inteligencia Artificial (2025-2)**, Universidad Nacional de Colombia – Sede Medellín.
