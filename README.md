Titanic Survival Prediction

Project Overview

This project aims to predict whether a passenger survived the Titanic disaster using machine learning classification models. The dataset was already cleaned as part of the IBM Data Science course practice project. The focus of this project is on preprocessing, model training, hyperparameter tuning, and model evaluation.

Dataset

The project uses the Titanic dataset, which contains information about passengers such as age, sex, passenger class, fare, family size, and embarkation port. The target variable is Survived.

Project Workflow

- Load the cleaned dataset.
- Split the data into training and testing sets.
- Build a preprocessing pipeline for numerical and categorical features.
- Train multiple machine learning models.
- Tune hyperparameters using GridSearchCV.
- Evaluate the models using classification metrics.
- Compare model performance and select the best model.

Machine Learning Models

- Logistic Regression
- Random Forest Classifier

Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall (True Positive Rate)
- F1-score
- Confusion Matrix

Results

Both models achieved good performance. However, the Random Forest Classifier slightly outperformed Logistic Regression across the evaluation metrics,
making it the preferred model for predicting passenger survival.

         Model| Accuracy| Precision| Recall| F1-score
Logistic Regression:| 0.82| 0.80| 0.71| 0.75
Random Forest      :| 0.82| 0.78| 0.72| 0.75

Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

How to Run

1. Install the required libraries.
2. Open the Jupyter Notebook.
3. Run all notebook cells to reproduce the results.

Conclusion

This project demonstrates a complete machine learning classification workflow. 
Although both models performed well, the Random Forest Classifier achieved slightly better predictive performance and was selected as the final model.
