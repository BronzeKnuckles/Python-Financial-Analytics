# TODO:

    EDA
        Is my data balanced
        What are descriptive stats for each feature
        Are there outliers if so handle them in the way you determine best
        Are there missing values
        What is the correlation of my data
    Split your data
    Treating missing values if they were not dropped already
    Do I need transform my data?
    Do I need balance my data
    Can I create new features in my data
    Model your data. Use an algorithm to create a model
    Evaluate your model (Evaluation metrics, confusion matrix)
    Create more models and iterate on process
    Compare models
    Apply hyperparamter tuning (Use Gridsearch)
    Summarize findings


## Process

Import Libs 
EDA
    descriptive stats
    missing values 
        remove row if it was 5 missing values ? 
        How to handle other missing data?
    outliers? 
        remove outliers
    Correlation ? 
Normalize ?
Split data
    How? in what way?

....
---

Classification Report for Logistic Regression with Up-Sampling:

              precision    recall  f1-score   support

           0       1.00      0.71      0.83     18023
           1       0.01      0.50      0.02       114
           
    accuracy                           0.70     18137
   macro avg       0.50      0.60      0.42     18137
weighted avg       0.99      0.70      0.82     18137

---
Classification Report for Logistic Regression with Down-Sampling:
              precision    recall  f1-score   support

           0       0.99      0.69      0.81     18023
           1       0.01      0.45      0.02       114

    accuracy                           0.68     18137
   macro avg       0.50      0.57      0.41     18137
weighted avg       0.99      0.68      0.81     18137

---
Classification Report for Naive Bayes with Up-Sampling:
              precision    recall  f1-score   support

           0       1.00      0.17      0.29     18023
           1       0.01      0.91      0.01       114

    accuracy                           0.17     18137
   macro avg       0.50      0.54      0.15     18137
weighted avg       0.99      0.17      0.29     18137
---
Classification Report for Naive Bayes with Down-Sampling:
              precision    recall  f1-score   support

           0       0.99      0.94      0.97     18023
           1       0.03      0.24      0.05       114

    accuracy                           0.94     18137
   macro avg       0.51      0.59      0.51     18137
weighted avg       0.99      0.94      0.96     18137
---

Classification Report for KNN with Up-Sampling:
              precision    recall  f1-score   support

           0       1.00      0.94      0.97     18023
           1       0.04      0.32      0.06       114

    accuracy                           0.94     18137
   macro avg       0.52      0.63      0.52     18137
weighted avg       0.99      0.94      0.96     18137
---
Classification Report for KNN with Down-Sampling:
              precision    recall  f1-score   support

           0       1.00      0.81      0.90     18023
           1       0.02      0.61      0.04       114

    accuracy                           0.81     18137
   macro avg       0.51      0.71      0.47     18137
weighted avg       0.99      0.81      0.89     18137


---

#### end 
---

Classification Report for KNN with Up-Sampling:
              precision    recall  f1-score   support

           0       1.00      0.96      0.98     18023
           1       0.05      0.33      0.09       114

    accuracy                           0.96     18137
   macro avg       0.52      0.65      0.53     18137
weighted avg       0.99      0.96      0.97     18137

Classification Report for KNN with Down-Sampling:
              precision    recall  f1-score   support

           0       1.00      0.87      0.93     18023
           1       0.03      0.59      0.05       114

    accuracy                           0.87     18137
   macro avg       0.51      0.73      0.49     18137
weighted avg       0.99      0.87      0.93     18137