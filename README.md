# Kenya Youth Opportunity Dashboard 🇰🇪

**Analyzing youth employment, education access, and digital connectivity across Kenya's 42 counties to identify investment priorities for economic inclusion.**

## 📊 Project Overview

This interactive dashboard presents a data-driven analysis of three critical metrics affecting Kenya's youth:

1. **Youth Unemployment Rate (%)** - Percentage of youth (15-34) without employment
2. **Education Access (%)** - Secondary education completion rate by county
3. **Digital Connectivity (%)** - Internet access and digital literacy metrics

The analysis reveals significant regional disparities and identifies high-opportunity counties for youth economic interventions.

## 🎯 Key Findings

### National Averages (Across 42 Counties)
- **Average Youth Unemployment:** 20.2%
- **Average Education Access:** 58.4%
- **Average Internet Connectivity:** 40.5%

### Top Investment Priorities (Highest Unemployment)
1. **Mandera** (29.5% unemployment) - Urgent intervention needed
2. **Wajir** (28.9%) - Severe skills gap, lowest internet access (19%)
3. **Samburu** (28.4%) - Pastoral economy, education access at 38%

### Model Counties (Best Practices - Lowest Unemployment)
1. **Kiambu** (11.5% unemployment) - Strong education (82%), high connectivity (72%)
2. **Nairobi** (12.5%) - Urban advantage, highest internet access (78%)
3. **Nyeri** (13.2%) - Balanced development across all metrics

### Critical Insights
- **Strong Education-Employment Correlation:** Counties with higher education access show significantly lower unemployment rates
- **Digital Divide:** Northern counties (Mandera, Wajir, Isiolo) have <25% internet access, limiting job market participation
- **Regional Clustering:** Central highlands (Kiambu, Muranga, Nyeri) outperform arid regions across all metrics

## 🛠️ Technology Stack

- **Frontend:** HTML5 + Vanilla JavaScript
- **Visualization:** Plotly.js (interactive charts & choropleth maps)
- **Data:** Synthetic county-level distributions based on World Bank Kenya indicators & KNBS census patterns
- **Deployment:** GitHub Pages (static site hosting)

## 📁 File Structure

```
kenya-youth-dashboard/
├── index.html              # Main interactive dashboard
├── README.md              # Project documentation
├── DEPLOYMENT.md          # GitHub Pages setup instructions
└── LICENSE                # MIT License
```

## 🚀 Quick Start (Local)

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Wanjiru-1/kenya-youth-dashboard.git
   cd kenya-youth-dashboard
   ```

2. **Open in browser:**
   - Double-click `index.html` or
   - Use a local server: `python -m http.server 8000` then navigate to `http://localhost:8000`

3. **Interact with the dashboard:**
   - Toggle between unemployment, education, and internet metrics
   - Hover over counties for detailed data
   - Analyze correlations in the scatter plot

## 📈 Dashboard Features

### Interactive Maps
- **Choropleth visualization** showing county-level metrics
- **Bubble size** correlates with metric intensity
- **Hover tooltips** display exact values and county names
- **Metric switcher** to toggle between unemployment, education, and internet access

### Analytical Charts
- **Top 10 counties by unemployment** - Priority investment zones
- **Bottom 10 counties by unemployment** - Model cases for replication
- **Education vs. Unemployment scatter plot** - Correlation analysis with internet access overlay

### KPI Cards
- National averages for all three metrics
- Best-performing county highlight

## 💡 Use Cases for Mastercard Foundation

This analysis directly supports the **Young Africa Works** strategy by:

1. **Targeting Interventions:** Identifying counties with highest youth unemployment (Mandera, Wajir, Samburu) for skills training programs
2. **Digital Inclusion:** Highlighting regions where digital access limits job market participation
3. **Education-Employment Linkage:** Demonstrating the power of education in reducing unemployment
4. **Benchmarking:** Using high-performing counties (Kiambu, Nairobi) as models for rural/arid regions

### Recommended Actions
- **Immediate:** Target digital skills programs in Mandera, Wajir (internet <20%)
- **Near-term:** Partner with education authorities in low-access counties
- **Long-term:** Scale successful models from Kiambu/Nyeri to underperforming regions

## 📊 Data Sources & Methodology

**Data Source:** World Bank Kenya Indicators, synthetic county-level distributions based on:
- Kenya National Bureau of Statistics (KNBS) 2019 Census
- World Bank Global Financial Inclusion Index (Findex) 2021
- Kenya Bureau of Statistics Labour Force Survey patterns

**Synthetic Distribution Rationale:** While individual county employment data is not published at granular level by World Bank, these distributions reflect actual regional development patterns observed in KNBS data and are calibrated to align with known urban-rural divides and sectoral distribution across Kenya's geography.

## 🔄 Future Enhancements

- [ ] Integration with real-time KNBS APIs for live data updates
- [ ] Predictive modeling for 5-year employment projections
- [ ] Intersection analysis: Education access + digital + employment
- [ ] Skills gap mapping by sector (agriculture, tech, services)
- [ ] Mobile-responsive dashboard improvements

## 📄 License

MIT License - See LICENSE file for details

## 👩🏾‍💻 Author

**Jecinta Wanjiru Kinyanjui**  
Geospatial Data Scientist | Data Analyst | Young African Leader  
📧 jecinta.w.kinyanjui@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/jecinta-wanjiru-) | [GitHub](https://github.com/Wanjiru-1) | [RPubs](https://rpubs.com/GIS_Analyst_J)

---

**For Mastercard Foundation Review:**  
This project demonstrates data storytelling for decision-makers, geospatial analysis capabilities, and alignment with Young Africa Works objectives. It was built to identify high-impact investment zones for youth economic inclusion across Kenya.
