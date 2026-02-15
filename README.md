# 📊 Excel Basics: Sales Data Analysis

**My first data analytics project! Learned core Excel formulas (SUM, AVERAGE, COUNT, MAX, MIN), percentage calculations, data sorting, and visualization.**

## 📋 Dataset
Monthly sales data for 10 products (Laptop, Mouse, Keyboard, etc.). Raw data includes Date, Product, Units Sold, Unit Price.

**Key Insights:**
- **Total Sales**: ₹5,60,000
<img width="108" height="42" alt="image" src="https://github.com/user-attachments/assets/4f2e5a1e-7317-4816-9075-fe2084b866d7" />

- **Average Units Sold**: 16.5 per product
- **Top Performer**: Laptop (55% of total sales, ₹2,50,000)
- **Bottom Performer**: Cable (2% of total sales, ₹8,000)

![Dashboard Screenshot](dashboard-screenshot.png)

## 🧮 Formulas Used

| Calculation | Formula | Cell Reference | Result |
|-------------|---------|----------------|--------|
| Total Sales | `=SUM(E2:E11)` | G2 | ₹5,60,000 |
| Average Units | `=AVERAGE(C2:C11)` | G3 | 16.5 |
| Count Products | `=COUNTA(B2:B11)` | G4 | 10 |
| Max Sales | `=MAX(E2:E11)` | G5 | ₹2,50,000 |
| Min Sales | `=MIN(E2:E11)` | G6 | ₹8,000 |
| Sales % | `=(E2/$G$2)*100` | H2 (copied down) | 45% |

## 📈 Visualization
3D Pie Chart shows **product-wise sales distribution**. Laptop dominates at 55%.

## 🔄 Steps I Followed
1. **Entered raw sales data** (A1:E11)
2. **Calculated Total Sales** column: `=Units*Price`
3. **Summary statistics** using SUM/AVERAGE/COUNT/MAX/MIN
4. **Percentage share**: Each product's % of total sales
5. **Sorted** table by Total Sales (descending)
6. **Created 3D Pie Chart** for visual distribution
7. **Formatted** numbers as Currency (₹) and Percentages

## 💾 Files
- `Excel_Basics_Sales_Analysis.xlsx` - Complete workbook with formulas & chart
- `dashboard-screenshot.png` - Final dashboard view

## 🎯 What I Learned
- Basic Excel formulas for data aggregation
- Absolute references (`$G$2`) for consistent calculations
- Percentage calculations for business insights
- Data visualization with charts
- Professional number formatting

**Next**: Python Pandas for same analysis!

---
*Built by Zikra | Data Analytics Learner | Feb 2026*

