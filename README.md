# IBM-HR-Employee-Attrition-and-Performance
Employee attrition is a significant challenge for many organizations, and IBM is no exception. Understanding the factors that lead to employee turnover can provide valuable insights into improving retention and performance. In this project, I deeply researched IBM's HR data using Python to uncover patterns and trends that can help address these issues. Through a combination of statistical analysis and data visualization, we aim to answer critical business questions and provide actionable recommendations.
 # Business Questions
The primary goal of this analysis is to model employee attrition and identify the dominant factors contributing to employee turnover. Specifically, the project addresses the following business questions:
 1. What is the extent of correlation between key demographic factors and how do they collectively impact the company's operations and performance?
 2. How does the relationship between age and total working years impact the monthly income?
 3. Does ageism play an important role in employees' layoffs?
 4. Does higher education level affect employees' daily rate in specific departments?
 5. To what extent does the duration of an employee's tenure with the company influence their likelihood of leaving, and how does this finding impact our attrition management strategies?
 6. How can we predict the monthly income based on age and total working years?
 # Dataset
The dataset used in this project is an augmented version created by real IBM data scientists, though it's not 100% real data. This dataset, available in CSV format, is a comprehensive collection of employee information with 1470 rows and 35 columns. Each row represents an individual employee, providing a wealth of features that allow for a detailed analysis of various factors influencing employee attrition. 
Key attributes in this dataset include:
Age
Attrition
Daily Rate
Education
Employee Number
Gender
Hourly Rate:
Job Role
Monthly Income
Total Working Years
Years at Company
 # Data Cleaning and Preprocessing 
Data cleaning steps include handling missing values, encoding categorical variables, and ensuring data consistency. This ensures accurate analysis and meaningful insights.
 Analysis and Results 
  # Correlation Analysis
 My first step was to examine the correlations between key variables:
 A strong positive correlation (77%) was found between monthly income and total working years. This suggests that experience significantly influences earnings at IBM.
 A 50% positive correlation between age and monthly income indicates that older employees tend to earn more.
 A 68% correlation between age and total working years highlights the intuitive relationship between these two factors. 
 These correlations provided a solid foundation for further analysis, revealing important trends in the data.
  # Scatterplots and Pair Plots 
 Next, I  used scatterplots and pair plots to visualize these relationships: The positive correlations observed in the previous step were clearly visible in these visualizations, confirming our initial findings. These plots also helped identify potential outliers and patterns that might not be immediately apparent from the raw data.
 #  Hypothesis Testing
 To address the question of ageism, I conducted a two-sample t-test: Surprisingly, the results indicated that younger employees are more likely to be laid off, countering claims of ageism. This finding suggests that factors other than age may be driving attrition among younger employees.
# Linear Regression 
 Finally, we built a linear regression model to predict monthly income based on age and total working years: The model explained about 60% of the variation in monthly income, indicating that these two factors are strong predictors of earnings. This predictive power provides a valuable tool for forecasting income and understanding the factors that influence it.
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
