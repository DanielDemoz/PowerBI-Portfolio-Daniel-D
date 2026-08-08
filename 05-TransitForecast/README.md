# Transit Forecast: Ridership Forecasting & Capacity Planning Dashboard

**Category:** 🚌 Transportation & Public Services  
**Analysis Type:** Demand Forecasting | Capacity Planning | Service Optimization

---

## Overview

This transit analytics dashboard combines historical ridership data with predictive forecasting to support capacity and service planning decisions. Analyze trends by route and time of day, view forecast confidence bands, and identify routes showing strongest growth or decline. Support data-driven decisions on vehicle allocation, staffing schedules, and service expansion.

**Coverage:**
- Multiple transit lines and routes
- 7+ years historical data (2018-2025)
- Monthly and daily trend analysis
- 12-month forward forecast

---

## Why This Matters

**Business Questions This Dashboard Answers:**
- How is ridership trending by line and time of day?
- What does the forecast imply for peak capacity needs?
- Which routes show the strongest growth or decline?
- Are seasonal patterns predictable and consistent?
- Where should we add service or reduce frequency?

**Transit Operations Impact:**
Better forecasting enables:
- Accurate staffing schedules aligned with predicted demand
- Vehicle allocation matching capacity needs
- Revenue forecasting for budgeting and bonds
- Service level planning (routes, frequencies)
- Identification of growth and decline opportunities

---

## Current Ridership Status

**Historical Performance:**
- 2020: Dramatic ridership decline (COVID-19 impact)
- 2021-2024: Gradual recovery trajectory
- 2024-2025: Approaching pre-pandemic baseline levels

**Seasonal Patterns:**
- Clear winter peaks (business travel, weather-related)
- Summer dips (vacation periods, holiday breaks)
- Weekday/weekend variance (commuter vs. leisure)

**Forecast Outlook:**
- 2025: Projected continued recovery
- Seasonal adjustments built into forecast
- Confidence intervals show forecast uncertainty range
- Trend suggests normalization by mid-2025

---

## How to Use This Dashboard

### Option 1: Quick Preview (No Software Needed)
Open `Transit Visual with Forecast.pdf` to see a snapshot of trends and forecasts.

### Option 2: Interactive Analysis (Power BI Desktop)

**Setup:**
1. Download Power BI Desktop (free at powerbi.microsoft.com)
2. Open `Transit Visual with Forecast.pbix`
3. Data auto-connects to `transit_data.csv` (historical boardings and forecast data)

**Dashboard Pages:**
1. **Historical Trends** - Past performance context
   - 7-year ridership history (2018-2025)
   - Month-over-month comparison
   - Year-over-year growth rates
   - Seasonal pattern identification

2. **Forecast View** - Predictive analytics
   - 12-month forward forecast (2025-2026)
   - Forecast confidence bands (high/low range)
   - Actual vs. forecast variance
   - Trend line showing recovery pattern

3. **By Route** - Line-level analysis
   - Top performing routes
   - Routes with strongest growth
   - Routes declining and needing intervention
   - Capacity utilization by route

4. **Seasonality** - Pattern analysis
   - Peak vs. off-peak comparison
   - Monthly seasonal indices
   - Day-of-week patterns
   - Special event impacts

5. **Peak Capacity** - Planning tool
   - Peak hour ridership by route
   - Vehicle capacity requirements
   - Crowding risk identification
   - Peak vs. average capacity splits

**Navigation:**
- **Route Filter:** Select specific line or compare multiple routes
- **Time Period Selector:** Focus on specific months or years
- **Forecast Toggle:** Show/hide forecast bands and predictions
- **Hover:** See exact ridership counts and forecast values
- **Click:** Drill into route detail and driver analysis

### Example Questions You Can Answer

**"How much vehicle capacity do we need in Q2 2025?"**
→ Go to Peak Capacity page, select Q2 dates, review projected peak hour ridership

**"Which route recovered fastest from pandemic?"**
→ Filter by route, compare 2020 low to 2024-2025 recovery rate

**"Is winter demand predictable?"**
→ View Seasonality page to see winter peak pattern consistency

**"Should we expand or reduce service on Route X?"**
→ Analyze route trending and forecast; compare to capacity utilization

---

## What's Inside

**Files Included:**

| File | Purpose |
|------|---------|
| `Transit Visual with Forecast.pbix` | Interactive Power BI forecasting dashboard |
| `transit_data.csv` | Historical boardings and forecast data (2018-2025+) |
| `Transit Visual with Forecast.pdf` | Static forecast report snapshot |

---

## Key Metrics

| Metric | What It Shows | Business Use |
|--------|--------------|--------------|
| **Daily Boardings** | Passengers per day across network | Staffing and vehicle needs |
| **Monthly Ridership** | Trend tracking and seasonality | Budget planning and forecasting |
| **Peak vs. Off-Peak Split** | Demand distribution by time | Service frequency optimization |
| **Year-over-Year Growth** | Recovery and trend direction | Long-term planning |
| **Forecast Confidence** | High/low range around prediction | Risk assessment |

---

## Key Insights

**Historical Context:**
- 2020 represents unprecedented demand shock (70%+ drop)
- Recovery started mid-2020 but remained suppressed through 2021
- 2022 showed significant recovery momentum
- 2023-2024 approaching but not yet at pre-pandemic levels

**Seasonal Consistency:**
- Winter months consistently strong (December-February)
- Summer typically weaker (July-August)
- Holiday periods show distinct patterns
- Weather impacts visible in data

**Growth Opportunities:**
- Routes with consistent upward trend: Expand service
- Routes declining: Evaluate route economics and customer needs
- Off-peak capacity: Opportunity for commuter-focused scheduling

**Forecast Implications:**
- 2025 forecast suggests continued recovery
- Peak season capacity constraints possible
- Off-peak opportunities for efficient service deployment
- Seasonal predictability supports accurate planning

---

## Technical Details

**Data Model:**
- Historical boardings: Daily/monthly aggregation by route
- Forecast data: Predicted values with confidence intervals
- Seasonal decomposition: Trend, seasonal, and residual components
- External factors: Holiday calendar, special events (optional)

**Forecasting Method:**
- Time series analysis with seasonal decomposition
- Trend extrapolation with recovery adjustment
- Confidence bands showing forecast uncertainty
- Actual vs. forecast variance tracking

**Visualizations:**
- Line charts: Historical trend with forecast overlay
- Confidence bands: High/low forecast range
- Bar charts: Route comparison and performance
- Trend indicators: Growth rate and year-over-year comparison
- Heatmaps: Seasonality patterns

**DAX Calculations:**
- Year-over-year growth: (Current Year - Prior Year) / Prior Year
- Seasonal index: Actual / Trend
- Forecast variance: Actual - Forecast
- Peak hour calculation: Max ridership in any hour
- Aggregations: Daily to weekly to monthly to yearly

---

## Business Impact

**Operational Planning:**
- Staffing schedules aligned with predicted demand
- Vehicle deployment matching capacity needs
- Service frequency adjusted to ridership trends
- Peak capacity preparation and management

**Financial Planning:**
- Revenue forecasts for budgeting accuracy
- Bond rating support with demand evidence
- Cost allocation based on ridership drivers
- Investment decisions on route expansion

**Strategic Decisions:**
- Growth route identification for expansion investment
- Declining route analysis for service optimization
- Capacity planning for peak season readiness
- Long-term service network design

---

## Questions?

**About the Dashboard:**
- How do I interpret confidence bands? (Wider band = higher uncertainty; narrower = higher confidence)
- What does forecast variance mean? (Difference between predicted and actual; helps refine model)
- Can I adjust forecast parameters? Yes, Power BI desktop allows what-if parameter updates
- How often does forecast update? Recommend monthly refresh with new actual data

**Forecasting Insights:**
- Is the forecast reliable? Yes for established routes; less reliable for new lines
- How far ahead can we forecast? 12 months reasonably; beyond that uncertainty increases
- What about external events? Special events and weather can cause variance; track separately
- How do we handle growth? Compare forecast to historical growth rates for reasonableness check

---

## Contact & Collaboration

**Daniel S. Demoz**

📧 Email: asbdansi9@gmail.com  
📱 Phone: (437) 249-3308  
🔗 LinkedIn: [linkedin.com/in/daniel-s-demoz](https://linkedin.com/in/daniel-s-demoz)  
💼 GitHub: [github.com/DanielDemoz](https://github.com/DanielDemoz)  
🌐 Website: [brukdconsultancy.com](https://brukdconsultancy.com)

**Open to:**
- Transit forecasting model customization and refinement
- Capacity planning and service optimization consulting
- Time series forecasting for transportation analytics
- Power BI training for transit operations teams
- Revenue forecasting and financial planning support

---

**Last Updated:** August 2026  
**Software Required:** Power BI Desktop (free) or Power BI Service (subscription)  
**Recommended Refresh:** Monthly (aligned with new actual data)  
**Forecast Horizon:** 12 months rolling forward

---

*This dashboard demonstrates time series forecasting and capacity planning analytics for public transportation systems.*
