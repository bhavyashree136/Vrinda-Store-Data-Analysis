# #🛍️ Vrinda Store - Sales Analysis Dashboard

Excel sales dashboard built from 2022 order data of an online fashion store.

🛠️ **Tool:** Microsoft Excel

🔑 **Keywords:** Data Cleaning • Data Analysis • Data Visualization • Dashboard • KPI Reporting • Excel Formulas • SUMIFS • COUNTIFS • E-commerce Analytics

## 🧹 Data Cleaning
- Checked 31,047 rows: no missing values, no duplicate rows, no extra spaces
- Made Age Group (`IF`) and Month (`TEXT`) columns and checked them
- Flagged one wrong size (`X`) and left it out of the size analysis
- Checked totals against the original pivot table

## 📊 Data Visualization
- One-screen dashboard with 6 KPI cards and 7 charts
- Charts: monthly sales, category, channel, top 10 states, age group, gender, order status
- Formula-driven (`SUMIFS`, `COUNTIFS`), so it updates with the data
- Works in Excel 2007 and Excel Online

## 📈 KPIs
| Total Sales | Order Lines | Units Sold | Delivered | Returned / Cancelled |
|:---:|:---:|:---:|:---:|:---:|
| ₹21.18M | 31,047 | 31,237 | 92.3% | 6.9% |

## 💡 Key Insights
- 👗 Sets are the top category (about 50% of sales)
- 🛒 Amazon is the top channel (about 36%)
- 📍 Maharashtra is the top state (about 14%)
- 👩 Women make about 64% of sales
- 📅 March is the best month

## 📁 File
- `Vrinda_Store_Sales_Dashboard.xlsx` - Excel file with the data sheet and the dashboard sheet
