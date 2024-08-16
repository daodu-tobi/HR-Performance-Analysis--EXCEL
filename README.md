
# Employee’s Performance for HR Analytics


## Description
Employee performance for HR analytics can provide valuable insights to organizations in terms of employee engagement, productivity, and overall organizational effectiveness. HR analytics involves using data to make informed decisions about human resources and employee-related matters. 

  #### About dataset

  -  Employee ID : Unique Identifier for Each Employee

  - Department  : Categorization of Employees into Different Departments

  - Region : Geographical Region of Employee's Work Location

  - Education : Employee's Educational Background

  - Gender : Distribution of Employees by Gender

  - Recruitment Channel - Source through which Employees were Recruited

  - Number of Trainings - Count of Training Programs Attended by Each Employee
  
  -  Age : Age of Employees

  - Previous Year Rating : Performance Rating of Employees from the Previous Year

  - Length of Service : Duration of Employment with the Company
  
### Problem statement
 




#### Objectives 
- Data Cleaning and Preparation: Clean and preprocess the data to ensure it is accurate and consistent. Handle missing values and outliers appropriately.

- Exploratory Data Analysis (EDA): Perform EDA to gain insights into the distribution of performance metrics, identify patterns, and visualize trends

- Recommendations and Actionable Insights: Based on the analysis, provide actionable insights and recommendations to the HR department and relevant stakeholders. 

### Steps Followed

- Viewing dataset in Microsoft Excel to fully understand the dataset

- Loaded dataset into power query for cleaning and preprocessing

Snapshot of dataset in power query
![Excel 2](https://github.com/user-attachments/assets/69aba7f3-25ed-427d-80fd-665433697539)

  - The Education column contained null values which were filled with the highest occuring field(Mode) which is 'Bachelors Degree'

  - The Region column which indicates the distance to work was categorized into 'Near', 'Far', 'Very-Far' in a new column to aid proper vizualization.

      - Region less than or equals to 12 is categorized as 'Near'

      - Region less than or equals to 24 is categorized as 'Far'

      - Region greater than 24 is categorized as 'Very-Far'

  - The 'Age' column was futher categorized into Age- range in a new column
    
    - Age range less than or equal to 30 is categorized in the ranges of '20-30'

    - Age range less than or equal to 40 is categorized in the ranges of '31-40'

    - Age range less than or equal to 50 is categorized in the ranges of '41-50'

    - Age range greater than 50 is categorized as 51 plus

- KPI grade more than 80 shows high performance, while KPI grade lower than 80 show low performance


   - The average training score was categorized into 'Training Grade' 
  
    - Training Score less than or equal to 49 was categorized as 'Poor'

    - Training Score less than or equal to 59 was categorized as 'Average'

    - Training Score less than or equal to 69 was categorized as 'Good'

     - Training Score less than or equal to 79 was categorized as 'Very-Good'

     - Training Score above 79 was categorized as 'Excellent'

    
- Creation of Pivot-Tables to analysis the transformed data

Snapshot of Pivot-Tables used for analysis 
![Excel 1](https://github.com/user-attachments/assets/664cec41-8156-4ecc-bd8e-5c56baec54ff)

