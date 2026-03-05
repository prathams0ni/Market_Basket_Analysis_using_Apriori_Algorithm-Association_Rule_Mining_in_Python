# 🛒 Market Basket Analysis using Apriori Algorithm

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Association%20Rule%20Mining-green)

![Library](https://img.shields.io/badge/mlxtend-Apriori-orange)

![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

# 📌 Project Overview

Market Basket Analysis is a **data mining technique** used to discover relationships between products that customers frequently purchase together.

This project applies the **Apriori Algorithm** to analyze grocery store transaction data and identify **frequent itemsets and association rules**.

These insights help businesses understand **customer purchasing behavior** and improve:

🛍 Product placement
📦 Cross-selling strategies
📊 Sales optimization
🤖 Recommendation systems

---

# 🎯 Problem Statement

Retail stores collect large amounts of transactional data, but extracting valuable insights from it can be challenging.

The goal of this project is to:

✔ Identify frequently purchased products
✔ Discover relationships between items
✔ Generate association rules using support and confidence
✔ Extract business insights from transactional data

---

# 📊 Dataset

The dataset contains **grocery store transactions** where each row represents items purchased together by a customer.

Example transactions:

MILK,BREAD,BISCUIT
BREAD,MILK,BISCUIT,CORNFLAKES
BREAD,TEA,BOURNVITA
JAM,MAGGI,BREAD,MILK

Total Transactions: **20**

Products present in the dataset include:

🥖 Bread
☕ Coffee
🍪 Biscuit
🍵 Tea
🥛 Milk
🥣 Cornflakes
🧂 Sugar
🍜 Maggi
🥤 Coke
🍫 Bournvita
🍓 Jam

---

# ⚙️ Technologies Used

This project was implemented using:

🐍 Python

Libraries:

📦 pandas – Data manipulation
🔢 numpy – Numerical operations
📊 matplotlib – Data visualization
📈 seaborn – Advanced plotting
⚡ mlxtend – Apriori algorithm implementation

---

# 🔬 Methodology

The project follows these steps:

### 1️⃣ Data Loading

Load the grocery dataset into a pandas dataframe.

### 2️⃣ Data Preprocessing

Split transaction strings into individual product lists.

### 3️⃣ Transaction Encoding

Use **TransactionEncoder** to convert transaction lists into a binary matrix.

### 4️⃣ Frequent Itemset Generation

Apply the **Apriori Algorithm** to identify frequent itemsets based on **support values**.

### 5️⃣ Association Rule Mining

Generate rules using metrics such as:

Support
Confidence
Lift

These metrics determine the strength of relationships between items.

---

# 📈 Exploratory Data Analysis

Product purchase frequency:

| Product    | Frequency |
| ---------- | --------- |
| Bread      | 13        |
| Coffee     | 8         |
| Biscuit    | 7         |
| Tea        | 7         |
| Sugar      | 6         |
| Cornflakes | 6         |
| Milk       | 5         |
| Maggi      | 5         |
| Bournvita  | 4         |
| Coke       | 3         |
| Jam        | 2         |

📌 **Bread is the most frequently purchased product.**

---

# 🔗 Association Rules

The Apriori algorithm generated several interesting rules.

Examples:

Bread → Biscuit
Coffee → Biscuit
Coffee → Cornflakes
Tea → Maggi
Bread → Sugar

These rules indicate strong product relationships in customer transactions.

---

# 💡 Business Insights

From the discovered patterns, businesses can:

📍 Place frequently associated products close to each other
📦 Create bundle offers and combo deals
📈 Improve cross-selling strategies
🛍 Build recommendation systems

Example:

If a customer buys **Bread**, the system may recommend **Biscuit**.

---

# 🚀 How to Run the Project

### 1️⃣ Clone the Repository

git clone https://github.com/prathams0ni/Market_Basket_Analysis_using_Apriori_Algorithm-Association_Rule_Mining_in_Python.git

### 2️⃣ Install Dependencies

pip install pandas numpy matplotlib seaborn mlxtend

### 3️⃣ Run the Notebook

jupyter notebook

Open the notebook and run all cells.

---

# 📊 Visualization

The project includes visualizations showing **product frequency distribution**.

Bread appears as the most dominant product followed by Coffee and Biscuit.

---

# 🔮 Future Improvements

Possible extensions of this project:

🔹 Use a larger retail dataset
🔹 Apply **FP-Growth Algorithm** for faster pattern mining
🔹 Build a **real-time recommendation system**
🔹 Deploy the project as a **web application**
🔹 Integrate with real e-commerce data

---

# 🏆 Conclusion

This project demonstrates how **Association Rule Mining using the Apriori Algorithm** can uncover hidden relationships between products in transactional data.

These insights can help retailers:

📈 Increase sales
🛍 Improve customer experience
📦 Design effective product bundles

Market Basket Analysis is widely used in **retail analytics, recommendation systems, and e-commerce platforms**.

---

Data Science | Machine Learning | AI Enthusiast
