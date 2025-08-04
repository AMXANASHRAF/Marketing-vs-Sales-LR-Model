# Advertising and Sales Prediction using Linear Regression

This project uses a simple **Linear Regression model** to analyze the relationship between advertising budgets and sales performance. The goal is to predict sales based on different types of ad spending using a clean dataset.

---

## Dataset

- **File Name:** `advertising_and_sales_clean.csv`
- **Features:**
  - Likely includes columns such as `TV`, `Radio`, `Newspaper`, etc.
  - Target: `Sales`

---

##  Tools & Libraries Used

- Python 3.x
- Pandas & NumPy
- Matplotlib
- Scikit-learn

---

## Workflow

1. **Data Loading & Exploration**
   - Read the CSV file and perform `.head()`, `.info()`, `.describe()` checks.

2. **Feature Selection**
   - Inputs: All columns except the last two
   - Target: Last column (Sales)

3. **Train-Test Split**
   ```python
   train_test_split(X, Y, test_size=0.2, random_state=1)
