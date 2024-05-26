### Preguntas sobre los datos

* Cuántas tipos de canastas diferentes existen
* Cuántos productos son incluidos en las canastas.
* Productos más vendidos.
* Cuándo compran los usuarios, análisis temporal
* Cuál es el tamaño de la canasta
* Qué productos son comprados en: Día, semana, mes
* Cuándo las personas compran, análisis por horario
* Qué productos no sean comprado
* Tamaño de la canasta por día, semana y mes

### tareas

* ~~cambiar en pairs, distribución, número por nombre~~
* ~~agregar conclusiones en análisis de estacionalidad. residual, observado~~
* ~~auto correlación~~
* ~~correlación entre los top10 productos, con mapa de calor.~~
* terminar análisis de monte carlo para hacer el análisis de shapiro wilks para verificar si existe o no homogeneidad en datos de ventas y luego en transformación - box-cox
* conclusiones  en autocorrelation
* conclusiones en correlation 10 productos
## tareas Modelos
* separar los notebook, uno solo para modelos y predicciones
* modelo AR, ARMA, ARIMA
    - fuente: https://www.kaggle.com/code/mehulgupta2016154/arima/notebook
    - AutoArima con Nixtla, fuente: https://nixtlaverse.nixtla.io/mlforecast/index.html
    - AutoArima con nixtla, https://nixtlaverse.nixtla.io/statsforecast/docs/getting-started/getting_started_short.html
    - mlforecast, https://nixtla.github.io/blog/machine%20learning/forecasting/2021/06/10/Intro-mlforecast.html


### ventas
* pairs
    - 
    - ~~se realizó para 10 productos top10~~
    - ~~se debe cambiar el cód. Prd por el nombre~~
* stationary, se realizó para redull
    -
    - ~~se aplicó ADF, link: https://www.analyticsvidhya.com/blog/2021/06/statistical-tests-to-check-stationarity-in-time-series-part-1/ ~~
    - ~~agregar conclusiones~~
* distributions
    -
    - ~~se realizó con pairs.~~
    - ~~análisis a red bull, dist. ventas~~
* box cox
    -
    - ~~transformación para realizar normalidad, se realizó para red bull~~
    - ~~test de homogeneidad con qq plot (eval. visual), antes y después- para verificar homogeneidad~~
    - ~~mostrar lambda óptimo calculado~~
    - ~~test con un estadístico, shapiro u otro.~~
    - ~~conclusiones~~
* autocorrelations
    -
    - ~~se realizo autocorrelation and partical correlation~~

* correlation entre top 10 productos
    - link: https://www.kaggle.com/code/bextuychiev/advanced-time-series-analysis-decomposition
    - ~~hacer un mapa de calor~~
    - ~~colocar nombre en números~~
    - conclusiones

* Fuentes
    - link:https://towardsdatascience.com/youve-got-a-time-series-now-what-38803e079175
