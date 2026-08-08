# Atlas Builders: Integrated Construction Project Dashboard

**Category:** 🏗️ Construction & Project Management  
**Analysis Type:** Project Timeline Tracking | Cost Management | Risk Analysis

---

## Overview

This interactive dashboard provides real-time visibility into construction project performance across multiple phases. Track schedule progress, cost variance, resource allocation, and risks all in one place. Built for project managers and executives who need to monitor status, identify issues early, and make data-driven decisions.

**What's Tracked:**
- 48 tasks across 7 project phases
- Schedule performance vs. baseline
- Budget tracking and cost variance
- Risk identification and mitigation
- Resource allocation by phase

---

## Why This Matters

**Business Questions This Dashboard Answers:**
- Are we on schedule? How far behind/ahead?
- Is the project over/under budget?
- Which phases have the most risk?
- Where are cost overruns concentrated?
- Are resources allocated efficiently?

**Project Management Impact:**
Better visibility enables:
- Early problem detection (schedule slips, cost overruns)
- Informed stakeholder communication
- Proactive resource management
- Data-backed decision-making
- Risk mitigation before issues escalate

---

## Key Metrics

| Metric | What It Shows |
|--------|--------------|
| **Schedule Variance** | Days ahead or behind baseline (-22 days = 22 days behind) |
| **Cost Variance** | Budget performance ($246.24K under = under budget) |
| **Completion %** | Overall project progress (68.75% complete) |
| **Phase Status** | Which phases are on track vs. at risk |
| **Top Cost Drivers** | Which activities consume most budget |

---

## Current Project Status

**Overall Progress:**
- **Completion:** 68.75%
- **Schedule Variance:** -22 days (behind schedule)
- **Cost Variance:** -$246.24K (under budget)
- **Total Tasks:** 48 across 7 phases

**Top Cost Overruns:**
1. Structural steel erection
2. Footings and foundation
3. Drywall finishing

**Cost Savings (Opportunities or Efficiencies):**
1. Controls and balancing
2. Life safety testing
3. HVAC installation

---

## How to Use This Dashboard

### Option 1: Quick Preview (No Software Needed)
Open `Construction Project Dashboard.pdf` to see the dashboard snapshot.

### Option 2: Interactive Analysis (Power BI Desktop)

**Setup:**
1. Download **Power BI Desktop** (free at powerbi.microsoft.com)
2. Open `Construction Project Dashboard.pbix`
3. Data auto-connects to CSV files:
   - `atlas_projects_Data.csv` — Project overview
   - `atlas_phases_Data.csv` — Phase-level details
   - `atlas_tasks_Data.csv` — Individual tasks
   - `atlas_task_assignments_Data.csv` — Resource allocation

**Dashboard Pages:**
1. **Overview** — High-level status and KPIs
   - Cards showing completion %, schedule variance, cost variance
   - Phase-by-phase status indicators
   - Key metrics at a glance

2. **Timeline (Gantt Chart)** — Schedule tracking
   - Planned vs. actual dates per task
   - Visual identification of schedule slips
   - Phase dependencies and sequencing

3. **Cost & Risk Analysis** — Budget performance
   - Cost by phase (actual vs. budget)
   - Top 10 cost drivers and savings
   - Risk identification and status

**Navigation:**
- **Phase Slicer:** Filter to specific phase or view all
- **Task Status Filter:** On track, at risk, complete, behind
- **Date Range:** Zoom to specific time period
- **Hover:** See detailed metrics for any task or phase
- **Click:** Drill into phase detail

### Example Questions You Can Answer

**"Why are we behind schedule?"**
→ Go to Timeline page, filter to In Progress tasks with negative variance

**"Which phase is over budget?"**
→ Go to Cost page, sort phases by cost variance

**"What's the biggest risk?"**
→ Filter tasks by status = "At Risk", review cost and schedule impact

**"Are we tracking to finish on time?"**
→ Review overall schedule variance trend; compare to original baseline

---

## What's Inside

**Files Included:**

| File | Purpose |
|------|---------|
| `Construction Project Dashboard.pbix` | Interactive Power BI dashboard |
| `atlas_projects_Data.csv` | Project-level data (dates, budgets) |
| `atlas_phases_Data.csv` | Phase breakdown and status |
| `atlas_tasks_Data.csv` | Individual task details |
| `atlas_task_assignments_Data.csv` | Resource assignments |
| `Construction Project Dashboard.pdf` | Static report snapshot |

---

## Key Insights

**Schedule Performance:**
- Project is 22 days behind schedule
- Completion expected beyond original baseline
- Behind status likely due to phase delays in Structural or MEP work

**Cost Performance:**
- Project is $246.24K under budget
- Cost savings suggest efficiency gains or original conservative budgeting
- Monitor for scope creep as project continues

**Phase Status:**
- Early phases (Permits, Site Prep) likely complete or on track
- Later phases (Structure, MEP, Interiors) driving schedule variance
- Commissioning phase shows typical resource/time crunch

**Resource Allocation:**
- Review task assignments to identify bottlenecks
- Some resources may be over/under allocated
- Peak demand periods visible in task concentration

---

## Technical Details

**Data Model:**
- Projects table: Overall timelines and budgets
- Phases: Major project divisions (7 phases tracked)
- Tasks: Granular activities (48 tasks with dependencies)
- Assignments: Resource and cost allocation by task
- Status: Track progress against baseline

**Visualizations:**
- Gantt chart: Schedule visualization
- Variance cards: KPI highlighting
- Cost breakdown: Phase-level analysis
- Status indicators: Red/yellow/green status
- Trend charts: Performance over time

**DAX Calculations:**
- Schedule variance: (Actual End - Planned End) in days
- Cost variance: (Actual Cost - Budget) in currency
- Completion %: Tasks completed / Total tasks
- Status flags: Logic for on-track vs. at-risk determination

---

## Business Impact

**Decision Support:**
- Stakeholders know project health at a glance
- Early identification of issues (schedule slips, cost overruns)
- Data-backed decisions on timeline extensions or budget changes
- Resource reallocation based on actual progress

**Risk Management:**
- Visible early warning signs
- Documented variance history
- Trend analysis to project final outcome
- Risk mitigation tracking

**Communication:**
- Executive dashboards for steering committee
- Team view for day-to-day management
- Subcontractor performance tracking
- Client reporting and transparency

---

## Questions?

**About the Dashboard:**
- How do I read the Gantt chart? (See "Dashboard Pages" section)
- Can I add new tasks? Yes — Update the CSV files and refresh
- Can I customize this? Yes — Power BI Desktop allows full editing
- How often should I update data? Update as tasks progress (weekly recommended)

**Troubleshooting:**
- Dashboard not showing latest data? Refresh data connection in Power BI
- Dates not showing correctly? Check CSV date format (MM/DD/YYYY recommended)
- Cost calculations off? Verify budget and actual cost columns in source data

---

## Contact & Collaboration

**Daniel S. Demoz**

📧 **Email:** asbdansi9@gmail.com  
📱 **Phone:** (437) 249-3308  
🔗 **LinkedIn:** [linkedin.com/in/daniel-s-demoz](https://linkedin.com/in/daniel-s-demoz)  
💼 **GitHub:** [github.com/DanielDemoz](https://github.com/DanielDemoz)  
🌐 **Website:** [brukdconsultancy.com](https://brukdconsultancy.com)

**Open to:**
- Dashboard customization and project-specific enhancements
- Project management consulting and best practices
- Construction analytics strategy
- Power BI training for teams
- Real-time project monitoring setup

---

**Last Updated:** August 2026  
**Software Required:** Power BI Desktop (free) or Power BI Service (subscription)  
**Recommended Refresh:** Weekly during active construction phases

---

*This dashboard demonstrates project management analytics and earned value tracking for the construction industry.*
