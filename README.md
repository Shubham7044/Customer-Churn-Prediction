📊 Customer Churn Prediction — Machine Learning Project

Customer churn directly impacts business revenue, especially in telecom and subscription-based industries. This project builds a complete Machine Learning pipeline to analyze customer behavior and predict churn using real-world telecom data.
The goal is to identify customers likely to leave and help businesses take proactive retention actions.

🚀 Project Overview

This project includes:

End-to-end ML workflow — data preprocessing → modeling → evaluation

Exploratory Data Analysis (EDA) to identify churn patterns

Feature Engineering to improve model performance

Supervised classification models: Logistic Regression & Random Forest

Performance metrics & business insights

Visualizations: churn distribution, correlations, feature importance

The final model helps organizations understand why customers churn and which groups are at the highest risk.

📁 Repository Structure
Customer-Churn-Prediction/
│── data/
│   └── customer_churn.csv
│
│── notebooks/
│   └── churn_model.ipynb
│
│── src/
│   ├── data_preprocessing.py
│   ├── model_training.py
│   └── utils.py
│
│── README.md
│── requirements.txt
└── .gitignore

📦 Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/YOUR_USERNAME/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction

2️⃣ Create a Virtual Environment
python -m venv venv

3️⃣ Activate Environment

Windows

venv\Scripts\activate


Linux/Mac

source venv/bin/activate

4️⃣ Install Dependencies
pip install -r requirements.txt

📊 Dataset Summary

The dataset contains customer demographics, service usage, billing information, and a target column Churn.

Category	Example Columns
Demographics	gender, SeniorCitizen, Partner
Services	PhoneService, InternetService, TechSupport
Billing	MonthlyCharges, TotalCharges
Contract Details	Contract, PaymentMethod
Target	Churn (Yes/No)
🧹 Data Preprocessing Steps

Removed missing/inconsistent values

Encoded categorical variables with Label Encoding

Converted Churn to binary (1 = churn, 0 = no churn)

Train-test split with stratified sampling

Optional scaling for numerical features

🤖 Model Development

Two ML models were trained and compared:

📌 Logistic Regression

Establishes baseline performance

Useful for interpretability

📌 Random Forest Classifier

Handles non-linear patterns

Provides feature importance

Achieved higher accuracy and recall

📈 Model Evaluation Metrics

Accuracy

Precision

Recall

F1-score

Confusion Matrix

These metrics help assess how well the model identifies churners vs. non-churners.

🔍 Key Insights

Customers on month-to-month contracts churn more frequently

Higher monthly charges correlate with churn

Lack of tech support increases churn probability

Tenure is one of the strongest retention indicators

These insights enable companies to implement targeted retention strategies, such as offering discounts or upgrading contracts.

📉 Visualizations

The project includes professional-quality plots:

Churn Distribution Bar Plot

Correlation Heatmap

Feature Importance Chart (Random Forest)

Numerical Feature Distributions

🏁 How to Run
Run Notebook
jupyter notebook


Open:
notebooks/churn_model.ipynb

Run Python Scripts
python src/data_preprocessing.py
python src/model_training.py

📘 Requirements (Libraries)
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter

📂 Future Improvements

Hyperparameter tuning (GridSearchCV, RandomizedSearchCV)

Deploying model via FastAPI / Flask API

Saving model using joblib or pickle

Creating a Streamlit dashboard for churn prediction

Adding SHAP/LIME explainable AI

⭐ Project Impact

This project demonstrates your ability to:

Work with real-world business datasets

Build complete Machine Learning pipelines

Perform EDA & extract insights

Train classification models

Communicate results effectively

Perfect to showcase in your CV, GitHub, LinkedIn, and interviews.

🤝 Contributing

Pull requests, feedback, and suggestions are welcome!

🛡 License

This project is licensed under the MIT License.

⭐ Support

If you found this project useful, please give it a star on GitHub!
