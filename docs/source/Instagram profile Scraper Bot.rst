Instagram profile Scraper Bot
********************************

Instagram profile Scraper Bot Scrapes bio, followers, followed_by, following, posts, profile_name with instagram profile_link

.. image:: images/instagram_profile_scraper.*

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.instagram_profile_scraper(profile_link="https://www.instagram.com/ashliemolstad/")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.instagram_profile_scraper("https://www.instagram.com/ashliemolstad/")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"instagram_profile_scraper~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"profile_link":"https://www.instagram.com/ashliemolstad/"}}'

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
	
