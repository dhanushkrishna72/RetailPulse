# RetailPulse - Retail Sales & Profitability Analysis

## 1. Project Overview
**RetailPulse** is a data analytics project that explores retail sales transactions to identify business trends, evaluate product performance, and understand profitability.
Built using Python, Pandas, NumPy, and Matplotlib, the project transforms raw retail data into meaningful insights through data cleaning, exploratory data analysis, statistical analysis, and visualizations.

## 2. Business Problem
Retail businesses generate large amounts of transaction data, but raw data alone does not explain how the business is performing.
Understanding which products generate the most revenue, which categories are profitable, how sales change over time, and whether discounts affect profitability is essential for making informed business decisions.
RetailPulse addresses these questions by analyzing historical retail sales data and identifying patterns that can support better business decisions.

## 3. Objectives
- Analyze overall retail sales and profit performance.
- Identify top-performing product categories and sub-categories.
- Understand sales trends over time.
- Compare profitability across different regions.
- Identify products and transactions generating losses.
- Examine the relationship between discounts and profit.
- Apply NumPy statistical operations to understand data distribution and outliers.
- Present findings through clear and informative visualizations.

## 4. Dataset Description
The project uses the **Sample Superstore Dataset**, which contains historical retail transaction records. It provides information about customer orders, product categories, shipping methods, sales, discounts, and profitability.
The dataset contains **20 columns**, grouped into the following categories:

### Dataset Attributes

| Column | Description |
|---|---|
| Row ID | Unique identifier for each row. |
| Order ID | Unique identifier for each order. |
| Order Date | Date when the order was placed. |
| Ship Date | Date when the product was shipped. |
| Ship Mode | Shipping method selected by the customer. |
| Customer ID | Unique identifier for each customer. |
| Customer Name | Name of the customer. |
| Segment | Customer segment. |
| Country | Customer's country of residence. |
| City | Customer's city of residence. |
| State | Customer's state of residence. |
| Postal Code | Postal code associated with the customer. |
| Region | Geographical region of the order. |
| Product ID | Unique identifier for each product. |
| Category | Main category of the product. |
| Sub-Category | Sub-category of the product. |
| Product Name | Name of the product. |
| Sales | Revenue generated from the product. |
| Quantity | Number of units ordered. |
| Discount | Discount applied to the product. |
| Profit | Profit or loss generated from the sale. |

### Dataset Categories
The dataset attributes can be organized into five groups:
- **Order Information:** Row ID, Order ID, Order Date, Ship Date, Ship Mode.
- **Customer Information:** Customer ID, Customer Name, Segment.
- **Geographical Information:** Country, City, State, Postal Code, Region.
- **Product Information:** Product ID, Category, Sub-Category, Product Name.
- **Sales & Financial Information:** Sales, Quantity, Discount, Profit.

**Dataset Source:** [Kaggle - Sample Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

## 5. Technologies Used
- **Python** - Core programming language
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical and statistical operations
- **Matplotlib** - Data visualization
- **Jupyter Notebook** - Interactive analysis environment
- **Git & GitHub** - Version control and project hosting

## 6. Project Workflow
The project follows a structured data analytics workflow:
1. **Data Collection:** Obtain the Sample Superstore dataset.
2. **Data Loading:** Import the dataset using Pandas.
3. **Data Inspection:** Examine dimensions, columns, data types, and missing values.
4. **Data Cleaning:** Handle missing values, duplicates, and date formatting where required.
5. **Exploratory Data Analysis:** Analyze sales, profit, categories, customers, and regions.
6. **Statistical Analysis:** Apply NumPy functions to calculate statistical measures and identify outliers.
7. **Data Visualization:** Create charts to communicate important patterns.
8. **Business Insights:** Summarize findings from the analysis.

## 7. Exploratory Data Analysis
The analysis focuses on the following questions:
- What is the total revenue and total profit?
- Which product category generates the highest revenue?
- Which sub-category generates the highest sales and profit?
- Which region performs best in terms of sales and profit?
- Which products generate the highest losses?
- Which month records the highest sales?
- What is the average discount offered?
- Who are the top customers based on sales?
- How does discounting relate to profitability?

### NumPy Statistical Analysis
NumPy is used to perform additional statistical analysis:
- Mean and median sales.
- Standard deviation of sales.
- Sales distribution using percentiles.
- Profit margin calculation.
- Outlier detection using the Interquartile Range (IQR) method.

## 8. Visualizations
The project includes the following visualizations:
1. **Category-wise Sales:** Compares revenue generated by each product category.
2. **Monthly Sales Trend:** Tracks changes in sales over time.
3. **Regional Profit Analysis:** Compares profit across geographical regions.
4. **Sales vs. Profit Analysis:** Examines the relationship between sales and profitability.
5. **Sales Distribution:** Displays the distribution of transaction values.

## 9. Key Findings

This section will document the actual insights discovered during the analysis.

Examples of findings to investigate:
- The product category contributing the highest revenue.
- The region generating the highest profit.
- Products or sub-categories consistently generating losses.
- Monthly sales patterns and seasonal trends.
- Whether higher discounts are associated with lower profitability.
*Note: Final findings will be added after validating the analysis results.*

## 10. How to Run

### Prerequisites

- Python 3.10 or later
- Git
- Jupyter Notebook

### Clone the Repository

```bash
git clone https://github.com/dhanushkrishna72/RetailPulse.git
cd RetailPulse
```

### Create a Virtual Environment

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Analysis

```bash
jupyter notebook
```

Open the notebook inside the `notebooks/` directory and execute the cells.

### Dataset Setup
Download the Sample Superstore CSV from the dataset source and place it inside the `data/` directory.

## 11. Future Improvements
- Develop an interactive dashboard using Streamlit.
- Add interactive filters for category, region, and date.
- Introduce advanced statistical analysis.
- Perform sales forecasting using machine learning.
- Add customer segmentation and purchasing behavior analysis.
- Deploy the dashboard for public access.

## 12. Author

**Dhanush Krishna**
Engineering Student | Aspiring Software Engineer & Data Analyst
- GitHub: [Your GitHub Profile](https://github.com/dhanushkrishna72)
- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/dhanushkrishna-plutoexplain/)

---

*RetailPulse - Turning retail data into meaningful business insights.*