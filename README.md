# HR Analytics Dashboard - Employee Attrition Analysis

Welcome to the HR Analytics Dashboard focusing on employee attrition analysis. This dashboard provides valuable insights into factors influencing employee attrition within the organization.

## Data overview 

 The analysis is based on a comprehensive dataset containing information on employee demographics, job characteristics, and satisfaction levels. This data is obtained from an youtube source .

| Column Name              | Description                                                                                   |
|--------------------------|-----------------------------------------------------------------------------------------------|
| EmpID                    | Employee ID, a unique identifier for each employee.                                           |
| Age                      | Age of the employee.                                                                          |
| AgeGroup                 | Possibly a derived attribute based on age, grouping employees into specific age ranges.       |
| Attrition                | A binary variable indicating whether the employee has left the company (Yes/No).             |
| BusinessTravel           | Frequency of business travel (e.g., Travel_Rarely, Travel_Frequently, Non-Travel).            |
| DailyRate                | The daily rate of pay for the employee.                                                       |
| Department               | The department in which the employee works (e.g., Sales, Human Resources, Research & Development).|
| DistanceFromHome         | Distance from the employee's home to the workplace.                                            |
| Education                | Level of education attained by the employee.                                                   |
| EducationField           | Field of education of the employee (e.g., Life Sciences, Medical, Marketing).                  |
| EmployeeCount            | Possibly a constant value indicating the count of employees (likely 1 for each row).          |
| EmployeeNumber           | Another unique identifier for each employee.                                                   |
| EnvironmentSatisfaction  | Satisfaction level of the employee with their work environment.                                |
| Gender                   | Gender of the employee.                                                                       |
| HourlyRate               | Hourly rate of pay for the employee.                                                           |
| JobInvolvement           | Level of involvement the employee has in their job.                                            |
| JobLevel                 | Level of the employee's job within the company hierarchy.                                      |
| JobRole                  | Specific role or position of the employee (e.g., Sales Executive, Research Scientist, Manager).|
| JobSatisfaction          | Satisfaction level of the employee with their job.                                             |
| MaritalStatus            | Marital status of the employee (e.g., Single, Married, Divorced).                              |
| MonthlyIncome            | Monthly income of the employee.                                                                |
| SalarySlab               | Possibly a derived attribute categorizing monthly income into salary slabs or ranges.          |
| MonthlyRate              | The monthly rate of pay for the employee.                                                       |
| NumCompaniesWorked       | Number of companies the employee has worked for previously.                                     |
| Over18                   | A binary variable indicating whether the employee is over 18 years old (Yes/No).               |
| OverTime                 | A binary variable indicating whether the employee works overtime (Yes/No).                     |
| PercentSalaryHike        | Percentage increase in salary for the employee.                                                 |
| PerformanceRating        | Performance rating of the employee.                                                             |
| RelationshipSatisfaction | Satisfaction level of the employee with their relationships at work.                            |
| StandardHours            | Possibly a constant value indicating the standard number of working hours (likely 8 for each row).|
| StockOptionLevel         | Level of stock options granted to the employee.                                                 |
| TotalWorkingYears        | Total number of years the employee has been working.                                            |
| TrainingTimesLastYear    | Number of times the employee was trained last year.                                             |
| WorkLifeBalance          | Level of balance between work and personal life for the employee.                               |
| YearsAtCompany           | Number of years the employee has been with the company.                                         |
| YearsInCurrentRole       | Number of years the employee has been in their current role.                                     |
| YearsSinceLastPromotion  | Number of years since the employee's last promotion.                                            |
| YearsWithCurrManager     | Number of years the employee has been with their current manager.                               |


## Data Cleaning Operations

In preparation for analysis and visualization, the raw dataset underwent several data cleaning operations to ensure accuracy and consistency. The following steps were performed:

1. **Handling Null Values:**
   - Null values were identified across the dataset, and appropriate strategies were applied to handle them .
  
    ![Screenshot 2024-05-15 114243](https://github.com/Kedhar193/powerbi-dashboard/assets/115712936/6afad59d-3c64-4016-983d-dd63c1477939)

    ![Screenshot 2024-05-15 114426](https://github.com/Kedhar193/powerbi-dashboard/assets/115712936/a72fbc78-8381-4bf0-98bc-211739f75b57)


2. **Removing Duplicate Columns:**
   - Duplicate column were identified and removed to eliminate redundancy and streamline the dataset. This ensures that each attribute provides unique and valuable information for analysis.
  
     ![Screenshot 2024-05-15 114508](https://github.com/Kedhar193/powerbi-dashboard/assets/115712936/2d113000-3c23-424c-9c9a-57342821169f)


3. **Data Type Formatting:**
   - Data types of the columns were standardized to ensure uniformity and compatibility with analytical tools. This involved converting categorical variables into appropriate data types (e.g., strings to categorical factors) and ensuring numerical variables are represented in the correct format (e.g., integers or floats).
  
     ![Screenshot 2024-05-15 114547](https://github.com/Kedhar193/powerbi-dashboard/assets/115712936/0af0540a-3837-4bae-a316-4d9fdd26f0e6)

4. **Adding Additional columns:**
   - Adding conditional column to calculate Attrition Count which simplyfies the further calculations like Attrition Rate .
  
     ![Screenshot 2024-05-15 135041](https://github.com/Kedhar193/powerbi-dashboard/assets/115712936/5aaa12f2-c22c-479c-961c-795a651f20b0)

## Dashboard Overview

The HR Analytics Dashboard provides a comprehensive analysis of employee attrition through various visualizations, each designed to uncover insights and trends from the dataset. Below is a detailed description of the key visualizations included in the dashboard:

### Key Metrics
- **Cards:**
  - **Attrition Count:** Displays the total number of employees who have left the company.
  - **Count of Employees:** Shows the total number of employees.
  - **Attrition Rate:** Calculates the percentage of employees who have left the company.
  - **Average Age:** Displays the average age of employees.
  - **Average Salary:** Shows the average monthly income of employees.
  - **Average Years at Company:** Displays the average tenure of employees at the company.

### Visualizations
- **Donut Chart:**
  - **Attrition by Education:** Illustrates the distribution of attrition across different education levels.

- **Stacked Column Chart:**
  - **Attrition by Age Group:** Displays the attrition rate segmented by different age groups, showing the distribution and proportion of attrition across various age ranges.

- **Matrix:**
  - **Attrition by Job Role:** Provides a detailed view of the job satisfaction level for different job roles and attrition as values of the matrix .

- **Clustered Bar Chart:**
  - **Attrition by Salary Slab:** Compares attrition rates across different salary slabs, highlighting how compensation levels affect employee turnover.
  - **Attrition by job role:** Reiterates the analysis of attrition segmented by job role for additional insight.

- **Area Chart:**
  - **Attrition by Years at Company:** Shows the trend of attrition over the tenure of employees, providing insights into how long employees stay before leaving.

- **Heat Map:**
  - **Attrition by Gender:** Visualizes the distribution of attrition between different genders, highlighting any gender-based patterns in employee turnover.

### Interactivity
- **Slicer:**
  - **Department:** Allows users to filter the visualizations by specific departments, enabling a focused analysis of attrition within particular areas of the organization.

![Screenshot (85)](https://github.com/user-attachments/assets/5f8189f8-64f7-41a6-809e-2dd7fc2b24e7)



## Conclusion
These visualizations collectively provide a comprehensive understanding of employee attrition, allowing stakeholders to identify key factors and trends influencing turnover. The interactive elements, such as the department slicer, further enhance the analytical capabilities of the dashboard, enabling users to drill down into specific segments and derive actionable insights.

By leveraging these visualizations, HR professionals and organizational leaders can make data-driven decisions to address attrition, improve employee retention, and foster a more engaged and satisfied workforce.
 
## Source

I have completed this project following an youtube tutorial 

link to the source :  https://youtu.be/j4xlVLgsmNQ?si=OjvOOJXI_eqAGOJ_
