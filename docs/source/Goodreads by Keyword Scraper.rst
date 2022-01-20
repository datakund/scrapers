Goodreads by Keyword Scraper
********************************

Scrapes Books Information on Goodreads by Keyword
.. image:: images/goodreads_keywords.*

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	
	response = datakund.goodreads_keywords(keyword="rich dad poor dad")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.goodreads_keywords("rich dad poor dad")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"goodreads_keywords~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"keyword":"rich dad poor dad"}}'

Response Data
##############

.. code-block:: json

	{
	  "body": {
		"bio": "Life Coach & Podcast Host @youcansipwithus ⁣⁣Passionate about helping women live a life they love, without waiting on the weight💞🤸🏼‍♀️⁣",
		"followed_by": "1,102",
		"followers": "213k",
		"following": "1,102",
		"posts": "5,259",
		"profile_name": "ashliemolstad"
	  },
	  "errors": [],
	  "resume_variable": 0,
	  "success_score": "100"
	}
	
