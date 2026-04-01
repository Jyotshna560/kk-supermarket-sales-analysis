# 🛒 KK Supermarket Sales Analysis

## 📌 Project Overview
This project analyzes sales data from KK Supermarket’s store branches to uncover insights into what drives store performance. Using exploratory data analysis (EDA), feature engineering, and predictive modeling, the project identifies top-performing stores, efficiency metrics, and key factors influencing sales.

---

## 📊 Dataset
- **Rows**: 896  
- **Columns**: 5  
- **Features**:
  - `Store ID`: Unique identifier for each store  
  - `Store_Area`: Physical area of the store (sq. ft.)  
  - `Items_Available`: Number of items available in the store  
  - `Daily_Customer_Count`: Average daily customer visits  
  - `Store_Sales`: Daily sales revenue  

---

## 🛠️ Methodology
1. **Data Cleaning**  
   - Checked for missing values and duplicates  
   - Standardized column names  

2. **Exploratory Data Analysis (EDA)**  
   - Correlation heatmap  
   - Scatter plots (Store Area vs Sales, Items vs Customers)  
   - Distribution analysis  

3. **Feature Engineering**  
   - `Sales_per_Customer` = Store_Sales / Daily_Customer_Count  
   - `Sales_per_Item` = Store_Sales / Items_Available  

4. **Modeling**  
   - Linear Regression (baseline)  
   - Random Forest Regressor (non-linear relationships)  
   - Evaluation metrics: R², MSE  

5. **Insights & Visualization**  
   - Top 10 stores by sales  
   - Efficiency metrics (sales per customer/item)  
   - Feature importance analysis  

---

## 📈 Key Insights
- Larger store area and higher customer count generally correlate with higher sales.  
- Random Forest outperformed Linear Regression, showing non-linear relationships in the data.  
- Efficiency metrics reveal that some smaller stores achieve higher sales per customer, highlighting operational effectiveness.  
- Top-performing stores are not always the largest — customer engagement plays a critical role.  

---

## 📊 Visuals
Include screenshots of:
- Correlation heatmap  
- Scatter plots  
- Feature importance bar chart  
- Histograms of efficiency metrics  


## 📂 Repository Structure
├── supermarket_sales.csv   # Dataset
├── analysis.ipynb          # Jupyter Notebook with full workflow
├── README.md               # Project documentation
└── visuals/                # Plots and charts

## 🎯 Outcome
This project demonstrates:
- Strong EDA and visualization skills
- Ability to engineer features and build predictive models
- Clear business insights relevant to retail operations
- A portfolio-ready case study


