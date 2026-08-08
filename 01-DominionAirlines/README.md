# Dominion Airlines: Passenger Traffic Dashboard

**Category:** 📊 Transportation & Aviation  
**Analysis Type:** Route Network Visualization | Capacity Planning | Demand Analysis

---

## Overview

This interactive dashboard visualizes passenger flows across Dominion Airlines' five major Canadian hub airports. The chord diagram shows which routes carry passengers and how volume moves between airports, helping answer key questions about route profitability, capacity needs, and network optimization.

**Airports Analyzed:**
- YEG (Edmonton International)
- YOW (Ottawa Macdonald-Cartier)
- YUL (Montreal-Trudeau)
- YVR (Vancouver International)
- YYZ (Toronto Pearson International)

---

## Why This Matters

**Business Questions This Dashboard Answers:**
- Which routes generate the highest passenger demand?
- How does passenger flow move through the network (bidirectional analysis)?
- Which airports act as major hubs vs. connection points?
- Where are bottlenecks or underutilized routes?
- How do seasonal patterns affect route planning?

**Operational Impact:**
Better route visibility supports:
- Aircraft deployment and fleet optimization
- Crew scheduling and positioning
- Dynamic pricing and revenue management
- Informed decisions on route expansion
- Capacity allocation across the network

---

## Key Metrics

| Metric | What It Shows |
|--------|--------------|
| **Passenger Volume** | Total passengers per route and direction |
| **Load Factor** | Percentage of seats filled (efficiency measure) |
| **On-Time Performance** | Percentage of flights meeting schedule |
| **Route Pairs** | Bidirectional flows showing balance/imbalance |
| **Hub Connectivity** | Which airports connect most routes |

---

## How to Use This Dashboard

### Option 1: Quick Preview (No Software Needed)
Open `PDF - Airport Traffic Visual.pdf` to see a snapshot of the visualization.

### Option 2: Interactive Analysis (Power BI Desktop)

**Setup:**
1. Download **Power BI Desktop** (free at powerbi.microsoft.com)
2. Open `Airport Traffic Visual.pbix`
3. Data auto-connects to `Dominion Airlines -Traffic Dashboard-Data.csv`

**Navigation:**
- **Chord Diagram:** Shows passenger flows as colored lines between airports
  - Chord width = passenger volume
  - Chord color = direction (origin to destination)
- **Slicers/Filters:** Select airports, time periods, or route groups
- **Hover:** See exact passenger counts and percentages
- **Click:** Drill into specific routes for detail

### Example Questions You Can Answer

**"Which routes need bigger aircraft?"**
→ Filter to routes with 80%+ load factor (capacity-constrained)

**"Are we missing growth opportunities?"**
→ Look at routes in 40-60% load factor range (room to grow)

**"How seasonal is our network?"**
→ Compare monthly trends to identify peak/off-peak patterns

---

## What's Inside

**Files Included:**

| File | Purpose |
|------|---------|
| `Airport Traffic Visual.pbix` | Interactive Power BI dashboard |
| `Dominion Airlines -Traffic Dashboard-Data.csv` | Source data (flights, routes, passengers) |
| `PDF - Airport Traffic Visual.pdf` | Static report snapshot |

---

## Key Insights

**Network Structure:**
- Some routes run balanced traffic both directions (efficient network)
- Other routes carry mostly one-way passengers (connecting traffic)
- Hub airports (YYZ, YVR) anchor the network
- Spoke airports (YEG, YOW) feed traffic to hubs

**Seasonal Patterns:**
- Summer peaks reflect family travel
- Winter maintains strong business travel
- Holiday periods show distinct demand spikes

**Growth Opportunities:**
- Routes at 40-60% load factor have capacity for growth
- Underutilized routes may indicate pricing or scheduling misalignment
- Hub connectivity reveals network expansion opportunities

---

## Technical Details

**Data Model:**
- Flight operations: Departure/arrival, passenger count, timing
- Route master: Origin/destination pairs, distance, frequency
- Aggregations: Summarized by route and direction for visualization

**Visualization:**
- Chord diagram: Shows network flows visually
- Interactive filters: Dynamic exploration of subsets
- Time series: Month-over-month trend tracking
- DAX calculations: Load factor, percentages, performance metrics

**Performance:**
- Optimized for fast interactions on large datasets
- Pre-aggregated data for quick filtering
- Responsive design for different screen sizes

---

## Business Impact

**Strategic Decisions Enabled:**
- Route expansion: Data-backed selection of new routes
- Fleet deployment: Aircraft size matched to demand
- Pricing strategy: Dynamic pricing based on route demand
- Hub optimization: Confirmation of hub roles in network

**Financial Results:**
- Revenue growth through targeted expansion
- Cost savings via efficient deployment
- Improved load factors through optimization
- Risk reduction through network diversification

---

## Questions?

**About the Dashboard:**
- How do I interpret the chord diagram? (See "How to Use" section)
- Can I modify this? Yes — Power BI Desktop allows full customization
- How often does data update? Updates when you refresh the data connection

---

## Contact & Collaboration

**Daniel S. Demoz**

📧 **Email:** asbdansi9@gmail.com  
📱 **Phone:** (437) 249-3308  
🔗 **LinkedIn:** [linkedin.com/in/daniel-s-demoz](https://linkedin.com/in/daniel-s-demoz)  
💼 **GitHub:** [github.com/DanielDemoz](https://github.com/DanielDemoz)  
🌐 **Website:** [brukdconsultancy.com](https://brukdconsultancy.com)

**Open to:**
- Dashboard customization and enhancements
- Data analysis and strategy consulting
- Power BI training and support
- Business intelligence projects

---

**Last Updated:** August 2026  
**Software Required:** Power BI Desktop (free) or Power BI Service (subscription)

---

*This dashboard demonstrates network analysis and interactive visualization for the transportation industry.*
