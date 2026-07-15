# Blinkit Sales & Outlet Performance Dashboard

An interactive **Power BI** dashboard built on Blinkit's grocery sales data, designed to analyze outlet performance, product category trends, and customer ratings across India.


## 📊 Overview

This dashboard provides a single-page, end-to-end view of Blinkit's grocery outlet data — covering total sales, item-level performance, outlet characteristics, and regional/tier-wise trends. It is designed for quick, filter-driven exploration by business stakeholders.

## 🧩 Key Features

### KPI Summary Cards
- **Total Sales:** $1.20M
- **Average Sales:** $141
- **Number of Items:** 8,523
- **Average Rating:** 3.9 ⭐

### Filter Panel
Located on the left sidebar, allowing users to slice the entire report by:
- **Outlet Location Type**
- **Outlet Size**
- **Item Type**

### Visuals Included

| Visual | Description |
|---|---|
| **Outlet Establishment** | Line chart showing sales trend by outlet establishment year (2012–2022), highlighting a peak in 2018 ($205K). |
| **Item Type Analysis** | Toggleable bar chart (tabs: Total Sales, Average Sales, Number of Items, Average Rating) broken down by grocery item category (Fruits & Veg, Snacks, Household, Frozen, Dairy, etc.). |
| **Fat Content Breakdown** | Donut chart segmenting sales by fat content — Low Fat, Regular, LF, reg. |
| **Fat by Outlet Tier** | Horizontal bar chart comparing fat content distribution across Tier 1, 2, and 3 outlets. |
| **Outlet Size** | Donut chart of sales split across Small, Medium, and High outlet sizes. |
| **Outlet Location (Tier-wise)** | Bar chart comparing performance across Tier 1 ($336.40K), Tier 2 ($393.15K), and Tier 3 ($472.13K). |
| **Outlet Type Table** | Detailed matrix comparing Total Sales, Number of Items, Average Sales, Average Rating, and Item Visibility across Supermarket Type1, Type2, Type3, and Grocery Store formats. |

## 🗂️ Data Model

The report is built on two core tables:
- **BlinkIT Grocery Data** — transactional-level data (item type, fat content, outlet details, sales, ratings, visibility).
- **Metrics** — a measures table used to dynamically toggle between Total Sales, Average Sales, Number of Items, and Average Rating within the same visual using field parameters.

## 🛠️ Tools Used

- **Power BI Desktop**
- DAX for calculated measures (Total Sales, Average Sales, Average Rating, etc.)
- Field parameters for dynamic visual switching
- Drill-through configured (currently set to off, with "Keep all filters" enabled)

## 📁 Repository Structure

```
├── Blinkit Dashboard.pbix     # Power BI report file
├── data/                      # Source dataset (if included)
├── screenshots/                # Dashboard preview images
└── README.md                  # Project documentation
```

## 🚀 Getting Started

1. Clone or download this repository.
2. Open `Blinkit Dashboard.pbix` in **Power BI Desktop** (2023 or later recommended).
3. If prompted, update the data source path to point to your local copy of the dataset.
4. Click **Refresh** to load the latest data.
5. Use the filter panel on the left to explore sales by Outlet Location Type, Outlet Size, and Item Type.

## 📌 Key Insights

- Tier 3 outlets generate the highest total sales ($472.13K), followed by Tier 2 and Tier 1.
- Supermarket Type1 leads in total sales ($787.55K) and item count (5,577) among outlet types.
- Sales peaked for outlets established around 2018 ($205K).
- Average customer rating remains consistently around 3.9–3.93 across most outlet tiers and item types.


## 🤝 Contributing

Contributions, suggestions, and feedback are welcome. Feel free to open an issue or submit a pull request.

## 📄 License

This project is available under the MIT License. Feel free to use and adapt it for your own learning or portfolio purposes.

---

*Built with ❤️ using Power BI to explore Blinkit's grocery outlet performance data.*
