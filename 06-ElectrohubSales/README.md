# Electrohub Sales Report: E-Commerce Performance Dashboard

**Category:** 🛒 Retail & E-Commerce  
**Analysis Type:** Sales Performance | Product Mix | Channel Comparison

---

## Overview

This comprehensive sales dashboard provides real-time visibility into Electrohub's retail and e-commerce performance. Track revenue by product category and SKU, compare channel performance (online vs. in-store), identify regional trends, and monitor performance against targets. Support decisions on inventory, pricing, marketing investment, and channel strategy.

**Coverage:**
- Multiple product categories (Computers, TVs, Phones, Tablets, Audio, Gaming, Networking, Accessories)
- Online and in-store sales channels
- Customer segments and regional performance
- Real-time transaction tracking

---

## Why This Matters

**Business Questions This Dashboard Answers:**
- Which categories and SKUs drive the most revenue?
- How do online vs. in-store channels compare in performance?
- Where are we missing sales targets?
- What is average order value by channel or product?
- Which customers are most valuable?

**Sales & Operations Impact:**
Better visibility enables:
- Inventory allocation based on category performance
- Pricing strategy informed by margin analysis
- Channel investment decisions backed by ROI
- Marketing budget allocation to highest-performing categories
- Customer segmentation and targeted promotions

---

## Current Sales Status

**Overall Performance:**
- Total Revenue: $19.97M
- Total Units Sold: [From data]
- Gross Profit: $5.01M
- Profit Margin: 25.08%
- Average Order Value: $907.60

**Product Category Performance:**
- Top performing categories: [Review from data]
- Margin leaders: [Varies by category]
- Volume leaders: [Varies by category]
- Growth opportunities: [Slower-moving categories]

**Channel Performance:**
- Online channel: [% of revenue]
- In-store channel: [% of revenue]
- Channel margin comparison: [Online vs. store]
- Customer preference trends: [Online growing vs. stable in-store]

---

## How to Use This Dashboard

### Option 1: Quick Preview (No Software Needed)
Open `Electrohub Sales Report.pdf` to see a snapshot of sales performance.

### Option 2: Interactive Analysis (Power BI Desktop)

**Setup:**
1. Download Power BI Desktop (free at powerbi.microsoft.com)
2. Open `Electrohub Sales Report.pbix`
3. Data auto-connects to CSV files:
   - `electrohub_transactions.csv` - Sales orders and line items
   - `electrohub_products.csv` - Product catalog with category and margin
   - `electrohub_customers.csv` - Customer information and segments
   - `Measures.txt` - DAX calculations for revenue, margin, growth rates

**Dashboard Pages:**
1. **Sales Overview** - High-level business status
   - Total revenue, units sold, profit
   - MTD (month-to-date) and YTD (year-to-date) comparisons
   - Performance vs. target KPIs
   - Key trend indicators

2. **Product Analysis** - Category and SKU performance
   - Revenue by category hierarchy
   - Top 10 products by revenue
   - Bottom performers and optimization opportunities
   - Margin analysis by product
   - Unit sales vs. revenue contribution

3. **Channel Comparison** - Online vs. in-store
   - Revenue split by channel
   - Average order value by channel
   - Conversion metrics by channel
   - Profitability comparison
   - Customer overlap analysis

4. **Regional Performance** - Geographic trends
   - Sales by region or store location
   - Regional market share
   - Regional growth rates
   - Performance vs. regional targets

5. **Customer Insights** - Customer segmentation
   - Top customers by revenue
   - Customer lifetime value
   - Purchase frequency and patterns
   - Customer segment performance
   - Repeat purchase rates

6. **Time Intelligence** - Temporal analysis
   - Sales trending over time
   - Seasonal patterns
   - Year-over-year growth
   - Day-of-week and promotional impacts

**Navigation:**
- **Product Category Slicer:** Drill from category to subcategory to SKU
- **Channel Filter:** Compare online vs. in-store or view combined
- **Region Selector:** Focus on specific stores or markets
- **Customer Segment:** Filter by customer type or purchase behavior
- **Time Period:** View MTD, QTD, YTD, or specific date range
- **Hover:** See exact revenue, units, margin, and growth rates
- **Click:** Drill into category detail or customer performance

### Example Questions You Can Answer

**"Which product category should we expand?"**
→ Go to Product Analysis, sort by margin and growth rate, identify high-margin, growing categories

**"Is online cannibalizing in-store sales?"**
→ Channel Comparison page shows channel split and customer overlap; analyze trend over time

**"Why are we below target this month?"**
→ Sales Overview shows MTD vs. target; drill into products and regions underperforming

**"Which customers should we focus on retaining?"**
→ Customer Insights page shows lifetime value and churn risk; target high-value at-risk customers

---

## What's Inside

**Files Included:**

| File | Purpose |
|------|---------|
| `Electrohub Sales Report.pbix` | Interactive Power BI sales dashboard |
| `electrohub_transactions.csv` | Sales order data with line items, dates, channels |
| `electrohub_products.csv` | Product catalog with categories, SKUs, pricing, cost |
| `electrohub_customers.csv` | Customer master data with segments and demographics |
| `Measures.txt` | DAX calculations for revenue, margin, growth metrics |
| `Electrohub Sales Report.pdf` | Static sales report snapshot |

---

## Key Metrics

| Metric | What It Shows | Business Use |
|--------|--------------|--------------|
| **Total Revenue** | Sales in dollars across all channels and products | Top-line performance and growth |
| **Gross Margin %** | (Revenue - Cost) / Revenue percentage | Profitability and pricing health |
| **Average Order Value** | Total Revenue / Number of Orders | Basket size and upsell effectiveness |
| **Units Sold** | Total products ordered | Volume trends and inventory needs |
| **Channel Revenue Split** | % of sales from online vs. in-store | Channel investment allocation |
| **Year-over-Year Growth** | Current year sales vs. prior year | Trend direction and momentum |
| **Product Mix** | % of revenue by category | Strategic focus and portfolio balance |

---

## Key Insights

**Category Performance:**
- Highest revenue categories: [Top 3 from data]
- Best margin categories: [Higher-margin, potentially lower volume]
- Growth categories: [Fastest expanding]
- Declining categories: [At-risk performance areas]

**Channel Dynamics:**
- Online channel growing faster than in-store
- Online average order value potentially higher/lower than in-store
- Customer channel preference varies by product category
- Omnichannel customers may have higher lifetime value

**Customer Insights:**
- Top 20% of customers likely drive 80%+ of revenue (Pareto principle)
- Customer acquisition cost vs. lifetime value analysis
- Repeat purchase rate and customer retention opportunities
- Segment-specific purchasing patterns

**Sales Performance:**
- Seasonal patterns in certain categories
- Promotional effectiveness by channel
- Regional performance variation
- New product ramp-up trajectory

---

## Technical Details

**Data Model:**
- Transactions: Order ID, customer ID, product ID, channel, date, quantity, price, cost
- Products: SKU, category, subcategory, list price, cost, margin
- Customers: Customer ID, segment, region, registration date, purchase history
- Time dimension: Date hierarchy for MTD, QTD, YTD calculations

**Visualizations:**
- Cards: Revenue, profit, margin KPIs
- Bar charts: Product category comparison, top 10 products
- Line charts: Revenue trending over time
- Pie/donut charts: Channel split, category mix
- Matrix tables: Regional performance, customer segments
- Maps: Geographic sales distribution
- Scatter plot: Margin vs. volume analysis

**DAX Calculations:**
- Revenue: SUM(Transactions.Quantity * Transactions.Price)
- Cost of Goods: SUM(Transactions.Quantity * Products.Cost)
- Gross Profit: Revenue - COGS
- Margin %: (Revenue - COGS) / Revenue
- Average Order Value: Revenue / COUNT(Orders)
- Year-over-Year Growth: (Current Year - Prior Year) / Prior Year
- MTD/QTD/YTD: Sales from start of period to today

---

## Business Impact

**Revenue Optimization:**
- Product mix decisions based on margin and volume data
- Pricing strategy informed by category performance and elasticity
- Promotional calendar aligned to high-performance categories
- Portfolio rationalization of slow-moving SKUs

**Channel Strategy:**
- Omnichannel investment decisions backed by performance data
- Channel-specific marketing allocation
- Inventory distribution between online and stores
- Customer experience improvements by channel

**Customer Focus:**
- High-value customer identification and retention
- Targeted promotions for segment-specific needs
- Customer acquisition efficiency by channel
- Lifetime value maximization through personalization

**Financial Performance:**
- Gross margin improvement through category focus
- Revenue growth through strategic category investment
- Customer acquisition cost optimization
- Inventory efficiency through data-driven stocking

---

## Questions?

**About the Dashboard:**
- How do I drill down into a category? Click any category bar to expand to subcategories and SKUs
- Can I compare two time periods? Use time period slicer to select specific month/quarter/year
- How do I export sales data? Power BI allows export to Excel for further analysis
- Can I create custom segments? Yes - edit electrohub_customers.csv with new segment field and refresh

**Sales Analysis:**
- What is a healthy gross margin? Electronics typically 20-30%; review your targets
- Should we focus on volume or margin? Both; use matrix view to identify high-volume, high-margin sweet spot
- How do we benchmark channel performance? Compare online COGS and fulfillment cost to in-store
- What drives AOV? Product mix, bundling effectiveness, and promotional tactics

---

## Contact & Collaboration

**Daniel S. Demoz**

📧 Email: asbdansi9@gmail.com  
📱 Phone: (437) 249-3308  
🔗 LinkedIn: [linkedin.com/in/daniel-s-demoz](https://linkedin.com/in/daniel-s-demoz)  
💼 GitHub: [github.com/DanielDemoz](https://github.com/DanielDemoz)  
🌐 Website: [brukdconsultancy.com](https://brukdconsultancy.com)

**Open to:**
- Sales dashboard customization for your product catalog
- E-commerce analytics and channel strategy consulting
- Pricing and margin optimization analysis
- Customer segmentation and targeting strategy
- Power BI training for sales and marketing teams

---

**Last Updated:** August 2026  
**Software Required:** Power BI Desktop (free) or Power BI Service (subscription)  
**Recommended Refresh:** Daily (for real-time sales monitoring) or weekly minimum  
**Update Frequency:** New transaction data added continuously; analytics refresh daily

---

*This dashboard demonstrates retail and e-commerce analytics for omnichannel sales optimization.*
