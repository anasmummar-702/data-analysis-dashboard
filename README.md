# CAIR-KPI-DASHBOARD-Analysis (Interactive Dashboard Creation Using Power BI)
## student project 
This dashboard provides a visual overview of key academic metrics related to student enrollment, performance, and outcomes across different academic years. It is designed to help education administrators monitor trends, track institutional effectiveness, and support data-driven decision-making.

## Dataset used

-<a href="https://github.com/anasmummar-702/data-analysis-dashboard/blob/main/Data%20file%20for%20dashboard_CAIR_fin.xlsx">Dataset</a>

## Question (Kpis)

-What does the KPI “Selected Students = 1318” represent, and how is it calculated in your dashboard?

-How does the ‘30+ Units in Year 1’ KPI help measure student academic performance or progress?

-What insight can you draw from the fact that only 21.62% of students completed more than 30 units in their first year?

-Why is tracking student count by year important for institutional performance measurement?

-How do the KPIs for awards (A.A., A.S., Certificates) reflect student success trends?

-What does the transfer institute KPI reveal about student continuation rates and preferred universities?

-How do you define success metrics in this dashboard — what KPIs show improvement or decline?

-If the number of selected students decreases next year, which other KPIs would you analyze to find the reason?

-What thresholds or goals would you set for these KPIs to evaluate academic progress over time?

-How could you automate or refresh KPI values when new data is added to the source file?

 -DashBord Interaction 
 <a herf="https://github.com/anasmummar-702/data-analysis-dashboard/blob/main/Screenshot%202025-10-21%20145619.png">View Dashboard</a>

---

## ⚙️ Process and Steps

### 1. Data Collection
- Imported student dataset from Excel/CSV into Power BI.
- Included key fields: Student ID, Cohort Year, Gender, Ethnicity, Award Type, Units Completed, and Transfer Institute.

### 2. Data Transformation
- Cleaned and transformed data using **Power Query**.
- Removed duplicates, handled missing values, and standardized column names.
- Created calculated columns and measures (e.g., students with 30+ units in Year 1).

### 3. Data Modeling
- Built relationships between tables (`Sheet1`, `Query1`) using **Student ID**.
- Used **DAX** measures to calculate KPIs such as total selected students and percentage completion.

### 4. Dashboard Design
- Created an interactive dashboard featuring:
  - **Line Chart** – Student count by year  
  - **Donut Chart** – 30+ units completed in Year 1  
  - **Bar Charts** – Award distribution & Transfer institute  
  - **KPI Card** – Total selected students (1318)
- Added slicers for Gender, Ethnicity, Cohort Year, and Veteran Status.

### 5. Insights
- Student enrollment decreased over time (2010–2013).  
- Only **21.62%** of students completed 30+ units in their first year.  
- Most students earned **A.A.** or **A.S.** awards.  
- Highest transfers were to **UC campuses (846 students)**.

---
## Dashboard 
<img width="1920" height="1080" alt="Screenshot 2025-10-21 145619" src="https://github.com/user-attachments/assets/14dfada2-dc40-49a9-8c6a-865413be3a0d" />

## 📊 Project Insights

1. **Enrollment Trend:**  
   The line chart shows a **steady decline in student enrollment** from 2010 to 2013, indicating a possible drop in student intake or retention rates.

2. **Academic Progress:**  
   Only **21.62%** of students completed **30+ units** in their first year, suggesting a need for enhanced academic support during the early stages of study.

3. **Award Distribution:**  
   The majority of students received **A.A. (Associate of Arts)** and **A.S. (Associate of Science)** degrees, while a notable portion received **no awards**, signaling potential gaps in completion rates.

4. **Transfer Outcomes:**  
   **UC campuses** accounted for the highest number of student transfers (**846 students**), highlighting strong transfer pathways and partnerships.

5. **Demographic Insights:**  
   Interactive slicers (Gender, Ethnicity, Cohort Year, and Veteran Status) enable dynamic filtering and deeper analysis of student demographics and performance trends.

---

## 🧠 Final Conclusion

The **CAIR KPI Dashboard** delivers a comprehensive view of student performance, enrollment trends, and transfer outcomes.  
By leveraging **Power BI**, this analysis transforms raw educational data into meaningful insights that support data-driven decision-making.  

This project demonstrates how visual analytics can help educational institutions:
- Track key performance indicators (KPIs)  
- Identify performance gaps early  
- Improve academic planning and student success outcomes  


