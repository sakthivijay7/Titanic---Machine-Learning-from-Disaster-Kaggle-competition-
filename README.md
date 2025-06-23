# Titanic-Machine-Learning-from-Disaster-Kaggle-competition-
Kaggle competition page: https://www.kaggle.com/competitions/titanic
Data collection:
Data collect from kaggle competition page train and test data.

Data handle:
pandas to read the files and check null values.

Null values handle:
Fill numerical values fill with median .

Features:
selected columns -'PassengerId', 'Pclass', 'Sex', 'Age', 'SibSp', 'Parch', 'Fare'.

Target:
"Survived"

Encoding:
Get dummies to encoding the categorical values.

Model:
Training a model with LogisticRegression,DecisionTreeRegressor,RandomForestRegressor.

Submission:
submitted the DataFrame of test data :PassengerId  and predicted: "Survived" to csv format.

Result:
Got public score 0.76555/1.000





