# darkway30-Retail_Forecasting
Data Set Information:
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

Attribute Information:

InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation. 

StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product. 

Description: Product (item) name. Nominal. 

Quantity: The quantities of each product (item) per transaction. Numeric. 

InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated. 

UnitPrice: Unit price. Numeric, Product price per unit in sterling. 

CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer. 

Country: Country name. Nominal, the name of the country where each customer resides.


1. Data Preparation

-This Dataset contains 532619 rows and eight columns

2. Exploring the content of variables

Countries

-check the different values for the top and bottom 20 countries
Customers and products

-Approximately 25 % of the customers are unknown or Null, and 0.2% of items were missing; these values that we'll have to remove to understand the actual data better.

Canceling orders

-We already have any idea of the numbers of unique transactions but let us get an accurate value of the C or canceled invoices.
StockCode
-How many Unique Invoices

Basket price

-Adding a new column with the Sales Data
-Since we have only 22190 Unique invoices, let's analyze our customers and look at their total number of transactions made this year and their last purchase. However, in a later step, a NaN Description shows us a failed transaction, so we will have to deal with NaN values to better analyze our customers.

3. Insight on merchandise

Product description

Labeling product categories
