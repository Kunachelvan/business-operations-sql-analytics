# Business Operations SQL Analytics

## End-to-End Business Intelligence & Decision Analytics Project

This project demonstrates a complete end-to-end business analytics workflow using **MySQL, SQL, Python, Pandas, NumPy, and Matplotlib** to transform relational business data into actionable insights.

The project covers the complete analytics lifecycle:

**Database Creation → Data Validation → Descriptive → Diagnostic → Predictive → Prescriptive Analytics**

The repository is designed to be reproducible. The first notebook creates and populates the MySQL demonstration database, while the second notebook performs the complete business analytics workflow.

---

# Project Objectives

- Build a relational MySQL business operations database
- Create and populate structured business tables
- Validate database integrity and financial totals
- Analyze business revenue, expenses, customers, products, and employee performance
- Build executive-level business KPIs
- Identify revenue concentration and operational risks
- Analyze monthly financial performance trends
- Evaluate customer and product contribution
- Develop and evaluate a revenue forecasting model
- Convert analytical findings into management recommendations

---

# Technology Stack

## Database

- MySQL
- Relational Database Design
- SQL

## Programming & Analytics

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Analytics Techniques

- SQL Data Analysis
- KPI Development
- Data Validation
- Exploratory Data Analysis
- Trend Analysis
- Customer Analysis
- Product Performance Analysis
- Financial Performance Analysis
- Forecasting
- Business Recommendations

---

# Repository Workflow

The project is organized into two primary notebooks that should be executed in numerical order.

## 01 — Database Setup

`01_Business_Operations_Database_Setup.ipynb`

This notebook:

- Connects Python to MySQL
- Creates the demonstration database
- Builds the relational schema
- Creates 8 interconnected business tables
- Loads synthetic portfolio data
- Calculates transaction totals
- Validates record counts
- Validates revenue, payments, expenses, and operating surplus

The database created by this notebook is:

`business_operations_analytics_demo`

### Database Tables

- departments
- employees
- customers
- products
- orders
- order_items
- payments
- expenses

### Validated Dataset

- 5 departments
- 6 employees
- 10 customers
- 10 products/services
- 20 orders
- 38 order items
- 20 payments
- 20 expenses

### Financial Validation

- Total Revenue: **$84,300**
- Payments Received: **$84,300**
- Total Expenses: **$27,300**
- Operating Surplus: **$57,000**

---

## 02 — Business Analytics

`02_Business_Operations_SQL_Analytics_Portfolio.ipynb`

This notebook connects to the database created by Notebook 01 and performs the complete analytical workflow.

It includes:

- Database validation
- Executive KPI analysis
- Revenue analysis
- Expense analysis
- Operating surplus analysis
- Customer performance analysis
- Product performance analysis
- Employee performance analysis
- Monthly financial trend analysis
- Data visualization
- Revenue forecasting
- Forecast evaluation
- Management recommendations

---

# Analytics Framework

## 1. Descriptive Analytics

Analyzes historical business performance, including:

- Revenue trends
- Expense patterns
- Operating surplus
- Customer activity
- Product performance
- Employee performance

---

## 2. Diagnostic Analytics

Investigates the factors influencing business performance:

- Revenue concentration
- Customer dependency
- Product contribution
- Employee performance patterns
- Operational risks

---

## 3. Predictive Analytics

Develops forecasting models to estimate future revenue trends.

Model evaluation includes:

- Baseline comparison
- Error measurement
- Forecast accuracy assessment

---

## 4. Prescriptive Analytics

Converts analytical findings into business actions, including:

- Customer retention strategies
- Revenue growth opportunities
- Operational improvement recommendations
- Risk reduction strategies
- Management decision support

---

# Relational Database Design

The project demonstrates relational database concepts through interconnected operational tables.

Key relationships include:

- Departments → Employees
- Customers → Orders
- Employees → Orders
- Orders → Order Items
- Products → Order Items
- Orders → Payments
- Departments → Expenses

This structure allows business performance to be analyzed across customers, employees, products, transactions, payments, and operating expenses.

---

# How to Run This Project

## Prerequisites

Install:

- MySQL Server
- Python
- JupyterLab or Jupyter Notebook

Required Python packages:

```bash
pip install mysql-connector-python pandas numpy matplotlib

```

---

## Step 1 — Create the Database

Open:

`01_Business_Operations_Database_Setup.ipynb`

Run the notebook from top to bottom.

When prompted, enter your local MySQL root password.

The notebook will create:

`business_operations_analytics_demo`

and populate all required tables automatically.

---

## Step 2 — Run the Analytics

After Notebook 01 completes successfully, open:

`02_Business_Operations_SQL_Analytics_Portfolio.ipynb`

Run the notebook from top to bottom.

When prompted, enter your MySQL root password.

Notebook 02 connects to the database created by Notebook 01 and performs the complete analytics workflow.

---

# Data Privacy

All business records used in this repository are **synthetic demonstration data created specifically for portfolio purposes**.

The repository does not contain production customer information, confidential company information, passwords, or private business records.

Database passwords are requested interactively at runtime and are not stored in the notebooks.

---

# Key Skills Demonstrated

- SQL Database Analysis
- Relational Database Design
- MySQL
- Python Data Analysis
- Pandas
- NumPy
- Business Intelligence
- Data Cleaning and Transformation
- Exploratory Data Analysis
- KPI Development
- Financial Performance Analysis
- Customer Analysis
- Product Analysis
- Data Visualization
- Forecasting Models
- Business Decision Making
- Analytical Storytelling

---

# Business Value Delivered

This project demonstrates the ability to:

- Design and build a relational business database
- Transform operational data into business insights
- Build analytical solutions from database systems
- Validate financial and transactional data
- Identify performance drivers and business risks
- Develop forecasting models
- Translate analytical findings into management recommendations
- Support strategic decision-making
- Communicate findings through data storytelling

---

# Project Structure

```text
business-operations-sql-analytics/
│
├── 01_Business_Operations_Database_Setup.ipynb
│   └── Creates, populates, and validates the MySQL database
│
├── 02_Business_Operations_SQL_Analytics_Portfolio.ipynb
│   └── Performs SQL, Python, BI, visualization, and forecasting analysis
│
└── README.md
    └── Project documentation and execution instructions
```

---

# Author

**Kunachelvan Shanmugalingam**

Data Analyst | SQL | Python | Business Intelligence
