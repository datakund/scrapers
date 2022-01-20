Coindesk Price Scraper with Commodity Link
************************************************

This bot helps to scrape price, price_24_changed, price_24_low, price_24_high with coin desk link
.. image:: images/coindesk_bitcoin.*

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	
	response = datakund.coindesk_bitcoin(currency_link="https://www.coindesk.com/price/ethereum/")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.coindesk_bitcoin("https://www.coindesk.com/price/ethereum/")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"coindesk_bitcoin~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"currency_link":"https://www.coindesk.com/price/ethereum/"}}'

Response Data
##############

.. code-block:: json

	{
	  "body": {
		"market_capital": "$373.16B",
		"price": "3,171.52",
		"price_24_changed": "-2.96%",
		"price_24_high": "$3,281.55",
		"price_24_low": "$3,144.64",
		"volume": "$669.33M"
	  },
	  "errors": [],
	  "resume_variable": 0,
	  "success_score": "100"
  }


	
