# **Junior Data Engineer: Take-Home Assignment**
## Overview

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
3. Install dependencies if required

## **Provided Data**
You will recive 3 datasets:
### > a. farmers.csv
### > b. products.csv
### > c. orders.csv

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

Deliverable:

```bash
notebooks/data_exploration.ipynb
```

### *2. Clean the Data*

Write a Python script that:

> Cleans the datasets

> Fixes data issues

> Ensures consistent formats

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

### *6. Visualization (Optional Bonus)*

Build a small dashboard showing:

> Revenue by product

> Revenue by country

> Top customers

Suggested tools:

> Streamlit

> Dash

> Flask + Chart.js

Deliverable:
```bash
app/dashboard.py
```
