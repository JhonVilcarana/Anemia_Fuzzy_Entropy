# 🔬 Clasificación de Anemia Infantil con Entropía Difusa y XGBoost

Este proyecto desarrolla un modelo de **clasificación basado en entropía difusa** integrado con **XGBoost** para identificar factores que contribuyen a la prevalencia de anemia infantil en Perú.  
El enfoque permite **manejar la incertidumbre** presente en los datos de salud y mejorar el rendimiento frente a métodos tradicionales de *machine learning*.

---

## 🎯 Objetivo
Desarrollar un modelo de clasificación basado en **entropía difusa** para la **identificación de factores que contribuyen a la prevalencia de anemia infantil en niños peruanos**, optimizando la precisión y el balance entre sensibilidad y especificidad.

---

## 🗂️ Estructura del repositorio

---

## ⚙️ Tecnologías utilizadas
- **Python 3.10+**
- pandas, numpy, scikit-learn
- XGBoost
- Matplotlib / Seaborn
- Entropía difusa implementada como transformador personalizado

---

## 📊 Resultados principales
- **Accuracy:** 90.9%  
- **Recall (Sensibilidad):** 88.3%  
- **Precisión:** 85.8%  
- **F₁-score:** 0.870  
- **ROC-AUC:** 0.962  
- **PR-AUC:** 0.937  

### 🔹 Curvas de rendimiento
| ROC-AUC | PR-AUC |
|---------|--------|
| ![ROC Curve](./results/auc_curve.png) | ![PR Curve](./results/pr_curve.png) |

### 🔹 Comparación con modelos previos
| Modelo | Accuracy | Recall | Precisión | F₁-score |
|--------|----------|---------|-----------|----------|
| Random Forest (Perú, ENDES 2022) | 70% | 65.9% | - | - |
| Árboles de decisión (Arequipa)   | 74.5% | - | - | - |
| **XGBoost + Entropía Difusa + Ajuste de Umbral (este estudio)** | **90.9%** | **88.3%** | **85.8%** | **0.870** |

---

## 🔎 Interpretabilidad
- La **entropía difusa** captura la incertidumbre en los datos clínicos.  
- Permite representar la gradualidad en los estados de salud.  
- Aporta un valor agregado para la toma de decisiones en salud pública.

---

## 🚀 Cómo ejecutar
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tuusuario/anemia-fuzzyentropy.git
