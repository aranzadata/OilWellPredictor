# Análisis de riesgos/beneficios de posibles locaciones para el desarrollo de nuevos pozos petroleros

El objetivo de este trabajo es ayudar a determinar la región geográfica más óptima para el desarrollo de 200 nuevos pozos petroleros de la compañía Oily Giant, a través del cálculo de ganancias potenciales y el riesgo de pérdidas económicas.

Para lograr este objetivo se crea un modelo de aprendizaje supervisado que predice el volumen de reservas de crudo a partir de parámetros indicadores de calidad. Posteriormente se calcula la raíz del error cuadrático medio para evaluar la calidad de este modelo implementado en las tres regiones de estudio. 

Después se diseña una función para calcular las ganancias proyectadas para los 200 pozos con mayores reservas estimadas en cada una de las tres regiones. Posteriormente se utiliza el método de bootstrap para 1000 submuestras de 500 pozos para calcular la ganancia promedio total y su intervalo de confianza de 95% para cada región. Además se calcula el riesgo de pérdidas expresado como probabilidad.

Finalmente se encuentra la región con mayor potencial de ganancias y menos riesgo de pérdidas.

Para este análisis se consideran los siguientes puntos:

· Al explorar la región, se lleva a cabo un estudio de 500 puntos con la selección de los mejores 200 puntos para el cálculo del beneficio.

· El presupuesto es de 100 millones de dólares.

· Un barril de materias primas genera 4.5 USD de ingresos. 

· Se mantienen solo las regiones con riesgo de pérdidas inferior al 2.5%. De las que se ajustan a los criterios, se selecciona la región con el beneficio promedio más alto.
