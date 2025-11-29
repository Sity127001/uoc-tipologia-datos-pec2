# Simulación PEC2 - Limpieza y análisis de datos con Titanic

Este proyecto reproduce los conceptos de la PEC2 del Máster de Ciencia de Datos (UOC) mediante un **notebook de simulación**. Se utiliza el dataset clásico de Kaggle [Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data), que contiene información sobre pasajeros del Titanic y su supervivencia.

---

## Objetivos
- Practicar técnicas de **limpieza de datos**: detección de valores perdidos y extremos.
- Aplicar **reducción de dimensionalidad** (PCA) y **reducción de cantidad** (muestreo).
- Explorar **normalización** (min-max, z-score) y **transformaciones** (Box-Cox).
- Implementar **imputación** de datos perdidos (media, regresión).
- Comparar **correlaciones** (Pearson vs. Spearman).
- Diferenciar **regresión lineal** y **logística** con ejemplos prácticos.
- Simular **particiones de datos** (hold-out, k-fold, bootstrap).
- Calcular métricas de clasificación (**VP, FP, VN, FN**) y derivadas (precisión, sensibilidad, especificidad).

---

## Estructura del Notebook
1. **Importación de librerías y dataset**
2. **Limpieza de datos**
   - Filtros, selección de variables, tratamiento de valores perdidos y outliers
3. **Reducción**
   - PCA y muestreo
4. **Normalización y transformaciones**
   - Min-Max, Z-score, Box-Cox
5. **Imputación**
   - Media y regresión
6. **Correlación**
   - Pearson y Spearman
7. **Regresión**
   - Lineal (ejemplo con `Fare`)
   - Logística (ejemplo con `Survived`)
8. **Partición de datos**
   - Hold-out, k-fold, bootstrap
9. **Métricas de rendimiento**
   - Matriz de confusión, precisión, sensibilidad, especificidad
10. **Conclusiones**

---

## Requisitos
- Python 3.9+
- Librerías: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

pip install pandas numpy matplotlib seaborn scikit-learn


Instalación rápida:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
