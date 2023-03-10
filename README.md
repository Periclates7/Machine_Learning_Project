![Cabecera](https://github.com/Periclates7/Machine_Learning_Project/blob/main/img/cabecera_repo.jpg)

# 馃尦 MACHINE LEARNING PROJECT -> PREDICTING SALARIES (KAGGLE COMPETITION) 馃弳  
  
El presente proyecto nace de la inscripci贸n a la competici贸n de Kaggle ["Predict the Salary for Data Science Jobs"](https://www.kaggle.com/competitions/predict-salary-for-data-science-jobs/). La competici贸n se basa en el entrenamiento de modelos de *Machine Learning* para la predicci贸n salarios en posiciones relativas a la ciencia de datos. Para ello se cuenta con tres archivos .csv. El primero para entrenar nuestros modelos, el segundo para testearlos y el tercero nos servir谩 como herramienta para competir.
  
## 馃幆 OBJETIVOS DEL PROYECTO 
  
1. Crear un repositorio en GitHub con una buena organizaci贸n de los recursos.
2. Extraer los datos de manera 贸ptima.
3. Aplicar herramientas, t茅cnicas y metodolog铆as para la limpieza de datos acordes a nuestras necesidades:
    - Filtrado de los datos extraidos
    - Exploraci贸n del conjunto de los datos
    - Limpieza de valores nulos
    - Transformaci贸n de diferentes conjuntos de datos
    - Librer铆as utilizadas: Pandas, Numpy, Pylab, Seaborn, Sklearn.
3. Analizar, Adecuar y codificar los datos para ser entrenados.
4. Aplicar modelos de *Machine Learning*.
5. Evaluar dichos modelos.
6. Hacer predicciones con nuestros modelos.
7. Exportar y cargar en Kaggle nuestras predicciones.
  
## 鉀? AN脕LISIS Y LIMPIEZA DE LOS DATOS  
  
Nos encontramos con un *dataset* que contiene el salario de diferentes posiciones en el 谩mbito de la ciencia de datos seg煤n varias variables tales como, el tipo de empleo, la posici贸n, el pa铆s o su nivel de experiencia entre otras. El conjunto de datos es un conjunto muy limpio, con los datos bastante consistentes pero inoperativos ya que la mayor铆a de las columnas son categ贸ricas. El gran reto de este proyecto ser谩 el codificar dichas columnas de la manera m谩s acertada para que nuestros modelos puedan trabajar con el m谩ximo rendimiento. 
  
Esta transformaci贸n parte de un an谩lisis exhaustivo de las columnas a transformar. En su mayor铆a, intento determinar la relevancia de cada dato para codificarlo en base a su importancia. Esto nos crear谩 un sesgo, s铆, pero un sesgo basado en los datos. Por otro lado tambi茅n se prueban t茅cnicas de *one-hot-encoding* para aquellas columnas que no estaban tan claramente jerarquizadas.
  
Cabe destacar que el proceso de transformaci贸n del dato se ha visto modificado a lo largo de la realizaci贸n del proyecto con el fin de testear cuantas m谩s posibilidades y de esta manera conseguir el mayor rendimiento en nuestros modelos.
  
## 馃 ENTRENAMIENTO Y TESTEO DE MODELOS  
  
Una vez preparado el dato para ser entrenado, me apoyo en herramientas comparadoras de modelos de *Machine Learning* tales como *Lazy* o H2O. Ambas herramientas concluyen lo mismo. Con los datos que manejamos el modelo que m谩s rendimiento alcanza es el modelo lineal *Huber Regressor* de la librer铆a *SKLearn*.
  
A partir de este momento la labor consistir谩 en hacer peque帽as modificaciones en los datos y su limpieza para intentar exprimir nuestro modelo al m谩ximo. Para el mismo fin, se ha hecho un trabajo de *Grid searching* para encontrar los par谩metros 贸ptimos de nuestro modelo.
  
## 馃摑 CONCLUSIONES
  
Con la realizaci贸n de este proyecto me doy cuenta de la existencia de un sin fin de modelos y herramientas a nuestro alcance para realizar predicciones. Sin embargo, considero que la parte m谩s fundamental del proceso es la limpieza, preparaci贸n y etiquetaci贸n del dato. Sin realizar de manera adecuada este proceso, nuestros modelos carecer谩n de la consistencia y fiabilidad necesaria para ser tomados como v谩lidos.
  
Por otro lado concluyo, que las iniciativas tales como la impulsora de este proyecto (competici贸n de Kaggle), son una excelente manera para que los participantes aprendan, se desaf铆en a s铆 mismos, construyan su reputaci贸n y ganen reconocimiento en el campo de la ciencia de datos.
