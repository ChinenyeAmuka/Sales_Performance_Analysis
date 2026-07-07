# Sales_Performance_Analysis

Analysis of Sales Performance Across Customer Segments, Product Categories, Locations, and Delivery Metrics (2011–2014)

----

## Table of Content
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
This report presents a structured analysis of four years of sales data (2011–2014) from a U.S.-based superstore operating across three business segments — Consumer, Corporate, and Home Office — and three product categories: Technology, Furniture, and Office Supplies. The analysis was conducted using an interactive Excel dashboard spanning three analytical pages: Executive Summary, Sales Analysis, and Operations Dashboard. The dashboard examines revenue performance, geographic distribution, product category trends, shipping behaviour, and seasonal demand patterns to surface actionable insights for business decision-making

---

## Business_Problem

Despite recording consistent sales growth over the four-year period, the business lacks clear visibility into which customer segments, product categories, and geographic markets are the true drivers of revenue. Without this insight, decisions around inventory allocation, staffing, and marketing spend remain largely reactive. This analysis was conducted to close that gap, providing data-backed direction that enables the business to prioritize resources where they deliver the highest return and build a foundation for sustainable, scalable growth.

---

## Objectives
- Examine which customer segment generates the highest profit.
- Determine the product category and sub-categories that drive the most sales.
- Understand the states and regions that represent the strongest and weakest markets.
- Know how total sales and profit trended year-over-year from 2011 to 2014?
- Find out What shipping methods do customers prefer, and how does delivery performance affect order volume?
- Which months record peak order volumes, and what operational patterns explain seasonality
  
---
## Tools_Used
- Microsoft Excel
- Powerquery
- Dax
---
## Dataset
- Source: Online Superstore Sales data
- Records: 9,994
- Periods: 2011-2014

## Exploratory Data analysis


  
---
## Data_Cleaning

- The dataset had an inconsistent date format which was cleaned using condtional statement. The inconsistency in data structure was standardized as well using power query. Some DAX measures where created for YoY sales and YoY profit
  
---
# Data Analysis
---

### Customer Segments
The Consumer segment dominates profit at $134.12K, more than 64% ahead of Corporate ($91.98k) and over 170% ahead of Home Office ($60.30K).

<img width="354" height="214" alt="image" src="https://github.com/user-attachments/assets/4498de51-7791-4f75-8c59-e12e235b4928" />



### Product Categories
Technology is the top-performing category in terms of sales at $836K, narrowly ahead of Furniture ($742K) and Office Supplies ($719K).

<img width="370" height="163" alt="image" src="https://github.com/user-attachments/assets/89f9de3f-7d93-4e79-b16f-7e4be6efbcb3" />


### Geographic Performance

California is the single largest state market at $458K (19.9% of total), outperforming the average state by 876%. The West region leads nationally at 31.6% ($725K), while the South trails at 17.1% ($392K). The top 5 states account for 52% of all revenue, signalling high geographic concentration risk.The Consumer segment dominates revenue at $1.16M, more than 64% ahead of Corporate ($706K) and over 170% ahead of Home Office ($430K) across all regions, Consumer leads consistently.

<img width="583" height="330" alt="image" src="https://github.com/user-attachments/assets/962209d0-7696-40a4-a852-eb3d7c6bb8e5" />



### Sales & Profit Trend

Total sales grew from $484K in 2011 to $734K in 2014 — a 51% increase. Profit grew faster, rising from $50K to $94K, an 80% gain over the same period. Both metrics show consistent upward trajectory, with the steepest growth in the final year. 

<img width="605" height="271" alt="image" src="https://github.com/user-attachments/assets/6cd1b1fb-7435-487c-8c7a-dd75bd27455a" />


### Shipping

Standard Class is the preferred shipping mode with 2,994 orders, nearly triple First Class (787) and Same Day (264). On-time delivery leads at 2,586 orders versus 1,990 late.
<img width="943" height="174" alt="image" src="https://github.com/user-attachments/assets/367a3d92-5407-4fce-b832-a98e06e3567d" />
<img width="1099" height="136" alt="image" src="https://github.com/user-attachments/assets/b317eff1-18b2-4a39-b1b5-3fd27bdb99a2" />
<img width="1094" height="136" alt="image" src="https://github.com/user-attachments/assets/4b9d3809-f2d8-4c94-9cca-e8f969019a18" />




### Operational Patterns
 November records peak quantity sold (5,741 units) and peak orders (747), aligning with seasonal retail demand.

 <img width="943" height="164" alt="image" src="https://github.com/user-attachments/assets/af46bb87-74cc-49d2-b214-bde796606392" />


 ### Key_Insights
 

1. With Consumer generating 50% of total profits, the business is exposed if this segment contracts. A deliberate strategy to grow Corporate and Home Office reduces concentration risk and opens higher-margin B2B opportunities.
   
2. Technology leads($836.15k) in total sales, closely followed by Furniture($742k) and Office Supplies(60.30k). The gap between categories is narrow, suggesting balanced demand rather than a single dominant product line.
   
3. Sales is heavily concentrated in the West region($725.46k). The South region significantly underperforms every other region with targeted investment, the South could become the next growth lever. The top 5 states alone lead by California account for more than half of all sales, this poses a high risk to the business if not taken care of immediately.

4. Increase in proft and sales from 2011-2014 is due to gradual increase in order volumn and total quantity sold which the varing average discount price from 15.83% from 2011 to 15.65% in 2014 is a major contributing factor.

5. With standard shipping accounting for the (2994)59% orders, it is evident that customers are cost conscious and the need to improve operational efficiency in the standard shipping mode is increased while still ensuring that other shipping modes are working effectively to help build customers confidence. The business also records high on-time at (2586)51% delivery which should be maintained as well.

6. Peak demand in November is predictable and repeatable. Yet 1,990 late deliveries across the dataset suggest the operation is not consistently ready for volume spikes. Missing November means leaving the year's biggest revenue window on the table.
 



---
## Recommendations

1. Grow B2B Segments: The customer segment show room for targeted B2B outreach and bundle pricing strategies,to help drive profit for lagging segment like home office equipment.

2. Ensure inventory efficency of all the product categories especilayy technology to ensure continuous sales.

3. Also as California and New York account for over 33% of total revenue, prioritise marketing spend and inventory allocation in these states to sustain momentum.
   
4.  An average discount of 15.62% compresses margins. Introduce tiered pricing or loyalty programmes to protect profit without sacrificing volume.
  
5. Optimise Standard Class: Standard Class drives 2,994 orders — highest of any ship mode. Improve fulfilment speed in this tier to maintain customer satisfaction at scale.

6. Capitalise on Q4 Seasonality: November peaks in both quantity (5,741 units) and orders (747). Pre-position inventory and staffing by October to maximise seasonal demand capture.

---

## Dashboard

<img width="1112" height="457" alt="image" src="https://github.com/user-attachments/assets/26b9a1a4-7191-4614-9ad6-b435b9e42411" />
<img width="1096" height="457" alt="image" src="https://github.com/user-attachments/assets/2feeff53-ad28-4202-b919-928a89416867" />
<img width="1105" height="456" alt="image" src="https://github.com/user-attachments/assets/0da901b5-99ce-4bb6-815c-2df66e718ca7" />



---
# Connect_with_me

Linkedin: www.linkedin.com/in/
chinenye-amuka-79a992137


---
