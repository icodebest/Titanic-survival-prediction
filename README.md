# Titanic Survival Prediction Model

## Project Description

This project predicts the survival of passengers aboard the RMS Titanic using machine learning techniques. The dataset includes features such as passenger class, age, gender, and fare.

## Dataset

The dataset contains the following columns:
- `PassengerId`: Unique ID for each passenger
- `Survived`: Survival status (0 = No, 1 = Yes)
- `Pclass`: Passenger class (1st, 2nd, 3rd)
- `Name`: Passenger's name
- `Sex`: Passenger's sex
- `Age`: Passenger's age
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Ticket`: Ticket number
- `Fare`: Passenger fare
- `Cabin`: Cabin number
- `Embarked`: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Workflow

1. Perform Exploratory Data Analysis (EDA)
2. Preprocess the data (handle missing values, encode categorical variables, scale features)
3. Build and evaluate machine learning models
4. Optimize the model through hyperparameter tuning
5. Generate predictions and create a submission file

## Submission File

The submission file should be a CSV containing:
- `PassengerId`: Unique ID for each passenger
- `Survived`: Predicted survival status (0 = No, 1 = Yes)

Tools and Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn


Example of submission file:
```csv
PassengerId,Survived
892,0
893,1
894,0
895,1
896,0
