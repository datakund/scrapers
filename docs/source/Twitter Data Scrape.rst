Twitter Data Scrape
********************************

Twitter Data Scrape with Profile Link without login to twitter.Scrapes Twitter Data Scrape with Profile Link like followers, total tweets, following , joined date etc.

.. image:: images/twitter_analyzer.*

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.twitter_analyzer(profile_link="https://twitter.com/MAS")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.twitter_analyzer("https://twitter.com/MAS")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"twitter_analyzer~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"profile_link":"https://twitter.com/MAS"}}'

Response Data
##############

.. code-block:: json

	{
	  "body": {
		"description": "Proudly flying the nation's flag and connecting places and hearts through our inimitable Malaysian Hospitality.",
		"followers": "1.7M",
		"following": "Following",
		"joined": "Joined January 2009",
		"profile": "Malaysia Airlines",
		"tweets": "70.3K Tweets"
	  },
	  "errors": [],
	  "resume_variable": 0,
	  "success_score": "100"
		}

	
