Google Search Result Scraper
********************************

Google Search Result Scraper is a python library to scrape for a google search result using browser automation
.. image:: images/google_search_result_scraper.*

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.google_search_result_scraper(search="science")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.google_search_result_scraper("science")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"google_search_result_scraper~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"search":"science"}}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "link": "https://en.wikipedia.org/wiki/Science",
		  "title": "Science - Wikipedia"
		},
		{
		  "description": "Science, any system of knowledge that is concerned with the physical world and its phenomena and that entails unbiased observations and systematic",
		  "link": "https://www.britannica.com/science/science",
		  "title": "science | Definition, Disciplines, & Facts | Britannica"
		},
		{
		  "link": "https://www.sciencedirect.com/",
		  "title": "ScienceDirect.com | Science, health and medical journals, full ..."
		},
		{
		  "link": "https://iisc.ac.in/",
		  "title": "Indian Institute of Science"
		},
		{
		  "link": "https://plos.org/",
		  "title": "PLOS: Home"
		},
		{
		  "link": "https://www.sciencenews.org/",
		  "title": "Science News | The latest news from all areas of science"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100",
	  "resume_dict": {}
		}
