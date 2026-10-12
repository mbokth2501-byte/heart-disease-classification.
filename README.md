# Heart Disease Classification Using Machine Learning

## Project Overview

This project uses machine learning to analyze the Cleveland Heart Disease dataset and evaluate different classification models for predicting the presence of heart disease.

The goal was to explore the data, train multiple machine learning models, compare their performance, and identify the model that performed best based on evaluation metrics.

## Objectives

- Explore and prepare the dataset for machine learning.
- Train and compare multiple classification models.
- Evaluate model performance using different metrics.
- Examine feature importance and identify variables that influence model predictions.
- Interpret the results and discuss the limitations of the models.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Machine Learning Models

The following models were trained and compared:

1. Logistic Regression
2. Decision Tree
3. Random Forest
4. K-Nearest Neighbors (KNN)
5. Support Vector Machine (SVM)

## Results

Logistic Regression achieved the strongest overall performance among the models evaluated in this project.

| Evaluation Metric | Logistic Regression |
|---|---:|
| Accuracy | 85.2% |
| Precision | 85.3% |
| Recall | 87.9% |
| F1-Score | 86.6% |

The model was evaluated using a held-out test set of 61 observations. These results reflect performance on this particular test set and may vary with different data splits.

## Key Findings

- Logistic Regression performed best overall among the five models tested.
- Recall was approximately 87.9%, meaning the model correctly identified 29 of the 33 positive cases in the test set.
- Confusion matrices and classification metrics helped evaluate the strengths and weaknesses of each model.
- Feature importance analysis was used to explore which variables contributed to model predictions.

## Limitations

This project is intended for educational purposes. The test set was relatively small, and the results do not establish that the model is reliable for real-world medical diagnosis. Further validation on independent datasets would be necessary before considering any clinical application.

## How to View the Project

Open `Heart Disease ML.html` to review the notebook's code, analysis, visualizations, and results.

## Conclusion

This project provided practical experience in data exploration, machine learning model development, model evaluation, and interpreting classification results using Python.

