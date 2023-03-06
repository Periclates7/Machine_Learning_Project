![Cabecera](https://github.com/Periclates7/Machine_Learning_Project/blob/main/img/brain%20lightning_3.jpg)

# 🌳 MACHINE LEARNING PROJECT -> PREDICTING SALARIES (KAGGLE COMPETITION) 🏆  
  
El presente proyecto nace de la inscripción a la competición de Kaggle ["Predict the Salary for Data Science Jobs"](https://www.kaggle.com/competitions/predict-salary-for-data-science-jobs/). La competición se basa en el entrenamiento de modelos de *Machine Learning* para la predicción salarios en posiciones relativas a la ciencia de datos. Para ello se cuenta con tres archivos .csv. El primero para entrenar nuestros modelos, el segundo para testearlos y el tercero nos servirá como herramienta para competir.
  
## 🎯 OBJETIVOS DEL PROYECTO 
  
1. Crear un repositorio en GitHub con una buena organización de los recursos.
2. Extraer los datos de manera óptima.
3. Aplicar herramientas, técnicas y metodologías para la limpieza de datos acordes a nuestras necesidades:
    - Filtrado de los datos extraidos
    - Exploración del conjunto de los datos
    - Limpieza de valores nulos
    - Transformación de diferentes conjuntos de datos
    - Librerías utilizadas: Pandas, Numpy, Pylab, Seaborn, Sklearn.
3. Analizar, Adecuar y codificar los datos para ser entrenados.
4. Aplicar modelos de *Machine Learning*.
5. Evaluar dichos modelos.
6. Hacer predicciones con nuestros modelos.
7. Exportar y cargar en Kaggle nuestras predicciones.
  
## ⛏ ANÁLISIS Y LIMPIEZA DE LOS DATOS  
  
Nos encontramos con un *dataset* que contiene el salario de diferentes posiciones en el ámbito de la ciencia de datos según varias variables tales como, el tipo de empleo, la posición, el país o su nivel de experiencia entre otras. El conjunto de datos es un conjunto muy limpio, con los datos bastante consistentes pero inoperativos ya que la mayoría de las columnas son categóricas. El gran reto de este proyecto será el codificar dichas columnas de la manera más acertada para que nuestros modelos puedan trabajar con el máximo rendimiento. 
  
Esta transformación parte de un análisis exhaustivo de las columnas a transformar. En su mayoría, intento determinar la relevancia de cada dato para codificarlo en base a su importancia. Esto nos creará un sesgo, sí, pero un sesgo basado en los datos. Por otro lado también se prueban técnicas de *one-hot-encoding* para aquellas columnas que no estaban tan claramente jerarquizadas.
  
Cabe destacar que el proceso de transformación del dato se ha visto modificado a lo largo de la realización del proyecto con el fin de testear cuantas más posibilidades y de esta manera conseguir el mayor rendimiento en nuestros modelos.
  
## 🦾 ENTRENAMIENTO Y TESTEO DE MODELOS  
