# Sales_Performance_Analysis

Analysis of Sales Performance Across Customer Segments, Product Categories, Locations, and Delivery Metrics (2011–2014)

----

## Table of Contenet
1. [Overview](#overview)
2. [Business_Problem](#Business_Problem)
3. [Objectives](#Objectives)
4. [Tools Used](#Tools_Used)
5. [Dataset](#Dataset)
6. [Data_Analysis](#Data_Analysis)
7. [Key_Insights](#Key_Insights)
8. [Recommendations](#Recommendations)
9. [Dashboard](#Dashboard)
10. [Connect_with_me](#Connect_with_me)

----

# Overview
The Superstore management team is planning a business expansion but lacks visibility into which products, regions, and customer segments are driving growth and which are underperforming. Without this clarity, resource allocation and market entry decisions carry significant risk.

This analysis using excel examines four years of transactional sales data (2011–2014) across 5,009 orders to identify the key drivers of revenue and profit performance. The study covers five dimensions: customer segment contribution, product category revenue, regional and state-level sales distribution, seasonal order trends, delivery and fulfilment metrics.

The findings are presented through an interactive sales dashboard and this accompanying report, with the goal of equipping Superstore leadership with the data-backed insight needed to prioritise expansion markets, optimise product focus, and reduce concentration risk across their customer base.

---

## Business_Problem

The management wants 


---

## Objectives
- To ascertain sales performance across customer segment.
- To determine the product that drives sales growth.
- To uncover the region with the highest sales performance across the three product segment
- To access the effect of discount on sales performance
- To determine the month with highest order volume.
- To examine the delivery status with highest sales
- To determine the monthly quantity trend
  
---
## Tools_Used
- Microsoft Excel
- Powerquery
- Dax
---
## Dataset
- Source: Online Superstore Sales data
- Records: 9,994
- Perios: 2011-2014
---
## Data_Analysis

- Data cleaning process: The dataset had an inconsistent date format which was cleaned using condtional statement
                          The inconsistency in data structure was standardized as well using power query
                          Some DAX measures where created for YoY sales and YoY profit 
---
##Key_Insights




### Product Sales Performance

Technology leads all product categories by revenue, followed by Furniture and Office Supplies. This distribution reflects the relatively higher unit value of technology products compared to consumable office supplies.

Category performance summary
- Technology: $836.15K — the top-performing category, driven by high average order values.
- Furniture: $742.00K — second highest, with strong performance in the West region.
- Office Supplies: $719.05K — highest volume category but lower average transaction value.

While Technology generates the highest revenue, Office Supplies likely drives the highest order frequency given its consumable nature. A margin analysis by category would reveal whether Technology’s revenue lead translates to a proportional profit contribution, particularly given the business’s 15.62% average discount rate.
Sub-category filters available on the dashboard enable more granular analysis — for example, identifying whether specific sub-categories like Phones, Chairs, or Binders are disproportionate contributors within each parent category.

### Sales by region and segment
The following table presents the full breakdown of sales by region and customer segment. The West region leads across all three customer segments, while the South consistently records the lowest performance.

Region | Consumer |	Corporate |	Home Office	| Total
-------|----------|----------|-----------|------
West	 | $362.88K |	$225.88K	| $136.72K |	$725.48K
East	 | $350.91K |	$208.41K |	$127.46K	| $686.78K
Central	| $252.03K |	$158.00K |	$91.21K	| $501.24K
South |	$195.58K |	$121.88K |	$74.26K |	$391.72K

The West region’s dominance (+876.3% above the average state performance for California) is a significant finding. While this reflects strong market penetration in the West, it also creates dependency on a single geographic cluster. The South region’s underperformance ($391.72K total vs $725.48K in the West) represents the most actionable expansion opportunity in the near term.



---
##Recommendations
---
##Dashboard

---
#Connect_with_me

---
