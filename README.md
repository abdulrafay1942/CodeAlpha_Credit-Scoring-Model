
# Credit Scoring Model (Machine Learning)

This project focuses on predicting an individual’s **creditworthiness**—in simple terms, how likely someone is to repay a loan—using past financial data. The goal is to build and evaluate machine learning models that can estimate the **probability of default** based on real-world financial behavior.

## What this project does

We use historical credit data that includes information such as income, debt ratio, number of loans, and past payment behavior. After cleaning the data and handling missing values, we apply feature engineering to extract more meaningful signals from the financial history. These features help the models better understand risk patterns.

Multiple classification algorithms are trained and compared, including:

* Logistic Regression
* Decision Tree
* Random Forest

Each model is evaluated using standard classification metrics like **Precision, Recall, F1-score, and ROC-AUC** to measure how well it separates risky borrowers from safe ones.

## Key result

Among all the models, **Random Forest performed the best**, achieving the highest ROC-AUC score. This indicates that it is the most effective at distinguishing between individuals who are likely to default and those who are not.

## Output

The final output of the project is a CSV file containing:

* `Id` – a unique identifier for each individual
* `ProbabilityOfDefault` – a value between 0 and 1 representing the predicted risk

Lower probabilities indicate higher creditworthiness, while higher probabilities indicate greater financial risk.

## Why this matters

Credit scoring is a real-world problem used by banks and financial institutions to make lending decisions. Instead of giving only a yes/no decision, this model provides a **risk score**, which can help institutions decide loan approvals, interest rates, or further review.

## Tools and libraries used

* Python
* Pandas, NumPy
* Scikit-learn
* Jupyter Notebook / Google Colab

## Conclusion

This project demonstrates a complete machine learning pipeline for credit risk prediction—from data preprocessing and feature engineering to model training, evaluation, and final prediction generation. It shows how machine learning can be used to make informed, data-driven decisions in financial applications.

---
