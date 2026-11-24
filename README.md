# Term Deposit Prediction

A machine learning project that predicts whether a bank client will subscribe to a term deposit, using data from a bank's marketing campaign. It helps a bank decide which clients to contact, so campaigns target the people most likely to say yes.

## What it does

- **Predicts subscription.** Takes a client's profile and campaign history and returns whether they are likely to subscribe, with a probability.
- **Full ML workflow.** Exploratory data analysis, preprocessing and encoding, model training, hyperparameter tuning with GridSearchCV, and evaluation.
- **Compares models.** Logistic Regression, XGBoost and Random Forest were trained and compared. Random Forest is the deployed model, reaching about 91% accuracy.
- **Live app.** A Streamlit app collects client details (age, job, balance, loans, contact history and previous campaign outcome) and shows the prediction instantly.

## Keywords

Machine Learning · Classification · Predictive Modeling · Banking Analytics · Marketing Analytics · Random Forest · XGBoost · Logistic Regression · GridSearchCV · Feature Engineering · Streamlit · Data Science · Python

## Tech Stack

- Python, pandas, NumPy
- scikit-learn (preprocessing, label encoding, Logistic Regression, Random Forest, GridSearchCV)
- [XGBoost](https://xgboost.readthedocs.io/)
- [Streamlit](https://streamlit.io/) for the deployed app
- Jupyter Notebook for analysis and modeling

## Project Structure

| Folder | Purpose |
| :--- | :--- |
| `Data/` | Bank marketing dataset (train and test) and field descriptions |
| `Term_Deposits_Prediction model/` | Analysis and model training notebook |
| `Deploy_Term_Deposit/` | Streamlit app, trained Random Forest model and encoders |

## Author

**Amar Chaurasiya**, Data Scientist working as an AI Engineer. Open to full-time roles and freelance work.

- Email: [amarchaurasiya124@gmail.com](mailto:amarchaurasiya124@gmail.com)
- LinkedIn: [linkedin.com/in/amar-chaurasiya-163788262](https://www.linkedin.com/in/amar-chaurasiya-163788262)
- Portfolio: [amarchaurasiya.vercel.app](https://amarchaurasiya.vercel.app)
