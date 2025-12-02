# Análisis Telco Customer Churn

Este proyecto contiene ejercicios de reducción, limpieza, normalización y modelado aplicados al dataset Telco Customer Churn.

## Contenido

1. **Reducción y normalización**
   - Selección de variables numéricas (`tenure`, `MonthlyCharges`, `TotalCharges`).
   - Conversión de tipos y tratamiento de valores faltantes.
   - Muestreo del 10% de los datos.

2. **Limpieza e imputación**
   - Conversión de `TotalCharges` a numérico.
   - Imputación de valores faltantes con la mediana.
   - Validación de ausencia de blancos y NA.

3. **Normalización**
   - Transformación Box-Cox para mejorar la distribución.
   - Escalado Z-score para centrar y estandarizar.
   - Escalado Min-Max para rango [0,1].
   - Reducción de dimensionalidad con PCA (ACP).

4. **Correlación y regresión**
   - Correlaciones Pearson y Spearman entre variables y churn.
   - Visualización con mapas de calor.

5. **Partición y métricas**
   - Preparación de datos con variables dummies.
   - Entrenamiento de un modelo Random Forest.
   - Evaluación con accuracy, AUC, matriz de confusión y reporte de clasificación.

## Librerías utilizadas

- pandas, numpy, matplotlib, seaborn
- scikit-learn (preprocesamiento, PCA, RandomForest)
- IPython.display para visualización en notebook

## Resultados principales

- Transformaciones de normalización mejoran la adecuación de las variables para modelos.
- PCA reduce tres variables a dos componentes que explican ~98% de la varianza.
- El modelo Random Forest alcanza ~80% de accuracy y ~0.82 de AUC.
- El modelo predice bien los clientes que permanecen, pero menos los que se van.

## Referencias

- Documentación oficial de scikit-learn y scipy
- Tutoriales de seaborn y matplotlib
- Subirats et al. (2019) para técnicas de normalización
