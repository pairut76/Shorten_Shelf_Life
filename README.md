# <center>Shorten_Shelf_Life

## Analyzing Inventory Trends: Predicting Quantity Sold

### Problem:

<i>Marketing is huge - how do we improve efficiency and target the problem of overstocking an item? Items are being stocked up on the shelf and start collecting dust, they take up space and are not being sold, some items have been sitting on the shelf for years untouched. We will need to determine and examine the time period what items sell best during what time frame. This will help us determine and prepare for which particular item to stock up on in accordance to the needs/demand of the consumers.</i>

### Solution:
The solution will determine and predict future sales of approximately how many units of a particular item will be sold on a specific date. This is valuable information when the warehouse is limited in capacity to store products and needs to maximize space to potentially add more (new) products in the future.
Benefits:

	1. Maximize Space - when a particular item is determined to sell at a particular date or time we can stock up that particular item and also expect the space to be </br> available after the item is sold.
	2. Maximizes Turnover - with this predictive model we can expect the products to have less “shelf life”. 
	3. Cash Flow - the quicker items are sold, the more immediate profits or gains the company can make in contrast to reshelving the product and it remains unsold, the </br>  company can be sitting on inventory and no cash flow.

Taking the time to research this data and review the solutions will greatly improve the 
business overall - maximizing space, turnover and improving cash will move the company forward and allow future expansion (such as more room for future products)
	

### The Data:
The dataset is an online retail data collected between 1/12/2009 thru 9/12/2011. This is a UK-based online retail with many of its clients in the UK while app. 8% of clients in other countries, but overall are mainly wholesalers (link). Contains approximately 5,000+ different gift-ware products and more than 50,000+ transactions within the time span. Basic information includes invoice date, unit price, quantity, stock code (product id) along with item description and other information.


### Technical Tools:
The model will mostly consist of time series analysis - examining the sales of each product over time. ARIMA modeling to analyze and forecast the dataset. First, split the data into training sets and testing sets - the target will be how many products were sold for a particular item. Now, compare different periods if there is a cycle by weeks, months and years. Then, train the model and run the model through cross-validation to see how the model can predict and how well it does. Also, compare the model to the average sales.  

### Challenges:
How many unique products are there? Number of unique product descriptions is greater than the number of unique Product IDs. 
Check if there is seasonality and determine the period of the cycle if there is any.
Tweaking and improving the model
Are there changes to the sales price? 
How to account for that
Are there repeating customers?




