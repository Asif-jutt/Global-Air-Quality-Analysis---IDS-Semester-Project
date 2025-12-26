🌍 Global Air Quality Analysis & AQI Prediction
📌 Project Overview

This project analyzes global air quality data collected from major cities worldwide to understand pollution patterns, calculate Air Quality Index (AQI), and build machine learning models for AQI prediction. The study combines data preprocessing, exploratory data analysis (EDA), visualization, and machine learning to evaluate the impact of air pollutants on human health and suggest environmental improvements.

This project was developed as a Semester Project (CCP) for CSC380 – Introduction to Data Science at
University of Engineering and Technology (UET), Lahore.

🎯 Objectives

Analyze global air pollution trends and patterns

Calculate and categorize Air Quality Index (AQI)

Perform statistical and visual exploratory data analysis

Build and compare multiple machine learning models

Interpret results to understand health impacts

Suggest strategies for environmental improvement

📊 Dataset

Source: Kaggle – Global Air Quality Dataset

Records: 10,000

Features:

PM2.5, PM10

NO₂, SO₂, CO, O₃

Temperature, Humidity, Wind Speed

City, Country, Date

🛠️ Technologies Used

Python

Pandas & NumPy – Data handling

Matplotlib & Seaborn – Visualization

Scikit-learn – Machine Learning

🧹 Data Preprocessing

Missing value analysis

Outlier detection using IQR and Z-score

Outlier treatment using capping

AQI calculation and categorization

Feature scaling (Standardization & Normalization)

Train–test split (80% / 20%)

📈 Exploratory Data Analysis (EDA)

Univariate Analysis: Distribution of pollutants

Bivariate Analysis: Pollution vs weather factors

Correlation Analysis: Heatmap of feature relationships

Comparative Analysis: City-wise and country-wise AQI

Trend Analysis: Temporal pollution behavior

🤖 Machine Learning Models Implemented

The following five classification models were used to predict AQI categories:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

📊 Model Evaluation

Models were evaluated using:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

Ensemble models (especially Random Forest) showed the best performance.

🩺 Health Impact & Insights

PM2.5 and PM10 were the most critical pollutants affecting AQI

High pollution levels increase risks of:

Asthma and lung infections

Cardiovascular diseases

Reduced life expectancy

🌱 Environmental Recommendations

Promote public and electric transportation

Enforce industrial emission regulations

Increase green urban spaces

Use renewable energy sources

Implement real-time air quality monitoring

🚀 Future Scope

Integration of real-time air quality data

Use of deep learning models

Direct health impact analysis

Development of an interactive dashboard

📂 Repository Structure
├── notebook/
│   └── Air_Quality_Analysis.ipynb
├── report/
│   └── Air_Quality_Project_Report.pdf
├── dataset/
│   └── global_air_quality.csv
├── README.md

👨‍🎓 Author

Asif Hussain
Department of Computer Science
University of Engineering and Technology, Lahore

📜 License

This project is for academic and educational purposes only.
