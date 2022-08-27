# Pima_Indians_Diabetes Project

### Input Dataset
------------------------------
https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database

### Dataset details
===============

1: Pregnancies: Number of times pregnant

2: Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test.

3: BloodPressure: Diastolic blood pressure (mm Hg)

4: SkinThickness: Triceps skinfold thickness (mm)

5: Insulin: 2-Hour serum insulin (mu U/ml)

6: BMI: Body mass index (weight in kg/(height in m)²)

7: DiabetesPedigreeFunction: Diabetes pedigree function

8: Age: Age (years)

9: Outcome: Class variable (0 or 1) 268 of 768 are 1, the others are 0

## EDA (Exploratory Data Analysis):

1: Analyse the target variable

2: Explore dataset to understanda which type of algorithms can be used to solve this 
   problem.
   
3: After exploring the data I understand that this is a classification problem so we can solve
   this using classification algorithms
   
4: Check the dataset information such as  shape , info , describe.

5: Check whether there is any missing values.

6: Plot the heatmap using correlation in input dataset.

## Pairplot :

1: After plairploting it shows some arguments have zero values And also outliers.
2: Considering zero as missing value replace it with median is less robust to outliers.
3: To threat outliers check continuous columns and cap it with standard deviation

## Train Test Split :
1 : Done train_test_split as X_train and y_train.

## Scale Down :
1: it is done using StandardScaler function.
2: X_train scaled using fit-transform and X_test scaled using transform
3: Create pickle file of scale down using joblib

## Algorithm :
1: Apply all classification algorithms such as LogisticRgression,
   DecisionTreeClassifier,SVC.
2: Check the score of X&y train and accuracy of X&y test

## Hyperparameter Tunning :
1: Hypperparameter tuning done in al algorithms for find the best model.
2: And print the tain accuracy,test accuracy and best parameter
3: I choose SVC as best model in the basis of accuracy values.
4: Create pickle file of model using joblib

Flask :
1: set the backend api using flask.
3: The User Interface is set using html code.

## Model Deployment :
 Connect with heroku 
 https://ai-diabetes.herokuapp.com/







  
