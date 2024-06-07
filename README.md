# Proyecto - ML ¿Precio del diamante? 💶💎
## Estado
Proyecto finalizado del Modulo 3 de IronHack
## Herramientas usadas en el proyecto ⚒️

He tenido que hacer uso de dos Jupyter Noteboks: 
* ___Jupyter Notebook Train RFR:___ En este JN, me he encargado de realizar la limpieza de datos y el "Encoding Categorical Data" correspondiente del CSV extraído de una base de datos SQL, además por supuesto, del entrenamiento gracias al modelo Random Forest Regression.
* ___Jupyter Notebook Test RFR:___ Por otro lado, en el JN Test he calcado la limpieza de datos del DataFrame del anterior JN para que se puediese hacer el Test y he añadido un CSV donde única y exclusivamente aparecían unas features completamente nuevas que el modelo no se había estudiado previamente y en el que por tanto, el precio no aparece para así poder realizar la predicción oportuna

### Python
* Pandas
* sqlite3
* numpy
* pickle
### Sklearn
* LabelEncoder
* train_test_split
* RandomForestRegressor
* GridSearchCV
* RandomizedSearchCV
* make_regression
* mean_squared_error
