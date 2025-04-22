# 🛒 Customer Purchase Association Rules with Apriori

## 📌 Objective

This checkpoint focuses on discovering **association rules** using the **Apriori algorithm** on a dataset of **customer purchase history**. The goal is to help supermarket owners identify product associations and design more effective marketing strategies and product placements.

---

## 📂 Dataset

- **Source**: [Kaggle – Customer Purchases History](https://www.kaggle.com/)
- **Structure**: Each row in the dataset represents a **single customer transaction** (i.e., a purchase).

  ![Dataset Example](https://i.imgur.com/uYpSaHm.png)

---

## ⚙️ Tasks

- Load and clean the dataset
- Handle missing values (e.g., `NaN` dropped per transaction)
- Transform transactions into one-hot encoded format using `TransactionEncoder`
- Apply **Apriori** algorithm to extract frequent itemsets
- Generate **association rules** based on:
  - 📊 **Support**
  - 📈 **Confidence**
  - 🧲 **Lift**

---

## 🔍 Insights & Interpretation

Top association rules (with `lift ≥ 1.8`) were interpreted in natural language such as:

> 🛒 If you buy **ground beef**, you might also like ➕ **spaghetti**

These rules help uncover meaningful product combinations that are bought together more frequently than random chance — enabling better marketing, cross-selling, and shelf organization.

---

## 🧰 Tools & Libraries

- Python 🐍
- pandas
- numpy
- mlxtend
- matplotlib / seaborn (optional for visualization)

---

## 🧠 Why It Matters

Market basket analysis helps retailers understand **buying patterns**. By implementing association rules, they can:
- Increase average order value through **cross-selling**
- Improve product placement on shelves
- Create **bundle promotions** based on actual customer behavior

---

## ✅ Deliverables

- Cleaned dataset (one-hot encoded)
- Frequent itemsets with support scores
- Association rules with confidence & lift
- 📋 Human-readable interpretation of top rules

---

