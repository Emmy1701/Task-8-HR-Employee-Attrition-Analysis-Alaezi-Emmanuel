# 👥 HR Employee Attrition Analysis Dashboard

![HR Employee Attrition Analysis Dashboard](HR%20Attrition.png)

## 1. Executive Summary
This Power BI dashboard analyzes workforce dynamics, turnover metrics, and key attrition drivers across a total headcount of **1,470 employees**[cite: 7]. Developed using **Power Query** for data transformation and **DAX** for HR calculations, it evaluates turnover patterns across departmental classifications, job roles, overtime exposure, job satisfaction, and employee tenure[cite: 7].

---

## 2. Key Performance Indicators (KPIs)
* **Total Employees:** `1,470`[cite: 7]
* **Employees Left (Attrition Volume):** `237`[cite: 7]
* **Attrition Rate:** `16.1%`[cite: 7]
* **Average Monthly Income:** `$6,503`[cite: 7]

---

## 3. Key Analytical Insights
1. **Department & Role Breakdown:**
   * **Research & Development** records the highest absolute attrition (**133 employees**)[cite: 7], followed by **Sales** (**92**)[cite: 7] and **Human Resources** (**12**)[cite: 7].
   * The Top 5 roles affected by turnover are **Laboratory Technicians (62)**[cite: 7], **Sales Executives (57)**[cite: 7], **Research Scientists (47)**[cite: 7], **Sales Representatives (33)**[cite: 7], and **HR staff (12)**[cite: 7].
2. **Age Demographic Vulnerability:**
   * Staff aged **25–34** experience the highest turnover rate (**112 employees**)[cite: 7], followed by the **35–44** group (**51**)[cite: 7] and **Under 25** cohort (**38**)[cite: 7].
3. **Overtime Impact:**
   * Working overtime is a major turnover driver, accounting for **46% (110 employees)** of all departures[cite: 7], despite representing a smaller total proportion of the workforce[cite: 7].
4. **Tenure & Turnover Timing:**
   * Attrition spikes significantly within the **first 1 to 3 years** of employment before flattening out dramatically after 10 years[cite: 7].

---

## 4. Technical Workflow (Power Query & DAX)
* **Data Transformation (Power Query):** Processed raw HR records, converted categorical variables, handled missing values, and created structured age demographic bins (Under 25, 25-34, 35-44, 45-54, 55+)[cite: 7].
* **DAX Calculations:** Formatted custom measures for overall headcount, total departures, percentage attrition rates, average monthly income, and satisfaction score groupings[cite: 7].
* **UI/UX Design:** Built a clean navy-themed layout featuring left-hand filter slicers (Department, Gender, Job Role, Marital Status, Business Travel, Overtime)[cite: 7] alongside KPI cards, donut distributions, line plots, and bar charts[cite: 7].

---

## 5. Strategic Recommendations
* **Early Tenure Retention Programs:** Implement structured onboarding and 90-day check-ins to reduce turnover during the critical 1-to-3-year window[cite: 7].
* **Overtime Balance & Workload Review:** Review workload distribution in R&D and Sales departments to mitigate burnout among overtime workers[cite: 7].
* **Mid-Career Growth Pathways:** Develop clear career progression tracks tailored for the 25–34 age demographic to improve retention in core technical and sales roles[cite: 7].
