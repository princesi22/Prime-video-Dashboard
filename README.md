# 📺 Prime Video Content & Profit Analysis Dashboard

> Interactive Power BI dashboard analyzing Prime Video's content catalog, profitability, and strategic positioning in the streaming market.

[![Power BI](https://img.shields.io/badge/Power%20BI-Latest-yellow.svg)](https://powerbi.microsoft.com/)
[![Excel](https://img.shields.io/badge/Excel-Data%20Source-green.svg)](https://www.microsoft.com/excel)
[![DAX](https://img.shields.io/badge/DAX-Advanced-blue.svg)](https://dax.guide/)

---

## 📸 Dashboard Preview

![Prime Video Power BI Dashboard](https://github.com/princesi22/Prime-video-Dashboard/blob/main/prime%20video%20dashboard.png)

---

## 🎯 Project Overview

An end-to-end Power BI project analyzing 9,651 Prime Video titles to uncover insights into content distribution, profitability, audience targeting, and growth trends. All data cleaning, transformation, and analysis performed using Power Query and DAX.

---

## 📊 Key Performance Indicators

<div align="center">

| KPI | Value |
|-----|-------|
| **Total Profit** | $2.66 Billion |
| **Total Titles** | 9,651 |
| **Rating Categories** | 25 |
| **Total Genres** | 29 |
| **Total Directors** | 5,769 |

</div>

---

## 💡 Key Insights

### Content Distribution
- **Movies dominate** with 80% of catalog (7,700 titles)
- **Drama leads genres** followed by Action and Comedy
- **13+ rating** has highest content volume
- Balanced targeting across all age demographics

### Profitability
- **Movies:** $2.2B (83% of total profit)
- **TV Shows:** $0.5B (17% of total profit)
- Similar per-title ROI for both content types

### Growth Trends
- **Rapid expansion 2015-2020** during streaming wars
- Peak content releases between 2018-2020
- Content volume increased 400% post-2015

---

## 🛠️ Tools & Technologies

| Technology | Purpose |
|------------|---------|
| **Power BI** | Dashboard development & visualization |
| **Power Query** | Data cleaning & transformation |
| **DAX** | Business logic & calculations |
| **Excel** | Data source |

---

## 🔄 Data Processing

### Power Query Transformations
- Removed duplicates and handled missing values
- Standardized genre and rating categories
- Created calculated columns for analysis
- Optimized data model with star schema

### Sample DAX Measures
```dax
Total Profit = SUM('Prime Video'[Profit])

Total Titles = COUNTROWS('Prime Video')

Movie Count = CALCULATE(
    COUNTROWS('Prime Video'),
    'Prime Video'[Type] = "Movie"
)
```

---

## 📂 Dataset Structure

| Column | Type | Description |
|--------|------|-------------|
| Title | Text | Movie/Show name |
| Genre | Text | Content category |
| Rating | Text | Age rating (13+, 16+, 18+, ALL) |
| Release Year | Number | Year of release |
| Type | Text | Movie or TV Show |
| Director | Text | Director name |
| Profit | Currency | Revenue generated |

---

## 🚀 How to Use

### Installation
1. Clone the repository
   ```bash
   git clone https://github.com/princesi22/Prime-video-Dashboard.git
   ```

2. Open the `.pbix` file in Power BI Desktop

3. Refresh data if needed

4. Explore insights using interactive filters and slicers

---

## 🔍 Key Findings

✅ **Movie-first strategy** drives 83% of profits

✅ **Drama dominance** confirms universal appeal

✅ **400% content growth** during 2015-2020 streaming wars

✅ **Balanced audience targeting** across all age groups

✅ **5,769 directors** showing extensive creator partnerships

---

## 🎓 Learning Outcomes

**Technical Skills:**
- Advanced Power BI dashboard development
- Power Query for ETL operations
- DAX for business calculations
- Data modeling and visualization best practices

**Business Intelligence:**
- KPI definition and tracking
- Profitability analysis
- Trend identification
- Strategic insight generation

---

## 🔮 Future Enhancements

- [ ] Real-time data integration via API
- [ ] Geographic analysis with regional performance
- [ ] Predictive analytics for content success
- [ ] User ratings and engagement metrics
- [ ] Mobile-optimized layouts

---

## 👨‍💻 Author

**Prince Kumar Singh**  
*Aspiring Data Analyst | Power BI Developer*

**Skills:** Power BI, Excel, SQL, Python, Data Visualization

