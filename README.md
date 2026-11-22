# Machine Learning Crash Course: Beginner to Advanced

A free, one-hour Colab walkthrough by **David Oluyale | Agentic AI Hub**.

Go from "what is machine learning?" to training, checking, and saving real models, in scikit-learn.
Every concept uses a simple everyday example: house prices, exam results, fruit, spam, loans, used cars, shop customers.

## Open the notebook

- **Colab:** [Open in Colab](https://colab.research.google.com/github/davolu/machine-learning-crash-course/blob/main/Machine_Learning_Crash_Course.ipynb)
- `Machine_Learning_Crash_Course.ipynb`: the course notebook (no outputs).
- `Machine_Learning_Crash_Course_EXECUTED.ipynb`: the same notebook with the outputs from our recorded run.

No API keys or accounts needed. Pure Python, with scikit-learn, pandas, numpy and matplotlib.
If the GitHub data files are not available yet, the first code cell builds the same made-up tables for you.

## What you will learn

1. **How machine learning works**: features, labels, supervised vs unsupervised, a train/test split.
2. **Linear regression**, with MAE, RMSE and R², on house prices.
3. **Logistic regression**, and probabilities, on whether a student will pass.
4. **KNN, Naive Bayes and SVM**, side by side, on fruit, spam and Iris flowers.
5. **Decision trees and random forests**, on loan approval.
6. **Gradient boosting**, on customer churn.
7. **Data prep and feature engineering**: missing values, scaling, encoding, new features, on a used-car table.
8. **Evaluation**: the confusion matrix, precision, recall, ROC, AUC, and imbalanced data, on fraud detection.
9. **Overfitting**, the bias–variance tradeoff, regularisation and cross-validation.
10. **Pipelines and GridSearch** for hyperparameter tuning.
11. **Unsupervised learning**: k-means and PCA, on shop customers.
12. **A small neural network** (`MLPClassifier`) on handwritten digits.
13. **Saving a model** with joblib, and where to go next.

## Run locally

```bash
pip install -r requirements.txt jupyter
jupyter notebook Machine_Learning_Crash_Course.ipynb
```

The CSV files in `data/` are small made-up example tables, used for teaching.
Iris flowers and handwritten digits come from scikit-learn's built-in teaching sets.
