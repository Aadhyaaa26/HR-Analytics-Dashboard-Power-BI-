# HR Analytics Dashboard (Power BI)

## Overview
An interactive Power BI dashboard analyzing employee attrition patterns across 
1,470 employees. The dashboard enables HR stakeholders to explore attrition 
drivers by department, age, education, salary band, tenure, and job role, 
with department-level filtering (Human Resources, Research & Development, Sales).

## Key Metrics
| Metric | Value |
|---|---|
| Total Employees | 1,470 |
| Total Attrition | 237 |
| Attrition Rate | 16.1% |
| Average Age | 37 |
| Average Salary | 6.5K |
| Average Years at Company | 7 |

## Key Insights
- **Age**: Employees aged 26–35 account for the highest attrition (116 cases), 
  far exceeding other age groups (18–25: 44, 36–45: 43, 46–55: 26, 55+: 8)
- **Gender**: Male employees show higher attrition (140) compared to female 
  employees (79)
- **Education**: Life Sciences (38%) and Medical (27%) backgrounds make up 
  the largest share of attrition by education field
- **Salary**: Employees earning "Upto 5k" account for the majority of 
  attrition (163 out of 237), suggesting a strong link between lower 
  compensation and turnover
- **Tenure**: Attrition peaks sharply in the first year (59 cases at year 0), 
  then declines — indicating early-tenure retention is a key risk area
- **Job Role**: Laboratory Technician (62), Sales Executive (57), Research 
  Scientist (47), and Sales Representative (33) are the roles with the 
  highest attrition counts

## Dashboard Features
- KPI summary cards: headcount, attrition count, attrition rate, avg age, 
  avg salary, avg tenure
- Department filter tabs: Human Resources / Research & Development / Sales
- Donut chart: Attrition by Education field
- Bar chart: Attrition by Age group
- Bar chart: Attrition by Salary band
- Line chart: Attrition by Years at Company (tenure trend)
- Bar chart: Attrition by Job Role
- Matrix table: JobRole breakdown across categories (1–4) with totals
- Attrition by Gender breakdown (Male vs Female)

## Tools & Skills Used
- **Power BI Desktop** — dashboard design and data visualization
- **Power Query** — data transformation and cleaning
- **DAX** — calculated measures (Attrition Rate, Avg Age, Avg Salary, etc.)
- **Data Modeling** — relationships between employee attributes

## Data Source
[Add dataset name/link here — e.g., IBM HR Analytics Employee Attrition & 
Performance dataset (Kaggle)]

## Screenshots
![Dashboard Overview](screenshots/dashboard-overview.png)

## How to Use
1. Download `HR_Analytics_Dashboard.pbix`
2. Open in Power BI Desktop
3. Use the department tabs at the top to filter by Human Resources, 
   Research & Development, or Sales
4. Click on any visual to cross-filter the rest of the dashboard

## Author
Aadhya Nadar | www.linkedin.com/in/aadhyanadar2605 
