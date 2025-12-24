# Customer-Churn-Prediction

## Objective

The objective of this project is to predict customer churn and understand the factors that influence customer retention so that telecom companies can take proactive actions before customers leave.

## Model Used & Techniques Applied

- To solve this problem, a machine learning classification approach was used.

- Logistic Regression was applied as a baseline model due to its simplicity and interpretability.

- Random Forest was used to capture non-linear relationships and complex interactions between customer features.

The following techniques were applied:

- Data cleaning and preprocessing

- Encoding of categorical variables

- Train–test split for unbiased evaluation

- Model training and prediction

## How This Helps the Business

By predicting whether a customer is likely to churn, the model helps the business:

- Identify customers who are at risk of leaving

- Design targeted retention strategies

- Reduce revenue loss caused by churn

- Improve overall customer satisfaction

This approach allows the company to move from reactive decision-making to proactive customer management.

## Model Evaluation

To evaluate model performance, multiple metrics were used instead of relying only on accuracy, since churn datasets are usually class-imbalanced.

## Accuracy

The model achieved an overall accuracy of 78%, showing good performance on unseen data.

## Confusion Matrix

The confusion matrix shows that the model performs well in identifying non-churn customers, while predicting churn customers remains more challenging.

## Precision

Precision indicates that a good proportion of customers predicted as churn actually churned, making the predictions useful for targeted actions.

## Recall

Recall for churned customers is moderate, which is expected due to class imbalance. This highlights the challenge of identifying all churn cases.

## F1-Score

The F1-score balances precision and recall, providing a more realistic measure of churn prediction performance.

## Tools & Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

## Conclusion

Although churn prediction is challenging due to class imbalance, the model provides meaningful insights that can help telecom companies identify at-risk customers early and take data-driven retention actions.

## Project link : https://colab.research.google.com/drive/1HZhPVCzfvI7QT7tm41276ha8i_ri3Y9y#scrollTo=8ymiqMH5-Xx1
