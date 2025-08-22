
#🩺Health Risk Analytics

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


👉 Do you want me to now create a ready-to-use project explanation (3–4 lines) for your resume/interviews that condenses all this detail into a professional summary?

