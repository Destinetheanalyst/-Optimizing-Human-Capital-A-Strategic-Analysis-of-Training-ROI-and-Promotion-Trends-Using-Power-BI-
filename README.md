# HR-Training-effective-

### Table of Contents

- [Project Objectives](#project-objectives)
- [Data Source](#data-source)
- [Tools](#tools)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis Process](#data-analysis-process)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)



### Project Objectives 
---
This report presents an HR analytics dashboard built using Power BI for **DYKE INTERGRATED**. The focus is to evaluate the **effectiveness of training programs**, **employee promotions**, and **performance improvements** across key departments: Finance, HR, IT, Marketing, and Sales.



### Data Source
---
#### Dataset Description:
The dataset, sourced from IBM's HR analytics, contains information on 1,470 employees, with 35 features including demographic, job-related, and satisfaction-related variables. The key target variable is Attrition, a binary indicator showing whether an employee has left the company.

![HR Dashboard 1](https://github.com/user-attachments/assets/5fa0e2a2-d16c-4478-9f75-5ed8d2eab61c)

#### Key Columns Include:
- Demographics: Age, Gender, Marital Status, Education.
- Job-related: Job Role, Department, Years at Company, Job Level.
- Satisfaction Metrics: Job Satisfaction, Environment Satisfaction, Relationship Satisfaction.
- Performance & Compensation: Monthly Income, Percent Salary Hike, Stock Option Level, Performance Rating.
- Work-Life Balance: Work Life Balance, OverTime, Distance from Home.

  

### Tools
---
Excel: Used for data aggregation, and analysis. -[Download_here](https://microsoft.com)

Power Query: for data cleaning and proper formatting.
-[Download_here](https://microsoft.com)

### Exploratory Data Analysis
---
EDA involved exploring the HR data to answer key questions such as:

- Total number of staff members.
- Total number of current staff members.
- Average satisfaction level of employees in each department.
- Number of employees per business travel.
- Performance level of each staff.
- Number of employees who left the company in each department (Attrition & Attrition Rate).
- Gender count of employee.
- Age band of employee.



### Data Analysis Process
---
#### Step 1: Data Collection.
The dataset was extracted from IBM analytics platform.

#### Step 2: Data Cleaning/Preparation.
 In the initial data preparation phase, we performed the following tasks using Excel and Power Query:
  1. Data loading and inspection.
  2. Handling missing values.
  3. Data cleaning and formatting.

#### Step 3: Data Aggregation.
- Used Excel Pivot Tables to summarise data for various factors.
- Summarized data using Excel Pivot Tables for Employee Overview.
- Calculated attrition rate by comparing the numbers for different factors.

#### Step 4: Data Analysis.
- Analysed average satisfaction levels and categorised them into Very Satisfied, Satisfied, Very Dissatisfied and Dissatisfied,
- Evaluated the correlation between employee satisfaction levels, performance levels, business travels and total working years.
- Examined employee count and attrritio count across departments.
-  Assessed attrition per job role, educational levels, age bands and gender.

#### Step 5: Visualisation & Insights
- Created pivot tables and charts to visualise trends.
- Derived insights to support HR decision-making, such as potential areas for employee engagement improvements, gender and age bands trends.

  

### Results
---
#### Promotion Overview

#### General Insights

- **Promotion Count**: 521 employees were promoted, representing **17.37%** of the total workforce.
- **Training Participation**:  
  - **Yes**: 1,828 employees (61%)  
  - **No**: 1,172 employees (39%)

- **Training ROI Concerns**:  
  - Only **28.5% of the training budget** (261K) went to employees promoted within 6 months.  
  - **71.5% of the budget** (654K) was spent on employees who were not promoted — indicating a potential **gap in post-training evaluation or application**.

#### Departmental Promotion & Training Cost Breakdown

| Department | Promotion Count | Total Employees | Avg Improvement Score | Training Cost |
|------------|------------------|------------------|------------------------|----------------|
| Sales      | 113              | 613              | 5                      | 181K           |
| HR         | 107              | 584              | 5                      | 179K           |
| IT         | 107              | 618              | 5                      | 189K           |
| Marketing  | 104              | 620              | 5                      | 183K           |
| Finance    | 90               | 565              | **6** (highest)        | 182K           |

🔍 **Observation**: Finance had the **highest score improvement** with a similar budget, indicating **more effective training strategies**.

---
  
![HR Dashboard 2](https://github.com/user-attachments/assets/d0a23232-69c6-4ab2-99f6-b7d85266eb40)

#### Performance Overview

#### Training Distribution

#### Trained Employees (By Department)
- Finance: 378  
- Sales: 366  
- HR: 362  
- Marketing: 364  
- IT: 358  

####  Untrained Employees
- IT: 254 (21.67%)  
- Sales: 240 (20.48%)  
- HR: 226  
- Marketing: 201  
- Finance: 190  

### Performance Scores (Before vs After Training)

| Department | Pre-Training Score | Post-Training Score | Improvement |
|------------|--------------------|---------------------|-------------|
| Finance    | 69.27               | **74.9**             | +5.63       |
| IT         | 69.39               | 74.55                | +5.16       |
| HR         | 69.20               | 74.55                | +5.35       |
| Marketing  | **74.43**           | 69.46                | **−4.97**   |
| Sales      | 74.20               | 69.36                | −4.84       |

📌 **Insight**: While most departments showed improvement, **Marketing and Sales experienced post-training performance drops**, highlighting a **potential mismatch in training content or execution**.



  
  
### Recommendations
---
- Implement Retention Programs: Focus on developing and implementing retention strategies, especially in high-attrition departments like Sales and Technical. This could include career development opportunities, mentorship programs, and clear career advancement paths.
- Enhance Employee Engagement: Address the varying levels of employee satisfaction by conducting regular surveys and feedback sessions. Use this data to tailor engagement initiatives that cater to the specific needs of each department.
- Promote Career Development: Increase opportunities for employee promotions by investing in training and development programs. Ensure that employees see a clear pathway to growth within the company.
- Balance Compensation and Workload: Review and adjust compensation and workload to ensure fairness and equity across departments.
- Strengthen Safety Measures: Even though work accidents are minimal, continuously reinforce safety protocols and provide regular training to maintain a safe work environment.

