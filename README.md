# IBM-HR-Employee-Attrition-and-Performance
This project provides a detailed analysis of employee attrition at IBM, aiming to uncover key factors influencing turnover and its impact on performance. Utilizing Python, the analysis explores various statistical methods and visualizations to offer insights and actionable recommendations.
 # Business Questions
The primary goal of this analysis is to model employee attrition and identify the dominant factors contributing to employee turnover. Specifically, the project addresses the following business questions:
 1. What is the extent of correlation between key demographic factors and how do they collectively impact the company's operations and performance?
 2. How does the relationship between age and total working years impact the monthly income?
 3. Does ageism play an important role in employees' layoffs?
 4. Does higher education level affect employees' daily rate in specific departments?
 5. To what extent does the duration of an employee's tenure with the company influence their likelihood of leaving, and how does this finding impact our attrition management strategies?
 6. How can we predict the monthly income based on age and total working years?
 # Dataset
 The dataset used in this project is provided by IBM and contains 1470 rows with 35 columns, including attributes such as age, attrition, daily rate, education, gender, monthly income, total working years, and years at the company.
 # Data Cleaning and Preprocessing 
 Data cleaning steps include handling missing values, encoding categorical variables, and ensuring data consistency. This ensures accurate analysis and meaningful insights.
 Analysis and Results 
   # 1. Correlation Analysis
  A strong positive correlation (77%) was found between monthly income and total working years.
  A 50% positive correlation between age and monthly income.
  A 68% correlation between age and total working years.
  # 2. Scatterplots and Pair Plots 
  Visualizations confirm the positive correlations, showing clear trends.
  # 3. Hypothesis Testing 
  A two-sample t-test indicates younger employees are more likely to be laid off, countering claims of ageism.
  # 4. Linear Regression 
  A model predicts monthly income based on age and total working years, with about 60% of the variation explained by these factors.
  # Visualizations
   # Boxplots and Scatter Plots: 
  Boxplots compare the age distribution of laid-off versus retained employees, showing younger employees are more frequently laid off.
  Scatter plots reveal the relationship between total working years and monthly income, particularly in the research and development department.
# Key Findings 
Employee age and total working years are strong predictors of monthly income.
Younger employees are more likely to be laid off, challenging claims of ageism.
Higher education levels correlate with higher daily rates, especially in the research and development department.
# Recommendations
Develop strategies to retain younger employees, such as mentoring programs and career development opportunities.
Implement educational programs to enhance job satisfaction and retention.
Use the predictive model to identify employees at risk of leaving and take proactive measures.

 # Conclusion 
This analysis provides a comprehensive understanding of employee attrition at IBM. The insights gained can help develop strategies to retain top talent and optimize workforce performance. Implementing educational and career development programs could enhance job satisfaction and retention, particularly among younger employees.
