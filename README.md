# Lab 6: Association Rule Mining (MSCS 634)

This project demonstrates Association Rule Mining using the Apriori algorithm on the Online Retail dataset. The goal is to discover interesting relationships (association rules) between items in large datasets, commonly used in market basket analysis.

## Contents

- `Lab6_AssociationRules.ipynb`: Jupyter notebook containing all code, analysis, and results for association rule mining.
- `OnlineRetail.csv`: The dataset used for mining association rules.
- `README.md`: Project documentation and instructions.

## Requirements

You will need Python 3.x and the following packages:

- pandas
- numpy
- mlxtend
- matplotlib
- seaborn

You can install the required packages using pip:

```bash
pip install pandas numpy mlxtend matplotlib seaborn
```

## Dataset

The `OnlineRetail.csv` file contains transactional data for online retail. Each row represents a product purchased in a transaction.

## How to Run

1. Open `Lab6_AssociationRules.ipynb` in Jupyter Notebook or VS Code.
2. Run the notebook cells sequentially to:
   - Load and preprocess the data
   - Apply the Apriori algorithm
   - Generate and analyze association rules
   - Visualize the results

## Project Steps

1. **Data Preprocessing:**
   - Load the dataset
   - Clean and transform data for association rule mining
2. **Frequent Itemset Mining:**
   - Use the Apriori algorithm to find frequent itemsets
3. **Association Rule Generation:**
   - Generate rules based on support, confidence, and lift
4. **Analysis & Visualization:**
   - Interpret and visualize the discovered rules

## References

- [mlxtend Documentation](http://rasbt.github.io/mlxtend/)
- [Association Rule Mining - Wikipedia](https://en.wikipedia.org/wiki/Association_rule_learning)

## Author

Sindhuja (MSCS 634)