# 📊 HR Budgeting & Workforce Planning

> **A data-driven HR analytics project using Microsoft Excel and Power BI to analyze workforce planning, HR costs, budget utilization, variance, and workforce scenarios.**

---

## 📌 Project Overview

This project focuses on **HR Budgeting and Workforce Planning** using **Microsoft Excel and Microsoft Power BI**.

The project uses a **hypothetical dataset of 500 employees** across five departments to analyze workforce requirements, employee costs, HR budget allocation, budget variances, and potential workforce scenarios.

The project demonstrates how HR data can be transformed into meaningful insights to support:

- Workforce planning
- HR budgeting
- Cost management
- Hiring decisions
- Training expenditure analysis
- Budget variance analysis
- Scenario-based planning
- Data-driven HR decision-making

> **Note:** All employee data and financial figures used in this project are hypothetical and created for educational and analytical purposes.

---

## 🎯 Project Objectives

The key objectives of this project are to:

- Analyze the current workforce structure across departments.
- Forecast future workforce requirements based on planned hiring and exits.
- Estimate and analyze employee-related HR costs.
- Compare planned HR budgets with actual employee costs.
- Identify department-wise cost distribution and budget variances.
- Analyze salary, benefits, and training expenditure.
- Perform What-If analysis for hiring and salary increment scenarios.
- Develop an interactive Power BI dashboard for HR analytics.
- Generate actionable insights to support HR budgeting and workforce planning.

---

## 📊 Dataset

The project uses a **hypothetical employee dataset containing 500 employees** distributed across five departments.

### Departments Covered

| Department | Current Headcount |
|---|---:|
| Engineering | 150 |
| Sales | 100 |
| Finance | 75 |
| Human Resources | 50 |
| Operations | 125 |
| **Total** | **500** |

### Employee Data Fields

The employee dataset contains the following fields:

- Employee ID
- Department
- Role
- Job Level
- Salary
- Benefits
- Training Cost
- Employment Status
- Total Compensation
- Annual Cost

### Workforce Planning Fields

A separate workforce planning dataset was created containing:

- Department
- Current Headcount
- Planned Hires
- Planned Exits
- Forecasted Headcount
- Average Salary
- Budget Allocation

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| **Microsoft Excel** | Data preparation, calculations, PivotTables and variance analysis |
| **Microsoft Power BI** | Interactive dashboard and data visualization |
| **DAX** | KPI measures and scenario calculations |
| **Power BI What-If Parameters** | Scenario analysis |
| **PivotTables** | Department-wise cost and workforce analysis |

---

# 📈 Analysis Performed

## 1️⃣ Workforce Planning & Forecasting

The workforce plan evaluates current headcount, planned hiring and planned exits to estimate the future workforce.

### Workforce Summary

| Metric | Value |
|---|---:|
| Current Headcount | **500** |
| Planned Hires | **85** |
| Planned Exits | **38** |
| Forecasted Headcount | **547** |

The forecasted workforce is calculated by considering planned additions and exits:

**Forecasted Headcount = Current Headcount + Planned Hires − Planned Exits**

---

## 2️⃣ Department-wise Workforce Forecast

The workforce plan provides a department-level comparison of current and forecasted headcount.

| Department | Current Headcount | Planned Hires | Planned Exits | Forecasted Headcount |
|---|---:|---:|---:|---:|
| Engineering | 150 | 28 | 12 | 166 |
| Sales | 100 | 18 | 8 | 110 |
| Finance | 75 | 10 | 5 | 80 |
| Human Resources | 50 | 7 | 3 | 54 |
| Operations | 125 | 22 | 10 | 137 |
| **Total** | **500** | **85** | **38** | **547** |

---

## 3️⃣ HR Budget & Cost Analysis

The project analyzes overall HR expenditure and compares it with the planned HR budget.

### Key HR Cost KPIs

| KPI | Value |
|---|---:|
| Total HR Spend | **₹447.95 Million** |
| Budget Allocation | **₹437.00 Million** |
| Budget Utilization | **102.51%** |
| Cost per Employee | **₹895,894** |
| Training Cost | **₹12.09 Million** |
| Training Spend per Employee | **₹24,184** |

---

## 4️⃣ HR Spend Breakdown

HR expenditure is analyzed across three major cost components:

- **Salary**
- **Benefits**
- **Training**

The Power BI dashboard provides an interactive breakdown of these components to understand their contribution to overall HR expenditure.

---

## 5️⃣ Budget vs Actual Variance Analysis

The project compares planned employee costs with actual employee costs to identify cost variances.

### Variance Analysis

The analysis covers:

- Planned Salary
- Actual Salary
- Salary Variance
- Planned Training Cost
- Actual Training Cost
- Training Variance
- Total Planned Cost
- Total Actual Cost
- Total Variance

### Overall Variance

| Metric | Amount |
|---|---:|
| Total Planned Cost | **₹420.30 Million** |
| Total Actual Cost | **₹401.37 Million** |
| Total Variance | **-₹18.92 Million** |

**Variance = Actual Cost − Planned Cost**

A negative variance indicates that actual cost is lower than the corresponding planned cost, while a positive variance indicates that actual cost is higher than planned.

---

## 6️⃣ Department-wise Cost Analysis

The project evaluates workforce costs across departments using:

- Average Salary
- Training Cost
- Headcount
- Annual Employee Cost
- Percentage of Total Cost

This analysis helps understand how workforce size and employee costs are distributed across different departments.

---

# 🔍 What-If Scenario Analysis

Power BI **What-If Parameters** were used to evaluate how changes in workforce and compensation assumptions can affect HR expenditure.

### Scenarios Considered

- Salary increment percentage
- Planned hiring numbers
- Impact of additional hiring on HR expenditure
- Scenario-based HR spend
- Scenario-based cost per employee
- Scenario-based headcount

The interactive parameters allow users to modify assumptions and observe the resulting changes in HR metrics.

### Example Scenario Values

| Scenario | Approx. HR Spend |
|---|---:|
| Current | **₹447.95 Million** |
| 10% Planned Hires | **₹455.56 Million** |
| 15% Training Cost Reduction | **₹446.13 Million** |
| 8% Salary Increment | **₹479.09 Million** |

> These scenario values are based on the assumptions used in the hypothetical project dataset.

---

# 📊 Power BI Dashboard

The Power BI dashboard provides an interactive view of the HR workforce and cost analysis.

### Dashboard Includes

- **Total HR Spend**
- **Headcount Forecast**
- **Cost per Employee**
- **Budget Utilization**
- **Current vs Forecasted Headcount**
- **HR Spend Breakdown**
- **Budget vs Actual Variance**
- **Department-wise analysis**
- **Job Level analysis**
- **Planning Year analysis**
- **What-If scenario analysis**

### Interactive Filters

The dashboard includes slicers for:

- Department
- Job Level
- Planning Year

These filters allow users to explore the HR data dynamically.

---

## 🖼️ Dashboard Preview

The Power BI dashboard visual is included in this repository.

**Dashboard Preview:**

`Dashboard 1 P3.PNG`

---

# 💡 Key Insights

Based on the analysis performed using the hypothetical dataset:

1. The current workforce consists of **500 employees**.

2. The workforce plan includes **85 planned hires** and **38 planned exits**.

3. The resulting forecasted workforce is **547 employees**.

4. Total HR spend in the dataset is approximately **₹447.95 Million**.

5. The planned HR budget allocation is **₹437 Million**.

6. Budget utilization is **102.51%** based on the project assumptions.

7. Salary, benefits and training represent the major components of HR expenditure.

8. Department-wise analysis highlights differences in workforce size, average salary and annual employee costs.

9. Variance analysis provides visibility into differences between planned and actual employee costs.

10. What-If analysis demonstrates how changes in hiring and salary assumptions can influence overall HR expenditure.

---

# 📌 Recommendations

Based on the analysis performed, the following areas can be considered for HR planning:

### 💰 Cost Optimization

- Monitor department-wise workforce expenditure regularly.
- Track salary and training cost variances against planned budgets.
- Review areas with significant deviations from budget.

### 👥 Hiring Strategy

- Align hiring plans with forecasted workforce requirements.
- Consider planned exits while determining future hiring requirements.
- Evaluate workforce requirements at the department level.

### 🎓 Training Programs

- Monitor training expenditure against allocated budgets.
- Evaluate training spending based on workforce requirements.
- Use training cost analysis to support future HR budget planning.

### 📊 Data-Driven HR Planning

- Use Power BI dashboards for regular HR performance monitoring.
- Incorporate scenario analysis into workforce planning.
- Update workforce assumptions periodically as business requirements change.

---

# 📂 Project Structure

```text
HR-Budgeting-Workforce-Planning/
│
├── 📊 HR Budgeting PBI.pbix
├── 📗 HR_Budgeting_Workforce_Planning.xlsx
├── 📑 HR_Budgeting_Workforce_Planning_Report.pptx
├── 🖼️ Dashboard 1 P3.PNG
└── 📄 README.md
