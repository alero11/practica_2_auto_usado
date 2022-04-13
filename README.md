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

#importamos las librerias
%matplotlib inline
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import pandas as pd
import re
import datetime
from sklearn.model_selection import train_test_split


## EDA (AnalIsis Exploratorio de Datos)

![image](https://user-images.githubusercontent.com/16781247/161183677-7172b1df-944b-4108-9486-703b9db27657.png)

información de los campos

![image](https://user-images.githubusercontent.com/16781247/161183789-b7c36f31-8eec-4559-8633-62d90373187a.png)

se tiene el analisis de dato por dato

![image](https://user-images.githubusercontent.com/16781247/163121971-7cdeb0fb-fa48-45c0-b9d8-3b7babc979b0.png)

![image](https://user-images.githubusercontent.com/16781247/163122050-5dd5e416-be12-474d-b98f-cb1b3cad78f4.png)

![image](https://user-images.githubusercontent.com/16781247/163122083-63b99d14-6de4-42b8-89c4-5873cecde0a9.png)

## Resultados

Dado que el conjunto de datos se tiene la predicción

![image](https://user-images.githubusercontent.com/16781247/163121107-7390cb1f-8ad0-406b-9653-8bb48352457e.png)

la prediccion seria 

![image](https://user-images.githubusercontent.com/16781247/163122413-ff0cd817-1a4b-4ddf-8a4d-b76da38b42d1.png)


## Conclusiones

dados los valores del dataset se predice que hay una reducción en el precio de 1000 al conjuto de datos original

## Publicación

puede visualizar el articulo en MEDIUM

https://medium.com/@alexr.torob/practica-2-prediccion-precio-autos-usados-cb5ffe8132f6


## License
This project is published in 2022 under MIT license.
