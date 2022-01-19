Facebook Friend List Scraper Bot
************************************************

Visit facebook and copy the profile link of whose friend list you want to scrape and paste the profile url in input box and click on the submit button. Facebook Friend List Scraper Bot will open the target user's profile and then open his friend list. when the friend list is opened, it will scrape all the friend's information like name and profile link and save the scraped data

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	datakund.facebook_login_password(email_address_or_phone_number="email",password="pass")
	#or
	linkedin_login_cookies(facebook_cookies="cookies")
	response = facebook_friendlist_scraper(facebook_profile_url="https://www.facebook.com/saibys")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.facebook_login_password("email@email.com","password")
	 //or
	 datakund.facebook_login_password("cookies")
         datakund.facebook_friendlist_scraper("https://www.facebook.com/saibys")
		 
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"facebook_login_password~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"email_address_or_phone_number":"email","password":"pass"}}'
		 				or
     curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"facebook_login_password~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"facebook_cookies":"cookies"}}'

		 
     curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"facebook_friendlist_scraper~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"facebook_profile_url":"https://www.facebook.com/saibys"}}'
		 
Response Data
##############

.. code-block:: json

	{
	"body": [
		{
		"name": "Liji Justine",
		"profile_links": "https://www.facebook.com/liji.tom"
		},
		{
		"name": "Jomin Varghese",
		"profile_links": "https://www.facebook.com/jomin.varghese.9"
		},
		{
		"name": "Soniya Francis",
		"profile_links": "https://www.facebook.com/soniya.francis.71"
		},
		{
		"name": "Shaji Chennangad",
		"profile_links": "https://www.facebook.com/shaji.chennangad"
		},
		{
		"name": "Perinchery Joshy Jose",
		"profile_links": "https://www.facebook.com/joshy.jose.1276"
		},
		{
		"name": "Anu Jiby",
		"profile_links": "https://www.facebook.com/anu.jiby"
		},
		{
		"name": "Sheena Jens",
		"profile_links": "https://www.facebook.com/sheena.jens"
		},
		{
		"name": "Haritha Stephen Mangalath",
		"profile_links": "https://www.facebook.com/haritha.stephen.3"
		}
	],
	"errors": [],
	"resume_variable": "n",
	"success_score": "100"
	}