# Mod_2_Analisis_y_Reporte


## Descripcion de los modelos

### Arbol de Decisiones
DecisionTreeClassifier es un algoritmo utilizado para el aprendizaje supervisado, el cual se usa para clasificar una serie de datos y poder predecir que rumbo tomaran los datos con respecto a ciertos parametros. La estructura de este modelo se divide en:

- El arbol de decisiones, donde los datos que se clasificaran tendran una serie de atributos o etiquetas.
- Luego esta la division de los datos, donde el algoritmo esta separando los datos en subconjuntos mas pequeños los cuales estan categorizados por las etiquetas, el objetivo de este paso es limpiar las impurezas que puedan existir.
- Luego estan los criterios de division, se tienen varios como la ganancia de informacion, indice de Gini y el error de clasificacion. El objetivo de estos es revisar la pureza de la division de los datos.
- Luego se tiene la profundidad del arbol, estos arboles pueden llegar a ser muy profundos si no se controla o limita su crecimiento. Para evitar un sobreajuste, se suele establecer limites en la profundidad maxima la cual puede alcanzar un arbol de decisiones.
- Una vez ya creado el arbol, se puede seguir el camino para crear una prediccion y al final cada respuesta que se le de a cada creterio de cada nodo guiara a la respuesta final en una de las hoja creadas.

### Regresion Logisitca / Regresion Lineal



## Estructura

- El archivo "iris.data" contiene los datos que se utilizaron para hacer las pruebas.
- El archivo "decision_tree.ipynb" es donde se estara utilizando el algoritmo de Arbol de decisiones
- El archvio "logistic_regresion.ipynb" es donde se estara utilizando el algoritmo de Regresion Logistica.


- El archivo "main.ipynb" es el que se estara revisando, el cual contiene ambos algoritmos introducidos a un mismo archivo, esto con el fin de poder probar cada archivo por separado previo a su implementacion en un mismo archivo.

## Descripcion del dataset

