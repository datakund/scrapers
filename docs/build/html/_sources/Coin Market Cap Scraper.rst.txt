Coin Market Cap Scraper
********************************

List of the dead. The following list details the number of deaths reported by companies in business premises at the World Trade Center. This Bot scrapes 9/11 Victim List, the names of all of those who lost their lives in the attacks.

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.coinmarketcap_data_scrape()

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.coinmarketcap_data_scrape()
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"coinmarketcap_data_scrape~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true}'

Response Data
##############

.. code-block:: json

			
		{
		"body": [
		{
		  "circulating_supply": "18,932,731 BTC",
		  "market_cap": "$797,044,034,763",
		  "name": "Bitcoin",
		  "price": "$42,098.74",
		  "sr": "1",
		  "volume": "$22,201,677,810"
		},
		{
		  "7d": "2.22%",
		  "circulating_supply": "119,204,659 ETH",
		  "market_cap": "$380,198,314,558",
		  "name": "Ethereum",
		  "price": "$3,189.46",
		  "sr": "2",
		  "volume": "$12,446,260,038"
		},
		{
		  "7d": "9.06%",
		  "circulating_supply": "166,801,148 BNB",
		  "market_cap": "$78,893,657,901",
		  "name": "BNB",
		  "price": "$472.98",
		  "sr": "3",
		  "volume": "$2,085,284,462"
		},
		{
		  "24h": "0.01%",
		  "7d": "0.02%",
		  "circulating_supply": "78,304,569,301 USDT",
		  "market_cap": "$78,342,225,662",
		  "name": "Tether",
		  "price": "$1.00",
		  "sr": "4",
		  "volume": "$51,730,465,132"
		},
		{
		  "24h": "8.23%",
		  "7d": "35.90%",
		  "circulating_supply": "33,526,602,253 ADA",
		  "market_cap": "$52,924,420,838",
		  "name": "Cardano",
		  "price": "$1.58",
		  "sr": "5",
		  "volume": "$5,677,267,400"
		},
		{
		  "24h": "0.03%",
		  "circulating_supply": "45,536,865,009 USDC",
		  "market_cap": "$45,522,416,540",
		  "name": "USD Coin",
		  "price": "$0.9997",
		  "sr": "6",
		  "volume": "$2,904,679,026"
		},
		{
		  "7d": "1.47%",
		  "circulating_supply": "314,152,501 SOL",
		  "market_cap": "$43,747,704,393",
		  "name": "Solana",
		  "price": "$139.26",
		  "sr": "7",
		  "volume": "$1,437,074,661"
		},
		{
		  "7d": "1.54%",
		  "circulating_supply": "47,663,117,635 XRP",
		  "market_cap": "$36,145,294,013",
		  "name": "XRP",
		  "price": "$0.7583",
		  "sr": "8",
		  "volume": "$1,454,912,554"
		},
		{
		  "7d": "6.12%",
		  "circulating_supply": "358,044,017 LUNA",
		  "market_cap": "$27,606,349,430",
		  "name": "Terra",
		  "price": "$77.10",
		  "sr": "9",
		  "volume": "$1,921,553,192"
		},
		{
		  "7d": "5.03%",
		  "circulating_supply": "987,579,315 DOT",
		  "market_cap": "$25,192,258,233",
		  "name": "Polkadot",
		  "price": "$25.51",
		  "sr": "10",
		  "volume": "$1,349,143,918"
		}
		],
		"errors": [],
		"resume_variable": "n",
		"success_score": "100",
		"resume_dict": {}
		}
