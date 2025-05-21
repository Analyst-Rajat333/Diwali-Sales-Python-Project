# 🪔 Diwali Sales Python Project

This project presents an in-depth **Exploratory Data Analysis (EDA)** on Diwali sales using Python. The dataset captures customer demographics, purchase behavior, and sales across Indian states and product categories — providing business insights during the festive season.

---

## 📦 Dataset Overview

- **Source File**: `Diwali Sales Data.csv`
- **Total Records**: 11,251
- **Columns Include**:
  - Customer Info: Gender, Age Group, Marital Status, State, Occupation
  - Purchase Info: Product Category, Orders, Amount

---

## 🛠 Technologies Used

- **Python 3**
- **Pandas** – data manipulation
- **Matplotlib & Seaborn** – data visualization
- **Jupyter Notebook** – data exploration & chart building

---

## 📊 Project Workflow

1. **Importing Libraries**  
   - NumPy, Pandas, Seaborn, Matplotlib

2. **Data Cleaning**  
   - Dropped null and irrelevant columns (`Status`, `unnamed1`)
   - Handled missing values (especially in `Amount`)
   - Converted `Amount` to integer type
   - Renamed `Marital_Status` → `Shaadi`

3. **Descriptive Analysis**
   - Used `.describe()` to understand sales amount, orders, and age distribution

4. **Visualization & EDA**
   - Gender-based and age-wise buying patterns
   - State-wise sales performance
   - Occupational and product category analysis
   - Top-selling products by Product ID

---

## 📈 Key Insights & Charts

### 📌 Gender-Based Insights
- **Most buyers were females**
- **Females spent more on average during Diwali**

### 📌 Age Group Analysis
- Highest purchases came from **26-35 age group**
- Female customers in this group dominated sales

### 📌 State-Wise Insights
- **Uttar Pradesh, Maharashtra, and Karnataka** led in both orders and total purchase amount

### 📌 Marital Status
- **Married women** had the highest purchasing power

### 📌 Occupation-Wise Buyers
- Top buyers were from:
  - IT Sector
  - Healthcare
  - Aviation

### 📌 Product Category Performance
- Top-selling categories:
  - **Food**
  - **Clothing**
  - **Electronics**

### 📌 Most Sold Products
- Top 10 most ordered Product IDs were identified and plotted

---

### 📌Clone the repository:
git clone 
https://github.com/Analyst-Rajat333/Diwali-Sales-Python-Project.git
