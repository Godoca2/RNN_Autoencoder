## Introducción

Las redes neuronales son herramientas fundamentales en el análisis de datos complejos y no lineales, con aplicaciones en una amplia variedad de disciplinas. Este laboratorio tiene como objetivo explorar dos arquitecturas clave en el ámbito del aprendizaje profundo: LSTM y autoencoders. Se busca demostrar cómo estas redes pueden adaptarse a problemas específicos, extrayendo patrones relevantes y proporcionando soluciones innovadoras.

El trabajo se divide en dos unidades:

1. **Unidad 1: Redes LSTM para series temporales**  
   - Aplicar arquitecturas LSTM para analizar datos de producción láctea y el índice IPSA, provenientes de la bolsa de Santiago de Chile.  
   - Generar predicciones a tres meses en ambas series temporales, evaluando el rendimiento del modelo con métricas estandarizadas.  

2. **Unidad 2: Autoencoders para procesamiento de imágenes**  
   - Diseñar un autoencoder para limpiar imágenes con ruido y recuperar información relevante.  
   - Utilizar un conjunto de datos adjunto para entrenar y validar el modelo, enfocándose en la reconstrucción de imágenes deterioradas.  

Este laboratorio combina análisis exploratorio, diseño de modelos y evaluación de resultados, proporcionando una visión integral del uso de redes neuronales en problemas de la vida real.

---

### Unidad 1: Redes LSTM para series temporales

Las redes LSTM (Long Short-Term Memory) son una variante de redes neuronales recurrentes diseñadas para manejar series temporales. Su capacidad para retener información a largo plazo las hace ideales para predecir valores futuros basándose en patrones históricos. En esta unidad, se entrenarán modelos para prever los valores de producción láctea mensual y el índice IPSA, generando predicciones para los próximos tres meses. Se evaluará el desempeño del modelo mediante métricas como RMSE y MAE, y se analizarán gráficas comparativas para determinar la precisión del modelo.

---

### Unidad 2: Autoencoders para procesamiento de imágenes

Los autoencoders son redes neuronales diseñadas para tareas de reducción de dimensionalidad, reconstrucción de datos y eliminación de ruido. En esta unidad, se implementará un modelo de autoencoder para procesar imágenes ruidosas, transformándolas en versiones limpias y legibles. El proceso incluye:  

- El diseño de un modelo con capas de codificación y decodificación.  
- Entrenamiento con imágenes ruidosas y sus correspondientes versiones limpias.  
- Evaluación visual del desempeño mediante comparaciones entre imágenes originales, reconstruidas y limpias esperadas.  

Este ejercicio resalta la aplicabilidad de los autoencoders en tareas de restauración y preprocesamiento de datos visuales.


