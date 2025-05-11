# phishing_Model
Dataset Summary: Phishing URL Detection
This dataset contains 176,262 website records with 20 features to help detect phishing websites.
Main Features:
•	Website Information: URL, domain, and top-level domain (TLD).
•	Security Checks: HTTPS usage, presence of social media links, and submit buttons.
•	Content Details: Page title, number of images, JavaScript files, and code lines.
•	Phishing Indicators: URL similarity, special character count, and matching scores.
•	Target Label:
o	1 → Phishing website
o	0 → Safe website

Phishing URL Detection with Machine Learning 🔒

📌 Project Overview
This project focuses on detecting phishing websites using a machine learning pipeline. It leverages a cleaned dataset of phishing URLs from Kaggle and applies EDA, preprocessing, and model building to accurately classify URLs as phishing or legitimate.

📁 Dataset
Source: UCI / Kaggle

Description: Pre-cleaned dataset of phishing URLs with extracted features

Features include:

URL-based attributes (length, domain, special characters, etc.)

HTML/JavaScript properties

Third-party service checks (like HTTPS usage, URL shortening, etc.)

🧠 Workflow Summary

1. 📊 Exploratory Data Analysis (EDA)
Univariate, Bivariate, and Multivariate visualizations

Feature distribution and correlation heatmaps

Outlier detection

2. 🛠️ Data Preprocessing
Duplicate and null handling

Outlier removal

Feature encoding (Ordinal, OneHot)

Handling class imbalance with resampling

Feature scaling

3. 🤖 Modeling
Training models like:

RandomForestClassifier

XGBoost

Logistic Regression

Model evaluation using accuracy, confusion matrix, and classification reports

📈 Results
Achieved high accuracy and precision for phishing detection

🧾 Requirements
Python 3.7+

Libraries:

pandas

numpy

scikit-learn

seaborn

matplotlib

xgboost

✨ Future Improvements
Real-time URL checker via Streamlit or Flask

Deployment using Docker

Integration with threat detection APIs



Visualized predictions and model performance using matplotlib/seaborn
