# Adidas Sales Analysis Project
![Adidas Logo]()
---

## Project Overview
This project analyses Adidas' sales trends using **Python**. It explores various business analytics techniques, including **Exploratory Data Analysis (EDA)**, **Statistical Analysis**, **Predictive Modeling**, and **Clustering** to understand key patterns in Adidas' sales operations.

---

## Dataset Description
- **Source:** The dataset was obtained from **Kaggle** and includes Adidas' sales records.
- **Purpose:** To analyse **product preferences, customer behavior, and sales performance**.
- **Data Cleaning:** The dataset was cleaned for missing and duplicate values.
- **Key Variables:**
  - `Total Sales`
  - `Price per Unit`
  - `Sales Method` (Online/In-store)
  - `Product Type`
  - `Units Sold`

---

## Key Analyses & Methods

### 1. Exploratory Data Analysis (EDA)
- Analyzed trends in Adidas' sales over time.
- Identified key sales patterns by **sales method** and **product category**.
- Found that **online sales significantly outperform in-store sales**.

### 2. Statistical Analysis (T-Test)
- **Hypothesis Testing:** Compared total sales between **online and in-store sales methods**.
- **Result:** The test confirmed a **significant difference**, indicating online sales outperform physical stores.

### 3. Predictive Modeling
- **Regression Models:**
  - **Linear Regression** (R² = 0.95)
  - **KNN Regression** (R² = 0.99)
  - **Decision Tree Regression** (R² = 0.99) – **Best Model**
- **Findings:**
  - Decision Tree Regression provided the **highest predictive accuracy**.
  - Increasing the **price per unit decreases total sales**.

### 4. Clustering Analysis (K-Means)
- Used **K-Means Clustering** to segment customers.
- Found **three distinct clusters** based on pricing and sales volume.
- The **Elbow Method** was used to determine the optimal number of clusters.

---

## Insights & Business Recommendations
1. **Price Optimization:** Adidas should fine-tune pricing to maximize sales.  
2. **Targeted Marketing:** Use **customer segmentation** insights for personalized marketing.  
3. **Inventory Management:** Focus on **high-demand products** (Men's Street Footwear) and **optimize low-performing categories** (Men’s Apparel).  
4. **Online Sales Growth:** Increase investment in **digital marketing and e-commerce platforms**.  

---
