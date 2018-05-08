# StockEx

Step 1. Open the workbook 

Step 2. If the developer tab is not visibe go to File->Options->Customize Ribbon under the main tabs, enable developer tab (Excel 2016)

Step 3. Under the developer tab click Visual Basic (or press Alt+F11) to bring up the code window

Step 4. In the Visual Basic cod window navigate to Tools->References and scroll down to find Microsoft WinHTTP Services, Version 5.1 and enable it

This should allow the user to send "GET" requests for the API, and run the app successfully

# Using the App:

The Current Day sheet will populate and graph todays data for the stock chosen.  To choose a stock, pick a symbol from the drop down list and click update.  A table with times and pricing data will appear, as well as a graph for the table data.  This is also where you can choose to buy stock, if you should choose to buy a stock the data table will be updated to ensure the most up to date pricing for the stock, so it is recommended that you click update prior to purchasing a stock to make sure the price is where you want it to be. If you have insufficient funds when trying to make a purchase, you will be prompted to invest more money so a purchase can be made.  Currently there is no cap on investments and no tracking of the total amount invested.  That will be available in version 1.2

## Current Day sheet
![alt text](https://github.com/us0173ol/StockEx/blob/master/screenshots/Current%20Day.PNG "Current Day")

The Historical Data sheet is mainly for analysis of the stock behavior over a chosen period of time.  Like the Current Day sheet, you will choose a symbol from the drop down list and choose a start and end date for the range of dates you would like to see data for.  A table will be populated along with a graph to show the behavior of the stock.  

## Historical Data sheet
![alt text](https://github.com/us0173ol/StockEx/blob/master/screenshots/Historical%20Data.PNG "Historical Data")

The My Portfolio sheet will keep a record of stocks you currently are invested in displaying the price you bought it for and the date purchased.  Everytime a stock is purchased and this table is populated, a sell button will be created so you can choose to sell the stock when you see fit.  If you try to sell more stock than you own, a message will appear informing you of the current number of shares you own and let you try again.  If you sell less than the total number of shares you own, the QTY will change on this sheet but the information will reamain.  If you sell all of the stock you own for that particular company, the data for that company will be removed along with the sell button associated with it.  Lastly this is where you can "deposit" more money in to your account to make purchases.  

## My Portfolio Sheet
![alt text](https://github.com/us0173ol/StockEx/blob/master/screenshots/MyPortfolio.PNG "My Portfolio")

The Sold Stock sheet will contain a record of every sale made regaurdless of quantity.  It will calculate profit and loss, your bank, and essentially give you a receipt of each sale made so you can track your ability to make good trades.  

## Stocks Sold Sheet
![alt text](https://github.com/us0173ol/StockEx/blob/master/screenshots/Stocks%20Sold.PNG "Stocks Sold")

