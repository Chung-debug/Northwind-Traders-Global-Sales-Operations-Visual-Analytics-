# Northwind Traders Global Sales and Operations Visual Analytics

## Project Background

The leadership team needed a clear, unified view of our global business performance to identify growth drivers and hidden operational inefficiencies. Transactional data was sitting siloed across seven different business segments, including customers, products, employees, and shipping metrics. This fragmentation made it difficult to track seasonal revenue patterns, evaluate the actual cost-effectiveness of our shipping partners, or understand if our discounting strategy was genuinely profitable. 

## Objective

The goal of this project was to design and build an interactive business intelligence dashboard using Tableau to centralize these data streams. I needed to isolate the top revenue-generating products and regions, evaluate logistics costs and delivery speeds, measure salesforce productivity, and provide leadership with concrete, data-backed recommendations to optimize profit margins.

## Technical Implementation

I extracted and modeled relational data from the Northwind database, establishing clear joins between the core transactional and master data tables. To enable deep analytical capabilities, I calculated custom business metrics within Tableau. These metrics included actual total price factoring in precise discount percentages, total dollar amounts lost to discounts, and exact shipping durations rounded to the nearest day. 

I then constructed a four-page interactive dashboard structured around specific corporate focus areas: Sales & Revenue Overview, Product & Category Intelligence, Operational & People Performance, and Customer Experience. I implemented dynamic cross-filtering actions across all views, allowing stakeholders to instantly isolate performance by time, geography, or specific product categories.

## Business Outcomes

The analysis revealed that our global revenue is heavily concentrated in a small group of countries, led by the USA at $245,584, Brazil at $106,925, and Canada at $50,196. I discovered a major revenue risk where high-performing items, specifically within Meat and Poultry, had been discontinued, leaving a clear void in future revenue pipelines. 

The data also disproved the internal assumption that steeper discounts always yield higher total returns. While moderate discounting drives healthy volume, aggressive price slashing actively harms profitability, proving our promotions must be managed strictly at the category level. Finally, the logistics audit uncovered massive variations in freight costs and delivery times among our shipping providers. 

Based on these findings, I secured leadership approval to implement strict category-specific discount caps and initiated an operational review to track warehouse locations and inventory levels, which will allow us to accurately calculate true shipping distances and optimize delivery efficiency moving forward.

## Interactive Dashboard

You can explore the fully interactive data visualizations and filter the live metrics directly on Tableau Public:

[View the Interactive Tableau Dashboard](https://public.tableau.com/views/Task3_17772525751980/SalesRevenueOverview?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
