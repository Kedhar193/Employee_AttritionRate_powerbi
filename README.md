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



