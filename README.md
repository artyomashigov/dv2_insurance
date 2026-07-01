# dv2_insurance

Data visualization project using an insurance dataset and an interactive Plotly Dash workflow.

## Project Overview

This notebook explores insurance beneficiary data and builds visual summaries that can support dashboard-style analysis. The project combines basic feature engineering, exploratory visualization, and an interactive dashboard built with Dash.

## Dataset

The dataset includes insurance-customer attributes such as age, sex, BMI, number of children, smoking status, region, and insurance charges.

The notebook also creates additional fields to make the data easier to analyze:

- `id`: unique customer identifier.
- `age_group`: grouped age bands such as 18-30, 31-45, 46-60, and 61+.
- `having_children`: binary indicator for whether a customer has children.
- BMI-related interpretation fields.

## Business Questions

The notebook is organized around visual questions about how insurance charges differ across customer groups. It looks at patterns connected to age, BMI, smoking, children, region, and other beneficiary characteristics.

## Notebook Structure

- Data import and preliminary analysis
- Feature engineering for grouped variables
- Exploratory data visualization
- Plotly chart construction
- Interactive dashboard setup with Dash
- Visual interpretation of insurance-cost patterns

## Files

- `artyom_ashigov_insurance.ipynb` - full notebook with data exploration, visualizations, and dashboard work.
- `insurance_data.csv` - source dataset.

## Tools

Python, pandas, Plotly, Dash, and Jupyter Notebook.
