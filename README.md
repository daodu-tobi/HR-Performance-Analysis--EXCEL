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

- Analysis

  - Calculation of total employee in the company using card visual for the dislay

  - calculation of total male and female employees with their respective percentage

Snapshot of visuals used for displaying the above anlysis 

![Excel 4](https://github.com/user-attachments/assets/45939026-1d8d-4489-83d3-2fec75c6f3f2)

 - Calculation of total employees with high performance by Department using bar chart for visual display

 Snapshot of visuals used for displaying the above anlysis 
 
 ![Excel 5](https://github.com/user-attachments/assets/910eba53-20a1-4cb1-bb56-f55dd79b12db)

 - Calculation of total employees with low performance by Department using bar chart for visual display

 Snapshot of visuals used for displaying the above anlysis 
 
 ![Excel 6](https://github.com/user-attachments/assets/22678968-3c66-4ff9-8f75-5355f5d20b54)

  - Calculation of total employee by Recruitment Channel using Tree Map for visual display

Snapshot of visuals used for displaying the above anlysis 

![Excel 7](https://github.com/user-attachments/assets/101b1bc4-3e9c-4288-9976-465e3944b9b3)

 - Calculation of total employees with high performance by Employees Age Group and Gender, by Distance to work, by Education level and training level using different visual for display

 Snapshot of visuals used for displaying the above anlysis 
 
 ![Excel 8](https://github.com/user-attachments/assets/c6d5b398-be98-49ad-8068-54383e4fbf7a)

 - Calculation of total employees with low performance by Employees Age Group and Gender, by Distance to work, by Education level and training level using different visual for display

 Snapshot of visuals used for displaying the above anlysis 
 
 ![Excel 9](https://github.com/user-attachments/assets/c03465d5-e269-4cc3-96ab-194736762585)

- Insight 
  - 6,250 employees had high performance with respect to KPIs grade value more than 80

  - The number of high performing employees was highest bewteen the ages of 31-40, with 2,048 males and 981 females

  - Employees between the ages of 21-30 had 1474 males and 632 females with high performance 

  - 2,879 employees with high performance lived at near distance to work, 2,146 lived far from work while 1225 lived very far from work

  - Among the 6,250 with high performance, 4,123 employee held barchelors degree, 133 were below secondary school and 1,783 had Masters degree and above

  - Among the 6,250 employees with high performance, 6,211 had Low training level, 36 had Minimal training while 3 were Highly trained

  - Among the 6,250 employees with high performance, 3,450 were recruited from other channels, 2,631 from sourcing while 169 were referred
