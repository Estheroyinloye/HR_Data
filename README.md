
## Project Title: Premium Consultancy Attrition Analysis

![](6946EF2B-755F-4352-83A7-7A1D1277AFCF_4_5005_c.jpeg)

### Introduction
This is a Microsoft Excel project on attrition analysis of an imaginary organization called **Premium Consultancy**. 
The project is aimed at analysing and deriving insights to answer critical questions and help the orgnization make data driven decisions.
**_Disclaimer_**: _All datasets and reports do not represent any company, institution or country but a dummy dataset to demonstrate the cabability of Microsoft  Excel._

### Problem Statement
- How many employees left the company?
- What was the impact of attrition on each department’s performance?
- What is the gender breakdown of employees who left?
- How is employee satisfaction related to attrition rates?
- Is there a link between age and attrition?
- Does education level correlate with attrition rates?
- Which job roles were most affected by attrition?
- Any other relevant insights.

### Excel Concept applied
- Excel functions; IF, IFS, TRIM, X-LOOKUP
```excel
=IFS(D2= "Under 25", 1,D2= "25 - 34", 2,D2= "35 - 44", 3, D2= "45 - 54", 4, D2= "Over 55", 5 )
```
- Pivot tables
- Filters
- Slicers

### Data Source
The data was obtained from an open-source data site as a CSV file, after which it was cleaned, analysed, and visualized with Microsoft Excel.

### Data Transformation and cleaning
To clean the data, duplicates and blanks were removed from from the table using the " Remove duplicate" and "filter" button in excel.
Trim funtion was used to remove excess spaces
Proper function was used to standardize the text


### Data Analysis and Visualization
The report comprises;
- Total Attrition count
- Total Employee count
- Attrition by Department
- Attrition by Age
- Attrition by gender
- Attrition by job satisfaction level
- Attrition by educational field
- Attrition by marital status
- Attrition by Job role 

![](5.png)

![](4.png)

![](3.png)

![](2.png)

![](1.png)


### From the dashboard we could discover the following insights;
1.	Out of 1,470 employees, 237 experienced attrition, representing approximately 16% of the workforce.
2.	There exist a  strong link between job satisfaction level and attrition, where lower satisfaction is seen to have the highest attrition.
3.	Job Level 1 had the highest attrition, with 143 employees leaving while the attrition rates decline significantly at higher job levels, with Job Levels 4 and 5 experiencing the least attrition (5 employees each).
4.	Laboratory Technicians and Sales Executives showed the highest attrition counts,with a noticeable proportion of both males and females leaving these roles while the Research Directors and Managers experience the lowest attrition rates, indicating potentially higher job satisfaction or stability within these roles.
5.	Attrition is highest among employees with a Life Sciences or Medical background, while Field like the Human Resources had e very low attrition rates.
6.	The R&D department showed the highest attrition rate 56.1%, followed by Sales and HR having a relatively low attrition rate 5.1%, suggesting greater stability or satisfaction within this department.
7.	Male employees account for 63.3% of the total attrition, while female employees make up 36.7%.
8.	The age group 25-34 had the highest attrition, constituting 47.7% of the total with the attrition decreasing significantly in older age groups, with those aged 35-44 representing 21.9% and those over 55 making up only 3.4%.

### Conclusion
The data revealed that employee attrition is significantly influenced by job role, satisfaction level, job level, department, gender, and age. 
Laboratory Technicians and Sales Executives exhibited the highest turnover, particularly among younger, entry-level employees with Life Sciences and Medical backgrounds. 
Employees with low job satisfaction were more likely to leave, highlighting satisfaction as a critical factor. 
The R&D and Sales departments experienced the highest attrition rates, with male employees showing a higher likelihood of departure compared to females. 

### Reccommendation
To reduce the attrition count, the organization could focus on enhancing job satisfaction in high-turnover departments like R&D and Sales and among entry-level employees. Additionally, the could implement targeted retention strategies for younger staff and provide clear career development paths, especially for roles with high turnover, such as Laboratory Technicians and Sales Executives.


