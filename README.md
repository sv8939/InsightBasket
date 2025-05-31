# InsightBasket

**InsightBasket** is a data mining and association rule mining project aimed at uncovering meaningful purchase patterns from grocery transactional data. By analyzing customers' buying habits, this project identifies frequently co-purchased items and generates actionable business insights to guide marketing strategies such as product placement, promotions, and inventory planning.

---

## Features

- Loads and preprocesses real-world grocery transactions.
- Uses the Apriori algorithm to find frequent itemsets.
- Generates association rules with metrics: support, confidence, and lift.
- Visualizes rules with a scatter plot (support vs confidence, sized by lift).
- Provides clear, formatted business insights based on discovered rules.
- Modular code with well-defined functions for easy customization.

---

## Dataset

The project uses the publicly available **Groceries dataset** (example dataset often used for market basket analysis).

- The dataset consists of transactional data where each row corresponds to an item purchased by a customer.
- Transactions are grouped by customer to analyze shopping baskets.

---

## Getting Started

### Prerequisites

- Python
- Libraries:
  - pandas
  - mlxtend
  - matplotlib
  - seaborn

You can install the required libraries using pip:

```bash
pip install pandas mlxtend matplotlib seaborn
