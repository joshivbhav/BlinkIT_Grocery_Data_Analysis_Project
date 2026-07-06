# BlinkIT Grocery Data Analysis 🛒📊

An Excel-based data analysis and dashboard project exploring sales performance across BlinkIT's grocery outlets. The workbook transforms raw transactional data into an interactive dashboard with KPIs, pivot tables, and visualizations to uncover trends in sales, outlet performance, and product categories.

## 📁 Project Overview

This project analyzes item- and outlet-level sales data for a grocery retail chain to answer key business questions such as:

- What is the total and average sales performance across the business?
- How do sales vary by fat content, item type, and outlet characteristics?
- Which outlet types, sizes, and locations drive the most revenue?
- How has performance trended by outlet establishment year?
- How are customer ratings distributed across items and outlets?

## 📂 File Structure

The workbook (`BlinkIT_Grocery_Data_Analysis_Project.xlsx`) contains three sheets:

| Sheet | Description |
|---|---|
| **BlinkIT Grocery Data** | Raw dataset — 8,500+ item-level records with 13 fields |
| **Sheets Design** | Calculation layer — KPI summaries and 10 pivot tables powering the dashboard |
| **Dashboard** | Interactive dashboard with charts and slicers for dynamic filtering |

## 🧾 Dataset Fields

| Column | Description |
|---|---|
| Item Fat Content | Low Fat / Regular |
| Sr N.o | Record serial number |
| Item Identifier | Unique item code |
| Item Type | Product category (e.g., Snack Foods, Dairy, Frozen Foods) |
| Outlet Establishment Year | Year the outlet was opened |
| Outlet Identifier | Unique outlet code |
| Outlet Location Type | Tier 1 / Tier 2 / Tier 3 city classification |
| Outlet Size | Small / Medium / High |
| Outlet Type | Grocery Store / Supermarket Type1 / Type2 / Type3 |
| Item Visibility | Shelf visibility percentage |
| Item Weight | Item weight |
| Sales | Sales value |
| Rating | Customer rating |

## 📈 Key Metrics (KPIs)
<img width="1884" height="699" alt="Screenshot 2026-07-06 223432" src="https://github.com/user-attachments/assets/73cc6f91-477a-4a35-8287-f50c7edaa6ce" />

- **Total Sales:** ₹12,01,681.49
- **Average Sales:** ₹140.99
- **Number of Items:** 8,523
- **Average Rating:** 3.97

## 📊 Dashboard & Analysis Highlights
<img width="1919" height="1075" alt="Screenshot 2026-07-06 213008" src="https://github.com/user-attachments/assets/6e877954-1ab4-40f8-9a1f-d8082237faba" />

The **Sheets Design** sheet computes 10 pivot tables that feed the dashboard, including:

- **Total Sales by Fat Content** — Low Fat vs. Regular
- **Fat Content by Outlet Tier** — cross-tab of sales across Tier 1/2/3
- **Sales by Outlet Size** — High / Medium / Small
- **Sales by Outlet Location Tier**
- **Total Sales by Item Type** — ranked from Seafood (lowest) to Fruits & Vegetables (highest)
- **Total Sales by Outlet Establishment Year**
- **All Metrics by Outlet Type** — Sum, Average, and Count of Sales across Grocery Store and Supermarket formats

The **Dashboard** sheet visualizes these pivots using **16 charts** and **3 interactive slicers**, allowing users to filter the dashboard dynamically by outlet type, location, and other attributes.

## 🛠️ Tools & Techniques Used

- Microsoft Excel
- Pivot Tables & Pivot Charts
- Slicers for interactive filtering
- KPI summary cards
- Data cleaning and categorization

## 🚀 How to Use

1. Download `BlinkIT_Grocery_Data_Analysis_Project.xlsx`
2. Open in Microsoft Excel (2016 or later recommended for slicer/chart support)
3. Navigate to the **Dashboard** sheet to explore the interactive visualizations
4. Use the slicers to filter data by outlet type, location tier, or other attributes
5. Refer to the **Sheets Design** sheet to review the underlying pivot table calculations

## 🔍 Key Insights

- **Supermarket Type1** outlets drive the majority of total sales (~₹7.88L), far outpacing other formats.
- **Fruits and Vegetables** and **Snack Foods** are the top-performing item categories by sales.
- **Tier 3** locations generate the highest sales among location tiers, followed closely by Tier 2.
- **Low Fat** items outsell **Regular** items across nearly every outlet tier.
- Average customer ratings remain consistent (~3.9–4.0) across outlet types, suggesting stable customer satisfaction regardless of format.

## 📌 Future Improvements

- Add year-over-year trend analysis as more data becomes available
- Incorporate profit margin data alongside sales for deeper profitability analysis
- Automate refresh with Power Query for recurring data updates
- Migrate dashboard to Power BI for enhanced interactivity and sharing

## 📄 License

This project is for educational and portfolio purposes.

---

*If you find this project useful, feel free to ⭐ star the repo!*
