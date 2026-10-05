# Monthly Sales Performance & Analytics Dashboard of Coffee Shop

##  Summary
This project provides an end-to-end sales performance analysis for a coffee and beverage retail business operating across three key locations: **Kanhangad**, **Calicut**, and **Kasaragod**. Using interactive Excel dashboards and dynamic data modeling, the report tracks monthly revenue trends, hourly customer transaction spikes, category-level product performances, and location-specific consumption patterns.

---

## Dashboard Overview & Visualizations

### 1. Master Dashboard (All Locations)
![Master Sales Dashboard](coffee_Screenshorts/Screenshot%20unfilter.png)

### 2. Location Filters Based
| Kanhangad Filter | Calicut Filter | Kasaragod Filter |
| :---: | :---: | :---: |
| ![Kanhangad](coffee_Screenshorts/Screenshot%20kanhn.png) | ![Calicut](coffee_Screenshorts/Screenshot%20cali.png) | ![Kasaragod](coffee_Screenshorts/Screenshot%20kasa.png) |

---

## Data Pipeline & Analytics Process

```
+------------------+     +-----------------------+     +-----------------------+     +------------------------+
|  Raw Sales Data  | --> | Data Cleaning & Prep  | --> | Data Modeling & Caches| --> | (Power Query / Formulas)| --> | (PivotTables & Slicers)| --> | Interactive Dashboard  |
+------------------+     +-----------------------+     +-----------------------+     +------------------------+
```

### The Raw Data-Set
![Raw Data Sample](coffee_Screenshorts/Screenshot%20Raw_data.png)

### Process:
1. **Data Cleaning & Preprocessing:**

2. **Data Modeling:**
  
3. **Formula Logic & Dynamic Intersections:**

4. **Dynamic Dashboard Elements:**
   
---

## Key Business Insights

### 1. Overall Business Performance
* **Steady Growth Trajectory:** Month-over-month revenue and transaction counts demonstrate consistent growth from February through June across all branches.
* **Volume Anchors:** **Coffee** (58,416 transactions) and **Tea** (45,449 transactions) drive over **70% of total company transactions**.
* **Primary Commute Rush:** Across all stores, peak customer volume surges sharply between **8:00 AM and 10:00 AM**, stabilizing through the afternoon before dropping off after 7:00 PM.

### 2. Store Location Deep-Dive

| Metric / Dimension | Kanhangad | Calicut | Kasaragod |
| :--- | :--- | :--- | :--- |
| **Top Revenue Driver** | Brewed Chai Tea (₹27,427.90) | Barista Espresso (₹32,420.20) | Barista Espresso (₹31,051.00) |
| **Top Food Category** | Bakery (7,289 items) | Bakery (7,617 items) | Bakery (7,890 items) |
| **Peak Rush Windows** | Extended (8 AM – 10 AM) | Steep Spike (8 AM – 10 AM) | Steady Morning to Midday |
| **Add-On Demand** | Moderate Flavors (1,490) | High Flavors (2,370) | Highest Flavors (2,930) |

---

## Strategic Recommendations

1. **Labor & Staffing Optimization:**
   * Allocate peak barista staffing between **8:00 AM and 10:00 AM** to minimize queue times during the morning rush.
   * Shift operational hours or reduce late-evening staffing after **7:00 PM** where transaction volume drops under 1,000 units.

2. **Targeted Cross-Selling & Combos:**
   * **Kanhangad:** Create specialized "Chai & Pastry" breakfast combos to capitalize on local tea preferences.
   * **Kasaragod:** Leverage high flavor syrup customization (2,930 transactions) by offering premium flavor add-ons with espresso and bakery items.

---
