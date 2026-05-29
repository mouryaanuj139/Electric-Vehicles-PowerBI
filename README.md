# ⚡ Electric Vehicles Analysis — Power BI Report

An interactive 3-page Power BI report analyzing **Electric Vehicle (EV) adoption across the United States** — covering total registrations, BEV vs. PHEV breakdown, average electric range, geographic distribution, top manufacturers, and model-level insights.

---


---

## 📸 Report Preview

<img width="899" height="495" alt="image" src="https://github.com/user-attachments/assets/402115ad-3954-4ff7-a7b2-1e0943575ec8" />

<img width="902" height="497" alt="image" src="https://github.com/user-attachments/assets/1b98a503-2286-4cc1-943a-3c6946877885" />

<img width="900" height="490" alt="image" src="https://github.com/user-attachments/assets/a1d4c56e-bce9-4976-8c53-9ec781621013" />




---

## 🎯 Objective

To build a clean, recruiter-ready Power BI report that reveals how EV adoption has grown over the years, which manufacturers and models lead the market, where EVs are concentrated geographically, and how BEV and PHEV vehicles compare in share and electric range.

---

## 📊 Report Pages & Visuals

### 📄 Dashboard 1 — Overview & Trends
| Visual | Type | Description |
|---|---|---|
| Total Vehicles | KPI Card | Total registered EVs in the dataset |
| Average Electric Range | KPI Card | Mean electric range (miles) across all vehicles |
| Total BEV Vehicles | KPI Card | Count of Battery Electric Vehicles |
| Total PHEV Vehicles | KPI Card | Count of Plug-in Hybrid Electric Vehicles |
| Total Vehicles by Model Year | Line Chart | Year-over-year EV registration growth trend |
| Top 10 Vehicle by Manufacturer | Table | Ranked list of top EV makers by volume |
| Model Year | Slicer | Filter all visuals by year of manufacture |
| Make | Slicer | Filter all visuals by manufacturer |

### 📄 Dashboard 2 — Geographic Distribution
| Visual | Type | Description |
|---|---|---|
| Total Vehicles by State | Filled Map | Choropleth map showing EV concentration across US states |
| KPI Cards (×4) | Cards | Same headline metrics — Total Vehicles, Avg Range, BEV, PHEV |
| Model Year / Make | Slicers | Cross-filter the map by year and manufacturer |

### 📄 Dashboard 3 — Model & CAFV Deep Dive
| Visual | Type | Description |
|---|---|---|
| CAFV Eligibility Breakdown | Donut Chart | Share of vehicles eligible for Clean Alternative Fuel Vehicle incentives |
| Top 10 Vehicles by Model | Table | Most popular EV models ranked by registration count |
| KPI Cards (×4) | Cards | Same headline metrics repeated for consistent navigation |
| Model Year / Make | Slicers | Filter by year and manufacturer |

> All 3 pages include a **Page Navigator** for seamless switching between dashboards.

---

## 💡 Key Insights

- 🔋 **BEVs significantly outnumber PHEVs** — fully electric vehicles dominate registered EV counts
- 📈 **EV adoption has grown sharply** year-over-year, especially in the most recent model years
- 🗺️ **Washington State** accounts for the largest concentration of EVs, reflecting strong state-level incentives
- 🏆 **Tesla** leads among manufacturers; models like the Model 3 and Model Y dominate the top 10
- 📏 **Average electric range** varies considerably across vehicle types and manufacturers
- ✅ A substantial portion of registered EVs qualify for **CAFV (Clean Alternative Fuel Vehicle)** incentives

---

## 📁 Dataset

| Field | Description |
|---|---|
| `Make` | Vehicle manufacturer (e.g., Tesla, Nissan, Chevrolet) |
| `Model` | Vehicle model name |
| `Model Year` | Year of manufacture / registration |
| `Electric Vehicle Type` | BEV (Battery Electric) or PHEV (Plug-in Hybrid) |
| `Electric Range` | All-electric range in miles |
| `Clean Alternative Fuel Vehicle (CAFV) Eligibility` | Qualifies for CAFV incentives (Yes / No / Unknown) |
| `State` | US state of registration |
| `County` | County of registration |
| `City` | City of registration |
| `Postal Code` | ZIP code |
| `Vehicle Location` | Geographic coordinates |
| `VIN (1-10)` | Partial Vehicle Identification Number (unique record key) |

- **Source:** Electric Vehicle Population Data (Washington State DOL)
- **Tool:** Microsoft Power BI Desktop

---

## 🔧 DAX Measures Built

| Measure | Description |
|---|---|
| `Total Vehicles` | `COUNT` of all registered EV records |
| `Total BEV Vehicles` | Count filtered to Battery Electric Vehicles only |
| `Total PHEV Vehicles` | Count filtered to Plug-in Hybrid Electric Vehicles only |
| `Total BEV Vehicles & % BEV` | BEV count with percentage share of total |
| `Average Electric Range` | `AVERAGE` of electric range across all records |

---

## 📂 Repository Structure

```
📁 electric-vehicles-powerbi/
├── 📊 Electric_Vehicle_Assignment.pbix   ← Power BI report file
├── 📄 README.md                           ← You are here
└── 📁 screenshots/
    ├── Dashboard 1.png
    ├── Dashboard 2.png
    └── Dashboard 3.png
```

---

## 🚀 How to Open

1. Download `Electric_Vehicle_Assignment.pbix`
2. Open with **Power BI Desktop** (free download at [powerbi.microsoft.com](https://powerbi.microsoft.com))
3. Use the slicers (Model Year, Make) and page navigator to explore all three dashboards

---

## 👤 Author

**[Anuj Mourya]**
[LinkedIn](https://www.linkedin.com/in/anujmourya/) • [GitHub](https://github.com/mouryaanuj139)
