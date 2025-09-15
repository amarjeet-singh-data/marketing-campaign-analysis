# 📊 Marketing Campaign Performance Dashboard  

---

## 🟦 1. Overview  
- This project analyzes customer response data from a marketing campaign to evaluate performance across **demographics, income groups, product categories, and channels**.  
- Using **Excel (Pivot Tables, KPIs, and Dashboard design)**, the project delivers key insights that highlight customer behavior and campaign effectiveness.  

---

## 🟥 2. Problem  
The company runs multiple marketing campaigns but struggles to:  
- Identify which **age group** and **income segment** responds best.  
- Understand which **product categories** drive the highest responses.  
- Compare **customer purchase behavior** across sales channels.  
- Measure the **overall campaign effectiveness** with clear KPIs.  

---

## 🟨 3. Solution  
An **interactive Excel dashboard** was developed, supported by pivot tables and KPIs. It provides:  
- 📌 A snapshot of campaign performance (response rate, top customer segments, and top products).  
- 📌 Visualized comparisons of customer responses across **age, income, and product categories**.  
- 📌 Channel-wise purchase analysis to evaluate **buying patterns of responders vs non-responders**.  

---

## 🟩 4. Details  

### 🔹 Data Preparation Highlights  
- Created **Age** field from Birth Year, cleaned unrealistic values (e.g., ages >100), and grouped customers into **Age Groups**.  
- Cleaned and standardized **Income** field — handled blanks and outliers by **median imputation & capping**; then created **Income Groups**.  
- Used **Python (pandas in Jupyter Notebook)** to reshape subsets of data:  
  - Converted product purchase columns into a **long format** for category-wise response analysis.  
  - Transformed channel purchase data (Web, Catalog, Store) into **long format** for comparison.  
- Exported reshaped datasets back to Excel for pivot tables, KPIs, and dashboard design.  
  

### 🔹 Key Pivot Table Findings  
- **Age Group Response:**  
  - `<30` had the highest response rate (**16.3%**) compared to ~14–15% for older groups.  

- **Income Group Response:**  
  - **High-income customers** responded significantly better (**28%**) vs Medium (**11.6%**) and Low (**10%**).  

- **Product Category Response:**  
  - **Fruits** and **Sweets** performed best (**16% each**) followed by **Fish (15.6%)** and **Wine (15%)**.  

- **Channel Purchases:**  
  - Responders purchase **more across all channels**, with **Stores leading** (6.1 avg purchases vs 5.7 for non-responders).  


### 🔹 Dashboard KPIs  
- 📊 Overall Response Rate: **14.9%**  
- 👥 Best Performing Age Group: **<30**  
- 💰 Best Performing Income Group: **High**  
- 🏆 Top Spending Product: **Wine**

  <img width="1003" height="883" alt="Screenshot 2025-09-15 162410" src="https://github.com/user-attachments/assets/ca7a0b21-3264-4e2c-89c4-0aa02c333686" />

---

## 🟦 5. Recommended Actions  
1. 🎯 Focus campaigns on **high-income customers** — they respond nearly **3x more** than others, making them the most profitable target group.  
2. 👥 Engage **younger customers (<30 years)** with personalized offers to build **long-term loyalty early**.  
3. 🛒 Promote **high-performing products (Fruits, Sweets, Wine)** through **store + online channels** to maximize sales impact.

---

## 📂 Repository Content  

- **Marketing_Campaign_Performance.xlsx**  
  Main Excel file containing:  
  - `Raw_Data` → Original dataset.  
  - `Prep_Data` → Cleaned dataset with derived fields (Age, Age Groups, Income Groups, etc.).  
  - `Product_Category` → Long-format product data (reshaped using Python).  
  - `Channels` → Long-format channel data (reshaped using Python).  
  - `Pivot_Tables` → Supporting pivot tables used for analysis.  
  - `KPIs` → Calculated KPI values.  
  - `Dashboard` → Final interactive Excel dashboard.  

- **notebooks/**  
  - `data_preparation.ipynb` → Jupyter Notebook used to reshape product and channel data into long format (exported back into the Excel file).  

- **images/**  
  - `dashboard.png` → Screenshot of the finalized Excel dashboard.  

- **README.md**  
  - Executive summary (overview, problem, solution, details, actions), project insights, and repo structure.  


