\# Clasificación de Imágenes con FastAI



Este repositorio contiene un notebook de Jupyter (`.ipynb`) donde se desarrolla un modelo de clasificación de imágenes utilizando FastAI y PyTorch.



El proyecto abarca el entrenamiento del modelo, su evaluación y el análisis detallado de los errores de clasificación.



---



\## Contenido del repositorio



\- `P2\_Ejs1y2.ipynb`  

&nbsp; Notebook principal con todo el desarrollo del proyecto.



---



\## Descripción del proyecto



El objetivo del proyecto es entrenar un modelo de deep learning capaz de clasificar imágenes en múltiples clases, evaluando su rendimiento sobre los conjuntos de entrenamiento, validación y test.



Durante el desarrollo se analizan métricas de rendimiento, matrices de confusión y los errores más frecuentes cometidos por el modelo.



---



\## Tecnologías utilizadas



\- Python  

\- FastAI  

\- PyTorch  

\- Scikit-learn  

\- Matplotlib  

\- NumPy  



---



\## Entrenamiento del modelo



El modelo se entrena utilizando FastAI con un sistema de early stopping para evitar el sobreajuste.  

El entrenamiento se detiene automáticamente cuando la pérdida de validación deja de mejorar, finalizando en la época 24.



Se analizan las curvas de pérdida y métricas a lo largo de las épocas.



---



\## Evaluación y métricas



Para evaluar el rendimiento del modelo se utilizan las siguientes métricas:



\- Accuracy  

\- F1-score  



Resultados obtenidos en el conjunto de test:



\- Accuracy ≈ 0.73  

\- F1-score ≈ 0.71  



---



\## Matrices de confusión



Se generan matrices de confusión para los conjuntos de entrenamiento, validación y test, lo que permite analizar visualmente el comportamiento del modelo y detectar patrones de error entre clases.



---



\## Análisis de errores



Se realiza un análisis de las clases con peor rendimiento (por ejemplo, 35, 28 y 23), mostrando imágenes mal clasificadas.



Las principales causas de error observadas son:

\- Alta similitud visual entre algunas clases  

\- Variaciones en ángulo, color y forma de los objetos  



---



\## Conclusiones



\- El modelo generaliza de forma aceptable.

\- El uso de early stopping mejora la estabilidad del entrenamiento.

\- El análisis de errores permite identificar las limitaciones del modelo.

\- Se podrían mejorar los resultados con más datos, data augmentation o modelos más complejos.





