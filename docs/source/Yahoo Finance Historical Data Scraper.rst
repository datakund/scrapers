Yahoo Finance Historical Data Scraper
************************************************

Yahoo! Finance is a media property that is part of the Yahoo! network. It provides financial news, data and commentary including stock quotes, press releases, financial reports, and original content. It also offers some online tools for personal finance management. With the help of Yahoo Finance Scrape Bot you can scrape Historical Data of any stock link from yahoo finance.

How Does it Work?

Run the bot, Enter Stock Link and click submit button and bot will scrape all the historical data of the given stock link yahoo finance.

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.yahoo_finance_historical_data(stock_link="https://finance.yahoo.com/quote/YM%3DF?p=YM%3DF")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.yahoo_finance_historical_data("https://finance.yahoo.com/quote/YM%3DF?p=YM%3DF")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"yahoo_finance_historical_data~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"stock_link":"https://finance.yahoo.com/quote/YM%3DF?p=YM%3DF"}}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "current_price": "2,151.60",
		  "stock_name": "E-mini Russell 2000 Index Futur (RTY=F)"
		},
		{
		  "adj_close": "2,151.60",
		  "date": "Jan 18, 2022",
		  "high": "2,168.60",
		  "low": "2,143.90",
		  "open": "2,162.30",
		  "volume": "27,076"
		},
		{
		  "adj_close": "2,157.70",
		  "date": "Jan 14, 2022",
		  "high": "2,163.30",
		  "low": "2,120.20",
		  "open": "2,157.00",
		  "volume": "225,874"
		},
		{
		  "adj_close": "2,155.50",
		  "date": "Jan 13, 2022",
		  "high": "2,197.50",
		  "low": "2,148.80",
		  "open": "2,176.50",
		  "volume": "225,874"
		},
		{
		  "adj_close": "2,173.10",
		  "date": "Jan 12, 2022",
		  "high": "2,209.30",
		  "low": "2,161.30",
		  "open": "2,190.20",
		  "volume": "203,930"
		},
		{
		  "adj_close": "2,190.40",
		  "date": "Jan 11, 2022",
		  "high": "2,194.00",
		  "low": "2,144.50",
		  "open": "2,168.50",
		  "volume": "200,103"
		},
		{
		  "adj_close": "2,168.00",
		  "date": "Jan 10, 2022",
		  "high": "2,184.10",
		  "low": "2,125.90",
		  "open": "2,172.80",
		  "volume": "310,296"
		},
		{
		  "adj_close": "2,175.90",
		  "date": "Jan 07, 2022",
		  "high": "2,219.80",
		  "low": "2,173.20",
		  "open": "2,207.70",
		  "volume": "230,479"
		},
		{
		  "adj_close": "2,202.70",
		  "date": "Jan 06, 2022",
		  "high": "2,220.50",
		  "low": "2,173.70",
		  "open": "2,189.30",
		  "volume": "267,822"
		},
		{
		  "adj_close": "2,190.60",
		  "date": "Jan 05, 2022",
		  "high": "2,276.40",
		  "low": "2,187.50",
		  "open": "2,267.20",
		  "volume": "248,172"
		},
		{
		  "adj_close": "2,266.50",
		  "date": "Jan 04, 2022",
		  "high": "2,288.60",
		  "low": "2,250.80",
		  "open": "2,268.90",
		  "volume": "182,380"
		},
		{
		  "adj_close": "2,269.40",
		  "date": "Jan 03, 2022",
		  "high": "2,284.40",
		  "low": "2,244.20",
		  "open": "2,247.60",
		  "volume": "222,614"
		},
		{
		  "adj_close": "2,242.80",
		  "date": "Dec 31, 2021",
		  "high": "2,258.80",
		  "low": "2,231.40",
		  "open": "2,245.90",
		  "volume": "134,759"
		},
		{
		  "adj_close": "2,246.90",
		  "date": "Dec 30, 2021",
		  "high": "2,272.30",
		  "low": "2,237.60",
		  "open": "2,244.40",
		  "volume": "122,020"
		},
		{
		  "adj_close": "2,247.80",
		  "date": "Dec 29, 2021",
		  "high": "2,252.60",
		  "low": "2,229.80",
		  "open": "2,247.10",
		  "volume": "132,269"
		},
		{
		  "adj_close": "2,243.80",
		  "date": "Dec 28, 2021",
		  "high": "2,275.20",
		  "low": "2,240.80",
		  "open": "2,259.10",
		  "volume": "145,387"
		},
		{
		  "adj_close": "2,259.60",
		  "date": "Dec 27, 2021",
		  "high": "2,260.30",
		  "low": "2,222.70",
		  "open": "2,238.00",
		  "volume": "130,970"
		},
		{
		  "adj_close": "2,236.90",
		  "date": "Dec 23, 2021",
		  "high": "2,245.00",
		  "low": "2,220.10",
		  "open": "2,220.90",
		  "volume": "135,494"
		},
		{
		  "adj_close": "2,219.30",
		  "date": "Dec 22, 2021",
		  "high": "2,223.50",
		  "low": "2,187.50",
		  "open": "2,203.00",
		  "volume": "178,647"
		},
		{
		  "adj_close": "2,199.70",
		  "date": "Dec 21, 2021",
		  "high": "2,204.60",
		  "low": "2,135.00",
		  "open": "2,139.80",
		  "volume": "206,131"
		},
		{
		  "adj_close": "2,135.90",
		  "date": "Dec 20, 2021",
		  "high": "2,173.60",
		  "low": "2,102.30",
		  "open": "2,169.00",
		  "volume": "292,340"
		},
		{
		  "adj_close": "2,142.43",
		  "date": "Dec 17, 2021",
		  "high": "2,160.70",
		  "low": "2,132.00",
		  "open": "2,152.70",
		  "volume": "334,169"
		},
		{
		  "adj_close": "2,151.90",
		  "date": "Dec 16, 2021",
		  "high": "2,227.60",
		  "low": "2,141.30",
		  "open": "2,198.50",
		  "volume": "56,533"
		},
		{
		  "adj_close": "2,198.10",
		  "date": "Dec 15, 2021",
		  "high": "2,201.90",
		  "low": "2,130.10",
		  "open": "2,164.30",
		  "volume": "83,275"
		},
		{
		  "adj_close": "2,161.30",
		  "date": "Dec 14, 2021",
		  "high": "2,195.30",
		  "low": "2,152.40",
		  "open": "2,184.60",
		  "volume": "155,043"
		},
		{
		  "adj_close": "2,180.00",
		  "date": "Dec 13, 2021",
		  "high": "2,227.20",
		  "low": "2,167.20",
		  "open": "2,209.40",
		  "volume": "258,168"
		},
		{
		  "adj_close": "2,212.40",
		  "date": "Dec 10, 2021",
		  "high": "2,244.90",
		  "low": "2,196.00",
		  "open": "2,219.00",
		  "volume": "243,187"
		},
		{
		  "adj_close": "2,218.40",
		  "date": "Dec 09, 2021",
		  "high": "2,274.10",
		  "low": "2,214.40",
		  "open": "2,269.00",
		  "volume": "265,664"
		},
		{
		  "adj_close": "2,269.80",
		  "date": "Dec 08, 2021",
		  "high": "2,279.90",
		  "low": "2,243.90",
		  "open": "2,262.10",
		  "volume": "200,531"
		},
		{
		  "adj_close": "2,253.90",
		  "date": "Dec 07, 2021",
		  "high": "2,274.30",
		  "low": "2,201.70",
		  "open": "2,207.90",
		  "volume": "217,576"
		},
		{
		  "adj_close": "2,203.60",
		  "date": "Dec 06, 2021",
		  "high": "2,220.40",
		  "low": "2,149.80",
		  "open": "2,166.40",
		  "volume": "250,218"
		},
		{
		  "adj_close": "2,159.30",
		  "date": "Dec 03, 2021",
		  "high": "2,222.50",
		  "low": "2,139.20",
		  "open": "2,214.70",
		  "volume": "327,736"
		},
		{
		  "adj_close": "2,205.20",
		  "date": "Dec 02, 2021",
		  "high": "2,213.10",
		  "low": "2,143.50",
		  "open": "2,146.00",
		  "volume": "332,772"
		},
		{
		  "adj_close": "2,146.30",
		  "date": "Dec 01, 2021",
		  "high": "2,255.90",
		  "low": "2,136.80",
		  "open": "2,213.80",
		  "volume": "373,963"
		},
		{
		  "date": "Nov 30, 2021",
		  "high": "2,258.30",
		  "open": "2,244.70"
		}
	  ],
	  "errors": [],
	  "resume_variable": 33,
	  "success_score": "100"
	}