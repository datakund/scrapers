9/11 Victim List Scraper
********************************

List of the dead. The following list details the number of deaths reported by companies in business premises at the World Trade Center. This Bot scrapes 9/11 Victim List, the names of all of those who lost their lives in the attacks.

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.nine_eleven_victim_list()

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.nine_eleven_victim_list()
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"nine_eleven_victim_list~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true}'


Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "Column A@txt": "Gordon M Aamoth, Jr"
		},
		{
		  "Column A@txt": "Edelmiro Abad"
		},
		{
		  "Column A@txt": "Laurence Christopher Abel"
		},
			{
		  "Column A@txt": "Igor Zukelman"
		}
	  ],
	  "errors": [],
	  "resume_variable": 0,
	  "success_score": "100"
	}			