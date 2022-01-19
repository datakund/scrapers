Yahoo finance Scraper
********************************

Yahoo finance Scraper is a python library to scrape stock, stock prices and stock change of company, using browser automation.

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.yahoo_finance()

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.yahoo_finance()
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"yahoo_finance~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "stock": "S&P Futures",
		  "stock_change": "(-0.48%)",
		  "stock_price": "4,632.25"
		},
		{
		  "stock": "Dow Futures",
		  "stock_change": "(-0.23%)",
		  "stock_price": "35,712.00"
		},
		{
		  "stock": "Nasdaq Futures",
		  "stock_change": "(-1.01%)",
		  "stock_price": "15,437.75"
		},
		{
		  "stock": "Russell 2000 Futures",
		  "stock_change": "(-0.35%)",
		  "stock_price": "2,150.20"
		},
		{
		  "stock": "Crude Oil",
		  "stock_price": "84.95"
		},
		{
		  "stock": "Gold",
		  "stock_price": "1,816.70"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100"
	}
