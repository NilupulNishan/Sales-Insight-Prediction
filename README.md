# Sales-Insight-Prediction 📺 [Watch on Google Drive](https://drive.google.com/file/d/1Yyu3axN7M86ODDZdwHeKAuPi0AvUvlpd/view?usp=sharing)


**A Data Mining and Business Intelligence project**  
Developed as part of the ICT 333: Data Mining and Data Warehousing course  
**Author:** K. A. N. N. Kodikara

---

## Project Summary

This project explores the application of data mining techniques on retail sales data to extract insights, identify sales patterns, segment customers, and build predictive models. The final outcome is delivered through an interactive Power BI dashboard, offering stakeholders a powerful tool to make data-driven decisions.

---

## Objectives

- Analyze sales trends across time, region, and product categories  
- Evaluate the impact of discounting on profitability  
- Perform customer segmentation using clustering techniques  
- Build predictive models to forecast future sales 
- Develop a professional and interactive dashboard for business users

---

## Dataset

- **Source:** Kaggle – Superstore Sales Dataset [Download the original dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

- **Records:** 9,994 transactions  
- **Features:** 21 columns including:
  - Temporal: `Order Date`, `Ship Date`
  - Financial: `Sales`, `Profit`, `Discount`, `Profit Margin`
  - Categorical: `Category`, `Sub-Category`, `Region`, `Ship Mode`
  - Customer info: `Customer ID`, `Segment`, `State`

---

## Tools & Technologies

| Tool/Library       | Purpose                            |
|--------------------|------------------------------------|
| **Python (Colab)** | Data cleaning, EDA, ML modeling    |
| **Pandas/Seaborn** | Data manipulation & visualization  |
| **Scikit-learn**   | Regression & clustering (K-Means)  |
| **Power BI**       | Interactive dashboard creation     |

---

## Project Highlights

### Data Analysis & EDA
- Seasonal sales peaks in **November–December**
- **Office Supplies** and **Furniture** lead in category sales
- Discounts negatively impact **Profit**

### Customer Segmentation
- Used **RFM (Recency, Frequency, Monetary)** features
- Applied **K-Means clustering** → 3 customer segments:
  - High-value, Mid-value, Low-value customers

### Predictive Modeling
- Built **Linear Regression** and **Random Forest** models  
- **Random Forest** achieved superior performance:
  - R² = **0.77**
  - MAE = **92.54**
  - MSE = **68,586**

### Dashboard Insights (Power BI)
- KPI metrics: Total Sales, Profit, Orders, Customers
- Visuals: Line charts, stacked bars, maps, scatter plots
- Filters: Region, Category, Segment, Date
- Additional pages: Product performance, shipping efficiency

---

## 📂 File Structure

