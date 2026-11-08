# 📊 Sales Performance Dashboard (Excel + VBA)

An interactive Excel dashboard for analysing e-commerce / retail B2B sales across India. It covers **8,356 orders** from **Jan 2025 to Aug 2026**, with pivot-table-driven KPIs, charts, slicers and macros, so revenue, profit, margin and target achievement can be tracked by category, region, customer, product and sales person.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `Data (5) (1).xlsm` | Macro-enabled Excel workbook containing the raw data, pivot tables and dashboard |
| `README.md` | Project documentation |

> Tip: rename the workbook to something clean such as `Sales_Dashboard.xlsm` before uploading.

---

## 🗂️ Workbook Structure

| Sheet | Purpose |
|-------|---------|
| **Sales Data** | Raw transactional data (8,356 rows × 20 columns) stored as an Excel Table |
| **Pivot Table** | 14 pivot tables that feed the dashboard visuals |
| **Dashboard** | Interactive dashboard with 17 charts, a slicer and navigation (hyperlinks / macros) |

---

## 🧾 Data Dictionary (Sales Data)

| Column | Description |
|--------|-------------|
| Order ID | Unique order identifier (e.g. `ORD00001`) |
| Order Date | Date the order was placed |
| Year / Month | Derived year and month of the order |
| Customer ID / Customer Name | Customer (marketplace or retailer) such as Amazon India, Flipkart, Myntra, Croma, Nykaa, Snapdeal, etc. |
| Product ID / Product Name | Product sold (27 unique products) |
| Category | Product category (7): Clothing, Furniture, Home & Living, Accessories, Electronics, Beauty & Care, Sports & Fitness |
| Region | Sales region (7): North, South, East, West, Central, Northeast, Others |
| State | Indian state / UT of delivery (34 values) |
| Sales Person | Sales executive (Neha, Kiran, Rahul, Priya, Ajay) |
| Order Status | Delivered, Shipped, Processing, Cancelled |
| Qty | Units ordered |
| Unit Price | Price per unit |
| Revenue | Qty × Unit Price |
| Cost | Total cost of the order |
| Profit | Profit on the order |
| Target Revenue | Revenue target set for the order |
| Margin % | Profit margin percentage |

---

## 📈 Key Metrics at a Glance

- **Total orders:** 8,356
- **Period covered:** 01 Jan 2025 – 31 Aug 2026
- **Total revenue:** ≈ ₹12.74 crore (₹127.4 million)
- **Total profit:** ≈ ₹2.27 crore (₹22.7 million)
- **Total target revenue:** ≈ ₹11.99 crore (₹119.9 million)
- **Dimensions:** 7 categories · 7 regions · 34 states · 5 sales people · 4 order statuses

*(Figures computed from the raw data in the workbook.)*

---

## ✨ Features

- 📌 KPI cards for revenue, cost, profit, margin and target vs. actual
- 📊 17 charts covering trends, category / region / state split, top customers and products, and sales-person performance
- 🔎 Interactive slicer for filtering the whole dashboard
- 🧮 14 pivot tables on a single shared pivot cache
- ⚙️ VBA macros / navigation links for a smoother user experience
- 🗺️ Geographic view of sales across Indian states and regions

---

## 🛠️ Tech Stack

- Microsoft Excel (Desktop, 2016 or later recommended)
- PivotTables & PivotCharts
- Slicers
- Excel Tables & formulas
- VBA (macro-enabled `.xlsm`)

---

## 🚀 How to Use

1. Download or clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open the `.xlsm` file in **Microsoft Excel (desktop)**.
3. Click **Enable Content / Enable Macros** when prompted.
4. Go to the **Dashboard** sheet and use the slicer to filter the data.
5. To refresh after changing data: **Data → Refresh All**.

> ⚠️ The file contains macros. Only enable them if you trust the source. Some chart types may not render in Excel for the web or in LibreOffice.

---

## 🔍 Suggested Insights to Explore

- Which categories and regions contribute the most revenue and profit?
- How is actual revenue performing against target month by month?
- Which sales people and customers drive the highest margins?
- What is the impact of cancelled orders on revenue?
- Which states are under-performing and need attention?

---

## 🔮 Future Improvements

- Add screenshots / a demo GIF of the dashboard
- Rebuild the dashboard in Power BI or Tableau for comparison
- Add Python (pandas) scripts for automated data cleaning and analysis
- Add forecasting for future revenue

---

## 📸 Screenshots

*Add a screenshot of the Dashboard sheet here:*

```
<img width="1127" height="994" alt="Screenshot 2026-11-08 124346" src="https://github.com/user-attachments/assets/45807e6a-5a11-48ec-bae7-d32ec98b5218" />

```

---

## 👤 Author

**Your Name**
GitHub: [@your-username]((https://github.com/barnabashansda01))
LinkedIn: [your-profile](linkedin.com/in/barnabas-hansda-546b65223)

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.
