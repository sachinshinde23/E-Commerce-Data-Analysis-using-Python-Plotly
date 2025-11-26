# E-Commerce-Data-Analysis-using-Python-Plotly
End-to-end E-Commerce data analysis using Python, Pandas, and Plotly. Includes data cleaning, EDA, time-series analysis, category-level insights, profit analysis, and interactive visualizations.
# 📦 E-Commerce Data Analysis Project (Python + Pandas + Plotly)

This project analyzes a real-world **E-Commerce “Superstore” dataset** using Python.  
It covers sales, profit, customer segments, product categories, and time-series patterns using Pandas and interactive Plotly visualizations.

The notebook includes complete data cleaning, feature engineering, visual analytics, and business insights.

---

# 📁 Project File
**E-Commerce Data Analysis Project.ipynb**  
(Python • Pandas • Plotly • Data Visualization)

---

# 🧹 1. Data Cleaning & Preparation

### ✔ Converted date columns  
The notebook converts the following into datetime format:
- `Order Date`
- `Ship Date`

### ✔ Added new date-based features  
To support time-series analysis:
- `Year`
- `Month`
- `Day`
- `Week Number`

### ✔ Checked dataset quality  
Performed:
- `.info()`  
- `.describe()`  
- Missing value review  

---

# 📊 2. Exploratory Data Analysis (EDA)

Notebook performs **deep analysis** in multiple dimensions:

---

## 📈 Monthly Sales Analysis
Using grouped monthly data:
- Shows seasonal trends  
- Identifies best-performing months  
- Highlights months contributing highest revenue  

**Tools used:** Pandas groupby, Plotly line charts

---

## 🛒 Sales Analysis by Category
Categories include:
- Furniture  
- Office Supplies  
- Technology  

Insights:
- Technology shows strongest sales  
- Furniture has high revenue but lower profit margins  
- Office Supplies are stable but low-profit

---

## 📦 Sales Analysis by Sub-Category
Subcategories analyzed:
- Phones  
- Chairs  
- Binders  
- Storage  
- Accessories  
- Tables  
- Machines  
- Others  

**Findings:**  
Phones & Chairs consistently dominate revenue.

---

## 💰 Monthly Profit Analysis
Profit trends reveal:
- Certain months show negative profit  
- Large discounting directly impacts profitability  
- Profit spikes during end-of-year seasons

---

## 🏷 Profit by Category
- Technology → Highest profit  
- Office Supplies → Moderate profit  
- Furniture → Lowest profit (due to high discounts, shipping cost)

---

## 🧩 Profit by Sub-Category
Profitability compared across:
- Phones  
- Accessories  
- Copiers  
- Bookcases  
- Tables  

**Key Insight:**  
Tables consistently show **negative profit** despite high sales.

---

## 👥 Sales & Profit by Customer Segment
Segments analyzed:
- Consumer  
- Corporate  
- Home Office  

**Conclusion:**  
- Consumer segment contributes maximum sales  
- Home Office segment drives highest profit margins

---

## 📉 Sales-to-Profit Ratio Analysis
- Some products have high sales but extremely low or negative profit  
- Ratio analysis helps identify loss-making product lines

---

# 📊 3. Visualizations (Plotly)

The notebook uses **interactive Plotly charts**, including:
- Line charts  
- Bar charts  
- Scatter plots  
- Category-wise drilldowns  
- Monthly trend charts  

---

# 🧠 4. Business Insights (Extracted from Your Notebook)

### 🔹 1. Technology category drives maximum profit  
### 🔹 2. Phones & Chairs are top revenue generators  
### 🔹 3. Table sub-category is *consistently loss-making*  
### 🔹 4. Consumer segment dominates sales volume  
### 🔹 5. Year-end months show seasonal peaks  
### 🔹 6. High discount items reduce overall profitability  
### 🔹 7. Some months show profit dips despite strong sales  

---

# 🎯 5. Skills Demonstrated

- Python (Pandas, NumPy)  
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis  
- Date Feature Engineering  
- Interactive Visualizations (Plotly Express, Plotly Graph Objects)  
- Business Intelligence Thinking  
- Retail/E-commerce domain analysis  

---

# 📎 6. How to Run the Project

### **Install dependencies**
```bash
pip install pandas plotly
```

### **Run Jupyter Notebook**
```bash
jupyter notebook
```

Open:  
`E-Commerce Data Analysis Project.ipynb`

---

# 👤 Author  
**Sachin Shinde**  
Data Analyst | Python | SQL | Excel | Power BI  
GitHub: https://github.com/sachinshinde23

---

# 📜 License  
This project is open-source under the MIT License.

