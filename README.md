# ML_core4
Predicción de Calidad del Vino (Core) 

**Objetivo**

Utilizar técnicas de clasificación aprendidas hasta el momento para predecir la calidad del vino basándose en características físico-químicas. Este ejercicio permitirá aplicar conceptos como la selección de características, preprocesamiento de datos, entrenamiento y evaluación de modelos de clasificación, y análisis de resultados mediante métricas y visualizaciones.

**Descripción del Dataset:** Este conjunto de datos contiene información sobre distintas características físico-químicas de muestras de vino tinto y su calidad asociada. Las características incluyen acidez fija, acidez volátil, ácido cítrico, azúcar residual, cloruros, dióxido de azufre libre, dióxido de azufre total, densidad, pH, sulfatos y alcohol. La calidad del vino está clasificada en una escala del 0 al 10.

**Justificación de selección del modelo final:**

Random Forest Classifier Tras aplicar GridSearchCV con validación cruzada para optimizar los hiperparámetros, se obtuvieron los siguientes resultados:

KNN Classifier con n_neighbors = 10 alcanzó un accuracy de 59.8%

Random Forest Classifier con n_estimators = 100 logró un accuracy de 66.8%

De estos, el modelo Random Forest mostró el mejor desempeño en términos de precisión..

Por ello, se procedió a exportar el modelo Random Forest optimizado como el más confiable y eficaz para el problema abordado.
