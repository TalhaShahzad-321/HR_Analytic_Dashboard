# HR_Analytic_Dashboard
🛠️ **HR Analytics Dashboard Project**

I am excited to share my latest project, an interactive and insightful HR Analytics Dashboard. This dashboard provides a comprehensive view of employee data, enabling better decision-making and strategic planning for human resources management.

📊 **Key Metrics:**

👥 **Employee Overview:**
- **Count of Employees:** Total number of employees.
- **Attrition Count:** Number of employees who have left the company.
- **Attrition Rate:** Percentage of employees who have left the company.
- **Average Age:** Mean age of the employees.
- **Average Years at Company:** Average tenure of employees at the company.
- **Average Salary:** Mean salary of the employees.

📈 **Visualizations:**

🍩 **Donut Chart:** Attrition by Education, providing insight into how education levels correlate with employee attrition.

📊 **Stacked Column Chart:** Attrition by Age, showcasing the age distribution of employees who have left the company.

📊 **Stacked Bar Chart:** Attrition by Salary, illustrating the correlation between salary levels and employee attrition.

📉 **Area Chart:** Attrition by Years at Company, highlighting trends in attrition based on tenure.

📊 **Stacked Bar Chart:** Attrition by Job Role, showing which job roles have the highest attrition rates.

📋 **Matrix:** Job Role by Job Satisfaction, with a sum of attrition count, providing a detailed view of job satisfaction across different roles.

🌳 **Tree Map:** Attrition by Gender, offering a visual representation of attrition rates among male and female employees.

🔄 **Interactive Features:**
- **Department Slicer:** Allows users to filter data by department (Human Resources, Research and Development, Sales) for focused analysis.

📐 **New Measure:**
- **Attrition Rate:** Defined as the sum of attrition count divided by the sum of employee count. 
  ```DAX
  Attrition Rate = SUM(HR_Analytics[Attrition Count])/SUM(HR_Analytics[EmployeeCount])
  ```

💡 **Insights:**
- **Educational Influence on Attrition:** The donut chart reveals significant differences in attrition rates among various education levels.
- **Age and Attrition Trends:** The stacked column chart helps identify which age groups are more likely to leave the company.
- **Salary and Attrition Correlation:** The stacked bar chart provides insights into how salary influences employee retention.
- **Tenure and Attrition Patterns:** The area chart shows attrition trends over the years employees stay at the company.
- **Job Role Impact:** The stacked bar chart highlights specific roles with higher attrition, aiding in targeted retention strategies.
- **Job Satisfaction Analysis:** The matrix visualization helps understand job satisfaction levels across different job roles.
- **Gender Disparity:** The tree map offers a clear view of attrition rates between male and female employees.

🔍 **Lessons Learned:**
- Leveraging data visualization to uncover valuable HR insights.
- Employing advanced data analysis techniques for accurate and meaningful metrics.
- Creating user-friendly interfaces with interactive slicers and filters to enhance usability.
