# 🏬 Data Analysis and Visualization of Superstore Sales Data
## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Superstore USA** dataset using **Python**.  
It covers **data cleaning, visualization, and insights** into sales, profit, customer segments, shipping modes, and product categories.

---

## 📂 Dataset Details
- **File:** `Superstore_usa.xlsx`
- **Rows:** 9,426  
- **Columns:** 25 (after processing)
- **Years Covered:** 2010–2013

---

## ⚙️ Technologies Used
- 🐍 **Python 3.10+**
- 📊 **Pandas** — Data manipulation
- 📉 **Matplotlib & Seaborn** — Data visualization
- 📅 **Datetime** — Handling date-related operations
- 🧮 **NumPy** — Numerical computations

---

## 🔍 Data Cleaning & Preprocessing
- Checked dataset shape and data types  
- Identified **72 missing values** in `Product Base Margin` and filled them with the **mean**  
- Added a new feature: **`order year`** extracted from `Order Date`

---

## 📊 Key Analysis
1. **Order Priority Distribution**  
   - Categories: High, Medium, Low, Critical, Not Specified  
   - Countplot used to visualize distribution

2. **Customer Segment Distribution**  
   - Segments: Corporate, Home Office, Small Business  
   - Compared frequency of orders

3. **Shipping Mode Analysis**  
   - Regular Air, Express Air, Delivery Truck  
   - Pie chart showing % share  
   - Compared product categories by shipping mode

4. **Product Category & Sub-Category Trends**  
   - Countplot for `Office Supplies` with breakdown by sub-category  
   - Profit analysis by product category

5. **Yearly Order Distribution**  
   - Orders from 2010–2013  
   - Bar chart showing order count by year

6. **Profit Trends**  
   - Average profit per product category  
   - Visualized with bar plots

---

## 📈 Visualizations
The notebook includes:
- 📊 **Countplots** for categorical variables  
- 🥧 **Pie chart** for shipping mode distribution  
- 📉 **Bar plots** for profits & yearly order trends  
- 📦 Sub-category analysis for office supplies  

---

## 🚀 How to Run Locally
1. **Clone the Repository**
   ```bash
   git clone https://github.com/nuragajraj/Data Analysis and Visualization of Superstore Sales Data.git
   cd superstore-usa-analysis

2. **Install Dependencies**
```bash
pip install pandas numpy matplotlib seaborn openpyxl
```
3. **Run the Notebook**
```bash
jupyter notebook project1.ipynb
```
## 🧠 Insights
- Regular Air is the most used shipping method (~74%)
- Corporate segment dominates in customer orders
- Technology products generally yield higher profit margins
- Orders peaked in 2013 with over 3,000 orders
- Some sub-categories in Office Supplies have negative profit, indicating potential losses

## 📜 License
- This project is for educational purposes only.
- Feel free to fork and explore!
