# Prediction of Obesity in Mexico, Peru, and Colombia

## Overview
Obesity is a major global health issue linked to conditions such as heart disease and diabetes. This project analyzes data from individuals in Mexico, Peru, and Colombia to identify key factors contributing to obesity, including Body Mass Index (BMI), exercise habits, and dietary patterns. The goal is to understand how lifestyle factors impact BMI and provide insights to help public health organizations combat obesity.
## Data Source
The dataset was obtained from [Kaggle.](https://www.kaggle.com/datasets/fatemehmehrparvar/obesity-levels) It contains 2111 records and 17 attributes, covering factors such as age, gender, family history of obesity, physical activity, and food consumption habits.
## Key Attributes:
- Gender: Male or female
- Age: Numeric
- Height/Weight: In kilograms
- Family History of Overweight: Yes/No
- High-Calorie Food Consumption: Yes/No
- Physical Activity Frequency
- Technology Use
- Alcohol Consumption
- Obesity: Categorized as Insufficient weight, Normal weight, Overweight, or Obessiy class I,II,III
  

## Data was cleaned using Excel Prep and processed in PowerBi:
- Renaming Columns: Simplified column names (e.g., 'family_history_with_overweight' → 'Family_w_Overweight').
- Handling Missing Data: Checked for and addressed missing values.

## Exploratory Data Analysis (EDA)
- BMI Category Distribution By Gender: Stacked Column charts to visualize BMI spread.
- Age Group Distribution: Stacked Bar charts showing the frequency of age groups.
- BMI vs. Physical Activity: Weak negative correlation, indicating higher physical activity may slightly reduce BMI.
- BMI vs. Age: BMI increases with age, particularly in the middle-aged and older group.
- BMI vs. Gender: Males generally have a higher average BMI than females.
  
## Key Insights:
1. Physical Activity & BMI: Higher activity is associated with lower BMI, though the effect is weak.
2. Age & BMI: BMI tends to increase in the 30-45 age group.
3. Gender Differences: Males have higher average BMI than females.
4. Water Consumption & BMI: No significant relationship was found.
5. Outliers in BMI: Extreme BMI values (very high or low) may indicate unique lifestyle factors or health conditions.
   
## Recommendations
1. Encourage Regular Physical Activity: Promote fitness programs and awareness campaigns, particularly targeting individuals with sedentary lifestyles.
2. Target Age Groups: Focus interventions on the 30-45 age group, where BMI tends to increase.
3. Develop Gender-Specific Programs: Tailor programs to address the specific needs and behaviors of males and females.
4. Promote Balanced Diets: Support educational initiatives on healthy eating alongside physical activity.
5. Address BMI Outliers: Provide personalized support for individuals with extreme BMI values through counseling or health monitoring.
   
## Technologies Used
- Excel Prep: Data cleaning and preparation.
- PowerBi: Data analysis, visualization, and modeling.
  
## Conclusion
This project provides actionable insights into obesity patterns in Mexico, Peru, and Colombia. By analyzing key factors like physical activity, age, and diet, the project offers useful information for creating targeted health interventions and obesity prevention strategies.
