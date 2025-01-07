# sleep-disorder-hypothesis-testing

# Dataset Overview
Size: 400 rows and 13 columns.
# Key Variables:
Sleep metrics: Sleep duration, quality, disorders.
Lifestyle factors: Physical activity, stress levels, BMI category.
Health metrics: Blood pressure, heart rate, daily steps.
Demographics: Gender, age, occupation.

# Data Source
dataset is from kaggle.com
# Data Preprocessing
- Missing Values:
Missing values were replaced with "unknown".
- Duplicates:
No duplicates were found.
- Shape:
Confirmed dataset dimensions: 400 rows × 13 columns.

# Hypotheses and Results
1. Sleep Apnea Prevalence by Gender
Hypothesis: Sleep apnea is more prevalent in males than females.
Test: Chi-squared test.
Result: Supported—Sleep apnea is more prevalent in males.
2. Sleep Apnea and Age
Hypothesis: Sleep apnea prevalence increases with age.
Test: Independent t-test.
Result: Not Supported—No significant association between age and sleep apnea.
3. BMI and Sleep Apnea
Hypothesis: Higher BMI categories correlate with increased sleep apnea risk.
Test: Chi-squared test.
Result: Supported—Individuals with higher BMI are more likely to have sleep apnea.
4. Stress Levels and Sleep Apnea
Hypothesis: Higher stress levels are associated with increased sleep apnea prevalence.
Test: Independent t-test.
Result: Not Supported—No significant association between stress levels and sleep apnea.
5. Gender and Sleep Duration
Hypothesis: Gender significantly affects average sleep duration.
Test: Independent t-test.
Result: Not Supported—Gender has no significant effect on sleep duration.
6. Age and Sleep Quality
Hypothesis: Sleep quality decreases with age.
Test: Pearson correlation.
Result: Not Supported—No significant correlation between age and sleep quality.
7. Sleep Duration and Quality
Hypothesis: Longer sleep durations improve sleep quality.
Test: Pearson correlation.
Result: Not Supported—No significant relationship between sleep duration and quality.
8. Gender and Physical Activity
Hypothesis: Males have higher physical activity levels than females.
Test: Independent t-test.
Result: Not Supported—No significant difference in physical activity levels between genders.
# Key Insights
Sleep Apnea:
Predominantly affects males.
Strongly associated with higher BMI categories.
# Other Factors:
Stress levels, age, and gender do not significantly influence sleep apnea.
Sleep quality and duration are not strongly correlated.
Gender Differences:
No significant differences in sleep duration or physical activity levels between males and females.
