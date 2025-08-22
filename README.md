#🩺Health Risk Analytics

📌 Project Overview

This project analyzes the BRFSS 2015 health dataset (250k+ records) to identify risk factors associated with diabetes and predict the likelihood of diabetes occurrence.
The goal is to combine exploratory data analysis (EDA) with machine learning models to generate actionable insights and predictive capabilities.

📊 Dataset

Source: Behavioral Risk Factor Surveillance System (BRFSS 2015)

Size: ~250,000 records, 300+ health-related features

Features include:

Demographics (age, gender)

Lifestyle indicators (BMI, smoking, alcohol, physical activity, sleep)

Health conditions (blood pressure, cholesterol, healthcare access)

🔍 Methodology

Data Cleaning & Preprocessing

Handled missing values and inconsistencies

Encoded categorical variables

Standardized numerical features

Exploratory Data Analysis (EDA)

Visualized relationships using Seaborn & Matplotlib

Identified strong correlations between diabetes and risk factors like BMI, high BP, smoking, and inactivity

Model Building & Evaluation

Implemented Logistic Regression for binary classification (diabetic / non-diabetic)

Compared results with other ML models (Random Forest, Gradient Boosting – optional extension)

Evaluated performance using accuracy, ROC-AUC, and confusion matrix

✅ Results

Achieved ~85% accuracy in predicting diabetes occurrence

Identified key contributors: BMI, smoking habits, high blood pressure, physical inactivity

Built a prediction pipeline to classify new patient records

🛠️ Tech Stack

Python: Pandas, NumPy, Scikit-learn

Visualization: Seaborn, Matplotlib

Modeling: Logistic Regression (extendable to Random Forest, Gradient Boosting)

📈 Key Learnings

Importance of feature selection in health data modeling

Balancing interpretability (Logistic Regression) with accuracy (ensemble models)

Generating insights that support preventive healthcare decisions

🚀 Future Scope

Incorporate advanced models (XGBoost, Neural Networks)

Deploy as a web app for real-time diabetes risk prediction

Integrate additional datasets for broader generalization
