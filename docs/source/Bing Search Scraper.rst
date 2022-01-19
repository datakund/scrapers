Bing Search Scraper
********************************

Bing Search Scraper is a python library to scrape for a bing search result using browser automation.

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.bing_search_result_scraper(q="science")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.bing_search_result_scraper("science")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"bing_search_result_scraper~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"q":"science"}}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "description": "a systematic enterprise that builds and organizes knowledge in the form of testable explanations and predictions about the universe.",
		  "link": "https://en.wikipedia.org/wiki/Science",
		  "title": "Science - Wikipedia"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100",
	  "resume_dict": {}
	}