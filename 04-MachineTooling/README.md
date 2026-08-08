# Machine Tooling: Rod Diameter Variance Analysis Dashboard

**Category:** 🏭 Manufacturing & Quality Control  
**Analysis Type:** Quality Control | Process Capability | Defect Analysis

---

## Overview

This quality control dashboard monitors dimensional variance in CNC-machined rods against specification tolerances. Real-time visibility into machine performance, defect patterns, and variance trends helps identify quality issues before they reach customers. Track which machines need maintenance, where variance is highest, and the cost impact of out-of-spec production.

**Machines Monitored:**
- CNC_A, CNC_B, CNC_C, CNC_D
- Rod diameter specification: 50.00mm (±0.45mm tolerance)
- Real-time measurement data from QC systems

---

## Why This Matters

**Business Questions This Dashboard Answers:**
- Which machines produce the highest defect rates?
- Is process variance trending within control limits?
- What machines need maintenance or recalibration?
- What is the cost impact of out-of-spec production?
- Which shifts or operators show quality issues?

**Quality & Operations Impact:**
Better visibility enables:
- Early detection of machine degradation
- Prevention of scrap and rework costs
- Identification of maintenance needs before failures
- Process improvement through data
- Customer quality assurance (zero defects)

---

## Current Quality Status

**Process Performance:**
- **Mean Diameter:** 50.00mm (on specification)
- **Std Dev (Variance):** 0.15mm
- **Range:** 49.55mm - 50.45mm
- **Critical Finding:** CNC_D shows significantly higher variance than peers

**Machine Performance:**
- **CNC_A:** Tight distribution, in control
- **CNC_B:** Tight distribution, in control
- **CNC_C:** Tight distribution, in control
- **CNC_D:** Wide distribution — requires maintenance/recalibration

**Quality Status:**
- Average acceptance rate: 95%+ (depends on tolerance spec)
- CNC_D rejection rate elevated due to high variance
- Early intervention on CNC_D will prevent scrap and rework

---

## How to Use This Dashboard

### Option 1: Quick Preview (No Software Needed)
Open `Machine Tooling Visual.pdf` to see a snapshot of quality metrics.

### Option 2: Interactive Analysis (Power BI Desktop)

**Setup:**
1. Download **Power BI Desktop** (free at powerbi.microsoft.com)
2. Open `Machine Tooling Visual.pbix`
3. Data auto-connects to `machine_stats.csv` (measurement data from QC system)

**Dashboard Pages:**
1. **Overview** — At-a-glance quality status
   - Mean diameter and standard deviation
   - Min/max range
   - Process capability indicators
   - Machine status indicators

2. **Statistical Distribution** — Variance analysis
   - Box-whisker plots by machine
   - Visual comparison of machine spread
   - Outlier identification
   - Control limit reference lines

3. **Control Charts** — Trend over time
   - Running mean by machine
   - Variance trending
   - SPC (Statistical Process Control) signals
   - Alert flags for out-of-control conditions

4. **Machine Drill-Down** — Detailed analysis
   - Histogram of measurements per machine
   - Measurement frequency distribution
   - Acceptance rate by machine
   - Batch-level detail

**Navigation:**
- **Machine Filter:** Select single machine or compare multiple
- **Date Range:** Analyze trends over time or specific period
- **Product Line Filter:** If running different rod types
- **Shift Filter:** Identify shift-specific issues
- **Hover:** See exact measurements and statistics
- **Click:** Drill into batch or operator detail

### Example Questions You Can Answer

**"Which machine needs immediate attention?"**
→ Look at box-whisker plot — CNC_D shows widest spread and outliers

**"Is CNC_D getting worse over time?"**
→ View control chart — increasing variance = maintenance needed NOW

**"What's our defect rate trend?"**
→ Track % out-of-spec over 30-day window

**"Which operator/shift has quality issues?"**
→ Filter by operator, compare variance across shifts

---

## What's Inside

**Files Included:**

| File | Purpose |
|------|---------|
| `Machine Tooling Visual.pbix` | Interactive Power BI quality dashboard |
| `machine_stats.csv` | Measurement data from QC system (diameter by machine, batch, date) |
| `Machine Tooling Visual.pdf` | Static quality report snapshot |

---

## Key Quality Metrics

| Metric | What It Means | Your Target |
|--------|--------------|------------|
| **Mean Diameter** | Average measurement across batches | 50.00mm |
| **Std Dev (σ)** | Spread of measurements (variance) | < 0.10mm (tight) |
| **Min/Max Range** | Tightest/loosest measurements | 49.55-50.45mm |
| **% Within Tolerance** | Acceptance rate | > 99% |
| **Cp (Process Capability)** | Machine capability vs. spec | > 1.67 (excellent) |
| **Cpk (Performance Index)** | Actual performance | > 1.33 (acceptable) |

---

## Key Insights

**Machine Performance Status:**
- **CNC_A, B, C:** Performing well with tight, consistent distributions
- **CNC_D:** Critical variance — requires immediate maintenance
  - Wider whiskers indicate loose tolerance
  - High outliers suggest calibration drift
  - Likely causing scrap/rework in production

**Root Cause Analysis for CNC_D:**
- Possible causes: Spindle wear, tool deflection, loose bearings, calibration drift
- Recommendation: Schedule preventive maintenance immediately
- Impact: Each out-of-spec rod = scrap cost + production delay

**Quality Trending:**
- Monitor CNC_D closely after maintenance to verify improvement
- Establish control limits and alert triggers
- Track mean drift (if trending away from 50.00mm)
- Watch for increased variation as sign of wear

---

## Technical Details

**Data Model:**
- Measurements: Diameter values by machine, batch, timestamp
- Machine master: CNC_A, B, C, D identification and calibration data
- Specification: Nominal 50.00mm with tolerance limits
- Batch reference: Production order traceability

**Visualizations:**
- Box-whisker plot: Shows median, quartiles, outliers per machine
- Histogram: Frequency distribution of measurements
- Control charts: Mean and variance trending
- Cards: Key metrics (mean, std dev, min, max)
- Alert indicators: Red flags for out-of-control conditions

**Statistical Measures:**
- Mean (average diameter)
- Standard deviation (variance measure)
- Min/Max (range)
- Quartiles (Q1, median, Q3)
- Process capability (Cp, Cpk)
- % within tolerance

---

## Business Impact

**Quality Assurance:**
- Zero-defect goal: Identify machines trending toward failure
- Early detection: Prevent customer issues before delivery
- Root cause: Quick identification of quality problems

**Cost Prevention:**
- Scrap avoidance: Stop producing out-of-spec parts
- Rework reduction: Catch issues before processing downstream
- Maintenance efficiency: Preventive action vs. reactive repair

**Operations:**
- Production continuity: Minimize downtime from machine failures
- Resource planning: Schedule maintenance during planned downtime
- Compliance: Document quality data for customer audits

---

## Maintenance & Troubleshooting

**When to Take Action:**
- **Yellow Alert:** Std Dev > 0.12mm — Monitor closely, schedule maintenance
- **Red Alert:** Std Dev > 0.15mm — Immediate maintenance required
- **Trend Alert:** Variance increasing over time — Wear pattern detected
- **Calibration Alert:** Mean drifting from 50.00mm — Recalibration needed

**Preventive Maintenance Schedule:**
- Weekly: Check CNC_D variance (currently at risk)
- Monthly: Full statistical analysis by machine
- Quarterly: Capability study (Cp/Cpk analysis)
- Annual: Preventive maintenance on all machines

---

## Questions?

**About the Dashboard:**
- How do I read the box-whisker plot? (Median line = 50th percentile, box = 25th-75th, whiskers = outliers)
- What does variance mean? (Higher = less consistent, quality risk)
- Should I stop production? (If Cpk < 1.0, yes — stop and investigate)
- Can I export data? Yes — Power BI allows export for SPC records

**Quality Standards:**
- What's an acceptable Cp? (> 1.67 = excellent, > 1.33 = acceptable, < 1.0 = at risk)
- When to recalibrate? (When mean drifts > 0.05mm from nominal)
- Defect cost impact? (Calculate: % scrap × cost/rod × daily production volume)

---

## Contact & Collaboration

**Daniel S. Demoz**

📧 **Email:** asbdansi9@gmail.com  
📱 **Phone:** (437) 249-3308  
🔗 **LinkedIn:** [linkedin.com/in/daniel-s-demoz](https://linkedin.com/in/daniel-s-demoz)  
💼 **GitHub:** [github.com/DanielDemoz](https://github.com/DanielDemoz)  
🌐 **Website:** [brukdconsultancy.com](https://brukdconsultancy.com)

**Open to:**
- Quality dashboard customization for other processes
- SPC (Statistical Process Control) implementation
- Machine performance analytics and trending
- Manufacturing operations consulting
- Power BI training for quality teams

---

**Last Updated:** August 2026  
**Software Required:** Power BI Desktop (free) or Power BI Service (subscription)  
**Recommended Refresh:** Real-time or daily (depends on QC system capability)  
**Alert Sensitivity:** Configurable based on tolerance and risk tolerance

---

*This dashboard demonstrates statistical quality control and process capability analysis for manufacturing operations.*
