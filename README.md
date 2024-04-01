# Market Analysis Report for National Clothing Chain

## Project Overview :
An online national clothing chain needs your help creating a targeted marketing campaign. Sales have been flat and they want to lure lost customers back. They want to advertise specific products to specific customers in specific locations, but they don’t know who to target. They have three products in mind:
 * Shirt: $25
 * Sweater: $100
 * Leather Bag: $1,000
They need you to conduct an analysis to determine the best product to advertise to each customer.

## Data Source :
The project will use a variety of data sources, including:
 * US Census Bureau : (Average income, location, population, industry)
 * Business Data : (Product inventory, Product prices, Customer rating, Product return rate)
 * Customer Data : (Customer ID, Names, Location, Date of birth, Purchase history)
 * Additional Data : (Weather, Economics, Demographics, Competition)

## Project Instructions :
In this project, you will use population statistics from the US Census Bureau to determine where the greatest income exists around the country and whether there is a correlation between sales and income. We don’t know the incomes of our customers, but we should be able to predict it by looking at their purchase history and locations and comparing that against the census data. Additionally, we want to analyze our inventory, specifically customer ratings and return rate and see if there’s a correlation between the two.

## Draw conclusions :
Draw conclusions from your analysis and use visuals to answer the following questions:
Analysis Questions:
  1. What is the correlation (R2 value) between sales and income?
  2. What is the correlation (R2 value) between customer ratings and product return rate?
  3. What are the linear regression formulas to predict customer sales and customer incomes?
  4. Which customer do you predict has the highest income?
  5. Which product will be advertised the most?

## Final Report :

 ### Data Model 
![image](https://github.com/Marah-At/National_Clothing_Chain-Report/assets/121014215/603cfe1b-5ce6-410e-914c-589fb0437acd)

 ### First tab : Income & Sales Insights 

  * Based on the Average Income by state visual , the following states have the highest income in the United States ( District of Columbia, New Jersey, Maryland, Massachusetts and Hawaii)
    While the following states have the lowest income ( New Mexico, Kentucky, Arkansas, West Virginia and Mississippi).
  * There is a strong correlation (R2) of 0.78 with a positive relationship ( It means that as average income increases, average expected sales rise ).
  * The formula that can be used to predict customer incomes & Sales is :   x = b-y/-m
    x : Average Income , y : Average Sales , b and m variables are replaced with the actual values .
  * The distribution of predicted income by category.

![image](https://github.com/Marah-At/National_Clothing_Chain-Report/assets/121014215/6557a6a0-8baf-4cfc-9da0-4d4a7dedecbd)

 ### Second tab : Product Insights

  * There is a correlation (R2) of 0.69 with a negative relationship ( It means that as Customer rating increases, the expected product return rate decrease)
    "The products with a higher rating have a lower return rate, which indicates customer satisfaction ".
  * This KPI graph shows that Purchase have been generally decreasing during the Q1-2021 . While the purchase last quarter ( Q4-2020) reach to 157.68K , the latest measurement came in at 
    14.93K meaning the goal was missed by 90.53%.
  *	The chronograph watch is the best rated product (4.9) while the Winter Gloves and Wool Scarf are the lowest rated products(3.1).
  *	Based on the correlation between the Customer Rating and the Product return rate , Cotton Sweater has a high rating ( 4.1 ) and a low return rates (0.0023)
    which indicates customer satisfaction , So it will be advertised the most .

![image](https://github.com/Marah-At/National_Clothing_Chain-Report/assets/121014215/97114eb9-8ea4-4ba9-a30d-d7978f98a0d0)

 ### Third tab : Customer Insights 

  * According to the analysis , Jon Little has the highest Income ( 597,214).
    
![image](https://github.com/Marah-At/National_Clothing_Chain-Report/assets/121014215/24ff0cfb-559b-45fd-b19d-c246b1de7a93)

## Recommendations :

  * The shirts have a good customer rating (3.5 – 4.2) with a low return rate, so these products can be marketed.
  * The leather bag is one of the lowest-rated products(3.3) so we must work to improve the quality of the product in proportion to the price, and we can market it in high-income state.
  * The chronograph watch, Leather Sneakers and Long Dress are among the three highest-rated products , so we can discuss the advertising of these products .







