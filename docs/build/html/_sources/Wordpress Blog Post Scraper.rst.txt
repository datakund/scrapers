Wordpress Blog Post Scraper
********************************

Posts are blog content listed in a reverse chronological order (newest content on top). You will see posts listed on your blog page. If you are using WordPress as a blog, then you will end up using posts for the majority of your website’s content. You can add and edit your WordPress posts from the ‘Posts’ menu in your dashboard.

This bot help to scrape the worldpress blog post

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.wordpress_blogs()

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.wordpress_blogs()
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"wordpress_blogs~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true}'

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

			