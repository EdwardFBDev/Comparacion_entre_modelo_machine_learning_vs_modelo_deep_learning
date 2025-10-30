<br clear="both">

<h1 align="left">Proyecto: Comparación entre un modelo de Machine Learning y un modelo de Deep Learning<br>Descripción general</h1>

###

<p align="left">Este proyecto compara el desempeño de un modelo de Machine Learning tradicional (Regresión Lineal) con un modelo de Deep Learning (Red Neuronal) para predecir la demanda de oxígeno químico a partir de valores de reducción de sólidos.<br><br>El objetivo es analizar cuál de los dos enfoques logra una mejor capacidad de predicción y generalización en un conjunto de datos pequeño, además de mostrar las diferencias prácticas entre ambos tipos de modelos.</p>

###

<h3 align="left">Objetivos</h3>

###

<p align="left">- Construir un modelo de regresión lineal y un modelo de red neuronal simple.<br><br>- Evaluar la relación entre la reducción de sólidos y la demanda de oxígeno químico.<br><br>- Comparar los resultados obtenidos por ambos modelos en términos de error y capacidad predictiva.<br><br>- Comprender las ventajas y limitaciones de cada enfoque en un problema de predicción numérica.</p>

###

<h3 align="left">Metodología</h3>

###

<p align="left">1. Creación del conjunto de datos:<br>Se generaron datos simulados que representan medidas de reducción de sólidos y demanda de oxígeno químico.</p>

###

<p align="left">2. Preparación de los datos:<br>Los datos fueron organizados en variables de entrada y salida, y divididos en conjuntos de entrenamiento y prueba para evaluar el rendimiento de los modelos.</p>

###

<p align="left">3. Modelo de Machine Learning (Regresión Lineal):<br>- Se utilizó la librería scikit-learn para construir un modelo de regresión lineal.<br><br>- Se analizaron los residuos para confirmar si la relación entre las variables era realmente lineal.<br><br>- Se calcularon las métricas de error cuadrático medio (MSE) y el coeficiente de determinación (R²).</p>

###

<p align="left">4. Modelo de Deep Learning (Red Neuronal):<br><br>- Se implementó una red neuronal sencilla con TensorFlow/Keras.<br><br>- La red contó con una capa de entrada, una capa oculta con función de activación ReLU y una capa de salida lineal.<br><br>- El entrenamiento se realizó con el optimizador Adam y la función de pérdida MSE.<br><br>- Finalmente, se evaluó el modelo con los datos de prueba.</p>

###

<p align="left">5. Comparación y visualización:<br>Se graficaron las predicciones de ambos modelos para observar su ajuste y se compararon las métricas de rendimiento.</p>

###

<h3 align="left">Resultados</h3>

###

<p align="left">- El modelo de regresión lineal logró capturar la tendencia general de los datos, pero mostró limitaciones ante relaciones no lineales.<br><br>- El modelo de red neuronal obtuvo un menor error de predicción y logró un mejor ajuste en los valores extremos del conjunto de datos.<br><br>- La comparación evidenció que, aunque ambos modelos cumplen su función, la red neuronal puede adaptarse mejor a patrones más complejos.</p>

###

<h3 align="left">Conclusiones</h3>

###

<p align="left">- El modelo de Deep Learning demostró un mejor rendimiento al manejar relaciones no lineales en los datos.<br><br>- La regresión lineal sigue siendo una alternativa eficiente cuando se busca un modelo más simple y fácil de interpretar.<br><br>- La elección entre un modelo de Machine Learning y uno de Deep Learning depende del tamaño del conjunto de datos, la complejidad del problema y los recursos disponibles.<br><br>- Este proyecto sirve como base para comprender las diferencias entre ambos enfoques y su aplicación práctica en problemas de predicción.</p>

###

<h3 align="left">Tecnologías utilizadas</h3>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" height="40" alt="tensorflow logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" height="40" alt="pandas logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/visualstudio/visualstudio-plain.svg" height="40" alt="visualstudio logo"  />
</div>

###
