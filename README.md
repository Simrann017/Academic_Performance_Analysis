# 📊 Pragmatic Academy – Student Performance Dashboard (Power BI)

An interactive **Power BI dashboard** project designed to analyze student academic performance across various U.S. states and school districts. The visualization provides actionable insights into **reading and math score trends**, **state-level performance**, and the **impact of extracurricular activities** on academic outcomes.

---

## 📁 Dataset Overview

### 1. `StudentTestingData.csv`
Primary dataset used in this project, containing academic assessment records.

**Key Features:**
- `District`: School district name
- `State`: U.S. state abbreviation (e.g., CA, NY, TX)
- `Reading Score` & `Math Score`: Standardized student performance metrics
- `Extracurricular Activity`: Activity type (e.g., Debate, Music, Drama)
- `Test Year`: Academic year of the test (e.g., 2022, 2023)

> 🔹 Cleaned, transformed, and modeled using Power BI's Power Query Editor.

---

## 📌 Dashboard KPIs

| KPI Description                                    | Metric / Calculation                                |
|----------------------------------------------------|-----------------------------------------------------|
| 📚 **Average Reading Score by District**           | District-level aggregation of reading scores        |
| 📐 **Average Math Score by Activity**              | Grouped average based on extracurricular type       |
| 🌎 **Reading Score by State**                      | State-wise average with conditional formatting      |
| 📈 **Reading Score YoY Growth**                    | Percentage difference between 2022 and 2023         |

---

## 🔍 Key Insights

- **Top Performing Districts**:  
  Districts like *Hawthorn Valley* and *Maple Ridge* scored highest in reading, indicating strong academic programs.

- **Activity Impact on Math Performance**:  
  Students in **Debate** and **Music** showed higher math scores than those in **Drama** or undefined categories—suggesting a link between structured activities and academic discipline.

- **State-Level Performance**:  
  - 🏆 **Wyoming (WY)** leads with the highest average reading score: `366.62`.
  - **Connecticut (CT)** and **Colorado (CO)** follow with scores above the national average.

- **Year-over-Year Growth**:  
  - **Arizona (AZ)** and **Maryland (MD)** reported the highest improvements in reading scores: `2.05%` and `2.03%` respectively.
  - Overall national improvement: **1.34%**

---

## 📊 Visualizations Included

- Bar Chart: Reading Score by District
- Column Chart: Math Score by Activity
- Matrix Table: State-wise Reading Score with YoY % Difference
- Interactive Filters: District selection slicer for drill-through

---

## 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query (M Language)**
- **DAX (Data Analysis Expressions)**
- **Excel/CSV Data Cleaning**

---

## 📌 Usage

1. Open the `.pbix` file in Power BI Desktop (if included).
2. Replace the sample CSV with updated datasets if needed.
3. Use the slicer in the top right to drill down by district.
4. Export or publish the report to Power BI Service for sharing.

---

## ✅ Outcomes

This project demonstrates the ability to:
- Model real-world education data in Power BI
- Build visually rich and insight-driven dashboards
- Apply DAX to calculate KPIs and time-based metrics
- Communicate trends in a clear, interactive format
