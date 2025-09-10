# Customer Analysis for Credit Card Launch

## Overview

This project analyzes customer demographics, credit profiles, and transaction data to identify target segments for AtliQo Bank's credit card launch. The analysis focuses on data cleaning, exploratory data analysis (EDA), and deriving actionable insights to optimize marketing strategies.

## Key Features

- **Data Cleaning:** Handled missing values, duplicates, and outliers in customer, credit profile, and transaction datasets.
- **Exploratory Analysis:** Visualized distributions, correlations, and trends using Python libraries.
- **Targeting Insights:** Identified age group 18-25 as an untapped market with high potential for credit card adoption.
- **Interactive Notebook:** Jupyter Notebook with step-by-step analysis and visualizations.

## Technologies Used

- **Python Libraries:** pandas, numpy, seaborn, matplotlib
- **Tools:** Jupyter Notebook

## Installation & Setup

1. Clone the repository:

   ```
   git clone https://github.com/yourusername/customer-analysis-credit-card.git
   cd customer-analysis-credit-card
   ```

2. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

## Usage

1. Open `analysis.ipynb` in Jupyter Notebook or VS Code.
2. Run cells sequentially to import data, clean it, and generate visualizations.
3. Key sections:
   - Data Import (CSV or MySQL)
   - Cleaning Customers, Credit Profiles, and Transactions tables
   - Merging data and EDA
   - Targeting recommendations

## Data

The analysis uses:

- `customers.csv`: Demographic data (1,000 records)
- `credit_profiles.csv`: Credit scores and limits
- `transactions.csv`: Transaction history (500,000 records)

## Key Insights

- Age group 18-25 (26% of customers) shows low credit card usage but high spending in electronics, fashion, and beauty.
- Strong correlation between credit score and credit limit (0.85).
- Recommended targeting: Focus marketing on young adults via Amazon/Flipkart.
