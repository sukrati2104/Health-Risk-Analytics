🩺 Health Risk Analytics

1. Objective- 
   To analyze health and lifestyle factors that contribute to diabetes.
   To identify patterns, correlations, and risk indicators that can help in early prediction and prevention.
   
2. Dataset- 
Source: BRFSS 2015 (Behavioral Risk Factor Surveillance System).
Size: ~253,000 records, 22 features.
Features: Diabetes status (target), BMI, blood pressure, cholesterol, smoking, alcohol consumption, age, income, education, general health, etc.

3. Data Cleaning & Preparation- 
Verified dataset had no missing values.

4. Exploratory Data Analysis (EDA) & Graphs- 
Barplot (Sex vs Age): Compared average age of males and females. Helps understand demographic differences in the dataset.
Correlation Heatmap (with Diabetes): Showed strongest correlations between diabetes and risk factors (BMI, high BP, cholesterol, physical activity). Helped prioritize key predictors.
Barplot (BMI vs HighBP): Individuals with high blood pressure had higher BMI on average. Confirms obesity as a major risk factor.
Barplot (Diabetes vs HighChol): People with high cholesterol had a higher chance of diabetes. Shows lifestyle and diet-related impact.
Lineplot (Age vs Heart Disease/Attack): Clear upward trend of heart disease with age. Indicates elderly are at greater risk of comorbidities.
Barplot (General Health vs Heavy Alcohol Consumption): Heavy alcohol consumers reported poorer health outcomes. Confirms alcohol as a negative lifestyle factor.
Histogram (Age Distribution by Sex): Age distribution across genders to check balance in dataset.

5. Insights & Findings-  Obesity (BMI) strongly correlates with both high BP and diabetes risk.
High cholesterol significantly increases diabetes prevalence.
Age is a crucial factor → older individuals face higher risks of both diabetes and heart disease.
Lifestyle choices (alcohol, smoking, physical inactivity) worsen overall health and increase diabetes risk.
Social determinants like income & education indirectly affect diabetes risk (via lifestyle).

6. Value of the Project- 
Builds an understanding of which health factors are most critical for diabetes prediction.
Provides a foundation for building machine learning models (like logistic regression, random forest) for risk prediction.
Helps in designing preventive health strategies (targeting obesity, cholesterol control, and lifestyle improvements).

7. Prediction Model- 
 i) Data Preparation:
Cleaned the dataset by removing rows with missing values.
Split the data into features (X) such as Age, BMI, physical activity, smoking, alcohol consumption, etc., and the target variable (y) which indicates whether a person has diabetes (0 = No, 1 = Yes).
Used an 80-20 train-test split to ensure reliable model evaluation.
Applied StandardScaler to normalize the data since Logistic Regression is sensitive to feature scaling.
 ii) Model Training & Evaluation:
Trained a Logistic Regression model on the training data.
Predicted outcomes for the test set and compared them with actual labels.
Measured performance using accuracy score, which showed the percentage of correct predictions (around ~80–85%).
 iii) Prediction on New Data:
Created a sample patient profile with inputs like Age = 60, BMI = 35, no physical activity, less sleep, alcohol consumption, and smoking.
Reindexed the new input to match the same feature structure as the training data.
Scaled th data and used the trained model to make a prediction.
Output was displayed in plain text → “The person is predicted to have diabetes” or “not have diabetes.”

