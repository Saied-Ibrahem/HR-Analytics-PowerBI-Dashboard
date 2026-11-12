# HR-Analytics-PowerBI-Dashboard

An interactive two-page Power BI dashboard designed to help HR teams monitor workforce demographics, promotion readiness, retention risks, and employee satisfaction.

## 📊 Dashboard Preview

### Home Page — Executive Overview
![Home Page](<img width="1397" height="777" alt="Home Page" src="https://github.com/user-attachments/assets/ff958e23-4534-4788-8f4d-dc70c7e8e572" />
)

### Details Page — Role & Performance Breakdown
![Details Page](<img width="1367" height="768" alt="details page" src="https://github.com/user-attachments/assets/b0d25dd1-398d-42b4-88df-a6f179e4f208" />
)

## 🎯 Project Objectives
- Consolidate employee records, promotion tracking, and retrenchment datasets into a unified data model.
- Provide dynamic filtering by **Department**, **Job Role**, and **Job Level**.
- Track key workforce KPIs in real time using custom DAX measures.

## 📈 Key Insights (1,470 Total Employees)
- **Workforce Split:** 60% Male (882) / 40% Female (588).
- **Promotion Pipeline:** **72 employees** are currently due for promotion, concentrated primarily in Research & Development (47) and Sales (23).
- **Retention Risk:** **117 employees (8%)** are categorized as retrenched, with the highest volume occurring in Research & Development (74).
- **Performance & Satisfaction:** 84.63% of employees maintain a high performance rating, while job satisfaction leans heavily toward Medium (722) over High (459) and Low (289).

## 🛠️ Tools & Techniques Used
- **Power Query:** Cleaned and transformed 4 source CSV datasets.
- **Data Modeling:** Linked Hr_analysis file data with promotion and retrenchment and employee tables.
- **DAX Measures:** Created custom calculations for headcount ratios, retrenchment percentages, and promotion eligibility counts.

## 🚀 How to Use
1. Download `HR_Dashboard.pbix` from this repository.
2. Open the file using **Microsoft Power BI Desktop** (free).
3. Use the **Quick Filters** on the left navigation panel or click **Clear Filter** to reset views.
