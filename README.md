# Forecasting Store Sales Volume
## Introduction
For brick-and-mortar retail stores, which must carefully balance how much inventory to acquire, sales volume estimates are critical. The stores are left with an excess of perishable goods if the forecasts are a little off. Accurate forecasting could help stores ensure they have just enough products at the correct time. If a store can match a product's demand with just the correct amount of supply, there will be no missed sales owing to a lack of inventory and no additional costs due to overstocking. 

Based on the estimates, the retailers would gain information on how to stock products, eventually retaining clients and ensuring consumer satisfaction. When it comes to perishable commodities, it is essential to ensure that there is enough and that nothing goes to waste owing to rising demand. Through this study, we also intend to assist Favorita in being profitable by examining the data based on the location.

Depending on the forecasting model we ultimately select, some recommendations we would want to offer include optimizing the number of stores by boosting the number of items on promotion, implementing customer loyalty programs, and restructuring the staffing schedule.
## Project Description
  Favorita is an Ecuador-based business that specializes in supermarket retail. Our data set is taken from one of Kaggle's ongoing competitions that emphasize the importance of brick and mortar stores to estimate sales. 
  
  The dataset includes data from various stores across the country as well as quantitative sales (sales volume) for all families (categories of items in the store) by date. The dataset also includes the number of items on promotion on a specific day at a specific store.
  
  The goal of this project is to develop a Time Series Forecasting model that can predict sales volume for a grocery store for 16 days (about two periods). The various models would be compared using evaluation metrics such as MAPE, R2, & RMSE, and the best model would be chosen for final forecasts. Based on the data, we will make recommendations and understand the parameters that are most important in determining sales volume on a given day for a specific store.
## Model Comparison
![image](https://user-images.githubusercontent.com/48169929/226693363-572c61f4-a925-4744-883a-b222429f0b4f.png)
## Recommendations
### Optimizing Shelf Space
 According to our data, the least sold products are those from the families of Hardware, Clothing, and Beauty. We advise giving shelf space for these products in accordance with the volume of sales. The shelf space should be assigned in such a way that the best-selling products, such as Groceries and Beverages, are placed at the back of the store. Customers would travel inside the store to purchase these items because they are the most popular, and the least sold items, such as hardware and clothing, should be placed on shelves and aisles that can attract customers' attention (near the store's entrance) so that sales volume for these items can be increased.
### Leveraging Number of Stores
 Despite having the second highest number of stores, the average sales for Guayaquil are lower than the average sales for Cayambe, Ambato, and Daule. We discovered that this was due to a greater number of items on promotion for the cities of Cayambe, Ambato, and Daule. We would suggest stores in Guayaquil to increase promotions in order to leverage their store count within the city for increased sales volume. 
### Thrifty Thrusdays
Thursdays have the lowest average daily sales. The reason for this is that there are fewer promotions on Thursdays. We recommend that stores launch a campaign such as "Thrifty Thursdays" to attract customers, where the number of items on promotion across all product families is highest on Thursdays, resulting in an increase in sales volume.
### Reasonable Work Schedule
Revamping the staffing schedule is one method to cut labor costs. For instance, compared to weekends, weekdays have lower sales volume. When opposed to weekends, we would recommend fewer active counters during the weekdays, which would result in lower overall labor costs.
### Customer Retention
As oil prices rose, we noticed a decline in sales volume (due to an increase in logistics costs). During such inflationary periods, we would advise the stores to introduce membership-based loyalty or rewards programs, as this would encourage customers to make more repeat purchases from the same stores. Implementing such programs can significantly help stores to retain customers & maintain sales volume.



