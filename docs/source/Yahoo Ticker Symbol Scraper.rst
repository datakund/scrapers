Yahoo Ticker Symbol Scraper
********************************

Bot will visit finance.yahoo.com and scrape all the Ticker symbols with their respective prices

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.yahoo_ticker_symbol_downloader()

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.yahoo_ticker_symbol_downloader()
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"yahoo_ticker_symbol_downloader~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "last_price": "15,369.50",
		  "name": "Nasdaq 100 Mar 22",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Mini Dow Jones Indus.-$5 Mar 22",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "E-Mini S&P 500 Mar 22",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Nasdaq 100 Mar 22",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "E-mini Russell 2000 Index Futur",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Treasury Yield 10 Years",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Crude Oil Feb 22",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Mini Dow Jones Indus.-$5 Mar 22",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Tesla, Inc.",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "CBOE Volatility Index",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "E-Mini S&P 500 Mar 22",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Advanced Micro Devices, Inc.",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "NVIDIA Corporation",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Cielo Waste Solutions Corp.",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Semiconductor Manufacturing International Corporation",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Exxon Mobil Corporation",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "ProShares UltraPro QQQ",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Air Canada",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "The Toronto-Dominion Bank",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Invesco QQQ Trust",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Apple Inc.",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "The Trade Desk, Inc.",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "The Goldman Sachs Group, Inc.",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Tencent Holdings Limited",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "STAG Industrial, Inc.",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "BrainChip Holdings Ltd",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "ProShares UltraPro Short QQQ",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Tesla, Inc.",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "SPDR S&P 500 ETF Trust",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		},
		{
		  "last_price": "15,369.50",
		  "name": "Occidental Petroleum Corporation",
		  "price_change": "-226.25",
		  "price_change_percent": "-1.45%",
		  "symbol": "NQ=F"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100"
	  }