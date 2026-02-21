# Timely Payment Prediction  ✔️💳

Every business that invoices customers faces one common challenge:

- Ensuring invoices are paid on time.
- Late payments can disrupt cash flow, increase administrative costs, and affect the company’s ability to operate efficiently.
"We Provide All", a mid-sized B2B service provider, issues hundreds of invoices monthly to clients across various industries. Some clients pay promptly, while others consistently delay payments. The Operations Department want to anticipate payment delays so they can take preventive action such as early reminders, offering discounts, or adjusting payment terms.

This project is a machine learning pipeline for predicting timely payments (arrears vs. on-time) using financial and behavioral indicators. It is aimed at improving the performance of "We Provide All" in terms improving ontime payments. of  The notebook demonstrates a complete end-to-end workflow including data preprocessing, model training, hyperparameter tuning, and evaluation.

## Key Features

- Data Preprocessing: Handles missing values, scaling, and feature preparation for modeling.
- Modeling: Explores multiple classification algorithms:
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Logistic Regression
- Random Forest Classifier
- Hyperparameter Tuning: Uses GridSearchCV to identify the best model parameters.
- Evaluation Metrics: Focus on accuracy across cross-validation, training, and test sets.
  Also used confusion matrix to check for TP, TN, FP, and FN
  
## Insights

- Random Forest Classifier outperforms other models:
- CV Accuracy is consistent with Train Accuracy, indicating minimal overfitting.
- Test Accuracy is ≈ 0.9, showing strong generalization on unseen data.
- Other models (KNN, Decision Tree, Logistic Regression) perform reasonably well but either underfit or show more variance across CV folds.
- Features such as credit score, debt-to-income ratio, and number of late payments are important predictors for timely payment behavior.

## Tech Stack
- Python 3.12
- scikit-learn, numpy, pandas, matplotlib, seaborn

✔️  Check out Machine Learning on this  [link](https://github.com/Dcroix/Classification_Time_Payments/blob/main/Predicting%20Timely%20Payments%20Quick%20App%20Deploy%20Version.ipynb). (right-click → Open in new tab)  
✔️  Check out the Machine Learning Application on this [link](https://huggingface.co/spaces/Dcroix/CreditML). (right-click → Open in new tab)
