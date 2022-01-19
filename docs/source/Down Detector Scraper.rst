Down Detector Scraper
********************************

Down Detector Issue Scraper, Detect Problem percentage with top problems in any Brand
Scrapes issues in brand with top parameters in down detector , Detect Problem percentage with top problems in any Brand

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	
	response = datakund.down_detector()

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.down_detector()
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"down_detector~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true}'

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
	
