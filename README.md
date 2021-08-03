# Insulete_challenge

Prueba para Insulete.

Challenge de 4 horas para resolver un problema de regresión, donde la variable target tiene tanto valores negativos como positivos y en escala de 10^5.

Se realizo la lectura de los datos, el análisis exploratorio descriptivo y la implementación de varios modelos con sklearn como:

- Regresión Ridge
- Regresión Lasso
- Arboles de Decisión
- Random Forest
- Gradient Boosting Machine

Evitando el Data Leakage al estandarizar los datos para las regresiónes y haciendo una limpieza de valores nulos, aplicando el método de Tukey.

Se evaluan los modelos por medio del RMSE donde la cota superior es de 77,500u y la cota inferior es de 10u, Obteniendo un resultado del mejor modelo como el arbol de decision con profundidad maxima de 11 con un RMSE 50,000
Se interpretan el resultado del modelo, aplicando importancia de variables, efectos marginales, importancia por permutación y SHAP values.
