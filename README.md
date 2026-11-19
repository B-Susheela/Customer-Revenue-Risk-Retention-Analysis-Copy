# Customer Revenue, Risk & Retention Analytics

## Project Overview
This project focuses on analysing customer behaviour, revenue patterns, order returns, delivery performance, and customer retention using Python and data analytics techniques.

The objective is to identify business risks, understand customer purchasing patterns, and generate actionable insights to support better business decisions.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Microsoft Excel
- Jupyter Notebook

## Datasets
The project uses one Excel workbook containing three datasets:

- **Customers:** Customer information and details.
- **Orders:** Order details, payment modes, delivery dates, and order status.
- **Order Items:** Product categories, quantities, and prices.

## Project Workflow
1. Data loading and exploration
2. Data cleaning and validation
3. Data transformation and feature engineering
4. Customer segmentation
5. Customer risk categorisation
6. Business analysis and visualisation
7. Business insights and recommendations

## Business Questions
1. Which customers generate high revenue but also have high return rates?
2. Which cities experience delivery delays and revenue loss?
3. How do repeat customers contribute to overall revenue?
4. Which product categories generate high revenue but also have high returns?
5. Which payment modes are associated with higher return and cancellation risks?

## Key Findings

- Identified 129 customers generating more than ₹10,000 in order value with return rates of 30% or higher.
- Pune recorded the highest potential at-risk order value of ₹20.74 lakh.
- Repeat customers contributed approximately 99.7% of total revenue.
- Electronics recorded the highest product category return rate at 18.77%.
- UPI recorded the highest potential at-risk order value of approximately ₹41.37 lakh.

## Visualisations
The project includes five major visualisations:

- Monthly Revenue Trend
- Customer Value Segmentation
- Return Rate by Product Category
- Delivery Duration vs Order Value
- City vs Product Category Revenue Heatmap

## Business Recommendations

- Introduce targeted retention strategies for high-value customers.
- Investigate return and cancellation patterns across cities.
- Improve delivery efficiency and order management.
- Investigate product quality and customer expectations in high-return categories.
- Monitor payment-related return and cancellation risks.

## Repository Structure

```text
Customer-Revenue-Risk-Retention-Analysis/
│
├── datasets/
│   └── Dataset.xlsx
│
├── Customer Revenue, Risk & Retention Analytics Project.ipynb
│
└── README.md
```

## How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Ensure the Excel workbook is available in the `datasets` folder.
5. Run the notebook cells sequentially.

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
```

## Project Conclusion

This project demonstrates practical data analytics skills, including data cleaning, data manipulation, customer segmentation, business analysis, and data visualisation.

It converts raw customer and order data into meaningful business insights that can help organisations improve customer retention, reduce returns, manage operational risks, and make data-driven decisions.
