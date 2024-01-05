# E-commerce
**Date: 2024/01/05**
<br>
E-commerce related lessons
# Cart Calculations Summary


This project provides a summary of calculations on a dataframe related to online shopping data. The primary focus is on analyzing customer transactions, visualizing purchase data, and extracting meaningful insights. The project utilizes Python, Pandas, and Plotly Express for data manipulation and visualization.

## Overview

- **Data Loading:** The project loads online shopping data from a JSON file using the Pandas library.

- **Data Exploration and Visualization:** The notebook explores the dataset, specifically the "items" column, which contains a list of dictionary lists representing items in each basket. Visualizations are created to understand customer behavior and purchase patterns.

- **Grouping and Summarization:** The data is transformed for better handling by grouping it based on customers, items, and their respective statuses. This allows for a comprehensive summary of purchases and customer activities.

- **Transaction Calculations:** The notebook includes functions for calculating various metrics, such as getting customer baskets, determining required stock after transactions, calculating the total amount spent by a customer, identifying top customers, and finding customers with open baskets.

## Usage

1. Clone the repository:

```bash
    git clone https://github.com/your-username/cart-calculations.git
    cd cart-calculations
```
Run the Jupyter Notebook:

```bash
jupyter notebook
```
Open and run the cart_calculations.ipynb notebook to explore the calculations and visualizations.
