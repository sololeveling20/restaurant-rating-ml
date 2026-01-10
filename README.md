# restaurant-rating-ml
Restaurant Rating Prediction and Analysis Using Machine Learning
Project Overview

This project focuses on analyzing restaurant data and predicting restaurant ratings using machine learning techniques. The analysis is performed on customer reviews and restaurant metadata to understand factors influencing customer satisfaction and to build predictive models for restaurant ratings.

The project follows a complete data science lifecycle, including:

Exploratory Data Analysis (EDA)

Hypothesis Testing

Feature Engineering

Machine Learning Model Development

Model Evaluation

CI/CD Integration using GitHub Actions

Development was carried out using Google Colab, while version control and automation were handled through GitHub.

🎯 Objectives

To analyze restaurant metadata and customer reviews

To identify key factors affecting restaurant ratings

To build regression-based machine learning models for rating prediction

To evaluate model performance using standard evaluation metrics

To implement CI/CD for automated notebook validation

📂 Project Structure
├── restaurant_rating_analysis.ipynb
├── README.md
└── .github/
    └── workflows/
        └── main.yml

📊 Dataset Description

The project uses two datasets:

Restaurant Metadata Dataset

Restaurant name

Cost

Cuisine type

Collections

Timings

Restaurant Reviews Dataset

Customer reviews

Ratings

Review metadata

Review timestamps

⚠️ Datasets are handled externally using Google Colab and Google Drive for persistence and are not included in the repository.

🧪 Methodology

Data Cleaning & Preprocessing

Handling missing values

Removing duplicate records

Data type conversions

Exploratory Data Analysis

Distribution analysis

Cost vs rating analysis

Cuisine-wise insights

Review sentiment patterns

Hypothesis Testing

Statistical tests to validate relationships between engagement and ratings

Feature Engineering

Review count

Average rating

Cost-based features

Machine Learning Models

Linear Regression

Ridge Regression (with hyperparameter tuning)

Random Forest Regressor

Model Evaluation

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

R² Score

🤖 Machine Learning Models Used
Model	Purpose
Linear Regression	Baseline prediction
Ridge Regression	Regularized linear model
Random Forest Regressor	Non-linear ensemble model

Hyperparameter optimization was performed using GridSearchCV with cross-validation.

📈 Evaluation Metrics

MAE – Measures average prediction error

RMSE – Penalizes large errors

R² Score – Explains variance captured by the model

These metrics help assess both technical performance and business impact.

🔄 CI/CD Implementation

CI/CD is implemented using GitHub Actions.

What the CI pipeline does:

Automatically triggers on every push or pull request

Validates all Jupyter notebooks in the repository

Ensures notebook integrity without executing data-dependent cells

This approach ensures reproducibility while remaining compatible with Google Colab workflows.

🛠️ Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook

Google Colab

GitHub Actions (CI/CD)

📌 Key Insights

Restaurants with higher customer engagement tend to have higher ratings

Cuisine type and cost significantly influence customer satisfaction

Ensemble models outperform linear models in capturing complex patterns

🚀 Conclusion

This project demonstrates how machine learning and data analytics can be used to extract meaningful insights from restaurant data and predict customer ratings effectively. The integration of CI/CD enhances reliability and aligns the project with industry best practices.

👩‍💻 Author

Ramsha Shaik
B.Tech – Computer Science & Engineering
