# Supply Chain Analytics and Inventory Optimization

This repository provides a comprehensive suite of tools for supply chain analysis, focusing on inventory management, demand planning, and operational efficiency. The project leverages SQL and Python to perform deep-dive operational analysis and generate actionable insights for S&OP and MRP processes.

## Key Features

- Inventory Classification: Automated ABC/XYZ analysis to prioritize stock management and optimize warehouse operations.
- Safety Stock Optimization: Statistical models to calculate optimal safety stock levels based on lead time variability and demand fluctuations.
- Demand Forecasting: Implementation of time-series models and forecasting techniques to improve planning accuracy.
- Purchase Order Analysis: Scripts to identify bottlenecks in procurement and evaluate supplier performance metrics.
- KPI Reporting: Automated generation of supply chain metrics including fill rates, stockout risks, and inventory turnover ratios.
- Data Validation: Robust root-cause analysis and data validation scripts to ensure accuracy in planning support.

## Technical Stack

- Languages: SQL, Python, VBA
- Libraries: Pandas, NumPy, Scikit-Learn, Matplotlib
- ERP/Tools: Integration logic for SAP MM, SAP APO, SAP SCM, and Oracle NetSuite data exports
- Visualization: Power BI and Tableau integration scripts

## Installation

1. Clone the repository:
   git clone https://github.com/saideekshithareddypalpunoori-cloud/supply-chain-analytics.git

2. Install the required dependencies:
   pip install -r requirements.txt

3. Configure your database connection in the config.py file for SQL-based analysis.

## Usage

To execute the inventory optimization module:
python src/inventory_optimization.py --input data/raw_inventory_data.csv

To generate a supplier performance report:
python src/supplier_analysis.py --report monthly

## Documentation

The project includes detailed documentation in the /docs folder covering:
- Statistical methodologies for safety stock calculation
- Data cleaning and validation procedures for SAP/Oracle exports
- Best practices for demand planning and ABC analysis

## Maintainer

This project is currently maintained by Sai Deekshitha Reddy Palpunoori. It was originally developed as a framework for operational analytics and continues to be updated with new features for supply chain optimization and business intelligence.

## About the Developer

Sai Deekshitha Reddy Palpunoori is a Supply Chain Analyst with over 4 years of professional experience across supply chain, business analysis, and operations. Specializing in demand planning and inventory management, Sai utilizes a technical toolkit including SQL, Python, and SAP to drive operational excellence and data-driven decision-making.

Contact Information:
- Email: saideekshithareddypalpunoori@gmail.com
- GitHub: https://github.com/saideekshithareddypalpunoori-cloud
- LinkedIn: https://www.linkedin.com/in/sai-deekshitha-reddy-palpunoori-b38b60215/