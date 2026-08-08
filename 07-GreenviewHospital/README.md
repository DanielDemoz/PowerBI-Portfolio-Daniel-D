# Greenview Hospital: Admissions & Patient Flow Analytics Dashboard

**Category:** 🏥 Healthcare & Patient Flow  
**Analysis Type:** Operations Analytics | Bed Utilization | Capacity Planning

---

## Overview

This healthcare operations dashboard provides real-time visibility into patient admissions, discharge patterns, length of stay, and bed utilization across Greenview Hospital. Track admission trends by department and payer, monitor how patient flow compares to benchmarks, and ensure bed capacity aligns with demand. Support operational decisions on staffing, resource allocation, and capacity planning.

**Coverage:**
- Multiple clinical departments (Emergency, ICU, Medical, Surgical, etc.)
- Patient demographics and diagnosis tracking
- Payer and insurance analysis
- Real-time census and bed status
- Discharge disposition tracking

---

## Why This Matters

**Business Questions This Dashboard Answers:**
- What are admission trends by department and payer?
- How does length of stay compare to clinical benchmarks?
- Is bed capacity aligned with current and projected demand?
- Which departments have highest readmission or complication rates?
- Where are bottlenecks in patient flow (admissions, transfers, discharges)?

**Hospital Operations Impact:**
Better visibility enables:
- Accurate staffing schedules aligned with patient volume
- Bed allocation and unit management decisions
- Discharge planning to prevent backup and delays
- Payer mix optimization and contract management
- Quality improvement targeting (readmission reduction)
- Financial forecasting based on admission patterns

---

## Current Hospital Status

**Admission Volume:**
- Total admissions tracked: 5,000+ across analysis period
- Emergency department admissions: 63.54% of total
- Average daily census: [From data]
- Peak occupancy: [From seasonal analysis]

**Department Performance:**
- Emergency (ED) - Volume leader with 1,183+ admissions
- Intensive Care (ICU) - Highest average length of stay at 6.94 days
- Medical floors - Moderate volume with 2-4 day average stay
- Surgical departments - Shorter stays (1-3 days average)

**Patient Flow Metrics:**
- Average length of stay (ALOS) - 3.68 days across hospital
- Discharge disposition: 71.94% home, 11.02% with services, 5.7% to long-term care, 4.6% expired
- ICU admission rate - 388 total ICU admissions
- Readmission tracking - [From readmission analysis]

---

## How to Use This Dashboard

### Option 1: Quick Preview (No Software Needed)
Open `Greenview Hospital Admissions Dashboard.pdf` to see a snapshot of admissions and utilization.

### Option 2: Interactive Analysis (Power BI Desktop)

**Setup:**
1. Download Power BI Desktop (free at powerbi.microsoft.com)
2. Open `Greenview Hospital Admissions Dashboard.pbix`
3. Data auto-connects to CSV files:
   - `hospital_admissions.csv` - Admission, discharge, transfer events
   - `hospital_departments.csv` - Department and unit information
   - `hospital_patients.csv` - De-identified patient demographics
   - `hospital_diagnosis_categories.csv` - Clinical diagnosis groupings
   - `Measures (2).txt` - DAX calculations for ALOS, occupancy, readmission rates

**Dashboard Pages:**
1. **Admissions Overview** - High-level operations status
   - Total admissions, discharges, current census
   - Admission vs. discharge balance
   - Emergency vs. scheduled admissions
   - Volume trending and seasonal patterns

2. **Department Analysis** - Unit-level performance
   - Admissions by department
   - Average length of stay by department
   - Bed utilization and occupancy rates
   - Department-specific bottleneck identification

3. **Daily Census** - Real-time bed status
   - Census trending (7-30 day view)
   - Peak and average occupancy
   - Seasonal demand patterns
   - Capacity vs. actual utilization

4. **Patient Flow** - Admissions to discharge
   - Admission time of day distribution
   - Discharge timing patterns
   - Length of stay distribution
   - Discharge destination breakdown

5. **Diagnosis & Acuity** - Clinical patterns
   - Top admission diagnoses
   - Diagnosis-specific length of stay
   - Severity/acuity level distribution
   - Sepsis, cardiac, trauma, psychiatric volumes

6. **Payer Mix** - Financial and operational
   - Admissions by insurance type
   - Average length of stay by payer
   - Payer profitability impact
   - Commercial vs. Medicare vs. Medicaid trends

**Navigation:**
- **Department Filter:** View specific unit or compare departments
- **Date Range Selector:** Analyze trends over 7-day, monthly, quarterly, or annual periods
- **Admission Type Filter:** Emergency vs. scheduled, urgent care, transfers
- **Diagnosis Filter:** Focus on specific diagnoses or patient populations
- **Payer Filter:** Compare performance by insurance type
- **Hover:** See exact admission counts, ALOS, occupancy rates
- **Click:** Drill into patient cohort detail or single-unit performance

### Example Questions You Can Answer

**"Do we have enough ICU capacity?"**
→ Go to ICU page, review current occupancy vs. peak historical, plan for surge capacity

**"Why are emergency patients staying longer?"**
→ Filter to ED admissions, compare ALOS to other departments, identify bottlenecks (bed availability, discharge planning)

**"Which diagnosis has highest readmission rate?"**
→ Diagnosis page shows ALOS and readmission %, identify quality improvement opportunities

**"Are we balanced on admissions and discharges?"**
→ Admissions Overview shows admission vs. discharge trending; imbalance indicates bed backup risk

---

## What's Inside

**Files Included:**

| File | Purpose |
|------|---------|
| `Greenview Hospital Admissions Dashboard.pbix` | Interactive Power BI hospital operations dashboard |
| `hospital_admissions.csv` | ADT (admit/discharge/transfer) events with dates, times, units |
| `hospital_departments.csv` | Department and unit master data with bed counts, acuity levels |
| `hospital_patients.csv` | De-identified patient demographics, payer, admission source |
| `hospital_diagnosis_categories.csv` | Clinical diagnosis groupings and severity classifications |
| `Measures (2).txt` | DAX calculations for ALOS, occupancy, readmission rates |
| `Greenview Hospital Admissions Dashboard.pdf` | Static admissions report snapshot |

**Note:** All data is de-identified or synthetic for portfolio use only. No PHI (Protected Health Information) included.

---

## Key Metrics

| Metric | What It Shows | Clinical/Operational Use |
|--------|--------------|--------------------------|
| **Admissions** | Patient volume entering hospital | Staffing and bed needs |
| **Discharges** | Patients leaving (home, transfer, expired) | Bed availability and flow |
| **Census (Daily)** | Patients in hospital at point in time | Real-time bed utilization |
| **ALOS (Average Length of Stay)** | Days from admission to discharge | Efficiency benchmark |
| **Occupancy Rate** | Census / Available beds as % | Capacity planning |
| **Readmission Rate** | Readmissions within 30 days | Quality indicator |
| **Discharge Destination** | Where patients go (home, rehab, LTC) | Discharge planning |

---

## Key Insights

**Volume Patterns:**
- Emergency department dominates admissions (63.54%)
- Admission patterns vary by day-of-week (weekends lower, weekdays peak)
- Seasonal variation affects bed demand (flu season surge, summer dips)
- Scheduled admissions more predictable; emergency less so

**Length of Stay Findings:**
- ICU stays longest at 6.94 days (complex cases, higher acuity)
- Medical/surgical floors vary: Medical 4-5 days, Surgical 2-3 days
- Emergency department serves as holding area; many don't convert to inpatient
- Sepsis and cardiac cases exceed average ALOS

**Bed Utilization:**
- Peak occupancy occurs winter months and certain times of week
- Evening hours show higher admission rate; morning higher discharge rate
- Discharge bottlenecks possible (slow morning discharges, delayed bed cleaning)
- Capacity appears adequate on average but peaks risk overflow

**Discharge Planning:**
- Majority discharge home (71.94%)
- Significant portion need post-acute services (29%)
- Timely discharge planning critical to bed availability
- Weekend discharge rates lower than weekdays

**Patient Flow Opportunities:**
- Bed turnover time (discharge to next admission) variable by unit
- ED boarding of admitted patients impacts ED flow and safety
- Transfer timing between units affects overall length of stay
- Early discharge planning could reduce ALOS

---

## Technical Details

**Data Model:**
- Admissions: Admit date/time, patient ID, department, admission type, severity
- Transfers: Transfer date/time, from unit, to unit, clinical reason
- Discharges: Discharge date/time, destination, disposition status
- Patients: De-identified demographics, payer, insurance type
- Diagnoses: ICD-10 grouping, primary vs. secondary, severity level
- Time dimension: Hour, date, day-of-week, week, month, year, season

**Visualizations:**
- Cards: Total admissions, discharges, current census, ALOS KPIs
- Line charts: Census trending, admission/discharge trends
- Bar charts: Admissions by department, diagnosis distribution
- Heat maps: Hourly admission patterns, day-of-week variations
- Pie charts: Discharge destination mix, payer mix
- Tables: Department detail with ALOS, occupancy, readmission rates
- Gauges: Current occupancy vs. capacity

**DAX Calculations:**
- ALOS: AVERAGE(Admissions.Days_in_Hospital)
- Daily Census: COUNT(Admissions) WHERE Admit_Date <= Today AND Discharge_Date >= Today
- Occupancy %: Census / Available_Beds * 100
- Readmission Rate: Count of patients readmitted within 30 days / prior discharges
- Time-based measures: Admission_Hour, Discharge_Hour, Day_of_Week_Admitted
- Payer calculations: Admission count and ALOS by insurance type

---

## Business Impact

**Operational Excellence:**
- Staffing aligned to predicted admission volume
- Bed allocation optimized through demand forecasting
- Discharge planning preventing bottlenecks and delays
- Unit-level performance accountability

**Quality Improvement:**
- Readmission reduction through targeted interventions
- ALOS benchmarking against clinical standards
- Complication rate tracking by diagnosis
- Care pathway optimization for high-volume diagnoses

**Financial Performance:**
- Payer mix monitoring for contract compliance
- Case-mix index tracking for DRG reimbursement
- Operational efficiency (lower ALOS, higher throughput)
- Capacity optimization reducing unnecessary beds

**Patient Safety:**
- ED boarding metrics (admission held in ED waiting for bed)
- Transfer delays identification and mitigation
- Escalation of acuity management
- Discharge disposition appropriateness

---

## Questions?

**About the Dashboard:**
- How do I filter to a specific diagnosis? Use diagnosis slicer to select single or multiple diagnoses
- Can I view real-time census? Yes; refresh data connection for current status
- How do I export data for reporting? Power BI allows export to Excel for board presentations
- Can I add custom calculations? Yes; edit Measures (2).txt with additional DAX and refresh

**Clinical Operations:**
- What is an acceptable ALOS? Varies by diagnosis; benchmark against CMS DRG standards
- How does occupancy affect quality? High occupancy (95%+) may increase adverse events and readmissions
- Should we expand bed capacity? Review peak occupancy trends and projected volume growth
- How do we reduce ED boarding? Faster inpatient admission and discharge planning improvements

**Financial & Compliance:**
- What is case-mix index? Average DRG weight; higher = more complex, higher-cost patients
- How does ALOS affect reimbursement? Lower ALOS may indicate efficiency or deny patterns
- What is readmission penalty? CMS penalizes hospitals with high unplanned readmissions
- How do we optimize payer mix? Track profitability by payer type; contract negotiation

---

## Contact & Collaboration

**Daniel S. Demoz**

📧 Email: asbdansi9@gmail.com  
📱 Phone: (437) 249-3308  
🔗 LinkedIn: [linkedin.com/in/daniel-s-demoz](https://linkedin.com/in/daniel-s-demoz)  
💼 GitHub: [github.com/DanielDemoz](https://github.com/DanielDemoz)  
🌐 Website: [brukdconsultancy.com](https://brukdconsultancy.com)

**Open to:**
- Hospital operations dashboard customization and enhancement
- Patient flow optimization and throughput analysis
- Quality improvement analytics and readmission reduction
- Payer mix and financial performance consulting
- Power BI training for hospital operations and clinical teams

---

**Last Updated:** August 2026  
**Software Required:** Power BI Desktop (free) or Power BI Service (subscription)  
**Recommended Refresh:** Real-time or daily (for operational monitoring)  
**Data Confidentiality:** All patient data is de-identified; no PHI included

---

*This dashboard demonstrates healthcare operations analytics and patient flow management for hospital systems.*
