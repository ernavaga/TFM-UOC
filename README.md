# TFM-UOC
Aplicación de _Machine Learning_ para la Gestión de Inventarios
Trabajo Final de Máster de Ciencia de Datos @UOC

Este repositorio contiene los códigos utilizados para la elaboración del trabajo final de Master de Ciencia de Datos en la UOC.

Para la elaboración de este trabajo se utilizaron datos anonimizados de unidades de venta de una empresa manufacturera de autopartes, el objetivo de realizar un pronóstico de previsión de la demanda utilizando Machine Learning. Adicional a los modelos elaborados se construyó una herramienta de visualización de datos en Tableau Public [TFM Dashboard](https://public.tableau.com/app/profile/ernavaga/viz/TFM_16383257266830/DashboardTendencias).

El dataset está integrado por 50 productos, cada uno con 1,022 registros; cada registro corresponde al volumen de ventas diario del periodo 2 enero 2019 a 10 octubre 2021.

Los notebooks con tienen los siguientes procesos:
* TFM_AnálisisExploratorio.ipynb: Contienen la lectura de los datos origen, la limpieza de los mismos y la transformación que tiene como resultado el *dataset* final. Se abora el análsis exploratorio de los datos, imputación de valores ausentes y tratamiento de valores atípicos.
* TFM_Correlación_50sku.ipynb: Creación de nuevas variables y análisis de correlación.
* TFM_CrossValidation_RF-NN-SVR.ipynb: Elección del modelo.
* TFM_Parámetros.ipynb: Elección de rango de parámetros a utilizar.
* TFM_RandomForest_50sku.ipynb: Entrenamiento y resultado de los modelos.
