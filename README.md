# Customer_behavior_analysis
data analytics project showcasing customer behavior analysis using python sql and power bi
# Data Analytics Project

## Overview

This project demonstrates an end-to-end data analytics workflow, from data collection and preparation to visualization and reporting. The objective was to analyze the dataset, uncover meaningful insights, and present findings through an interactive Power BI dashboard and a detailed analytical report.

---

## Dataset

* Data: [customer_shopping_behavior]
* Format: CSV / Excel 


---

## Tools & Technologies

* **Python** – Data loading, cleaning, and exploratory data analysis (EDA)
* **Pandas & NumPy** – Data manipulation and preprocessing
* **Matplotlib & Seaborn** – Data visualization
* **PostgreSQL** – Database management and SQL analysis
* **SQL** – Data querying and aggregation
* **Power BI** – Interactive dashboard development
* **Microsoft Word / PDF** – Final reporting

---

## Project Workflow

### 1. Data Loading

* Imported the dataset into Python.
* Performed initial data inspection and validation.

### 2. Exploratory Data Analysis (EDA)

* Analyzed data structure and distributions.
* Identified trends, patterns, and anomalies.
* Generated visualizations to understand key metrics.

### 3. Data Cleaning

* Handled missing values.
* Removed duplicate records.
* Corrected data types and formatting issues.
* Treated inconsistent or invalid entries.

### 4. SQL Analysis

* Loaded cleaned data into PostgreSQL.
* Executed SQL queries for:

  * Data aggregation
  * Trend analysis
  * Performance metrics
  * Business insights generation

### 5. Dashboard Development

* Connected Power BI to the processed dataset.
* Created interactive visualizations and KPIs.
* Built filters and slicers for dynamic analysis.

### 6. Reporting

* Summarized key findings and recommendations.
* Documented methodology and analytical outcomes.

---

## Dashboard Features

* KPI Summary Cards
* Trend Analysis Charts
* Category-wise Performance Breakdown
* Interactive Filters and Slicers
* Data-Driven Insights Visualization

---

## Results & Key Insights

* Identified major trends and performance drivers.
* Highlighted top-performing categories and segments.
* Revealed patterns that support data-driven decision-making.
* Presented findings through an interactive dashboard and comprehensive report.

---

## How to Run the Project

### Prerequisites

* Python 3.x
* PostgreSQL
* Power BI Desktop

### Steps

1. Clone the repository:

   ```bash
   git clone <repository-link>
   ```

2. Install required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Python scripts:

   ```bash
   python data_cleaning.py
   python eda.py
   ```

4. Import the cleaned dataset into PostgreSQL.

5. Execute SQL queries from the `sql_queries.sql` file.

6. Open the Power BI dashboard file (`.pbix`) and refresh the data source.

7. Review the generated report and dashboard insights.

---

## Project Structure

```text
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
├── scripts/
│   ├── eda.py
│   └── data_cleaning.py
├── sql/
│   └── sql_queries.sql
├── dashboard/
│   └── dashboard.pbix
├── reports/
│   └── final_report.pdf
├── requirements.txt
└── README.md
```

---

## Author

**[Your Name]**
Data Analyst | Python | SQL | Power BI
