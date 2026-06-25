# BMW Global Sales Performance Dashboard (2010–2024)

**Godfrey M. Kanotunga** | MSc in Applied Data Science | Clarkson University

An interactive finance dashboard analyzing BMW vehicle sales performance across global regions from 2010 to 2024, covering pricing, sales volume, fuel type mix, and regional trends.

> ⚠️ **Note:** This dashboard uses a **synthetic dataset** generated for analytical demonstration purposes. Revenue and volume figures do not reflect actual BMW AG financial results.

---

## Live Dashboard

🔗 [View Interactive Dashboard](https://godfreykanotunga.github.io/Tableau-Dashboard/bmw_dashboard.html)

---

## Dashboard Sections

| Section | Description |
|---|---|
| KPI Cards | Total units, avg price, top region, top model, EV+Hybrid share |
| Sales Trend | Annual volume by fuel type (2010–2024) with interactive filter |
| Revenue by Region | Ranked bar table across 6 global markets |
| Fuel Type Mix | Powertrain revenue share donut chart |
| Revenue by Model | Ranked horizontal bar across 11 BMW models |
| Avg Price by Model | Mean listing price comparison |
| Color Preference | Consumer color distribution |
| Transmission Split | Automatic vs Manual breakdown |

---

## Dataset

50,000 synthetic BMW vehicle sales records (2010–2024):

| Feature | Description |
|---|---|
| Model | BMW model (3 Series, 5 Series, 7 Series, X1, X3, X5, X6, M3, M5, i3, i8) |
| Year | 2010–2024 |
| Region | Asia, Europe, North America, Middle East, South America, Africa |
| Fuel Type | Petrol, Diesel, Hybrid, Electric |
| Transmission | Automatic / Manual |
| Price (USD) | $30,000–$120,000 |
| Sales Volume | Units per transaction |
| Color | Black, Blue, Grey, Red, Silver, White |

---

## Tools

`Chart.js` · `HTML/CSS` · `Python (pandas)` · `Tableau Desktop` · `Microsoft Excel`

---

## Files

```
Tableau-Dashboard/
├── bmw_dashboard.html          # Interactive web dashboard
├── bmw-sales/
│   ├── BMW Global and Regional Sales Dashboard.twbx   # Tableau workbook
│   ├── BMW sales data (2010-2024).xlsx                # Source dataset
│   └── Updated BMW Global Sales Performance Dashboard Project.pdf
└── README.md
```

---

## Running Locally

Open `bmw_dashboard.html` in any modern browser — no installation required.
