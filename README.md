# **Junior Data Engineer: Take-Home Assignment**

## Overview

*Due Date: 20th March*

Time Expectation

Expected approval timeline:

48 hours from recieving GitHub access

Submit by sharing your GitHub repository link

## Objectives

You will build a small data pipeline and analytics dataset using Python and SQL.

The goal of this exercise is to evaluate your ability to:

> Work with Git and GitHub

> Analyze and clean messy data

> Design normalized relational tables

> Transform and load data

> Write SQL queries

> Present data insights

**Please commit your work regularly to show your development process. Upon completion, replace this README file with your own.**

## **Setup**

1. Clone or fork this repository provided.
2. Create a new branch:
```bash
git checkout -b jde-technical
```

## **Provided Data**
You will recive 4 datasets:
### > a. customer.csv
### > b. products.csv
### > c. orders.csv
### > d. order_items.csv

## **Assignment**

### *1. Explore the Data*

Write a short analysis notebook or script that:

> Loads the datasets

> Explores their structure

> Identifies data issues

Document:

> Missing data

> Inconsistent fields

> Duplicate records

> Data type problems

> Assumptions and justify your decisions

Deliverable:

```bash
notebooks/data_exploration.ipynb
```

### *2. Clean the Data*

Write a Python script that:

> Cleans the datasets

> Fixes data issues

> Ensures consistent formats

> Notes assumptions and describes functions

Deliverable:

```bash
src/clean_data.py
```

### *3. Data Modeling*

Design a normalized rational schema for this data. Include:

> Tables

> Any keys (primary or foreign)

> Relationships

Deliverables:

1️⃣ A diagram
> docs/data_model.png

2️⃣ SQL schema
> sql/schema.sql

### *4. Load the Data*

Write a script that loads the cleaned data into a database.

Supported options:

> SQLite

> PostgreSQL

Your script should:

> Create tables

> Insert cleaned data

Deliverable:
```bash
src/load_data.py
```

### *5. Data Export*

Create a script that exports the following outputs:

> customer_sales.csv

> product_sales.csv

Deliverable:
```bash
output/
```

### *6. SQL Analysis*

Write SQL queries to answer the following questions:

> 1️⃣ Total revenue per customer

> 2️⃣ Top 5 best-selling products

> 3️⃣ Total sales by country

> 4️⃣ Average order value

Deliverable:
```bash
sql/analysis_queries.sql
```


### *7. Visualization (Optional Bonus)*

Build a small dashboard showing:

> Revenue by product

> Revenue by country

> Top customer

Suggested tools:

> Streamlit

> Dash

> Flask + Chart.js

Deliverable:
```bash
app/dashboard.py
```

### Repository Structure

Your repository should look as follows:

```bash
jde-technical/
│
├── data/
│   ├── customer.csv
│   ├── products.csv
│   ├── orders.csv
│   └── order_items.csv
│
├── notebooks/
│   └── data_exploration.ipynb
│
├── src/
│   ├── clean_data.py
│   └── load_data.py
│
├── sql/
│   ├── schema.sql
│   └── analysis_queries.sql
│
├── docs/
│   └── data_model.png
│
├── output/
│   ├── customer_sales.csv
│   └── product_sales.csv
│
├── app/
│   └── dashboard.py
│
└── README.md
```

**File types and structure can vary as you see fit. This is a guide on what is deliverable.**

## **Evaluation Criteria**
| Area               | What We Look For               |
| ------------------ | ------------------------------ |
| Git usage          | Clear commits and structure    |
| Data understanding | Identification of problems     |
| Data cleaning      | Logical transformations        |
| Data modeling      | Correct relational design      |
| SQL                | Correct joins and aggregations |
| Code quality       | Readable, modular code         |
| Documentation      | Clear explanations             |
