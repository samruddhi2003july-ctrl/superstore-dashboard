# superstore-dashboard
superstore retail data analysis using excel
# 📊 Excel Sales & Business Analysis Dashboard

An interactive **Excel Data Analyst Dashboard** built to analyze sales, revenue, costs, profit, regional performance, products, and business trends.

The project uses **Power Query, Power Pivot, DAX, PivotTables, Pivot Charts, Charts, Slicers, and Filters** to transform raw data into meaningful business insights.

---

## 📌 Project Overview

This project demonstrates how Excel can be used as an end-to-end data analysis tool — from **raw data cleaning and transformation** to **data modeling, DAX calculations, interactive visualization, and business insights**.

### 🛠️ Tools & Technologies

* Microsoft Excel
* Power Query
* Power Pivot
* DAX
* PivotTables
* Pivot Charts
* Excel Charts
* Slicers
* Filters
* Data Cleaning & Transformation

---

# 🎯 Project Objectives

The main objectives of this project are:

* Clean and transform raw business data using **Power Query**
* Create a structured **data model using Power Pivot**
* Build calculated measures using **DAX**
* Analyze sales, revenue, costs, profit, and margins
* Compare business performance across regions and quarters
* Identify high-performing and low-performing products
* Analyze salesperson performance
* Understand the impact of discounts and marketing expenses
* Create an interactive dashboard for business users
* Present complex data in an easy-to-understand visual format

---

# ❓ Business Questions

The dashboard is designed to answer questions such as:

### Sales & Revenue

1. What is the total revenue?
2. Which products generate the highest revenue?
3. Which quarter has the highest sales?
4. Which region generates the most revenue?
5. How are sales changing across quarters?

### Profitability

6. What is the total profit?
7. Which products generate the highest profit?
8. Which products are generating losses?
9. What is the overall profit margin?
10. Which region has the highest and lowest profit?

### Cost Analysis

11. Which products have the highest total cost?
12. Which region has the highest operating expenses?
13. How does marketing spend compare with revenue?
14. Which products have high costs but low revenue?

### Salesperson Analysis

15. Which salesperson generates the highest revenue?
16. Which salesperson generates the highest profit?
17. How does salesperson performance vary by region?

### Discount & Returns

18. How do discounts affect revenue and profit?
19. Which products have high discount percentages?
20. What is the return rate?
21. Which products have the highest number of returns?

---

# 🔄 Project Workflow

The project follows an end-to-end data analysis workflow:

```text
Raw Data
   ↓
Power Query
   ↓
Data Cleaning & Transformation
   ↓
Power Pivot
   ↓
Data Model & Relationships
   ↓
DAX Measures
   ↓
PivotTables
   ↓
Pivot Charts & Visualizations
   ↓
Slicers & Filters
   ↓
Interactive Dashboard
   ↓
Business Insights
```

---

# 🧹 1. Data Preparation — Power Query

Power Query was used to prepare the raw dataset before analysis.

### Data Cleaning Activities

* Removed unnecessary columns
* Removed duplicate records
* Handled missing values
* Corrected data types
* Standardized text values
* Cleaned inconsistent entries
* Created calculated/transformed columns
* Formatted dates and numerical fields
* Prepared the dataset for Power Pivot

### Why Power Query?

Power Query makes the data-cleaning process **repeatable and refreshable**.

Instead of manually cleaning the data every time new records are added, the transformation steps can be refreshed automatically.

---

# 🧩 2. Data Model — Power Pivot

The cleaned data was loaded into **Power Pivot** to create a structured data model.

### Example Data Model

```text
                 ┌─────────────────┐
                 │   Sales Table   │
                 ├─────────────────┤
                 │ Product         │
                 │ Quarter         │
                 │ Region          │
                 │ Salesperson     │
                 │ Category        │
                 │ Cost Price      │
                 │ Selling Price   │
                 │ Units Sold      │
                 │ Returns         │
                 │ Discount %      │
                 │ Marketing Spend │
                 │ Revenue         │
                 │ Total Cost      │
                 │ Profit          │
                 └─────────────────┘
```

The data model allows the dashboard to analyze multiple dimensions such as:

* Product
* Region
* Quarter
* Category
* Salesperson

against business metrics such as:

* Revenue
* Profit
* Cost
* Units Sold
* Returns
* Discount
* Marketing Spend

---

# 🧮 3. DAX Measures

DAX measures were created in Power Pivot to calculate important business KPIs.

### Total Revenue

```DAX
Total Revenue =
SUM(Sales[Revenue])
```

### Total Cost

```DAX
Total Cost =
SUM(Sales[Total Cost])
```

### Total Profit

```DAX
Total Profit =
SUM(Sales[Profit])
```

### Units Sold

```DAX
Total Units Sold =
SUM(Sales[Units Sold])
```

### Total Returns

```DAX
Total Returns =
SUM(Sales[Returns])
```

### Average Discount

```DAX
Average Discount =
AVERAGE(Sales[Discount %])
```

### Profit Margin

```DAX
Profit Margin % =
DIVIDE([Total Profit], [Total Revenue], 0)
```

### Return Rate

```DAX
Return Rate % =
DIVIDE([Total Returns], [Total Units Sold], 0)
```

> **Note:** DAX measure names and table/column names can be modified according to the actual Excel workbook.

---

# 📊 4. Dashboard Features

The dashboard provides an interactive view of business performance.

### KPI Cards

The dashboard includes key performance indicators such as:

* 💰 Total Revenue
* 📈 Total Profit
* 💸 Total Cost
* 📦 Units Sold
* 🔄 Returns
* 📊 Profit Margin %

### Interactive Filters

Users can filter the dashboard by:

* Quarter
* Region
* Product
* Category
* Salesperson

### Slicers

Slicers provide an easy way to interact with the dashboard and dynamically update the charts and KPIs.

### Charts

The dashboard uses visualizations such as:

* Revenue by Region
* Revenue by Quarter
* Profit by Product
* Salesperson Performance
* Product Performance
* Cost Analysis
* Returns Analysis

### Pivot Charts

Pivot Charts were connected to PivotTables to create dynamic visualizations that respond to filters and slicers.

---

# 🖥️ Dashboard Preview

## Main Dashboard

Add your dashboard screenshot here:

```markdown
![Excel Dashboard](images/dashboard.png)
```

Example:

![Dashboard Preview](images/dashboard.png)

---

## 📸 Additional Screenshots

### Power Query Transformation

```markdown
![Power Query](images/power-query.png)
```

![Power Query](images/power-query.png)

### Power Pivot Data Model

```markdown
![Data Model](images/data-model.png)
```

![Data Model](images/data-model.png)

### DAX Measures

```markdown
![DAX Measures](images/dax-measures.png)
```

![DAX Measures](images/dax-measures.png)

---

# 🔍 Key Findings

The dashboard was used to identify important business patterns such as:

* Differences in revenue performance across regions
* Quarterly changes in sales
* High-performing products
* Low-performing or loss-making products
* Differences in salesperson performance
* Products with high discount percentages
* Relationship between marketing expenses and revenue
* Products contributing significantly to total profit
* Areas with comparatively high operating expenses
* Return patterns across products and categories

> **Note:** Replace these general findings with the exact numerical findings from your dashboard.

---

# 💡 Business Insights

The analysis can help businesses:

* Identify products that require additional attention
* Understand regional sales performance
* Monitor profitability
* Control unnecessary costs
* Evaluate discount strategies
* Track salesperson performance
* Identify return-heavy products
* Make data-driven business decisions

---

# 📁 Repository Structure

```text
Excel-Dashboard/
│
├── README.md
│
├── Dataset/
│   └── sales_data.xlsx
│
├── Dashboard/
│   └── Excel_Dashboard.xlsx
│
├── Screenshots/
│   ├── dashboard.png
│   ├── power-query.png
│   ├── data-model.png
│   └── dax-measures.png
│
└── Documentation/
    └── project_notes.md
```

---

# 🛠️ Skills Demonstrated

This project demonstrates practical Data Analyst skills in Excel:

| Skill              | Application                      |
| ------------------ | -------------------------------- |
| Power Query        | Data cleaning and transformation |
| Power Pivot        | Data modeling                    |
| DAX                | Business calculations and KPIs   |
| PivotTables        | Data summarization               |
| Pivot Charts       | Interactive visualization        |
| Excel Charts       | Data presentation                |
| Slicers            | Interactive filtering            |
| Filters            | Data exploration                 |
| Data Analysis      | Business insights                |
| Data Visualization | Dashboard creation               |

---

# 🚀 How to Use the Project

1. Download the Excel workbook from this repository.
2. Open the `.xlsx` file in Microsoft Excel.
3. Go to the **Dashboard** sheet.
4. Use the slicers and filters to explore the data.
5. Select different regions, quarters, products, categories, or salespeople.
6. Observe how the KPIs and charts change dynamically.

---

# 📌 Project Highlights

### Data Preparation

**Power Query** → Cleaned and transformed raw data.

### Data Modeling

**Power Pivot** → Created a structured analytical data model.

### Calculations

**DAX** → Created reusable business measures.

### Analysis

**PivotTables + Pivot Charts** → Summarized and analyzed business performance.

### Visualization

**Charts + Slicers + Filters** → Created an interactive dashboard.

---

# 🎓 Learning Outcomes

Through this project, I gained practical experience in:

* Cleaning real-world business data
* Transforming data using Power Query
* Building data models with Power Pivot
* Writing DAX measures
* Creating dynamic PivotTables
* Building interactive Pivot Charts
* Using slicers and filters
* Performing business analysis
* Converting raw data into actionable insights
* Designing an Excel dashboard for decision-making

---

# 👩‍💻 Author

**Samruddhi Mane**

Aspiring Data Analyst | Excel | Power Query | Power Pivot | DAX

---

## ⭐ If you found this project useful

Feel free to ⭐ **star this repository** and explore the project files.
