
Youtube Data Scrape
********************************

Scapres title, channel, views, date, likes, comments, subscribers in youtube

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	
	response = datakund.youtube_data_scrape(search='netlfix')

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.youtube_data_scrape("netlfix")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"youtube_data_scrape~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"search":"netlfix"}}'

Response Data
##############

.. code-block:: json

	{
	  "body": [
		{
		  "channel": "Marvel Entertainment",
		  "comments": "Welcome to chaos 🌙 Watch the new trailer for Marvel Studios’ Moon Knight and start streaming the Original series March 30 on Disney+.    ► Watch Marvel on Disney+:",
		  "date": "18 Jan 2022",
		  "likes": "307K",
		  "subscribers": "17.8M subscribers",
		  "title": "Marvel Studios’ Moon Knight | Official Trailer | Disney+",
		  "views": "2,123,416 views"
		},
		{
		  "channel": "OTZ Media",
		  "comments": "CASH (कैश) Official Hindi Trailer 2021 | Amol Parashar, Smiriti Kalra | Disney+      SUBSCRIBE  me for more videos at:",
		  "date": "9 Nov 2021",
		  "likes": "10K",
		  "subscribers": "625K subscribers",
		  "title": "CASH (कैश) Official Hindi Trailer 2021 | Amol Parashar, Smiriti Kalra | Disney+",
		  "views": "1,105,971 views"
		},
		{
		  "channel": "MOVIE ON",
		  "comments": null,
		  "date": "31 Dec 2021",
		  "likes": "2.2K",
		  "subscribers": "293K subscribers",
		  "title": "Boys Stuck in The Middle of Zombies and Must Use Their Wits and Courage to Survive",
		  "views": "216,703 views"
		}
	  ],
	  "errors": [],
	  "resume_variable": 3,
	  "success_score": "100"
	}
		