# Machine Learning Projects

End-to-end machine learning projects in Python and scikit-learn. Each one covers data cleaning, exploratory analysis, feature preparation, model training and evaluation. Every notebook comes with a PDF report.

| Project | Problem | Approach | Notebook | Report |
|---|---|---|---|---|
| **Bank Customer Churn** | Classification: will a customer leave the bank? | Support Vector Classifier. Class imbalance handled with random under- and over-sampling, features standardized, and the model tuned with `GridSearchCV`. | [ipynb](Bank_Churn_Model.ipynb) | [pdf](Bank_Churn_Model%20Sarvesh.pdf) |
| **Big Sales Prediction** | Regression: predict sales per item | Random Forest Regressor. Evaluated with MSE, MAE and R². | [ipynb](Big_Sales_Prediction%20(1).ipynb) | [pdf](Big_Sales_Prediction.pdf) |
| **Disease Prediction** | Classification: predict disease from patient features | Logistic Regression with MinMax scaling. Evaluated with a confusion matrix and a classification report. | [ipynb](Disease_Prediction.ipynb) | [pdf](Disease_Prediction_Sarvesh.pdf) |
| **Exchange Vehicle Price** | Regression: estimate a used vehicle's price | Linear Regression. Evaluated with MSE, MAE and R². | [ipynb](Exchange_Vehicle_Price_Prediction.ipynb) | [pdf](Exchange%20Vehicle%20Price%20Prediction%20Sarvesh.pdf) |
| **Mileage Prediction** | Regression: predict a car's fuel efficiency | Linear Regression with standardized features. Evaluated with MAE, MAPE and R². | [ipynb](Mileage_Prediction.ipynb) | [pdf](Mileage_Prediction%20Sarvesh.pdf) |
| **Movie Recommendation** | Content-based recommender | TF-IDF on movie metadata plus cosine similarity. Fuzzy title matching with `difflib`. | [ipynb](Movie_Recommendation.ipynb) | [pdf](Movie_Recommendation_Sarvesh.pdf) |

## Tech stack

Python · pandas · NumPy · scikit-learn · imbalanced-learn · Matplotlib · Seaborn · Jupyter

## Run

```bash
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn jupyter
jupyter notebook
```
