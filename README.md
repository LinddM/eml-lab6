# Logistic Regression

El dataset proporcionado es del archivo “wine_data.csv” parte de datos para el reconocimiento de vinos (donados por Riccardo Leardi y actualizado por by C.Blake), dentro del cual se muestran diferentes atributos que pueden servir para identificar la clase de vino (clase 1, clase 2 y clase 3, primera columna del archivo):

1) Alcohol
2) Malic acid
3) Ash
4) Alcalinity of ash
5) Magnesium
6) Total phenols
7) Flavanoids
8) Nonflavanoid phenols
9) Proanthocyanins
10)Color intensity
11)Hue
12)OD280/OD315 of diluted wines
13)Proline

Para este ejercicio se le pide que proporcione un modelo de regresión logística que prediga si la clase de vino usando todas las features que considere necesarias. A continuación se mencionan las generalidades de los pasos sugeridos a realizar:

1. Leer el archivo CSV proporcionado y almacenarlo en un np.array para ser trabajado en el notebook.
2. Ajustar un modelo de regresión logística en base al dataset cargado que relacione cualquier subconjunto propio de las variables de los indicadores seleccionados con la probabilidad de tener la clase.
3. Asegúrese de hacer los ajustes y trabajos necesarios al modelo que ha implementado para describir y predecir la información sobre la nube de datos.
4. Haga un análisis sobre sus hallazgos, donde mencione claramente las razones por las que considera que su modelo es bueno justificando adecuadamente.
