# Sales Executive Performance Dashboard – Excel

## 📊 Project Overview

This project is an Excel-based Sales Executive Performance Dashboard designed to analyze sales performance against predefined targets.

The dashboard uses raw sales data to evaluate individual sales executives based on total sales, target achievement percentage, and the percentage by which each executive is away from the assigned target.

The project demonstrates the use of Microsoft Excel for data analysis, performance tracking, and dashboard visualization.

---

## 🎯 Business Objective

The main objective of this project is to provide a simple and visual way to evaluate sales executive performance.

The analysis helps answer questions such as:

* How much sales has each executive generated?
* Which sales executives have higher sales performance?
* How much of the assigned target has each executive achieved?
* How far is each executive from the target?
* How can sales performance be compared across executives?

---

## 🗂️ Dataset

The workbook contains a raw sales dataset with information about sales executives, regions, daily sales, total sales, and performance against targets.

### Dataset Columns

| Column             | Description                                |
| ------------------ | ------------------------------------------ |
| Emp Code           | Unique employee code                       |
| Sales Executive    | Name of the sales executive                |
| Region             | Assigned region/location                   |
| Day1               | Sales generated on Day 1                   |
| Day2               | Sales generated on Day 2                   |
| Day3               | Sales generated on Day 3                   |
| Day4               | Sales generated on Day 4                   |
| Day5               | Sales generated on Day 5                   |
| Total Sales        | Total sales generated across the five days |
| Target             | Assigned sales target                      |
| Target Hit %       | Percentage of target achieved              |
| Away From Target % | Percentage of target still remaining       |

---

## 🛠️ Tools & Techniques

### Tools

* Microsoft Excel

### Excel Techniques

* Data organization
* Data analysis
* Formula-based calculations
* Sales aggregation
* Percentage calculations
* Performance comparison
* Dashboard creation
* Charts and data visualization

---

## 📈 Dashboard Analysis

The dashboard presents multiple views of sales executive performance.

### 1. Total Sales Analysis

Displays sales executives according to their total sales generated.

This allows sales performance to be compared across employees.

### 2. Target Hit Percentage

Shows the percentage of the assigned target achieved by each sales executive.

The calculation is based on:

```text
Target Hit % = Total Sales / Target
```

### 3. Away From Target Percentage

Shows how much of the assigned target remains unachieved.

The calculation is based on:

```text
Away From Target % = 1 - Target Hit %
```

### 4. Sales Performance Visualization

The dashboard uses charts to provide a visual representation of sales performance and target-related metrics.

This makes it easier to identify differences in performance without manually analyzing the raw dataset.

---

## 🔍 Key Metrics

The major performance metrics used in the dashboard are:

* **Total Sales**
* **Sales Target**
* **Target Hit %**
* **Away From Target %**
* **Daily Sales Performance**

---

## 💡 Key Insights

The analysis can be used to identify:

* Sales executives with relatively higher total sales.
* Differences in target achievement between executives.
* Executives who are closer to achieving their assigned targets.
* Executives with a larger percentage of their targets still remaining.
* Daily sales patterns across the five-day period.

The dashboard provides a quick overview of individual sales performance and can support further sales performance analysis.

> Note: The observations are based on the dataset included in this workbook and are intended for analytical and learning purposes.

---

## 📁 Project Structure

```text
sales-executive-performance-dashboard/
│
├── Sales_Executive_Performance_Dashboard.xlsm
├── README.md
│
└── screenshots/
    └── dashboard.png
```

---

## 🚀 How to Use

1. Download the Excel workbook from this repository.
2. Open the `.xlsm` file using Microsoft Excel.
3. Navigate to the `DASHBOARD` sheet.
4. Review the sales performance visualizations.
5. Navigate to the `Raw_Data` sheet to inspect the underlying dataset.
6. Explore the sales, target, and performance calculations.

> Since the workbook is saved as `.xlsm`, open it in Microsoft Excel and enable macros if the workbook requires them.

---

## 📸 Dashboard Preview

Add a screenshot of your dashboard to the repository.

```markdown
![Sales Executive Performance Dashboard](screenshots/dashboard.png)
```

---

## 📋 Workbook Sheets

### DASHBOARD

Contains the visual analysis of:

* Total Sales
* Target Hit %
* Away From Target %

### Raw_Data

Contains the underlying sales dataset used for the analysis.

---

## 👨‍💻 Author

**Asutosh Hota**

B.Tech – Computer Science & Engineering

### Skills Demonstrated

* Microsoft Excel
* Data Analysis
* Data Visualization
* Dashboard Development
* Sales Performance Analysis
* Business Data Interpretation
* Excel Formulas

---

## ⭐ Project Purpose

This project was created as part of my Data Analysis learning journey to practice Excel-based data analysis, performance measurement, visualization, and dashboard development using sales data.
