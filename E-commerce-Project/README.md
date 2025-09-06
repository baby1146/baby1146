# 🛋️ E-commerce Furniture Sales Analysis

## 📌 Objective
Analyze e-commerce furniture sales data to uncover trends, pricing strategies, and customer preferences. Provide insights to optimize pricing, forecast demand, and improve overall sales performance.

---

## 🛠 Tech Stack
- **Language**: Python  
- **Libraries**: pandas, NumPy, matplotlib, seaborn  
- **Dataset**: 2,000+ furniture product entries scraped from AliExpress (via Kaggle)  

---

## 📂 Project Workflow

### 1. Data Collection
- Imported dataset from Kaggle (`e-commerce-furniture-dataset-2024`).  
- Dataset includes product details, pricing, sales, and shipping information.  

### 2. Data Cleaning & Preprocessing
- Handled missing values (filled missing prices & shipping costs).  
- Converted `price`, `originalPrice`, and `Shipping Cost` columns from string to float.  
- Standardized column names (e.g., *quantity sold*, *shipping cost*).  
- Created new calculated fields:  
  - `total revenue`  
  - `gross profit` & `gross profit margin`  
  - `net profit` & `net profit margin`  
  - `discount percentage`, `discount flag`, `loss flag`  

### 3. Exploratory Data Analysis (EDA)
- Identified top-selling products and categories.  
- Analyzed pricing distribution and discount impact.  
- Segmented products by type and brand.  
- Created profit/loss flags to measure financial performance.  

### 4. Data Visualization
- **Bar charts**: Top-selling products, revenue by category, loss-making vs profitable items.  
- **Histograms**: Price and sales distribution.  
- **Pie charts**: Discounted vs. non-discounted items.  
- **Scatter plots**: Cost vs. revenue trends.  

---

## 📊 Key Insights

- **Top Performers**: Chairs and tables generated the highest revenue and profit.  
- **Customer Behavior**: Most customers prefer **low-priced furniture**.  
- **Pareto Effect**: A few products contributed to the majority of sales (80/20 rule).  
- **Profitability**: Tables and chairs remained profitable, while sofas and beds often incurred losses.  
- **Discounts**: 
  - Discounts boosted sales volume but eroded profitability when too high.  
  - Products with **moderate discounts** (< $10,000) stayed profitable.  
- **Loss-Making Products**: Minimal share, showing efficient product range management.  

---

## ✅ Conclusion
The analysis highlights the importance of:
- Focusing on **high-performing products** (tables, chairs).  
- Maintaining **competitive yet profitable pricing**.  
- Managing **discounts strategically** to avoid losses.  
- Using sales insights to guide **marketing and inventory decisions**.  

By refining these strategies, the business can improve **profitability** and sustain **long-term growth**.  

---

## 📸 Sample Visualizations
*(Add images here by saving charts as `.png` and uploading them in the repo)*

- Top 10 Best-Selling Products  
- Price Distribution  
- Revenue vs. Gross Profit by Product Category  
- Discounted vs. Non-Discounted Items  

---

## 👩‍💻 Author
Developed by **Baby Venkatachalam**  
- [LinkedIn](#)  
- [Email](mailto:youremail@example.com)
