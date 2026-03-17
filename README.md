# **Junior Data Engineer: Take-Home Assignment**

## Overview

*Start Date: 20th March*

*Due Date: 23rd March*

### Time Expectation

Expected turnaround time: 48 hours from receiving GitHub access.

Expected completion time: 4–6 hours.

Please do not spend more than 6 hours on this assignment. We are not expecting a perfect production system. We are more interested in your thinking, data reasoning, and code structure.

You may use any tools or libraries you are comfortable with. If you use AI tools such as ChatGPT or Copilot, please note where they assisted you.

Submission Instructions

Please follow the process below:

Clone this starter repository:

```bash
https://github.com/FLC-Technologies/jde-technical.git
```

Create a new private repository using this repository as your starter repository.

Complete the assignment in your new private repository.

Share access to the repository with us (sean@farmlinkcapital.co.za, devstack@farmlinkcapital.co.za) for review.

Email us your GitHub repository link once complete (sean@farmlinkcapital.co.za, devstack@farmlinkcapital.co.za).

Important: Please do not push your work back to the starter repository.

## Objectives

You will build a small data pipeline and analytics dataset using Python and SQL.

The goal of this exercise is to evaluate your ability to:

> Work with Git and GitHub

> Analyze and clean messy data

> Design normalized relational tables

> Transform and load data

> Write SQL queries

> Present data insights

**Please commit your work regularly to the new repository to show your development process.**

Include a section in your README explaining:

> • Assumptions you made

> • Data issues you identified

> • Decisions you made during cleaning

## **Setup**

Clone the starter repository and use it as the base for your submission.

You may use any tools, libraries, or frameworks you are comfortable with.

## **Provided Data**
You will receive 4 datasets:
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

Design a normalized relational schema for this data. Include:

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
**Include a requirements.txt file if dependencies are used.**

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
