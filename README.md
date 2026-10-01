# Market Basket Analysis Using Apriori Algorithm

## Project Overview

This project focuses on **Market Basket Analysis**, a data mining technique used to identify relationships and purchasing patterns among products in retail transaction data.

The **Apriori Algorithm** is used to discover frequently purchased product combinations and generate association rules. These patterns can help businesses understand customer buying behavior and improve product recommendations, cross-selling, promotions, and inventory planning.

## Objective

- Analyze retail transaction data to identify purchasing patterns.
- Find frequently purchased products and product combinations.
- Apply the Apriori algorithm to generate frequent itemsets.
- Generate association rules using support, confidence, and lift.
- Visualize important product associations.
- Derive useful business insights from customer transactions.

## Dataset

The project uses retail transaction data containing information about customer invoices, products, quantities, prices, and transaction details.

The dataset is included in this repository to make the project easier to reproduce and review.

The data was cleaned and transformed into a transaction-based format suitable for applying the Apriori algorithm.

## Technologies Used

- Python
- Pandas
- Matplotlib
- Mlxtend
- Google Colab
- Jupyter Notebook

## Project Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis
4. Transaction Data Transformation
5. Basket Format Conversion
6. Frequent Itemset Generation
7. Association Rule Generation
8. Support, Confidence, and Lift Analysis
9. Data Visualization
10. Business Insight Generation

## Exploratory Data Analysis

The following factors were analyzed to understand customer purchasing patterns:

- Product purchase frequency
- Transaction distribution
- Most frequently purchased products
- Customer purchasing behavior
- Product combinations
- Transaction-level patterns

Visualizations were created using Matplotlib to identify important patterns in the retail transaction data.

## Apriori Algorithm

The Apriori algorithm was implemented to identify products that frequently occur together in customer transactions.

The analysis uses three important measures:

### Support

Support represents how frequently an item or itemset appears in all transactions.

### Confidence

Confidence represents the likelihood of purchasing the consequent product when the antecedent product or products are purchased.

### Lift

Lift measures how strongly two products are associated compared with their occurrence by chance.

- **Lift > 1:** Positive association
- **Lift = 1:** No significant association
- **Lift < 1:** Negative association

## Association Rules

The Apriori algorithm was used to generate association rules based on frequent itemsets.

Some of the important product relationships discovered include:

- **DOLLY GIRL LUNCH BOX → SPACEBOY LUNCH BOX**
- **CHARLOTTE BAG PINK POLKADOT → RED RETROSPOT CHARLOTTE BAG**
- **RED RETROSPOT CHARLOTTE BAG → STRAWBERRY CHARLOTTE BAG**
- **WOODLAND CHARLOTTE BAG → RED RETROSPOT CHARLOTTE BAG**
- **PAPER CHAIN KIT 50'S CHRISTMAS → PAPER CHAIN KIT VINTAGE CHRISTMAS**

These relationships indicate that customers purchasing certain products are also likely to purchase related products.

## Business Applications

The identified purchasing patterns can be used for:

- Product recommendation systems
- Cross-selling strategies
- Bundle offers
- Promotional campaigns
- Store layout optimization
- Inventory planning
- Customer purchase analysis

## Project Structure

```text
Market-Basket-Analysis/
│
├── Market_Basket_Analysis.ipynb
├── Online_Retail.csv
└── README.md
