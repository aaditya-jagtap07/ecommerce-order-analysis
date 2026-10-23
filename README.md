# E-commerce Order Analysis

## Project Overview
This project analyzes e-commerce order data to identify sales trends, top-performing product categories, revenue by customer state, and repeat customer behavior. The goal is to turn raw data into useful business insights using Python.

## Objectives
- Analyze total sales revenue and average order value.
- Explore monthly sales trends.
- Identify states contributing the most revenue.
- Find top-performing products and product categories.
- Analyze repeat customer behavior.
- Clean missing product category values.

## Tools and Technologies
- **Python** — programming language
- **Pandas** — data cleaning, manipulation, and analysis
- **Matplotlib** — data visualization
- **Jupyter Notebook** — interactive analysis

## Dataset
This project uses the Brazilian E-Commerce Public Dataset by Olist.

**Dataset source:** [Kaggle — Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

Download the dataset from Kaggle and place the required CSV files in the `data/` folder.

The dataset files are excluded from this GitHub repository. Please download them from the original source to reproduce the analysis.

## Key Findings
- **Total sales revenue:** Approximately R$ 13.22 million from delivered order items.
- **Average order value:** Approximately R$ 137.04, calculated using product prices per order.
- **Top revenue-generating state:** São Paulo (SP), contributing approximately 38.33% of delivered item revenue.
- **Leading product categories:** Beauty & Health, Watches & Gifts, and Bed, Bath & Table.
- **Repeat customer rate:** Approximately 3.0% among customers with delivered orders, based on unique customer identifiers.

*Note: Revenue is based on item prices and does not represent profit. Results depend on the dataset and analysis methods.*

## Project Structure
```text
ecommerce-order-analysis/
├── data/ 
│   └── Dataset CSV files (download separately)
├── Notebooks/
│   └── ecommerce_order_analysis.ipynb
├── .gitignore
└── README.md
```

## How to Run the Project
1. Clone or download this repository.
2. Download the dataset from Kaggle.
3. Place the required CSV files in the `data/` folder.
4. Install the required libraries:
   ```bash
   pip install pandas matplotlib jupyter
   ```
5. Open the notebook using Jupyter Notebook or JupyterLab.
6. Run the notebook cells in order.

## Skills Demonstrated
- Data cleaning and preprocessing
- Data manipulation using Pandas
- Grouping, aggregation, and merging datasets
- Exploratory Data Analysis (EDA)
- Data visualization
- Extracting business insights from data

## Future Improvements
- Analyze delivery times and order cancellations.
- Explore customer purchase patterns in greater detail.
- Create an interactive dashboard.
- Add more visualizations and business recommendations.

## Author
**Aaditya Jagtap**

GitHub: [aaditya-jagtap07](https://github.com/aaditya-jagtap07)

---

If you find this project useful, feel free to explore the notebook and its analysis.
