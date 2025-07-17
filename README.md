# Diagnóstico Oftálmico Automatizado con Deep Learning 👁️

[![Made with TensorFlow](https://img.shields.io/badge/Made%20with-TensorFlow-orange?logo=tensorflow)](https://www.tensorflow.org/)
[![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Explainable AI](https://img.shields.io/badge/XAI-Saliency%20Maps-purple)](https://en.wikipedia.org/wiki/Explainable_artificial_intelligence)

## 🌐 Descripción (Español)

Sistema de diagnóstico automatizado que utiliza Deep Learning para clasificar patologías oftálmicas (Retinopatía Diabética, Catarata, Glaucoma) a partir de imágenes de fondo de ojo.

### Características clave:
- 🧬 Arquitectura EfficientNetB0 con **Transfer Learning**
- 🤖 Clasificación multiclase con alto rendimiento
- 🔮 Implementación de **IA Explicable (XAI)** mediante Mapas de Saliencia para validar la relevancia clínica de las predicciones
- 📊 Evaluación con métricas clásicas: Accuracy, Precision, Recall, F1-Score, AUC-ROC

---

## 🌐 Description (English)

Automated diagnostic system using Deep Learning to classify ophthalmic diseases (Diabetic Retinopathy, Cataract, Glaucoma) from retinal fundus images.

### Key Features:
- 🧬 **EfficientNetB0** architecture with Transfer Learning
- 🤖 High-performance multiclass classification
- 🔮 **Explainable AI (XAI)** via Saliency Maps to support clinical relevance of model predictions
- 📊 Evaluation with standard metrics: Accuracy, Precision, Recall, F1-Score, AUC-ROC

---

## 💡 Tecnologías Utilizadas / Tech Stack
- Python 3.9+
- TensorFlow 2.x
- Keras
- NumPy, OpenCV, Matplotlib
- Jupyter Notebooks

---

## 🔹 Estructura del Proyecto / Project Structure

```
├── code/                    # Archivo i.pynb 
├── report/               # Reporte en latex
├── presentation/          # presentacion visual 
└── README.md
```

---

## 🔍 Resultados Destacados / Highlighted Results

### 🧪 Final Classification Report

| Class                | Precision | Recall | F1-Score | Support |
|---------------------|-----------|--------|----------|---------|
| Cataract            | 0.87      | 0.94   | 0.90     | 157     |
| Diabetic Retinopathy| 0.94      | 0.72   | 0.82     | 166     |
| Glaucoma            | 0.97      | 0.45   | 0.62     | 152     |
| Normal              | 0.56      | 0.94   | 0.70     | 162     |
| **Accuracy**        |           |        | **0.77** | **637** |
| **Macro Avg**       | 0.84      | 0.76   | 0.76     | 637     |
| **Weighted Avg**    | 0.84      | 0.77   | 0.76     | 637     |

📊 **Final Test Accuracy:** `0.7660910518053375`
