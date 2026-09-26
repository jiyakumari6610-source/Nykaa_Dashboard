# Nykaa Product & Brand Analysis Dashboard

An interactive Power BI dashboard analyzing product portfolio performance, 
pricing strategy, customer engagement, and stock availability across brands 
sold on Nykaa.

## 📊 Overview

This dashboard answers key business questions:
- Which brands drive the largest product portfolio and customer engagement?
- Where is the "sweet spot" between price and average rating across brands?
- How does pricing segment (Budget/Mid/Premium) affect stock availability 
  and discounting behavior?
- Which brand has the strongest volume-to-price trade-off?

## 🔍 Key Insights

- **Nykaa Cosmetics** combines the largest product portfolio with strong 
  customer engagement, while brands with smaller portfolios achieve 
  comparable ratings — suggesting that product breadth and customer 
  satisfaction are not necessarily correlated.
- Premium-priced products achieve the highest average ratings, while 
  mid-priced products dominate the portfolio and carry stronger discounting 
  — indicating a trade-off between perceived product quality and 
  price-driven accessibility.
- **Ikkai by Lotus Herbals** commands the highest average rating (4.75) 
  despite premium pricing, while **Nykaa Cosmetics** wins on product volume 
  at a much lower average price — highlighting two distinct strategies: 
  premium positioning vs. mass-market scale.

## 🛠️ Tools & Techniques

- **Power BI Desktop** for data modeling and visualization
- **DAX measures** for dynamic KPIs and a self-updating insights panel 
  (insight text recalculates live based on applied filters, using 
  `CALCULATE`, `TOPN`, and `SELECTEDVALUE`)
- Custom color theming aligned to brand identity
- Conditional formatting (bubble color by price segment) on the 
  price-vs-rating scatter plot

## 📂 Data

Dataset sourced from Kaggle — Nykaa Cosmetics product listings dataset.

## 🚀 What I'd Improve Next

- Extend dynamic insight logic to automatically adapt to new data as 
  the dataset grows
- Add year-over-year trend comparisons if historical data becomes available
- Explore drill-through pages for individual brand deep-dives

## 📁 Files

- `Nykaa Dashboard.pbix` — the Power BI file (open in Power BI Desktop to explore interactively)

## 👤 Author

**Jiya Kumari**
