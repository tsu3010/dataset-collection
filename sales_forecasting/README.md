# Sales Forecasting 

## Data Description:
A time-series data with daily historical sales information for items in different shops. T
he list of shops and items changes each month. You may not have information around a shop,item pair for all months. 

## File descriptions : 
• sales_train.csv - the training set. Daily historical data from January 2013 to October 2015.
• test.csv - the test set. You need to forecast the sales for these shops and products for November 2015

## Data Fields:
• ID - an Id that represents a (Shop, Item) tuple within the test set
• shop_id - unique identifier of a shop
• item_id - unique identifier of a product
• item_cnt_day - number of products sold. You are predicting a monthly amount of this measure
• item_price - current price of an item
• date - date in format dd/mm/yyyy
• date_block_num - a consecutive month number, used for convenience. January 2013 is 0, 
  February 2013 is 1,..., October 2015 is 33