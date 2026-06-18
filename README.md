# Chocolate Sales Dashboard

Single-page chocolate sales analytics dashboard built with Power BI — analyzing 1M+ transactions across 6 countries with star schema data modeling and YoY trend analysis.

## Overview
This project models a star schema data warehouse (5 related tables: Sales, Products, Stores, Customers, Calendar) to analyze chocolate sales performance across global markets from 2023–2024. The dashboard combines profitability, discount strategy, and customer loyalty analysis into a single executive view.

## Business Questions
- Which cities and product categories drive the most profit, and are there meaningful performance gaps between them?
- Does discounting meaningfully impact revenue, or is it an underused growth lever?
- How loyal is the customer base (Member vs Non-member), and is there room to grow membership?
- Is there a genuine recurring seasonal pattern in revenue and profit, or are dips one-off events?
- How did key metrics perform year-over-year (2023 vs 2024), and is growth accelerating or stable?

## Tools & Skills
- **Power BI**: Star schema data modeling across 5 related tables
- **DAX**: CALCULATE, DIVIDE, custom YoY growth measures
- **Power Query**: Data transformation and relationship management
- **Data Storytelling**: Insight writing with business implications

## Dashboard Preview

![Chocolate Sales Dashboard](Chocolate%Sales%Dashboard.png)

## Key Insights
- **New York leads city performance at $0.78M**, roughly 3x Berlin's $0.26M, while Sydney, Toronto, and Melbourne form a closely-clustered mid-tier around $0.52M each — suggesting New York's outperformance may warrant a closer look at what's driving it (market size, store count, or local demand) to see if it's replicable elsewhere
- **Praline and White Chocolate drive the most profit** despite not necessarily being the top-revenue categories — suggesting these products carry higher margins and may deserve more marketing focus relative to their current shelf space
- **No-discount transactions generate the vast majority of revenue**, while all discount tiers (10%, 15%, 20%) remain marginal — discounting does not appear to be a meaningful growth lever here, and budget currently spent on discounts might be better redirected toward retention or product mix optimization
- **Customer base is nearly evenly split** between Members (49.88%) and Non-members (50.12%) — the loyalty program hasn't yet captured a majority of customers, suggesting room to grow membership through stronger incentives
- **A recurring February dip in Revenue and Profit appears in both 2023 and 2024** — since it repeats across 2 consecutive years, this looks like a genuine seasonal pattern (e.g., post-holiday demand drop) rather than a one-off event, worth planning around (promotions, inventory adjustments) ahead of future Februaries
- **Revenue, Profit, and Profit Margin all grew modestly YoY** (+0.12%, +0.14%, +0.02% respectively) — positive but slow growth across all three metrics suggests the business is stable rather than rapidly scaling; worth identifying which specific levers (new stores, categories, or customers) could accelerate this in the next cycle

## Files
- `Chocolate Sales Dashboard.pbix` — Power BI dashboard file
- `Chocolate Sales Dashboard.pdf` — Full dashboard export
