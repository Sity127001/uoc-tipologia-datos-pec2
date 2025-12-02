# Análisis Telco Customer Churn de kaggle (fichero esta en la carpeta `/data`)


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

## Entorno de ejecución

Para que el notebook funcione correctamente:

- Usar **Python 3.9 o superior**.
- Asegurar de que el archivo del dataset de Kaggle se encuentra en la carpeta `/data`.
- Instalar las dependencias ejecutando el siguiente comando desde la raíz del proyecto:

```bash
pip install -r requirements.txt 
```

## Referencias

- Documentación oficial de scikit-learn y scipy
- Tutoriales de seaborn y matplotlib
- Subirats et al. (2019) para técnicas de normalización
