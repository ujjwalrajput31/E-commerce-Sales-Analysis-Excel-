# Vrinda Store Sales Analysis 📊

Ever wondered who's actually buying stuff online and where the money's really coming from? I dug through a year's worth of e-commerce data to find out.

## What This Is

This is an Excel-based analysis of **31,047 orders** from Vrinda Store's 2022 sales data. Instead of just making pretty charts, I wanted to answer real business questions: Who are our best customers? Where should we focus our marketing budget? Which sales channels actually work?

Spoiler: The answers surprised me.

## The Big Findings 🔍

**Women are driving this business** — and it's not even close:
- Women: ₹13.6M in sales (64%)
- Men: ₹7.6M in sales (36%)

**Age matters more than you'd think:**
- Adults (30-49 years): 50% of all sales
- Teenagers: 30%
- Seniors: 20%

**Geography is destiny:**
The top 3 states account for over a third of all orders:
1. Maharashtra: 14.6% of orders
2. Karnataka: 12.8%
3. Uttar Pradesh: 9.3%

**Amazon dominates, but not alone:**
- Amazon: 35.5% of orders
- Myntra: 23.4%
- Flipkart: 21.6%

**Operations are solid:**
- 92.3% delivery success rate
- Only 3.4% returns (that's really good!)

## What This Means (The "So What?")

If I had to make one recommendation based on this data: **Target women aged 30-49 in Maharashtra, Karnataka, and UP through Amazon and Myntra ads.**

Why? Because that's where the money is. This single segment probably represents 30-40% of your total revenue, and they're already buying — you just need to show up where they're looking.

## Tools & Techniques

- **Microsoft Excel** (yeah, Excel can do a lot)
- Pivot Tables for aggregations
- Conditional Formatting for quick insights
- Slicers for interactive filtering
- Charts & Dashboards for visualization

No Python, no fancy tools — just good old Excel doing the heavy lifting.

## Project Structure

```
📁 Vrinda Store Data Analysis/
├── 📊 Vrinda_Store_Data_Analysis.xlsm    # Main analysis file
│   ├── Sheet1                             # Raw data
│   ├── Vrinda Store                       # Cleaned dataset
│   ├── Vrinda Store Report 2022           # Dashboard
│   ├── Order Age Vs Gender                # Age/Gender analysis
│   ├── Order Channels                     # Channel breakdown
│   ├── Order Status                       # Fulfillment metrics
│   ├── Sales Vs Order                     # Revenue analysis
│   └── Man Vs Women                       # Gender comparison
└── 📄 README.md                           # This file
```

## How to Explore

1. Download the `.xlsm` file
2. Open in Excel (make sure macros are enabled if prompted)
3. Go to the **"Vrinda Store Report 2022"** sheet for the dashboard
4. Use the slicers to filter by month, category, channel, etc.
5. Explore other sheets for detailed breakdowns

**Pro tip:** The pivot tables are already set up, so you can refresh them with your own data if you want to try this analysis on a different dataset.

## Key Questions I Answered

✅ Who buys more — men or women?  
✅ Which age group spends the most?  
✅ Which states should we focus on?  
✅ Which sales channels are worth the marketing spend?  
✅ How's our delivery performance?  
✅ Are we losing money to returns?

## What I Learned

Beyond the data insights, here's what this project taught me:

1. **Context matters more than complexity** — A simple pivot table that answers a business question beats a fancy visualization that doesn't
2. **Excel is underrated** — People sleep on Excel, but it's incredibly powerful for datasets under 100K rows
3. **The 80/20 rule is real** — A small percentage of customers/states/channels drive most of the revenue

## Limitations

- This is 2022 data — consumer behavior changes over time
- No customer lifetime value (CLV) analysis due to data constraints
- Can't track repeat customers without unique IDs
- Seasonal trends need multi-year data to confirm

## Connect With Me

If you found this useful or have questions about the analysis:

- **GitHub:** [@ujjwalrajput31](https://github.com/ujjwalrajput31)
- **LinkedIn:** [linkedin.com/in/ujjwal-ds-ai](https://linkedin.com/in/ujjwal-ds-ai)
- **Email:** ujjwalrajput755@gmail.com

---

**Like this project?** Give it a ⭐ if you found it helpful!

**Want to use this for your own analysis?** Go for it! Just credit the source.
