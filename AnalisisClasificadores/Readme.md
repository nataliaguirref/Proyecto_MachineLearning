Dados los resultados de la matriz de correlacion trabajaremos con las siguientes variables:

- FFVV_final. Los vendedores que llevan realizando pedidos en los ultimos 3 catálogos
- Activos. Los vendedores del último catálogo
- Reclutados. Los recluatados de cada catálogo

Estimar los reclutados es el fin de este análisis, ya que, teniendo el dato mas preciso se realiza la compra de los incentivos y se reduce el gasto, los sobrantes o faltantes. 

## Clasificadores Supervisados 

Con esta función se trata de crear una relación entre la FFVV final vs los Activos para obtener la mejor estimación de los reclutados para los siguientes catálogos. 

[Regresión Lineal](Clasificacion_Supervisada.ipynb)

## Elección de Clasificadores

Para elegir el mejor clasificador que se adapte a nuestra data y nos de la mejor estimación de reclutados, se analizaron los siguientes:

- Random Forest
- Redes Neuronales Artificiale
- Support Vector Machine

Se entrenaron los modelos de acuerdo a las especificaciones de cada clasificador y se calcularon las variables de precisión, sensibilidad y especificidad para cada uno, así como también la matriz de confusión para obtener la mejor comparación. 

[Clasificadores y Redes Neuronales](Clasificadores.ipynb)

