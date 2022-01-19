Investing.com World Indices Scraper
************************************************

Investing.com offers free real time quotes, portfolio, streaming charts, financial news, live stock market data and more. Investing.com World Indices Bot help to scrape the stock details of world indices from investing.com

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.investing_com_world_indices()

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.investing_com_world_indices()
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"investing_com_world_indices~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true}'

Response Data
##############

.. code-block:: json

			
	
	{
	  "body": [
		{
		  "adv.": "15",
		  "change": "-201.81",
		  "change_percent": "-0.56%",
		  "dec.": "15",
		  "last_price": "50.00%",
		  "stock_link": "/indices/us-30",
		  "stock_name": "Dow Jones"
		},
		{
		  "adv.": "211",
		  "dec.": "291",
		  "last_price": "0.59%",
		  "stock_link": "/indices/us-spx-500",
		  "stock_name": "S&P 500"
		},
		{
		  "adv.": "26",
		  "dec.": "14",
		  "last_price": "35.00%",
		  "stock_link": "/indices/germany-30",
		  "stock_name": "DAX"
		},
		{
		  "adv.": "173",
		  "dec.": "65",
		  "last_price": "0.83%",
		  "stock_link": "/indices/s-p-tsx-composite",
		  "stock_name": "S&P/TSX"
		},
		{
		  "adv.": "51",
		  "dec.": "160",
		  "last_price": "4.09%",
		  "stock_link": "/indices/japan-ni225",
		  "stock_name": "Nikkei 225"
		},
		{
		  "adv.": "82",
		  "dec.": "105",
		  "last_price": "4.59%",
		  "stock_link": "/indices/aus-200",
		  "stock_name": "S&P/ASX 200"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100"
	}