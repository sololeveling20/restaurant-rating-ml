🍽️ Restaurant Rating Prediction using Machine Learning

📌 Project Overview

This project focuses on analyzing restaurant metadata and customer reviews to **predict restaurant ratings using machine learning techniques**.
The goal is to understand **key factors influencing customer satisfaction** and build reliable regression models for rating prediction.

The project follows a complete data science lifecycle, from data analysis to automation using CI/CD practices.

---

🎯 Objectives

* Analyze restaurant metadata and customer reviews
* Identify factors influencing restaurant ratings
* Build regression-based machine learning models
* Evaluate model performance using standard metrics
* Implement CI/CD for automated notebook validation

---

🔬 Project Workflow

* Exploratory Data Analysis (EDA)
* Hypothesis Testing
* Feature Engineering
* Machine Learning Model Development
* Model Evaluation
* CI/CD Integration using GitHub Actions

Development was carried out using **Google Colab**, with version control and automation managed through **GitHub**.

📂 Project Structure

├── restaurant_rating_analysis.ipynb
├── README.md
└── .github/
    └── workflows/
        └── main.yml
▶️ How to Clone and Run the Project (Google Colab)
1️⃣ Clone the Repository
git clone https://github.com/sololeveling20/restaurant-rating-ml.git

This command creates a local copy of the repository for reference and version control.

2️⃣ Open the Notebook in Google Colab

You can run this project directly in Google Colab.

Option A: Upload Manually

Open https://colab.research.google.com
Click Upload
Upload restaurant_rating_analysis.ipynb from the cloned repository

Option B: Open from GitHub (Recommended)
Open Google Colab
Click File → Open notebook
Select the GitHub tab
Paste the repository URL:
https://github.com/sololeveling20/restaurant-rating-ml
Open restaurant_rating_analysis.ipynb

3️⃣ Mount Google Drive
Datasets are stored in Google Drive.
from google.colab import drive
drive.mount('/content/drive')

This allows Colab to access datasets stored in Drive.

4️⃣ Update Dataset Paths
Ensure dataset paths point to your Google Drive location:
'/content/drive/MyDrive/<dataset-folder>/file.csv'

5️⃣ Run the Notebook
Run all cells from top to bottom to reproduce the analysis and results.


📊 Dataset Description

The project uses two datasets:

1️⃣ Restaurant Metadata Dataset

* Restaurant Name
* Cost
* Cuisine Type
* Collections
* Timings

2️⃣ Restaurant Reviews Dataset

* Customer Reviews
* Ratings
* Review Metadata
* Review Timestamps

⚠️ **Note:**
Datasets are handled externally using **Google Colab and Google Drive** and are not included in the repository.

---

🧪 Methodology

🔹 Data Cleaning & Preprocessing

* Handling missing values
* Removing duplicate records
* Data type conversions

🔹 Exploratory Data Analysis

* Rating distribution analysis
* Cost vs rating trends
* Cuisine-wise insights
* Review engagement patterns

🔹 Hypothesis Testing

* Statistical tests to validate relationships between review engagement and ratings

🔹 Feature Engineering

* Review count
* Average rating
* Cost-based features

---

🤖 Machine Learning Models

| Model                   | Purpose                                           |
| ----------------------- | ------------------------------------------------- |
| Linear Regression       | Baseline model                                    |
| Ridge Regression        | Regularized regression with hyperparameter tuning |
| Random Forest Regressor | Non-linear ensemble model                         |

Hyperparameter tuning was performed using **GridSearchCV with cross-validation**.

---

📈 Evaluation Metrics

* **MAE (Mean Absolute Error)** – Measures average prediction error
* **RMSE (Root Mean Squared Error)** – Penalizes large errors
* **R² Score** – Explains variance captured by the model

These metrics help assess both **technical accuracy and business impact**.

---

🔄 CI/CD Implementation

CI/CD is implemented using **GitHub Actions**.

What the CI pipeline does:

* Triggers automatically on every push or pull request
* Validates all Jupyter notebooks in the repository
* Ensures notebook integrity without executing data-dependent cells

This approach ensures **reproducibility and stability** while remaining compatible with **Google Colab workflows**.

---

📌 Key Insights

* Restaurants with higher customer engagement tend to have higher ratings
* Cuisine type and cost significantly influence customer satisfaction
* Ensemble models outperform linear models in capturing complex patterns

---

🚀 Conclusion

This project demonstrates how **machine learning and data analytics** can be effectively applied to real-world restaurant data.
The integration of **CI/CD practices** further enhances reliability and aligns the project with **industry best practices**.

## 👩‍💻 Author

**Ramsha Shaikh**
**B.Tech – Computer Science & Engineering**
