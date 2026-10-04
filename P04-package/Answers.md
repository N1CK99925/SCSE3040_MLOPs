__init__.py - this makes all the files in a folder to a package so that one can use them anywhere.

data.py - loads and splits the data.

features.py - does descriptions and calc for the average speed.

model.py  -  training scoring and converitng the model into a .joblib file.

validate.py - checks if the funcs all pass the rules 

predict.py - uses model to pridct the given delivery time from the cli.

train.py - train the model with linearRegression on the dataset.