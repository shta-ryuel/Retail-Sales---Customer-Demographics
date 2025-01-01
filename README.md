# Retail Sales and Customer Demographics Analysis

## Overview
This project focuses on analyzing retail sales data to uncover insights about customer demographics, purchasing behavior, and sales trends. By leveraging Python and Tableau, we aim to provide actionable insights for improving business strategies.

## Dataset
The dataset consists of the following columns:
- **Transaction ID**: Unique identifier for each transaction
- **Date**: Date of purchase
- **Customer ID**: Unique identifier for each customer
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Product Category**: Category of the purchased product
- **Quantity**: Number of items purchased
- **Price per Unit**: Price of a single unit of the product
- **Total Amount**: Total cost of the transaction

## Objectives
1. Understand the influence of age and gender on purchasing behavior.
2. Identify sales patterns across different time periods.
3. Determine the most popular product categories.
4. Analyze the relationships between age, spending, and product preferences.
5. Explore seasonal trends in customer shopping habits.
6. Examine purchasing behaviors based on the quantity of items bought.
7. Investigate the distribution of product prices within each category.

## Tools and Technologies
- **Python**: For data cleaning, analysis, and visualization.
- **Tableau**: For creating interactive dashboards.
- **Libraries Used**: Pandas, Matplotlib, Seaborn, NumPy.

## Process
1. **Data Cleaning and Preparation**:
   - Handle missing values and outliers.
   - Standardize date formats and ensure data consistency.

2. **Data Analysis**:
   - Conduct exploratory data analysis (EDA) to identify trends and patterns.
   - Analyze correlations between variables such as age, gender, and product preferences.

3. **Visualization**:
   - Create visualizations to showcase key insights using Python and Tableau.

## Insights for Tableau Dashboard
- **Sales Trends**: Visualize sales performance over time.
- **Customer Segmentation**: Highlight purchasing patterns by age and gender.
- **Product Preferences**: Showcase top-selling categories and seasonal trends.
- **Spending Behavior**: Illustrate correlations between customer demographics and spending habits.

## Folder Structure
```
Retail_Sales_Analysis/
|-- data/
|   |-- retail_sales.csv
|-- scripts/
|   |-- main.ipynb
|-- outputs/
|   |-- visualizations/
|-- tableau/
|   |-- retail_sales_dashboard.twb
|-- README.md
```

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/shta-ryuel/Retail-Sales---Customer-Demographics.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Retail-Sales---Customer-Demographics
   ```

3. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the `main.ipynb` file to perform the analysis:
   ```bash
   python scripts/main.ipynb
   ```

5. Open the Tableau dashboard file `retail_sales_dashboard.twb` to explore the visualizations.

## Results
This project provides actionable insights into customer demographics and purchasing behavior, enabling businesses to make data-driven decisions and optimize their sales strategies.

## License
This project is licensed under the MIT License.

 
