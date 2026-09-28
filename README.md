Student Performance Prediction

Project Overview

This project uses machine learning to predict a student's math score based on information such as gender, race/ethnicity, parental education, lunch type, test preparation course, reading score, and writing score.

The goal of the project is to practice the complete machine learning workflow, from loading and preprocessing data to training, evaluating, and comparing different models.

Dataset:

The project uses the students performance in exams dataset.

The dataset contains 1000 student records and includes information about:

Gender
Race/Ethnicity
Parental Level of Education
Lunch
Test Preparation Course
Math Score
Reading Score
Writing Score

Machine earning Workflow:

The project follows these steps:

1. Load and explore the dataset
2. Check for missing values
3. Select the target variable
4. Encode categorical features
5. Split the data into training and testing sets
6. Train a linear regression model
7. Train a random forest model
8. Evaluate the models using MAE and R squared
9. Use cross-validation
10. Perform hyperparameter tuning
11. Make a prediction for a new student
12. Save the trained model

Models:

Two main machine learning models were tested:

Linear regression
Random forest regressor

Hyperparameter tuning was also performed for the random forest model using GridSearchCV.

Results:

 Model                  MAE    R squared
 Baseline             12.33     — 
 Linear regression     4.21  0.88 
 Random forest         4.74  0.84 
 Tuned random forest   4.60  0.85 

For this dataset and test split, the linear regression model achieved the lowest test MAE among the models evaluated.

Example prediction

The trained linear regression model was also used to predict the math score of a new student based on the student's available information.


Technologies Used

Python
Pandas
NumPy
Scikit-learn
Matplotlib
Joblib
Jupyter notebook

Conclusion

This project demonstrates a complete basic machine learning workflow, including data preprocessing, model training, evaluation, comparison, hyperparameter tuning, prediction, and model saving.
