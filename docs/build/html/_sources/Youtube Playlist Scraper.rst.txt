Youtube Playlist Scraper
********************************

Scapres title, channel, channel_link, date, description, playlist_name, videos in youtube playlist

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.youtube_playlist(search='netlfix')

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.youtube_playlist("netlfix")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"youtube_playlist~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"search":"netlfix"}}'

Response Data
##############

.. code-block:: json

	{
	  "body": [
		{
		  "channel": "Netflix",
		  "channel_link": "https://www.youtube.com/channel/UCWOA1ZGywLbqmigxE4Qlvuw",
		  "date": "New in July 2021 | Netflix",
		  "description": "Netflix Our Planet | Full episodes | WWF collaboration",
		  "playlist_name": "Educational Documentaries | Netflix  Netflix",
		  "videos": "netflix",
		  "views": "360° Video"
		}
	  ],
	  "errors": [],
	  "resume_variable": 1,
	  "success_score": "100"
	}