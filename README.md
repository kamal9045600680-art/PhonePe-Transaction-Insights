# PhonePe Transaction Insights

## Project Overview

PhonePe Transaction Insights is an Exploratory Data Analysis (EDA) and data visualization project based on PhonePe Pulse data.

The project analyzes PhonePe transaction and user data to understand transaction trends, payment categories, registered users, and geographical patterns across Indian states and districts.

The project uses Python, SQL, Pandas, Matplotlib, Seaborn, and Streamlit for data extraction, analysis, visualization, and dashboard development.

---

## Objectives

The main objectives of this project are:

- Analyze PhonePe transaction trends over time.
- Analyze transactions by transaction type.
- Identify states with high transaction amounts.
- Identify districts with high transaction amounts.
- Analyze registered users over time.
- Identify states with high registered-user counts.
- Store and analyze the data using MySQL.
- Create visualizations using Python.
- Develop an interactive Streamlit dashboard.
- Generate meaningful insights from the analysis.

---

## Dataset

The dataset used in this project is the PhonePe Pulse dataset.

Source:

PhonePe Pulse GitHub Repository:
https://github.com/PhonePe/pulse

The available dataset contains aggregated transaction, user, map, and top-level geographical information.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- MySQL
- SQL
- Streamlit
- Git & GitHub

---

## Project Structure

```text
PhonePe-Transaction-Insights/
│
├── app/
│   └── streamlit_app.py
│
├── data/
│   ├── aggregated_transaction.csv
│   ├── aggregated_user.csv
│   ├── map_transaction.csv
│   ├── map_user.csv
│   ├── top_user.csv
│   ├── top_merchant.csv
│   └── visualization images
│
├── notebooks/
│   ├── phonepe_data_extraction.py
│   ├── phonepe_visualization.py
│   ├── state_visualization.py
│   ├── district_visualization.py
│   ├── user_visualization.py
│   └── top_user_visualization.py
│
├── sql/
│   ├── load_aggregated_transaction.py
│   ├── load_aggregated_user.py
│   ├── load_map_transaction.py
│   ├── load_map_user.py
│   ├── load_top_user.py
│   └── load_top_merchant.py
│
├── docs/
│
├── pulse/
│   └── PhonePe Pulse dataset
│
└── README.md
