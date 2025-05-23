# Optimizing Human Capital: A Strategic Analysis of Training ROI and Promotion Trends Using Power BI

### Table of Contents

- [Project Objectives](#project-objectives)
- [Data Source](#data-source)
- [Tools](#tools)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis Process](#data-analysis-process)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [Conclusion](#conclusion).



### Project Objectives 
---
This report presents an HR analytics dashboard built using Power BI for **DYKE INTERGRATED**. The focus is to evaluate the **effectiveness of training programs**, **employee promotions**, and **performance improvements** across key departments: Finance, HR, IT, Marketing, and Sales.

![page 1](https://github.com/user-attachments/assets/3a52f10a-b739-4498-ad28-9285235ded99)


### Data Source
---
#### Dataset Description:
The dataset, sourced from IBM's HR analytics, contains information on 1,470 employees, with 35 features including demographic, job-related, and satisfaction-related variables. The key target variable is Attrition, a binary indicator showing whether an employee has left the company.

#### Key Columns Include:
- **Promotion Rate**: % of employees promoted in each department.
- **Training Participation Rate**: % of employees who received training.
- **Score Improvement**: Change in test scores after training.
- **Training Cost Efficiency**: Cost per promoted employee vs. total cost.
- **Departmental Comparison**: Ranking departments by improvement score and cost-effectiveness.


### Tools
---
Power BI: Used for data aggregation, and analysis. -[Download_here](https://microsoft.com)

Power Query: for data cleaning and proper formatting.
-[Download_here](https://microsoft.com)

### Exploratory Data Analysis
---

#### Training Participation
- Which departments have the highest/lowest training participation rates?
- What percentage of employees attended training vs. didn't?

#### Score Analysis
- What's the average pre/post-training score difference across departments?
- How many employees showed score regression after training?

#### Promotion Correlation
- What percentage of trained employees received promotions vs. non-trained?
- Which department shows the strongest correlation between training and promotions?

#### Cost Analysis
- What's the total training investment per department?
- What's the average cost per promoted employee in trained vs. non-trained groups?




### Data Analysis Process
---
This section outlines the full process followed in conducting the HR analysis for DYKE INTERGRATED, with a focus on evaluating the effectiveness of employee training programs and promotion outcomes.

---

#### 1. Data Collection
- **Source**: HR database of DYKE INTERGRATED.
- **Format**: Excel/CSV datasets.
- **Content**:
  - Employee IDs, departments, and training participation.
  - Pre- and post-training assessment scores.
  - Promotion status and training costs.

#### 2. Data Cleaning & Preparation
- Checked for missing values (e.g., missing scores or promotion flags).
- Removed duplicate records to ensure unique employee entries.
- Converted categorical fields (e.g., "Yes"/"No" for training participation) to standard format.
- Standardized numeric fields such as scores and training costs.

#### 3. Exploratory Data Analysis (EDA)
- Used Power BI to create initial visuals and summaries.
- Identified trends across departments regarding:
  - Promotion rates.
  - Average score improvements.
  - Total training cost.
- Calculated basic statistics:
  - Promotion percentage = (Promoted Employees / Total Employees) × 100
  - Average improvement score = Post-training − Pre-training
  - Department-wise training coverage

#### 4. Data Visualization (Power BI)
- Built interactive dashboards for:
  - **Promotion Overview**: Training cost vs. promotion, departmental promotion breakdown.
  - **Performance Overview**: Score comparisons (before vs. after), trained vs. untrained distribution.
- Used visual elements:
  - Bar charts for score comparisons.
  - Pie charts for training participation.
  - Tables for departmental performance summaries.

#### 5. Insight Generation
- Identified departments with best and worst training outcomes.
- Highlighted finance department as most efficient (highest improvement with moderate cost).
- Observed drop in post-training performance in Marketing and Sales.
- Discovered mismatch between training investment and promotion outcomes (71.5% of budget went to non-promoted employees).

#### 6.  Reporting & Interpretation
- Documented all findings in a structured markdown report.
- Provided strategic recommendations to the HR department:
  - Reassess training content and alignment.
  - Optimize training budget distribution.
  - Evaluate training ROI based on promotions and performance.
  - Expand training coverage in undertrained departments.
  

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
  
![p2](https://github.com/user-attachments/assets/b2d5aaa6-70aa-4b46-b6b2-80547fe701ed)


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
1. **Reassess Training Content** for Marketing and Sales to align better with performance objectives.
2. **Expand Training Coverage** in IT and Sales to reduce the untrained employee ratio.
3. **Replicate Finance Department Strategies** across others, as it achieved the best score improvement per cost spent.
4. Consider **performance-based training budget allocation** — shifting focus to high-impact departments.


### Limitations
 ---
1. ##### **Limited Scope of Variables**
   The analysis focuses on core metrics such as training cost, promotion rate, and score improvements. Other important HR factors like employee satisfaction, engagement, retention rate, or qualitative feedback were not considered.

2. ##### **Training Effectiveness Not Fully Captured**
   The improvement score is quantitative and may not reflect behavioral changes or practical, on-the-job performance. The long-term impact of training is not assessed.

3. ##### **Lack of Clarity on Promotion Criteria**
   The report assumes a connection between training and promotion but does not clarify the actual criteria for promotions. Factors like tenure, manager recommendation, or performance evaluations may also influence promotions.

4. ##### **Data Granularity Constraints**
   The data is aggregated at the department level, which may mask insights from individual or team-level performance. High performers or underperformers may be hidden within averages.

5. ##### **Unclear Timeframe**
   The timeframe of data collection (monthly, quarterly, or yearly) is not specified, making it difficult to identify trends or seasonality in training outcomes and promotions.

 ### Conclusion
---
The Power BI dashboard highlights critical patterns in training efficiency, departmental performance, and promotion outcomes. DYKE INTERGRATED can leverage these insights to **optimize HR strategies**, ensure **cost-effective training**, and **foster talent development** organization-wide.
