
Wikipedia Current Events
********************************

Scrapes Wikipedia Current Events into title , description and link

.. image:: images/wikipedia_current_events.*

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.wikipedia_current_events()

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.wikipedia_current_events()
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"wikipedia_current_events~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "description": "The Hunga Tonga volcano erupts (satellite animation shown), causing damage in Tonga and tsunamis across the Pacific Ocean.",
		  "link": "/wiki/2022_Hunga_Tonga_eruption_and_tsunami",
		  "title": "Hunga Tonga volcano erupts"
		},
		{
		  "description": "An apartment fire in the Bronx, New York City, kills 17 people.",
		  "link": "/wiki/2022_Bronx_apartment_fire",
		  "title": "An apartment fire"
		},
		{
		  "description": "A rockfall at Furnas Lake in Capitólio, Brazil, kills 10 people.",
		  "link": "/wiki/Capit%C3%B3lio_rockfall",
		  "title": "A rockfall"
		},
		{
		  "description": "Sidney Poitier, the first black actor to win the Academy Award for Best Actor, dies at the age of 94.",
		  "link": "/wiki/Sidney_Poitier",
		  "title": "Sidney Poitier"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100",
	  "resume_dict": {}
	}
