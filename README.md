# practica 2 Prediccion precio autos usados

Con el aumento en la variedad de automóviles con capacidades y características diferenciadas, como modelo, año de producción, categoría, marca, tipo de combustible, volumen del motor, millaje, cilindros, color, bolsas de aire y muchos más, presentamos un desafío de predicción de precios de automóviles para todos. Todos aspiramos a tener un automóvil dentro del presupuesto con las mejores características disponibles. Para resolver el problema del precio, hemos creado un conjunto de datos de 19237 para el conjunto de datos de entrenamiento y 8245 para el conjunto de datos de prueba.

## Requerimientos

Librerias requeridas:

Python 3
Scikit-learn
Seaborn

Puede descargar el dataset aqui:

https://neuraldojo.org/media/carprice/archive.zip

puede crear una carpeta dentro del proyecton con el nombre "data"

pegue ahi el archivo .csv.

## Librerias



## Dataset

![image](https://user-images.githubusercontent.com/16781247/161183677-7172b1df-944b-4108-9486-703b9db27657.png)

información de los campos

![image](https://user-images.githubusercontent.com/16781247/161183789-b7c36f31-8eec-4559-8633-62d90373187a.png)

información estadistica de los datos

![image](https://user-images.githubusercontent.com/16781247/161184043-7d5bd086-60a2-4585-b235-c000ae8329b6.png)

## Resultados

Se han realizado pruebas con RandomForest, AdaBoostClassifier y GradientBoostClassifier. De todos ellos, obtuvimos la mejor puntuación con AdaBoosClassifier. Para las métricas, se utilizó el promedio "Macro" ya que el conjunto de datos está desequilibrado.

Evaluación total sobre todas las categorías: Precisión: 0.7763, Recordación: 0.6473, FScore: 0.6793

## Conclusiones

Dado que el conjunto de datos tiene un sin fin de valores, procederemos a utilizar el 'promedio macro' para las métricas de evaluación del modelo. Por lo tanto, el macropromedio da a cada clase la misma importancia y, por lo tanto, refleja mejor qué tan bien se desempeña el modelo.


## License
This project is published in 2022 under MIT license.
