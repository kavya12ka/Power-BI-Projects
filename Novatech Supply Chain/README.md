# 🚚 NovaTech Supply Chain Control Tower — Power BI Dashboard

An interactive Power BI dashboard that gives supply chain managers a single view of delivery reliability and inventory health for **NovaTech**, covering **1,800 orders, 8 suppliers and 5 regions from January to August 2026**.

![Dashboard preview](./images/dashboard.png)
<!-- Add a screenshot of the dashboard at images/dashboard.png -->

---

## 🎯 Business Problem

Supply chain teams need to know quickly whether orders arrive on time and in full, which suppliers and regions are falling behind, and where stock is running out or piling up. This dashboard answers questions such as:

- Are we delivering orders **on time and in full (OTIF)**, and how does it vary by region and supplier?
- Which **suppliers perform worst** and need attention?
- Which **product categories** suffer the most **stockouts**?
- How efficiently is inventory moving (**inventory turns** and **days of inventory**)?
- How do fill rate, OTIF and stockouts compare across every **category and region** combination?

## 📊 Dashboard Overview

The report is a single 1920 × 1080 page titled **NovaTech Supply Chain Control Tower**.

**KPI cards** (colour-coded On Target / Watch / Critical)

| KPI | What it tracks |
|---|---|
| OTIF % | Share of orders delivered on time and in full |
| Fill Rate % | Share of ordered quantity that was fulfilled |
| Stockout % | Share of cases where stock was unavailable |
| Inventory Turns | How many times inventory is sold and replaced |
| Days Inventory | How many days current stock would last |

**Visuals**

| Visual | Purpose |
|---|---|
| OTIF % by Region (bar chart) | Compare delivery reliability across the 5 regions |
| OTIF % by Supplier — worst first (bar chart) | Spot the weakest of the 8 suppliers |
| Stockout % by Category (column chart) | Find categories with the most stockouts |
| Inventory Value by Category (column chart) | See where inventory value is concentrated |
| Category × Region matrix | Average inventory units, fill rate, OTIF %, stockout % and order quantity side by side |

**Interactivity**
- **Slicers:** Region, Category, Supplier, and Month
- **Drillthrough** on Category for a focused view
- Conditional colour coding (green / amber / red) to highlight KPIs that need attention

## 🔎 Key Insights

> Replace the placeholders below with what you see in your dashboard.

- **Overall OTIF:** [add value and what it means]
- **Weakest supplier(s):** [add supplier names and their OTIF %]
- **Best and worst regions:** [add region names and OTIF %]
- **Highest-stockout category:** [add category and stockout %]
- **Recommendation:** [add one action, for example renegotiate delivery terms with the lowest-OTIF supplier]

## 🗂 Dataset

- **Table:** `NovaTech_Supply_Chain_Analytics_Dataset`
- **Scope:** 1,800 orders · 8 suppliers · 5 regions · Jan – Aug 2026
- **Fields used:** Region, Category, Supplier, Month, Order Qty, plus delivery and inventory fields feeding the measures
- **Measures (DAX):** OTIF %, Fill Rate %, Stockout %, Inventory Turns, Days Inventory, Inventory Value, Average Inventory Units

## 🛠 Tools

`Power BI Desktop` · `DAX` · `Data Modeling` · `Data Visualization` · `Conditional Formatting` · `Drillthrough`

## 🚀 How to Use

1. Download `SupplychainPowerBI_Kavya_Cohort148.pbix` from this repository.
2. Open it in **Power BI Desktop** (free download from Microsoft).
3. Use the **Region, Category, Supplier and Month** slicers to filter the KPIs and charts.
4. Right-click a category to use **drillthrough**.

## 📁 Repository Structure

```
.
├── SupplychainPowerBI_Kavya_Cohort148.pbix   # Power BI report
├── images/
│   └── dashboard.png                          # Dashboard screenshot
└── README.md
```

## 👤 Author

**Kavya K Vinay** — Data Analyst | Data Scientist | AI/ML Engineer
[GitHub](https://github.com/kavya12ka) · [LinkedIn](https://www.linkedin.com/in/kavya-k-v)
