# 🛒 QuickCart Market Basket Analysis

## 📌 Project Overview

This project performs Market Basket Analysis on QuickCart customer transaction data to identify products that are frequently purchased together.

The analysis uses **Apriori** and **FP-Growth** algorithms to discover frequent itemsets and **Association Rule Mining** to identify relationships between products.

## 🎯 Objectives

- Analyze customer purchasing patterns
- Identify frequently purchased products
- Find products that are commonly purchased together
- Compare Apriori and FP-Growth algorithms
- Generate association rules
- Evaluate rules using Support, Confidence, and Lift
- Provide useful business recommendations

## 📊 Dataset

The dataset contains QuickCart transaction information including:

- 5,000 orders
- 26,878 item-level transaction records
- 60 different products
- 12 stores
- Transaction data from November 2026

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Mlxtend
- Jupyter Notebook

## 🔍 Methodology

1. Load and explore the transaction dataset
2. Check missing values and data quality
3. Convert transactions into basket format
4. Apply one-hot encoding
5. Apply the Apriori algorithm
6. Apply the FP-Growth algorithm
7. Compare execution times
8. Generate association rules
9. Evaluate Support, Confidence, and Lift
10. Identify actionable product relationships
11. Visualize the results
12. Provide business recommendations

## 📈 Algorithms

### Apriori

Apriori is used to identify frequent itemsets based on a minimum support threshold.

### FP-Growth

FP-Growth is another frequent-pattern mining algorithm that can be faster than Apriori because it avoids generating candidate itemsets in the same way.

## 📏 Evaluation Metrics

### Support
Measures how frequently an itemset appears in all transactions.

### Confidence
Measures how often the consequent is purchased when the antecedent is purchased.

### Lift
Measures how strongly two products are associated compared with random purchasing.

## 🛍️ Business Applications

The discovered associations can help QuickCart with:

- Product recommendations
- Bundle offers
- Cross-selling
- Product placement
- Personalized promotions
- Improving customer shopping experience

## 📌 Conclusion

Market Basket Analysis helps QuickCart understand customer purchasing behavior and discover relationships between products. The results from Apriori, FP-Growth, and association rule mining can be used to make better product recommendations and develop effective marketing strategies.
