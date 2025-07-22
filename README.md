# 🧾 HR Dataset Analysis using Power BI

## 📌 Overview

This project uses Power BI to analyze an HR dataset covering key workforce information including demographics, performance, tenure, attrition, and hiring channels. The goal is to enable data-driven decisions in recruitment, retention, diversity, and employee engagement.

---

## 📂 Dataset Summary

**Data Source**: Internal HR Data
**Number of Records**: \~1000+ (sample shown)
**Data Format**: Excel / CSV
**Filename**: `HR_Dataset.csv`

### 📊 Key Columns:

| Column Name                                   | Description                                      |
| --------------------------------------------- | ------------------------------------------------ |
| `Employee_Name`                               | Full name of the employee                        |
| `EmpID`                                       | Unique employee ID                               |
| `GenderID`, `Sex`                             | Gender (binary ID and label)                     |
| `MarriedID`, `MaritalStatusID`, `MaritalDesc` | Marital status indicators and description        |
| `DOB`, `Age`                                  | Date of birth and calculated age                 |
| `RaceDesc`, `HispanicLatino`                  | Race and ethnicity details                       |
| `Salary`                                      | Annual salary                                    |
| `Position`, `PositionID`                      | Job title and identifier                         |
| `Department`, `DeptID`                        | Department name and ID                           |
| `DateofHire`, `DateofTermination`             | Employment duration                              |
| `TermReason`, `Termd`                         | Reason for termination and flag (1 = terminated) |
| `EmploymentStatus`                            | Current employment status                        |
| `PerfScoreID`, `PerformanceScore`             | Performance score ID and description             |
| `EmpSatisfaction`                             | Employee satisfaction rating                     |
| `EngagementSurvey`                            | Engagement survey score (1–5)                    |
| `RecruitmentSource`                           | Source through which employee was hired          |
| `FromDiversityJobFairID`                      | Diversity hiring flag                            |
| `ManagerName`, `ManagerID`                    | Reporting manager details                        |
| `SpecialProjectsCount`                        | Number of special projects involved in           |
| `Absences`                                    | Days absent during the year                      |
| `LastPerformanceReview_Date`                  | Date of the last performance review              |

---

## 🎯 Dashboard Objectives

* **Monitor workforce composition**: age, gender, marital status, race
* **Analyze performance and satisfaction trends**
* **Track attrition and its causes**
* **Evaluate recruitment sources and diversity hiring**
* **Measure manager performance through team metrics**

---

## 📈 Power BI Dashboard Features

### 📊 Visualizations:

* **KPI Cards**: Headcount, Attrition Rate, Avg Tenure, Avg Salary
* **Bar Charts**:

  * Attrition by Department
  * Performance by Manager
* **Pie/Donut Charts**:

  * Gender and Race Distribution
  * Marital Status Breakdown
* **Heatmaps**:

  * Absence by Department and Manager
* **Line/Timeline Charts**:

  * Hiring vs. Termination Trends
* **Scatter Plots**:

  * Engagement vs Satisfaction
* **Table/Matrix Views**:

  * Detailed Employee Roster
  * Termination Reasons by Department

### 🔍 Filters & Slicers:

* Department
* Manager
* Job Role / Position
* Gender, Race
* Employment Status
* Termination Reason
* Performance Rating

---

## 🔧 Technical Stack

* **Power BI Desktop** for dashboard development
* **Power Query** for data transformation
* **DAX** for calculated columns and measures
* Optional: Power BI Service for sharing and collaboration

---

## 📝 Recommendations (Sample)

* Employees hired via **LinkedIn** tend to have **higher performance** and **lower attrition**.
* Departments like **Production** have **higher absence rates** – investigate workplace conditions.
* **Diversity hiring** initiatives via job fairs show promise but need better retention focus.
* Employees with **zero special projects** often show **lower engagement scores**.
* High-performing employees with **no recent promotions** may be at **risk of attrition**.

---

## 📤 Getting Started

1. Download and open the `.pbix` file in Power BI Desktop.
2. Click **Refresh** to load the latest data.
3. Interact with slicers and visuals to explore trends.
4. Export or share insights as needed.
