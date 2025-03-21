Titanic Survival Prediction

Project Overview

This project builds a machine learning model to predict whether a passenger survived the Titanic disaster based on various features such as age, ticket class, and gender.

Dataset

The dataset used is Titanic: Machine Learning from Disaster.

Source: Kaggle Titanic Dataset

Key Features:

Pclass: Passenger class (1st, 2nd, 3rd)

Sex: Gender of the passenger

Age: Age in years

Fare: Ticket fare

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Survived: Target variable (1 = Survived, 0 = Not Survived)

Technologies Used

Python

Pandas, NumPy (Data handling and preprocessing)

Matplotlib, Seaborn (Data visualization)

Scikit-learn (Model training and evaluation)

Data Preprocessing

Handled missing values by filling:

Age with mean value

Embarked with mode value

Converted categorical variables (Sex, Embarked) into numerical format.

Scaled numerical features for better performance.

Model Training

Split data into training (80%) and testing (20%) sets.

Used Logistic Regression to classify survival.

Evaluated model using accuracy score.

How to Run the Project

Clone the repository:

Install dependencies:

Run the Jupyter Notebook:

Results

The model achieved 78% accuracy .

Feature importance analysis showed that Sex, Pclass, and Fare significantly impact survival predictions.

Future Improvements

Try different models (Random Forest, SVM, etc.)

Perform feature engineering to enhance predictions.

Contributors

PARAMESHWAR S

