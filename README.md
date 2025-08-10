# Occupational-Health-Performance-Evaluation
![download (5)](https://github.com/user-attachments/assets/3222bd1f-7294-4e62-acbb-f98b700950e9)

What Your Work Life Says About Your Stress and Blood Pressure,This project analyzes the Sleep Health and Occupation Dataset to understand how factors such as occupation, stress levels, BMI, and blood pressure relate to sleep patterns.he analysis provides data-driven wellness to different professions.
a detailed collection of information on sleep patterns, blood pressure, and heart rate for 374 individuals.The dataset contains 13 key variables, organized into the following categories:

- Person ID: Unique identifier for each individual.
- Gender: Male/Female
- Age: Years
- Occupation: e.g Nurse, Doctor, Teacher, Accountant
- BMI Category: Underweight, Normal, Overweight, Obese
- Blood Pressure: Systolic/Diastolic
- Heart Rate: Beats per minute
- Sleep Duration: Hours per day
- Quality of Sleep: Scale of 1 to 10
- Physical Activity Level: Minutes per day
- Stress Level: Scale of 1 to 10
- Daily Steps: Number of steps
- Sleep Disorder: None, Insomnia, Sleep Apnea
  
## Objective
To examine the relationship between health-related factors and various occupations such as :
- Analyze the association between occupation and sleep duration
- Investigate the relationship between sleep disorders (e.g., insomnia, sleep apnea) and cardiovascular health indicators such as blood pressure and heart rate.
- Assess the association between BMI and blood group in relation to occupation.
- Analyze average stress levels and physical activity in relation to occupation and cardiovascular health.
- Develop predictive models to estimate how cardiovascular health, stress levels, and demographic factors influence sleep duration.
- Identify potential risk factors for sleep disorders and related cardiovascular health issues.
  
## Tools used:
- Excel(data Analysis, linear regression model and Visualization)
- Python(deep analysis and chi2_contingency test)

Data Exploratory Analysis:
- There are no missing values or inconsistencies in the dataset.
- Feature engineering was performed to extract systolic and diastolic blood pressure, as well as hypertension type, from the blood pressure measurements.
Additionally, were classified into the following categories: 27–29, 30–39, 40–49, and 50–59.

Hypertension Classification Based on Systolic Blood Pressure:
- Normal: Systolic BP ≤ 129 mmHg
- Hypertension Stage 1: Systolic BP between 130 mmHg and 139 mmHg
- Hypertension Stage 2: Systolic BP ≥ 140 mmHg
Hypertension Stage 1: Systolic BP between 130 mmHg and 139 mmHg
Hypertension Stage 2: Systolic BP ≥ 140 mmHg

<img width="405" height="364" alt="Screenshot 2025-08-09 141311" src="https://github.com/user-attachments/assets/199bd050-7ba9-4a58-a033-59df3e6586de" />
The following table presents the frequency distribution of each occupation included in this analysis.

## Dashboard 1
<img width="1318" height="703" alt="Screenshot 2025-08-09 165427" src="https://github.com/user-attachments/assets/1ef3b3ec-1e02-4c63-9dcd-0b7e54b5ed29" />

## Dashboard interpretation
The average blood pressure in this dataset is 129/85 mmHg, with 129 mmHg representing the average systolic and 85 mmHg the average diastolic pressure.

### Gender Distribution:
- Over 51% of the individuals are male, while 49% are female.
### Sleep Disorders:
- None: 45.90% reported no sleep disorder, indicating nearly half the population has no diagnosed sleep issues.
- Sleep Apnea: 30.35% have Sleep Apnea, making it the second most common sleep disorder in the dataset.
- Insomnia: 23.75% experience Insomnia.
### BMI Classification:
- The majority fall within the normal or overweight categories. Only a small portion are classified as obese or underweight.
### Age Distribution:
- Most respondents are between 30 and 39 years old, with relatively few under the age of 30.

### This visualization illustrates gender distribution across age groups and occupations.
  <img width="1512" height="636" alt="Screenshot 2025-08-09 150350" src="https://github.com/user-attachments/assets/3692d61c-5d93-4971-99d4-6010dff1b59f" />
- In the 50–59 age group, 100% of respondents are female.
- Among occupations, all nurses are female, and approximately 97% of doctors are male.
 - Female doctors and Engineers have a longer average sleep duration than their male counterparts, suggesting a heavier workload on male doctors and engineers
- About 96% of lawyers are male, yet male lawyers report longer sleep durations than female lawyers.
- These findings highlight notable variations in sleep duration across different genders and occupations.

## Dashboard 2
  <img width="1499" height="716" alt="Screenshot 2025-08-09 165458" src="https://github.com/user-attachments/assets/75f86341-a878-4222-b4a5-0cb0b1770e09" />
  
  ### Dashboard interpretation
- The average physical activity levels of nurses, lawyers, accountants, and lawyers exceed their average stress levels.
- In contrast, occupations such as doctors, software engineers, salespersons, and others exhibit higher average stress levels than their physical activity.
- The systolic blood pressure for the 40–49 age group indicates generally high levels with a narrow distribution, suggesting that nearly everyone in this group has elevated systolic BP, with only a few outliers showing lower values.
- the 30–39 age group shows a wider distribution of systolic blood pressure values, which are generally lower compared to the older group.
### 40–49 age group:
- 52.73% report insomnia,32.46% have no sleep disorder,and 14.81% suffer from sleep apnea.
This age group also shows generally high systolic blood pressure with a narrow distribution, indicating that most individuals have elevated levels, which may be linked to the higher prevalence of sleep disorders.

### 30–39 age group:
Has 88.84% reporting no sleep disorder,4.46% with insomnia,and 6.52% with sleep apnea,
also  displays a wider, generally lower distribution of systolic blood pressure.
These patterns suggest a potential association between higher systolic blood pressure and increased prevalence of sleep disorders in the older age group.

### Heart Rate Across BMI Groups
- Obese individuals have the highest average heart rate at 84.3 beats per minute.\
- Underweight group follows with an average of 71.3 bpm.
- Overweight individuals average 70.9 bpm.Normal weight group has the lowest average heart rate at 68.7 bpm
- 
### Sleep disorder
- Individuals with no sleep disorder have the longest average sleep duration at 7.4 hours,they are followed by those with sleep apnea, averaging 7.0 hours of sleep,the shortest sleep duration is observed in individuals with insomnia, averaging 6.6 hours.

  ### Hypertension type in relation to BMI categories
- <img width="1127" height="303" alt="Screenshot 2025-08-09 181751" src="https://github.com/user-attachments/assets/a7854bf7-9a80-4014-897c-ffdd7c763fc6" />

### Hypertension and BMI
- Hypertension Stage 2 accounts for approximately 19% of the population and primarily occurs in the obese and overweight BMI categories.
- Hypertension Stage 1 is present across all BMI categories, affecting about 37% of the population.
- Normal blood pressure is recorded in about 44% of respondents, with no representation from the obese category.

## Hypertension type and BMI group across different occupation
  <img width="1129" height="402" alt="Screenshot 2025-08-09 181821" src="https://github.com/user-attachments/assets/2521fa76-5515-48c0-890c-3a17c225d0c5" />
  
This analysis compares BMI and blood pressure categories (Normal, Hypertension Stage 1, and Hypertension Stage 2) across different occupations,most occupations fall within normal weight and normal blood pressure categories,Majority of lawyers fall within the normal weight category; however, most are classified under Hypertension Stage 1.
This could suggest that factors beyond body weight ,possibly work-related stress, long working hours, or sedentary habits that may be influencing their blood pressure, although further analysis would be needed to confirm this.
However, Nurses stand out and they are all female ,they have a higher percentage of overweight others are underweight a significant portion also falls into Hypertension Stage 2, this suggests a potential correlation between BMI and high blood pressure within this occupation.

This suggests there may be a relationship between hypertension and BMI categories.
To explore this, we will build a Chi-square test of independence (chi2_contingency), comparing the two categorical variables: BMI and Hypertension Type.

### Chi-square test of independence (python)
<img width="1570" height="408" alt="Screenshot 2025-08-09 183614" src="https://github.com/user-attachments/assets/c23b763b-f25e-49ce-99b1-b7b2310197f6" />

## Statistical Conclusion
A chi-square test of independence was performed to evaluate the association between BMI categories and Hypertension type. The test results indicated a significant relationship between these two variables (χ² = [chi-square statistic], p-value = [p-value]).
Since the p-value is less than the typical significance level of 0.05, we reject the null hypothesis that there is no association between BMI and Hypertension type.This suggests that BMI category is significantly related to Hypertension status. In other words, variations in BMI categories correspond to differences in the distribution of hypertension types.These findings imply that BMI may play an important role in influencing or predicting hypertension

## Predicting the extent to which key factors influence sleep duration.

The following factors will be used to predict sleep duration (in hours), as they exhibit the strongest positive and negative correlations with the target variable.
<img width="890" height="208" alt="Screenshot 2025-08-09 135103" src="https://github.com/user-attachments/assets/77fc3d5f-6359-4717-a8e5-63353b8cea0a" />

## Regression Analysis to Predict Sleep Duration (Excel)
A regression model was built with sleep duration as the dependent variable (Y) and the selected predictors (X) based on correlation analysis


<img width="1056" height="574" alt="Screenshot 2025-08-09 184941" src="https://github.com/user-attachments/assets/a41215c5-64e7-48b3-8f2b-6284ece97ceb" />
Linear regression Result

## Statistical Interpretation of Regression Analysis:
The model explains 83% of the variance in sleep duration, as indicated by the R-squared value. This high R-squared suggests a strong fit between the predictors and sleep duration.
- Age is 0.018 less than p < 0.05 For each additional year in age, sleep duration increases by 0.018 hours (~1.08 minutes),holding other factors constant.
- Stress Level -0.355 less than p < 0.05 Higher stress reduces sleep duration. For each 1-unit increase in stress level, sleep drops by ~21 minutes. strong negative impact, highly significant.
- Systolic BP -0.026 less than p < 0.05 higher blood pressure is linked to shorter sleep. Each 1 mmHg increase reduces sleep by ~1.6 minutes. Significant negative relationship.
- Heart Rate 0.026 less than p < 0.05 Higher heart rate is associated with slightly longer sleep. Each 1 bpm increase predicts ~1.6 minutes more sleep. Statistically significant, but small effect
  
## Result Summary:
- Stress management appears to have the biggest potential impact on improving sleep hours.
- Slight effects from blood pressure and heart rate suggest that cardiovascular health also plays a role.
- Age has a small but positive influence
  
# Analysis summary

- The analysis reveals a relationship between sleep duration, health metrics, and occupational factors. These findings underscore the importance of managing stress and cardiovascular health to improve sleep quality across diverse occupational groups. Key findings include:
- The dataset includes 374 individuals with comprehensive variables on sleep patterns, blood pressure, heart rate, BMI, stress levels, physical activity, occupation and more
- Correlation analysis revealed strong negative associations between sleep duration and stress levels, and moderate positive correlations with age.
- Sleep disorders vary by age group, with older adults (40–49) showing higher rates of insomnia and elevated systolic blood pressure compared to other blood groups.
- Hypertension stages are linked to BMI categories, with Stage 2 hypertension primarily affecting overweight and obese individuals.
- Gender and occupation influence sleep patterns; for example, female doctors tend to sleep longer than male doctors, while male lawyers report longer sleep than female lawyers.
- Female dominance in Nursing, largely fall under Hypertension Stage 2, indicating a high prevalence of elevated blood pressure in this group.
- Most lawyers are of normal weight, many still fall under Hypertension Stage 1, suggesting other factors like work-related stress may contribute to their blood pressure levels.
- Stress and physical activity levels differ across occupations and relate to cardiovascular health metrics.

# Recommendations:
## Physical and Mental Stress Management:
- Introduce mindfulness, meditation, and relaxation techniques in workplaces to reduce mental stress.
- Encourage breaks during work hours to prevent burnout and physical fatigue.
- Encourage the adoption of comfort-focused workplace designs to minimize physical strain, alongside regular medical check-ups for workers across different occupations and ongoing health awareness programs.
- Offer access to counseling or employee assistance programs to support mental health.
  
## Good Sleep Etiquette:
- Educate individuals on maintaining a consistent sleep schedule, even on weekends.
- Encourage creating a sleep-friendly environment: cool, dark, and quiet bedrooms for breaks
- Limit exposure to screens (phones, computers) at least an hour before bedtime.
- Avoid heavy meals, caffeine, and intense exercise close to bedtime.
- Advocate for relaxation routines before sleep, such as reading or light stretching.
  
  ## Integrated Wellness Programs:
  - Develop comprehensive wellness programs that integrate physical activity, stress management, and sleep education, tailored to the specific needs of various occupational groups.

    
# Thank you for reading💕💕





  






