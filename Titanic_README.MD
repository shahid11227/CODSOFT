🚢 Titanic Survival Prediction
 Project Overview

This project builds machine learning models to predict whether a passenger survived the Titanic disaster.
Using demographic and travel-related features, multiple classification models are trained and evaluated to determine the best performing model.

This is a classic supervised machine learning classification problem.

 Objective

To develop a predictive model that determines whether a passenger survived or not based on:

Age

Gender

Passenger Class (Pclass)

Fare

Number of Siblings/Spouses (SibSp)

Number of Parents/Children (Parch)

Embarked Port

 Dataset Information

The dataset contains passenger-level information including:

Survived (Target Variable)

Age

Sex

Pclass

Fare

SibSp

Parch

Embarked

Cabin (Dropped due to many missing values)

 Project Workflow
1. Data Exploration

Checked dataset shape and structure

Identified missing values

Checked duplicates

2. Data Cleaning

Filled missing Age with mean

Filled missing Embarked with mode

Dropped Cabin column

3. Feature Engineering

Converted Survived (0/1) → “Died” / “Survived”

Applied Label Encoding to categorical features

4. Feature Selection

Selected important features:

Age, Sex, Embarked, Pclass, SibSp, Parch, Fare
5. Train-Test Split

80% Training Data

20% Testing Data

🤖 Models Implemented

Decision Tree Classifier

Random Forest Classifier

Logistic Regression

 Model Evaluation

Models were evaluated using:

Accuracy Score

Classification Report (Precision, Recall, F1-score)

Confusion Matrix

 Results

Among the trained models, Random Forest Classifier achieved the best performance with higher accuracy and balanced precision-recall scores compared to other models.

 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

 Conclusion

This project demonstrates how machine learning can be applied to real-world classification problems.
Through proper preprocessing, feature selection, and model comparison, we successfully built a predictive system for passenger survival.

👤 Author

Shahid
Machine Learning & Data Science Enthusiast
