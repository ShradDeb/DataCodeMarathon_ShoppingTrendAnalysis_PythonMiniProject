# Shopping Trends Analysis

A Python-based exploratory data analysis project that studies customer shopping behavior, purchase patterns, product category performance, seasonal demand, payment preferences, and high-performing customer segments using a retail shopping trends dataset.

## Project Overview

This project analyzes shopping transaction data to understand how customer demographics, product categories, purchase amounts, seasons, payment methods, discounts, promo code usage, subscription status, and purchase frequency influence retail performance.

The analysis is completed in a Jupyter Notebook using Python data analysis and visualization libraries. The notebook walks through data loading, data quality checks, univariate exploration, grouped analysis, cross-tab analysis, and business insights.

## Objectives

- Explore customer shopping behavior across demographic and behavioral attributes.
- Identify popular product categories based on total sales, average sales, and purchase count.
- Analyze seasonal purchase trends and sales performance.
- Understand how payment methods, shipping types, discounts, and promo codes are distributed.
- Compare purchase behavior by gender, subscription status, location, and product category.
- Identify high-performing customer segments for business decision-making.

## Dataset

The dataset contains **3,900 customer shopping records** and **19 columns**.

Key fields include:

- `Customer ID`
- `Age`
- `Gender`
- `Item Purchased`
- `Category`
- `Purchase Amount (USD)`
- `Location`
- `Size`
- `Color`
- `Season`
- `Review Rating`
- `Subscription Status`
- `Payment Method`
- `Shipping Type`
- `Discount Applied`
- `Promo Code Used`
- `Previous Purchases`
- `Preferred Payment Method`
- `Frequency of Purchases`

## Data Quality Checks

The notebook performs basic validation checks before analysis:

- Dataset shape inspection
- Column and data type review
- Missing value check
- Duplicate record check

Initial checks show:

- 3,900 rows and 19 columns
- No missing values
- No duplicate records

## Analysis Performed

### 1. Customer Demographics

- Age distribution
- Gender distribution
- Location distribution

### 2. Product and Category Analysis

- Item purchased distribution
- Product category distribution
- Size and color preferences
- Total sales by product category

### 3. Purchase Behavior

- Purchase amount distribution
- Previous purchases distribution
- Frequency of purchases
- Review rating distribution

### 4. Payment and Fulfillment Analysis

- Payment method distribution
- Preferred payment method distribution
- Shipping type distribution

### 5. Promotion and Subscription Analysis

- Discount applied distribution
- Promo code usage distribution
- Subscription status distribution
- Category purchases by subscription status

### 6. Business Segment Analysis

- Purchase amount by location
- Purchase amount by payment method
- Purchases by season
- Frequency of purchases by gender
- Product category purchases by gender
- High-performing customer segments by gender, age, location, and subscription status

## Key Insights

### Product Category Performance

| Category | Total Sales | Average Sales | Purchase Count |
|---|---:|---:|---:|
| Clothing | 104,264 | 60.03 | 1,737 |
| Accessories | 74,200 | 59.84 | 1,240 |
| Footwear | 36,093 | 60.26 | 599 |
| Outerwear | 18,524 | 57.17 | 324 |

**Clothing** is the top-performing category by total sales and purchase count, followed by **Accessories**.

### Seasonal Trends

| Season | Total Sales | Average Sales | Purchase Count |
|---|---:|---:|---:|
| Fall | 60,018 | 61.56 | 975 |
| Spring | 58,679 | 58.74 | 999 |
| Winter | 58,607 | 60.36 | 971 |
| Summer | 55,777 | 58.41 | 955 |

**Fall** generated the highest total sales, while **Spring** had the highest purchase count.

### High-Performing Segments

The project groups customers by gender, age, location, and subscription status to identify high-value segments. These segments can help guide targeted marketing, customer retention, and promotional strategies.

## Tools and Libraries Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Project Structure

```text
.
├── Shopping Trends Analysis.ipynb
├── shopping_trends.csv
└── README.md
```

## How to Run the Project

1. Clone this repository:

```bash
git clone <your-repository-url>
cd <your-repository-name>
```

2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Add the dataset file to the project folder:

```text
shopping_trends.csv
```

4. Open the notebook:

```bash
jupyter notebook "Shopping Trends Analysis.ipynb"
```

5. Update the file path in the notebook if needed:

```python
filepath = "shopping_trends.csv"
df = pd.read_csv(filepath)
```

6. Run the cells from top to bottom.

## Visualizations Included

The notebook includes visual analysis for:

- Age distribution
- Gender distribution
- Item purchased distribution
- Category distribution
- Purchase amount distribution
- Customer location distribution
- Size and color distribution
- Seasonal distribution
- Review rating distribution
- Subscription status
- Payment methods
- Shipping type
- Discount and promo code usage
- Previous purchases
- Frequency of purchases
- Total sales by location
- Total sales by product category
- Heatmaps for category behavior by gender and subscription status

## Business Use Cases

This analysis can support:

- Retail sales performance reporting
- Customer segmentation
- Product category planning
- Seasonal campaign planning
- Promotion and discount strategy
- Inventory and merchandising decisions
- Payment and shipping preference analysis

## Future Improvements

- Add predictive modeling to estimate future purchase amount or customer purchase frequency.
- Build a customer segmentation model using clustering.
- Add interactive dashboards using Tableau, Power BI, Streamlit, or Plotly Dash.
- Include customer lifetime value analysis.
- Perform deeper analysis on discount effectiveness and subscription conversion.
- Automate the analysis pipeline for recurring retail reporting.

## Author

**Shraddha Debata**

GitHub: [ShradDeb](https://github.com/ShradDeb)
Tableau: https://public.tableau.com/app/profile/shraddha.debata2941/vizzes
LinkedIn: https://www.linkedin.com/in/shraddha-debata-59726094

## License

This project is intended for educational and portfolio purposes. Add a license file if you plan to make the repository open source.
