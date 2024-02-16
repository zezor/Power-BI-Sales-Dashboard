# Power-BI-Sales-Dashboard

## INTRODUCTION
This project aims to develop a Data Analysis tool for analyzing the overall sales  using Power BI.

The Report consists of three pages:

A report page

AI Narrative Page


## PROBLEM STATEMENT
- To  present revenue by countries
  
- To identify the top 3 cars sold

- Compare Revenue and Pofit between the Brands
  
- Show Revenue and Sales by City and Dealer

## SKILLS DEMONSTRATED

**AI Narrative integration** 

![](Narrative_Page_1.png)

![](Narrative_Page_2.png)


![](Narrative_Tile.png)
## DATA SOURCING
The Data was extracted from the Kaggle data set
## DATA TRANSFORMATION
Data cleaning and transformation were carried out using Power Query. After scrutinizing all the columns, they were found valid and devoid of empty cells and errors. To calculate the deliveries on time and not on time we needed to know the delivery date and expected delivery date 

Therefore, I created a new column to extract the Expected Delivery Date by combining the Collection Date and Contracted Term

A second column was also extracted from the Delivery Date and Expected Delivery Date to know Late or Not Late deliveries 


![image](https://github.com/zezor/Power-BI-Logistics-Dashboard/assets/39943217/d664b2e2-99ce-4c82-b222-ee34e6acbfa8)

## MODELLING
The data was modelled to find the relationship between various tables

The invoice table is marked as the fact table with the Carrier and ClientBase tables being dimension tables

![](Model_LD.png)

## ANALYSIS AND VISUALIZATION
### KPI 
The main KPI focused on in this analysis is the OTIF. On-time in full (OTIF) is a supply chain metric for measuring performance in the logistics
 industry. OTIF generally refers to a supplier's ability to deliver product within prescribed delivery windows and at full quantities ordered.
From the tile below, the business under consideration had an OTIF of 61.07%. This will be compared with the targeted OTIF KPI to determine if the business is doing well.

![](KPI.png)

The tile from the diagram below shows the OTIF performance for the clients (Top Five). 
Management would have to investigate these clients to understand the factors contributing to their low performance.

### Revenue by Country
Individual OTIF for various carriers was calculated. From the chart below, Delivery Express has the highest OTIF of 65.91%.
![](Revenue_byCountry.png)


### Revenue by Brand
![](Revenue_by_brand.png)

### Quantity Sold by Brand
![](Quantity_sold_by_brand.png)



## CONCLUSION AND RECOMMENDATION
![](Report_SD.png)


