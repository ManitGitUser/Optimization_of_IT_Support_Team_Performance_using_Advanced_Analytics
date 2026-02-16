# Internship Learning Documentation

This document summarizes the key concepts, tools, and practical skills covered during the Infosys Springboard Data Visualization Internship while building the IT Support Performance Analytics project.

---

# Core Concepts Covered

## Categories of Data Analysis
During the internship, we explored different analytical approaches used in real-world projects:

- Descriptive Analysis – Understanding what happened using historical data.
- Diagnostic Thinking – Identifying patterns, outliers, and performance gaps.
- Exploratory Data Analysis (EDA) – Understanding data structure before visualization.

We learned that dashboards should not just display charts but should answer business questions.

---

## Types of Data
Understanding data types helped decide which visuals and calculations to use:

- **Categorical Data** – Used for grouping (Priority, Assignment Group).
- **Numerical Data** – Used for calculations (Resolution Time, Counts).
- **Time-Based Data** – Used to analyze trends over months or days.

---

## Data Cleaning & Preparation

### Python & Power Query
Data cleaning was performed using both Python and Power BI Power Query.

Key tasks included:
- Handling missing values
- Removing duplicates
- Fixing incorrect formats
- Cleaning string values inside numeric columns
- Detecting and handling outliers
- Structuring datasets for analysis

The process followed a workflow:
Transfer → Clean → Visualize → Structure.

---

## Python for Data Processing
Python and Pandas were used to:
- Convert event-level logs into ticket-level records.
- Engineer features like Resolution_Time_Hours.
- Prepare datasets suitable for Power BI.

Concepts learned:
- DataFrames
- Basic EDA
- Data aggregation
- Dataset restructuring

---

## Power BI Fundamentals

### Three Main Views
- Report View – Building visual dashboards.
- Data View – Inspecting tables and columns.
- Model View – Managing relationships and schema.

### Data Modeling Concepts
- Fact Tables
- Dimension Tables
- Star Schema & Snowflake Schema
- Primary Key & Foreign Key relationships
- Types of relationships (One-to-Many, Many-to-One)

Understanding data modeling helped improve DAX calculations and dashboard performance.

---

## Data Visualization Principles

Different charts were used depending on the data type:

- Bar Charts → Category comparison with precision.
- Pie Charts → Proportion visualization (used carefully).
- Line Charts → Time-based trends.
- KPI Cards → Highlight key performance indicators.

We also discussed when NOT to use certain charts to avoid misleading insights.

---

## DAX & Measures

DAX (Data Analysis Expressions) was introduced as the calculation engine of Power BI.

Concepts covered:
- Measures vs Columns
- CALCULATE function
- Conditional logic using IF
- KPI calculations
- Impact of data modeling on DAX queries

---

## Interactivity & Filtering

Slicers were used to make dashboards dynamic and allow users to explore data through:
- Priority filters
- Resolution categories
- Assignment group selection

---

## Live Data & Real-World Context

The internship included discussions on:
- Live data import challenges
- APIs and web data sources
- Zendesk ticketing workflows
- Dummy vs Synthetic data
- Power BI Premium concepts

---

## Personal Learning & Improvement

Throughout the internship, significant improvement was made in:

- Power Query transformations
- Power BI modeling
- Dashboard storytelling
- Structuring GitHub repositories
- Converting raw data into analytical insights

---

# Tools & Technologies Covered
- Power BI
- Power Query
- Python
- Pandas
- GitHub
- Jupyter Notebook

---

# Summary

This internship provided hands-on experience in transforming raw IT support data into a structured analytical solution.  
The focus was not only on creating dashboards but also on understanding data modeling, visualization best practices, and real-world analytics workflows.
