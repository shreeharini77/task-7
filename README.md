# Titanic Survival Prediction using Logistic Regression

## About the Project
This project is done as part of **AI & ML Internship – Task 7**.  
The goal of this task is to predict whether a passenger survived the Titanic disaster using **Logistic Regression**, which is a binary classification algorithm.

## Dataset Used
- Titanic dataset loaded using Seaborn (`load_dataset('titanic')`)
- Important features used:
  - Age
  - Sex
  - Fare
  - Embarked
  - Survived (target column)

## Steps Performed
1. Loaded the Titanic dataset
2. Selected only important columns
3. Handled missing values in Age and Embarked
4. Converted categorical columns into numeric form using One Hot Encoding
5. Applied feature scaling on Age and Fare
6. Split the data into training and testing sets
7. Trained the Logistic Regression model
8. Made predictions on test data
9. Evaluated the model using:
   - Accuracy
   - Precision, Recall, F1-score
   - Confusion Matrix
   - ROC Curve and AUC score

## Tools and Libraries Used
- Python
- Pandas
- Seaborn
- Scikit-learn
- Matplotlib

## Results
- The Logistic Regression model was able to predict passenger survival with good accuracy.
- Confusion Matrix was used to analyze correct and incorrect predictions.
- ROC Curve and AUC score were used to evaluate overall model performance.

## Conclusion
Through this task, I learned how Logistic Regression works for binary classification problems and how to evaluate a machine learning model using different performance metrics and graphs.
