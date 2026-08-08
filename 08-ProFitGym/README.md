# Pro Fit Gym: Member Engagement & Retention Analytics Dashboard

**Category:** 💪 Wellness & Fitness  
**Analysis Type:** Member Engagement | Retention Analytics | Class Performance

---

## Overview

This fitness industry dashboard provides comprehensive visibility into member engagement, retention, and class performance across Pro Fit Gym locations. Track membership lifecycle, identify at-risk members before churn occurs, analyze class popularity and optimal scheduling, and optimize retention through data-driven member experience improvements. Support decisions on facility planning, class offerings, pricing strategy, and targeted member retention campaigns.

**Coverage:**
- Multiple gym locations and facilities
- Membership tiers and pricing models
- Class schedules and instructor performance
- Member check-in and engagement tracking
- Retention and churn analysis

---

## Why This Matters

**Business Questions This Dashboard Answers:**
- Which members are at risk of churn and when?
- What classes and time slots drive the most engagement?
- How does retention vary by membership tier?
- Which locations and demographics show strongest engagement?
- What is the optimal class schedule and pricing strategy?

**Fitness Operations Impact:**
Better visibility enables:
- Proactive member retention through early churn warnings
- Class scheduling optimized to member preferences and capacity
- Membership tier pricing aligned to engagement and retention
- Facility expansion decisions based on location performance
- Targeted marketing to high-value member segments
- Staff scheduling matching class demand patterns

---

## Current Membership Status

**Membership Overview:**
- Active members: 695 (86.88% retention rate)
- Inactive members: 105 (13.13% churn rate)
- Total check-ins: 6,000+ across analysis period
- Average minutes per visit: 60.42
- Average check-ins per member: 7.50

**Member Demographics:**
- Primary market (26-45 years): 66.26% of membership
- Age breakdown: 18-25 (17.88%), 26-35 (33.88%), 36-45 (32.38%), 46-60 (14.5%), 60+ (1.38%)
- Geographic distribution: Multiple locations with varying performance

**Class Performance:**
- Top performing classes: Spin, Boxing, Strength Training
- Other popular offerings: Pilates, Yoga, Zumba, CrossFit, HIIT
- Peak attendance times: Morning and evening (commute-adjacent)
- Off-peak opportunities: Midday scheduling availability

**Engagement Patterns:**
- High retention rate indicates strong value proposition (86.88%)
- Average visit frequency sustainable (7.50 visits per member)
- Session duration healthy (60.42 minutes average)
- Class diversity shows member interest in varied fitness experiences

---

## How to Use This Dashboard

### Option 1: Quick Preview (No Software Needed)
Open `Pro Fit Gym Membership Report.pdf` to see a snapshot of member engagement and retention metrics.

### Option 2: Interactive Analysis (Power BI Desktop)

**Setup:**
1. Download Power BI Desktop (free at powerbi.microsoft.com)
2. Open `Pro Fit Gym Membership Report.pbix`
3. Data auto-connects to CSV files:
   - `fitness_members.csv` - Member master data with join date, tier, demographics
   - `fitness_checkins.csv` - Check-in history with dates, times, visit duration
   - `fitness_classes.csv` - Class catalog with schedules, instructors, capacity
   - `fitness_membership_types.csv` - Tier definitions, pricing, feature access
   - `Measures (1).txt` - DAX calculations for retention rate, engagement score, churn prediction

**Dashboard Pages:**
1. **Member Overview** - High-level engagement status
   - Active members count and trend
   - Retention rate and churn rate
   - Total check-ins and average visits per member
   - New member acquisition rate
   - Engagement score distribution

2. **Engagement Analysis** - Activity tracking
   - Check-in frequency distribution
   - Session duration trends
   - Member activity clusters (highly active, moderate, at-risk)
   - Engagement trend by new vs. established members
   - Cohort retention curves (cohorts by join month)

3. **Class Performance** - Course and schedule optimization
   - Class attendance rankings (top 10 classes)
   - Attendance by time slot (peak hours identification)
   - Instructor performance metrics
   - Class capacity utilization
   - Trend in class-specific attendance

4. **Member Lifecycle** - Retention and churn
   - Cohort retention curves (% retained by month since join)
   - At-risk member identification
   - Churn prediction scoring
   - Membership tier retention comparison
   - Win-back campaign targeting

5. **Demographic Insights** - Member segmentation
   - Membership distribution by age group
   - Engagement by demographic
   - Retention rates by segment
   - Geographic location performance
   - Tier preferences by demographic

6. **Location Performance** - Facility-level analysis
   - Members by location
   - Engagement by location
   - Class popularity by location
   - Location-specific retention rates
   - Facility utilization and expansion opportunities

**Navigation:**
- **Membership Tier Filter:** Compare retention and engagement across tiers
- **Location Selector:** Analyze specific facility or compare locations
- **Class Filter:** Focus on specific classes or types
- **Age Group Slicer:** Segment by demographic
- **Date Range:** Analyze specific periods or cohorts
- **Hover:** See exact check-in counts, visit frequency, engagement scores
- **Click:** Drill into member cohort detail or single member profile

### Example Questions You Can Answer

**"Who are our at-risk members?"**
→ Go to Member Lifecycle page, filter to At-Risk status, use for targeted retention outreach

**"Should we expand our boxing class?"**
→ Class Performance page shows Boxing as top 2 performer; check capacity utilization and add sessions

**"Why is the 46-60 age group underrepresented?"**
→ Demographic Insights shows 14.5% of membership; classes and marketing may not appeal to this age group

**"Which location has the highest churn?"**
→ Location Performance page shows retention by facility; investigate what drives lower retention there

---

## What's Inside

**Files Included:**

| File | Purpose |
|------|---------|
| `Pro Fit Gym Membership Report.pbix` | Interactive Power BI member engagement dashboard |
| `fitness_members.csv` | Member master data with join date, tier, demographics |
| `fitness_checkins.csv` | Check-in history with dates, times, duration, location |
| `fitness_classes.csv` | Class catalog with schedule, instructor, capacity, type |
| `fitness_membership_types.csv` | Membership tier definitions, pricing, features |
| `Measures (1).txt` | DAX calculations for engagement, retention, churn scoring |
| `Pro Fit Gym Membership Report.pdf` | Static engagement report snapshot |

---

## Key Metrics

| Metric | What It Shows | Business Use |
|--------|--------------|--------------|
| **Active Members** | Members with recent activity | Revenue and utilization baseline |
| **Retention Rate** | % of members retained month-over-month | Long-term membership value |
| **Churn Rate** | % of members canceling | Urgency of retention programs |
| **Check-in Frequency** | Average visits per member per month | Engagement health indicator |
| **Session Duration** | Average time per visit | Intensity and satisfaction proxy |
| **Engagement Score** | Composite metric of frequency and consistency | Member lifecycle stage |
| **At-Risk Score** | Probability of churn (0-100) | Targeting for retention campaigns |

---

## Key Insights

**Retention Performance:**
- 86.88% retention rate is strong indicator of member satisfaction
- High retention suggests effective class programming and facility quality
- New member cohort tracking shows retention drop-off in months 1-3 (focus area)
- Membership tier retention varies; analyze whether pricing affects commitment

**Engagement Patterns:**
- 7.50 visits per member suggests regular (weekly+) attendance
- 60.42 minutes average session: Quality workout time indicating satisfaction
- Bimodal distribution likely reflects commuter patterns (morning/evening peaks)
- Seasonal variation possible; summer dips are common in fitness

**Class Performance:**
- Spin and Boxing top performers indicate demand for high-energy classes
- Strength Training popularity shows interest in structured, results-oriented programming
- Pilates and Yoga round out offerings for different fitness philosophies
- Early morning and evening slots consistently full; midday availability

**Demographic Insights:**
- Primary market: 26-45 years (66.26%) represents sweet spot
- 18-25 underrepresented (17.88%); opportunity for student/young professional marketing
- 60+ underrepresented (1.38%); potential growth segment with age-appropriate programming
- Gender and income data (if available) show targeted marketing opportunities

**Location Performance:**
- Variation by location suggests facility quality, scheduling, or demographic differences
- Best-performing locations offer insight into best practices
- Under-performing locations warrant investigation and improvement plan

---

## Technical Details

**Data Model:**
- Members: Member ID, join date, membership tier, age, location, status
- Check-ins: Member ID, check-in date/time, session duration, class attended
- Classes: Class ID, name, instructor, schedule, capacity, class type
- Tiers: Tier ID, name, price, features, contract term
- Time dimension: Date, month, quarter, year, day-of-week, hour-of-day

**Visualizations:**
- Cards: Active members, retention rate, churn rate, average visits KPIs
- Line charts: Retention curves (cohort analysis), churn trending, new member sign-ups
- Bar charts: Class attendance rankings, age group distribution, location performance
- Heat maps: Class popularity by time slot, day-of-week patterns
- Scatter plot: Engagement score vs. tenure (identify at-risk cohorts)
- Tables: Member segment detail with engagement metrics
- Gauges: Retention rate vs. target

**DAX Calculations:**
- Active Members: COUNT(Members) WHERE Status = 'Active' AND Last_Checkin >= TODAY()-30
- Retention Rate: Active Members This Month / Active Members Prior Month
- Churn Rate: (Lost Members / Prior Month Members) * 100
- Engagement Score: Composite (Visits * 0.6 + Recency * 0.4)
- At-Risk Score: Predictive scoring based on declining check-in frequency
- Cohort Retention: % of cohort members retained at each month milestone
- Class Metrics: Attendance by class, capacity utilization %, instructor ratings

---

## Business Impact

**Member Retention:**
- Early churn warning system identifies members at risk before cancellation
- Targeted win-back campaigns for at-risk segments
- Personalized offers based on engagement patterns
- Improved lifetime value through reduced churn

**Revenue Optimization:**
- Pricing strategy informed by tier-specific retention and engagement
- Upsell opportunities to highly engaged members
- Cross-selling recommendations (personal training, nutrition)
- Membership tier optimization based on customer preferences

**Class & Scheduling Optimization:**
- Peak-time classes sized to demand
- Off-peak opportunities for underutilized time slots
- Instructor assignment matching member preferences
- New class development based on member interest signals

**Facility & Growth:**
- Location expansion decisions backed by demand data
- Best practice identification from top-performing facilities
- Demographic targeting for marketing by location
- Capacity planning aligned to projected growth

---

## Questions?

**About the Dashboard:**
- How do I identify at-risk members? Go to Member Lifecycle page, filter to At-Risk status score
- Can I export member lists for outreach? Yes; Power BI allows export to Excel for campaigns
- How do I track a specific member? Use member ID filter to drill into individual activity
- Can I add new metrics? Yes; edit Measures (1).txt with custom DAX formulas

**Fitness Operations:**
- What retention rate is healthy? 85%+ is excellent; 75-85% is acceptable; below 75% needs intervention
- How do we reduce churn? Target at-risk members proactively, improve class variety, ensure facility quality
- Should we add a new class? Yes if demand exists (attendance requests, peak hours full); test in off-peak time first
- How do we grow membership? Demographic targeting, location expansion, referral programs, and tiered pricing

---

## Contact & Collaboration

**Daniel S. Demoz**

📧 Email: asbdansi9@gmail.com  
📱 Phone: (437) 249-3308  
🔗 LinkedIn: [linkedin.com/in/daniel-s-demoz](https://linkedin.com/in/daniel-s-demoz)  
💼 GitHub: [github.com/DanielDemoz](https://github.com/DanielDemoz)  
🌐 Website: [brukdconsultancy.com](https://brukdconsultancy.com)

**Open to:**
- Fitness and wellness analytics dashboard customization
- Member retention and churn prediction modeling
- Class scheduling optimization and capacity planning
- Demographic targeting and marketing analytics
- Power BI training for gym operations and management teams

---

**Last Updated:** August 2026  
**Software Required:** Power BI Desktop (free) or Power BI Service (subscription)  
**Recommended Refresh:** Daily (for real-time member tracking) or weekly minimum  
**Update Frequency:** New check-in data added continuously; analytics refresh daily

---

*This dashboard demonstrates fitness industry analytics and member lifecycle management for gym and wellness operations.*
