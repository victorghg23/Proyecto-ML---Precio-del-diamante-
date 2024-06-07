# Proyecto - ML ¿Precio del diamante? 💶💎
## Estado
Proyecto finalizado del Modulo 3 de IronHack
## Herramientas usadas en el proyecto ⚒️

He tenido que hacer uso de dos Jupyter Noteboks: 
* ___Jupyter Notebook Train RFR:___ En este JN, me he encargado de realizar la limpieza de datos y el "Encoding Categorical Data" correspondiente del CSV extraído de una base de datos SQL, además por supuesto, del entrenamiento gracias al modelo Random Forest Regression.
* ___Jupyter Notebook Test RFR:___ Por otro lado, en el JN Test he calcado la limpieza de datos del DataFrame del anterior JN para que se puediese hacer el Test y he añadido un CSV donde única y exclusivamente aparecían unas features completamente nuevas que el modelo no se había estudiado previamente, y en el que por tanto el precio no aparece para así poder realizar la predicción oportuna

### 1. Python
* Pandas
* sqlite3
* numpy
* pickle
### 2. Sklearn
* LabelEncoder
* train_test_split
* RandomForestRegressor
* GridSearchCV
* RandomizedSearchCV
* make_regression
* mean_squared_error

## ¿Por qué este proyecto? 💭
Crear una herramienta que sea capaz de predecir ya no solamente el precio de los diamantes... Puede marcar un antes y un después en el ahorro del tiempo y del dinero del potencial cliente, el cuál será capaz de saber con un simple 'click' el precio del producto que desea conocer en función de sus características. De hecho, ¡¡gracias a este proyecto podríamos hasta conocer el precio del 'Diamante de Sangre' de Leonardo di Caprio!!

![image](https://www.telemadrid.es/2018/02/12/programas/cine/miercoles-Cine-Cortes-Diamantes-sangre_1984921523_4025198_640x360.png)

## Problema del proyecto 💩
En realidad no es un problema, sino más bien un inconveniente... Cada predicción puede tardar en torno a las 2 horas en adelante. Además de que el ordenador no se puede quedar apagado, porque si no la predicción se pararía y deberíamos de comenzar de cero.
