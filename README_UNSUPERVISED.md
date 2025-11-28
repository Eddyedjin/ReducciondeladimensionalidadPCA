# ReducciondeladimensionalidadPCA
1.Descripcion de la Tecnica y Justificacion de la Eleccion
Tecnica Utilizada
Se implemento el Analisis de Componentes Principales (PCA), una tecnica de reduccion de dimensionalidad no supervisada. ya que busca transformar un conjunto de variables posiblemente correlacionadas en un conjunto de un menor numero de variables no correlacionadas, llamadas Componentes Principales. Estos componentes son combinaciones lineales de las variables originales, y estan diseñados para capturar la mayor varianza posible en los datos.

Justificacion de la Eleccion
La eleccion de PCA se justifica por que:
-Identificar Redundancia y Multicolinealidad, Permite evaluar si existe una alta correlacion entre las variables numericas del dataset de entrenamiento.
-Simplificacion del Modelo: Se busca explorar una representacion de menor dimension que conserve la informacion relevante para el riesgo crediticio. Esto podria conducir a un modelo supervisado mas simple, rapido y estable.
-Analisis Estructural: Permite comparar la estructura de los Componentes Principales con las variables mas importantes obtenidas del modelo de scoring supervisado. Esto ayuda a validar si la esencia de la informacion predictiva se mantiene en el subespacio de menor dimension.


