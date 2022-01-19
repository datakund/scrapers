Trading View Market Indices Scraper
************************************************

Trading View Market Indices Scraper Scrapes Indices From Trading View Market

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.trading_view_market_indices()

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.trading_view_market_indices()
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"trading_view_market_indices~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "link": "https://in.tradingview.com/symbols/SPX/",
		  "stock": "S&P 500"
		},
		{
		  "link": "https://in.tradingview.com/symbols/DJ-DJI/",
		  "price": "35911.82",
		  "price_change": "−201.81",
		  "price_change_percent": "−0.56%",
		  "stock": "Dow 30"
		},
		{
		  "link": "https://in.tradingview.com/symbols/XETR-DAX/",
		  "price": "15833.570",
		  "price_change": "−100.150",
		  "price_change_percent": "−0.63%",
		  "stock": "DAX"
		},
		{
		  "link": "https://in.tradingview.com/symbols/TVC-UKX/",
		  "price_change": "−48.29",
		  "price_change_percent": "−0.63%",
		  "stock": "UK 100"
		},
		{
		  "link": "https://in.tradingview.com/symbols/TVC-NI225/",
		  "price": "28257.18",
		  "price_change": "−76.27",
		  "price_change_percent": "−0.27%",
		  "stock": "Nikkei 225"
		},
		{
		  "link": "https://in.tradingview.com/symbols/TVC-HSI/",
		  "price": "24112.79",
		  "price_change": "−105.25",
		  "price_change_percent": "−0.43%",
		  "stock": "Hang Seng"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100"
	  } 


			