# Employee Performance Analysis Dashboard

## TABLE OF CONTENT
- [EMPLOYEE PERFORMANCE OVERVIEW](#Employee-overview)
- [DATA SOURCE](#data-source)
- [TOOLS](#tools)
- [OBJECTIVES/KEY PERFORMANCE INDICATORS](#objectives/key-performance-indicators)
- [DATA CLEANING](#data-cleaning)
- [DATA PREPROCESSING](#data-preprocessing)
- [DATA ANALYSIS](#data-analysis)
- [DASHBOARD](#dashboard)
- [INSIGHTS](#insights)
- [RECOMMENDATIONS](#recommendations)


### EMPLOYEE PERFORMANCE OVERVIEW
This project provides a comprehensive analysis of employee performance across departments, job levels, and store locations. The goal is to improve employee satisfaction, optimize performance, and enhance organizational effectiveness.

### DATA SOURCE
The primary dataset was gotten from FP20 Analytics Challenge.

### TOOLS & TECHNIQUES
  The tools used for this project are;
  - Microsoft Excel: Data cleaning and preparation
  - Microsoft Power Bi: Data modeling, DAX calculations, relationships, slicers and KPI visuals.
  
### OBJECTIVES/KEY PERFORMANCE INDICATORS

OBJECTIVES
- Identify top-Performing employees & departments.
- Analyze employee distribution and turnover rates by departments.
- Evaluate compensation effectiveness.
- Assess manager performance.
- Discover patterns in employee satisfaction & retention.
- Provide insights for improving HR and operational efficiency.


 ### DATA CLEANING
 Data Cleaning Process using Excel(Power Query)
- I handle missing or inconsistent values in fields required
- I ensured dates are in the correct formula.
- I dropped some columns not relevant for the analysis.
- I removed duplicates
- I cleaned inconsistent writing formats to normalize data.

### DATA ANALYSIS
Data Metrics used
- Employee Metrics: Total Employees, Active Employees, Exit Employees.
- HR Metrics: Retention rate & Turnover Rate.
- Compensation Metrics: Average Salary, Bonus and Benefits.
- Performance Metrics: Average performance Rating, Training Hours & Employee Satisfaction.
- Operational Metrics: Sales and Store Type.

### DASHBOARD & INSIGHTS
1. Employee Overview
   
#### KEY INSIGHTS:
- Total Employees:7495
- Retention: 80.1%, Turnover:19.9%.
- Total Employees by department: Store operation department has the highest employees(3000) and marketing has the lowest employees(149).
- Exited Employees & Turnover by department: Highest in logistics(22.2%, 333 exited employees & HR(22 .2%, 50 exited employees) suggesting job satisfaction issues.
- Average Salary by Job Level: Senior Managers earn the highest salary (₦92K), while Entry-level staff earn the least (₦23K).
- Average performance by Manager name: Manager performance ratings are generally above 3.7, indicating strong team leadership.
  
<img width="1232" height="707" alt="Screenshot 2025-10-29 124558" src="https://github.com/user-attachments/assets/85b27896-4eae-4d04-a6e9-0860b3be6e56" />

2. Performance analysis

Key Insights:
- Avg Performance vs. Employee Satisfaction (Correlation: 0.41): 
A moderate positive correlation exists between employee satisfaction and performance, as shown by the upward trend in the scatter plot.
This means that as average employee performance increases, employee satisfaction levels also rise. higher performing employees tend to be more satisfied with their work environment which could reflect effective management, fair compensation. This suggests that improving job satisfaction can directly enhance performance outcomes.

- Avg Performance vs. Training Hours (Correlation: 0.04):
This is a very weak positive correlation (0.04) between training hours and performance, meaning more training doesn’t necessarily lead to better results. The scattered pattern suggests that while training exists, it may not be effectively driving productivity.

- Performance Rating by Training Hours:
Employees with 6–10 hours of training has the highest performance (3.97), while those with 0–5 hours had slightly lower ratings (3.67) despite being the largest group of employees. Performance declined beyond 10 hours, suggesting that moderate focused training drives better results than either minimal or lengthy sessions.

- Performance Rating by Age Group:
performance slightly improves with age, 51-64 has a higher performing rate of 3.75 suggesting more experience while 21-30 has a lower performing rate of 3.69.

- Performance by Age Group and Department:
Performance distribution across departments is balanced, with slight leads in customer service for age group(51-64 & 41-50) and Marketing has a slight lead for  age group(31-40 & 21-30) performance rating.

<img width="1231" height="724" alt="Screenshot 2025-10-29 124712" src="https://github.com/user-attachments/assets/3b06a908-6fef-457a-93b1-06777d154c25" />
  
3. Store analysis
Key Insights:

- Top & Bottom Stores by Sales: New York superstore made the highest sales of 24.33m while Philadelphia express made the lowest sales of 5.87m. However, most superstore are the top stores while express are the bottom stores based on sales.

- Employee Distribution by Store Type: Regular stores employ the most staff (54.7%), followed by Superstores (32.5%) and Express(12.71%). despite fewer employees, Superstores contribute most to total sales.

- Map of Total Sales and Store Type by City: This shows that most stores city are located in US and superstore showing the big bubbles of sales compared to other store types.

- Average Performance & Satisfaction by Store Type: Performance and satisfaction levels are consistent across store types, averaging 3.7 and 7.2 respectively.
  
<img width="1226" height="712" alt="Screenshot 2025-10-29 125701" src="https://github.com/user-attachments/assets/5e9fc6ef-08ed-48af-be19-e245cd6aacdc" />


4. Sales Performance
- Total Sales by Year: Highest sales was made in 2023 of 661m and YoY of 0.51%.

- Sales Variance by Department: Sales Variance measures the difference between actual sales and expected sales. Fresh produce, Meat/Fish & bakery has a negative variance while store operations has a positive variance they exceeded the sales target.

- Employee Satisfaction by Department: All departments has a high employee satisfaction of 7.00 . However, stores operation has the highest range of 7.32 and logistics has the lowest of 7.12 satisfaction score.
  <img width="1219" height="714" alt="Screenshot 2025-10-29 125834" src="https://github.com/user-attachments/assets/d7f7a219-46a9-40b7-a417-c9e35cdc8cc9" />


### RECOMMENDATIONS

- Enhance retention strategies in high-turnover departments.
- Focus on quality-driven training rather than longer hours.
- Replicate top-performing store practices across other store types.
- Strengthen manager engagement to boost team satisfaction and productivity.
- Continue tracking key performance correlations quarterly to sustain growth
- Recognize and reward employees contributing to consistent sales achievement.


