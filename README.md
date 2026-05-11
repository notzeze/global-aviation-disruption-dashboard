# ✈️ Global Aviation Disruption Dashboard
**Power BI | Data Visualization | Geopolitical Impact Analysis**

---

## 📌 Project Overview
This Power BI project analyzes the operational and financial impact of geopolitical 
events (specifically the US–Iran conflict) on global airline operations. 
The dataset was sourced from [Kaggle](https://www.kaggle.com) and covers 
flight disruptions across major international airlines and regions.

---

## Dashboard Pages

### 1. Global Aviation Disruption Dashboard (Overview)
The main landing page providing a high-level summary of disruptions:
- **20K** Total Flights Affected | **178K** Passengers Affected
- **$8.65bn** Total Airline Loss | **$439.23K** Loss per Flight
- **3.45%** Cancellation Rate | **2.77** Avg Delay Hours
- Time-series chart of flights cancelled vs disrupted (March trend)
- Geographical map of disruption hotspots
- Interactive slicers: Airline, Region, and Date range

![Dashboard 1](screenshots/dashboard_overview.png)

---

### 2. Disruption Overview & Regional Insights
Breaks down severity and regional impact:
- Stacked bar chart showing **severity distribution** (Critical / High / Moderate / Low / Severe) across regions
- **Middle East** dominates with **16.6K** disrupted flights, followed by South Asia (1.3K) and Europe (0.7K)
- Drill-through enabled → links to **Disruption Patterns & Regional Analysis**

![Dashboard 2](screenshots/disruption_regional.png)

---

### 3. Impact of Disruptions on Airline Loss
Deep-dive into financial losses by airline:
- **Saudi Arabian Airlines** leads with **$0.94bn** loss, followed by Etihad ($0.88bn) and flydubai ($0.86bn)
- **Flag carriers** account for **$5.6bn** out of the total $8.65bn loss
- Scatter plot: Disruptions vs Financial Loss (airline-wise)
- **Malaysia Airlines** incurred the highest additional fuel cost at **$176K**

![Dashboard 3](screenshots/airline_loss.png)

---

### 4. Global Aviation Disruption & Impact Analysis
Focuses on route changes and operational inefficiencies:
- **20.69%** average distance increase due to rerouting
- **754** total rerouted flights | **$3.21M** extra fuel cost
- **Malaysia Airlines** had the highest additional distance at **34K km**
- Route-level breakdown: Abu Dhabi, London, Sydney, Washington origins
- Strong positive correlation between additional distance and fuel cost

![Dashboard 4](screenshots/disruption_impact.png)

---

### 5. Disruption Patterns & Regional Analysis *(Drillthrough Page)*
Accessible via drill-through from Dashboard 2:
- **Iran** (2.5K), **Saudi Arabia** (2.1K), and **Iraq** (2.0K) are the top disrupted countries
- **Mehrabad International Airport** is the most disrupted with **1.8K** affected flights
- Disruption types: **Security (30%)** is the leading cause, followed by Closure (26%)
- Severity distribution: **High** (9 events), **Critical** and **Medium** (7 each)

![Dashboard 5](screenshots/disruption_patterns.png)

---

## 🗂️ Dataset
| Field | Details |
|-------|---------|
| Source | Kaggle — US–Iran War Airline Disruption |
| Format | Excel (.xlsx) |
| Coverage | December 2025 – March 2026 |
| Airlines | 30+ international carriers |
| Regions | Middle East, South Asia, Europe, North Africa, Asia Pacific |

---

## 🛠️ Tools & Techniques Used
- **Power BI Desktop** — Dashboard design & publishing
- **DAX** — Custom measures (cancellation rate, revenue loss %, avg delay)
- **Power Query** — Data cleaning and transformation
- **Excel** — Raw data source
- Features: Drill-through pages, slicers, dynamic KPI cards, custom tooltips

---

## 📁 Repository Structure
```
├── Airline_Disruption_Data.xlsx   # Raw dataset
├── Aviation_Disruption.pbix       # Power BI project file
├── Dashboard Screenshots/
│   ├── 1. Executive Overview.jpg
│   ├── 2. Disruption Analysis.jpg
│   ├── 3. Airline Impact & Financial Analysis.jpg
│   ├── 4. Route & Efficiency Analysis.jpg
│   └── 5. Region Drillthrough.jpg
└── README.md
```

---

## 💡 Key Insights
1. The **Middle East** accounts for over **87%** of all flight disruptions globally
2. **Security threats** are the #1 cause of disruptions (30%), indicating geopolitical sensitivity
3. Flag carriers bear the brunt financially — **$5.6bn out of $8.65bn** total losses
4. Route rerouting increased average flight distances by **~21%**, directly inflating fuel costs
5. **Mehrabad (Iran) and Muscat (Oman)** airports face the highest operational pressure

---

## 👤 Author
**Shruti Daw**  
Data Analytics | Power BI | Data Visualization  
[LinkedIn](www.linkedin.com/in/shruti-daw) 
