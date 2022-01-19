Google Trends Scraper Bot
********************************

Enter the keyword of which data you want to scrape and click on submit button.
Bot will scrape trending searches related to the keyword in Google Search across various regions.

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.google_trends(keyword="apple")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.google_trends("apple")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"google_trends~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"keyword":"apple"}}'

Response Data
##############

.. code-block:: json

				{
	  "body": [
		{
		  "state": "Chandigarh",
		  "trend": "100"
		},
		{
		  "state": "Delhi",
		  "trend": "87"
		},
		{
		  "state": "Punjab",
		  "trend": "85"
		},
		{
		  "state": "Himachal Pradesh",
		  "trend": "81"
		},
		{
		  "state": "Haryana",
		  "trend": "77"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100"
	}