# Market Basket Analysis Using Apriori Algorithm

## Project Overview

This project focuses on **Market Basket Analysis**, a data mining technique used to identify relationships and purchasing patterns among products in retail transaction data.

The **Apriori Algorithm** is used to discover frequently purchased product combinations and generate association rules. These patterns can help businesses understand customer buying behavior and improve product recommendations, cross-selling, promotions, and inventory planning.

## Objective

* Analyze retail transaction data to identify purchasing patterns.
* Find frequently purchased products and product combinations.
* Apply the Apriori algorithm to generate frequent itemsets.
* Generate association rules using support, confidence, and lift.
* Visualize important product associations.
* Derive useful business insights from customer transactions.

## Technologies Used

* **Python**
* **Pandas**
* **Matplotlib**
* **Mlxtend**
* **Google Colab**
* **Jupyter Notebook**

## Dataset

The project uses retail transaction data containing information about customer invoices, products, quantities, prices, and transaction details.

The data was cleaned and transformed into a transaction-based format suitable for applying the Apriori algorithm.

## Project Workflow

1. Import the required Python libraries.
2. Load the retail transaction dataset.
3. Understand the structure and characteristics of the data.
4. Clean the transaction data.
5. Perform Exploratory Data Analysis (EDA).
6. Convert transaction data into a basket format.
7. Apply the Apriori algorithm.
8. Identify frequent itemsets.
9. Generate association rules.
10. Analyze support, confidence, and lift.
11. Visualize the top association rules.
12. Extract business insights.

## Apriori Algorithm

The Apriori algorithm is used to identify products that frequently occur together in customer transactions.

Three important measures are used:

### Support

Support represents how frequently an item or itemset appears in all transactions.

### Confidence

Confidence represents the likelihood of purchasing the consequent product when the antecedent product or products are purchased.

### Lift

Lift measures how strongly two products are associated compared with their occurrence by chance.

* **Lift > 1:** Positive association
* **Lift = 1:** No significant association
* **Lift < 1:** Negative association

## Key Findings

The analysis identified strong associations among several products.

Some of the important product relationships discovered include:

* **DOLLY GIRL LUNCH BOX → SPACEBOY LUNCH BOX**
* **CHARLOTTE BAG PINK POLKADOT → RED RETROSPOT CHARLOTTE BAG**
* **RED RETROSPOT CHARLOTTE BAG → STRAWBERRY CHARLOTTE BAG**
* **WOODLAND CHARLOTTE BAG → RED RETROSPOT CHARLOTTE BAG**
* **PAPER CHAIN KIT 50'S CHRISTMAS → PAPER CHAIN KIT VINTAGE CHRISTMAS**

These relationships indicate that customers purchasing certain products are also likely to purchase related products.

## Business Applications

The identified purchasing patterns can be used for:

* Product recommendation systems
* Cross-selling strategies
* Bundle offers
* Promotional campaigns
* Store layout optimization
* Inventory planning
* Customer purchase analysis

## Project Structure

```text
Market-Basket-Analysis/
│
├── Market_Basket_Analysis.ipynb
└── README.md
```

## How to Run the Project

1. Open the Jupyter Notebook in **Google Colab** or Jupyter Notebook.
2. Upload the required dataset.
3. Run the notebook cells sequentially.
4. View the generated frequent itemsets, association rules, visualizations, and business insights.

## Project Outcome

This project demonstrates how **data mining and machine learning techniques** can be applied to retail transaction data to discover hidden relationships between products.

The insights obtained from Market Basket Analysis can support businesses in making better decisions related to product recommendations, cross-selling, promotions, and inventory management.

## Internship Project

**Project:** Market Basket Analysis Using Apriori Algorithm
**Domain:** Data Analytics / Machine Learning
**Internship:** CodeCTechnologies

## Conclusion

The Market Basket Analysis project successfully applied the Apriori algorithm to retail transaction data and identified meaningful product associations using support, confidence, and lift.

The project provides practical experience in **data preprocessing, exploratory data analysis, association rule mining, data visualization, and business insight generation**.
