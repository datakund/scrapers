Amazon Product Price Scraper Bot
********************************

Any product that will appear in the search results page of Amazon. this bot Will scrape the price of all the products.

.. image:: images/amazon_prices_scrape.*

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.amazon_prices_scrape(field_keywords="shoes")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.amazon_prices_scrape("shoes")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"amazon_prices_scrape~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"field_keywords":"shoes"}}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "price": "499",
		  "title": "Men's Wonder-13 Sports Running Shoes"
		},
		{
		  "title": "Men's Running Shoe"
		},
		{
		  "title": "Men's Sd0323g Sneakers"
		},
		{
		  "title": "Men's Loire-z126 Running Shoes"
		},
		{
		  "title": "Men's Training Shoe"
		},
		{
		  "title": "Men's Stonic Running Shoes"
		},
		{
		  "price": "299",
		  "title": "Men's Running Shoe"
		},
		{
		  "title": "Men's Tywin Tr Training Shoe"
		},
		{
		  "price": "570",
		  "title": "Men's Cosko Running,Walking,Gym,Training Shoes"
		},
		{
		  "title": "Leather with Lace Casual Shoes for Men RC1200"
		},
		{
		  "title": "Men's Boss-Slick Uniform Dress Shoe"
		},
		{
		  "title": "Men's Tyson Running Shoes"
		},
		{
		  "title": "Ignite Men's Running Shoes"
		},
		{
		  "title": "neo Men's Vs Set Sneakers"
		},
		{
		  "title": "WoMen's Alexa Running Shoes"
		},
		{
		  "price": "599",
		  "title": "Cosco Running Shoes,Training Shoes,Gym Shoes,Sports Shoes,Walking Shoes for Men's"
		},
		{
		  "price": "599",
		  "title": "Men's Bouncer-01 Sports,Walking,Gym,Training,Running Shoes"
		},
		{
		  "price": "499",
		  "title": "Men's Sports Shoes"
		},
		{
		  "price": "343",
		  "title": "Men's Sports Shoes"
		},
		{
		  "title": "Men's Clinch-x M Running Shoe"
		},
		{
		  "price": "721",
		  "title": "Men's Oxyfit Running Shoes"
		},
		{
		  "title": "Men's Loire-z1 Running Shoes"
		},
		{
		  "price": "1,199",
		  "title": "Men's Missile-01 Running Shoes for Men I Sport Shoes for Boys with Beads Technology Sole for Extra Jump I Phylon Sole Casual Shoes for Men"
		},
		{
		  "price": "699",
		  "title": "Men's Hattrick-21 Sports Running Shoes"
		},
		{
		  "price": "1,359",
		  "title": "Men's North Plus Running Shoes"
		},
		{
		  "price": "539",
		  "title": "Men's Sneaker"
		},
		{
		  "price": "699",
		  "title": "Men's Creta-12 Running,Sports,Walking Shoes"
		},
		{
		  "price": "1,099",
		  "title": "Men's Rider-01 Phylon Sports,Running,Walking Shoes"
		},
		{
		  "title": "Men's Protonium Lite Running Shoe"
		},
		{
		  "title": "Tesla-44 Running Shoes for Men"
		},
		{
		  "price": "1,048",
		  "title": "WoMen's Inspire W Running Shoe"
		},
		{
		  "title": "Men's Boss-Grip Uniform Dress Shoe"
		},
		{
		  "title": "Men's Crysta Running Shoes"
		},
		{
		  "price": "559",
		  "title": "Men's Boss-ace Uniform Dress Shoe"
		},
		{
		  "price": "1,835",
		  "title": "Men's Comfort Infused Running Shoe"
		},
		{
		  "price": "999",
		  "title": "Oxygen-01 Running Shoes for Boys"
		},
		{
		  "title": "Men's Thunderwatch Running Shoe"
		},
		{
		  "price": "624",
		  "title": "Plasma-08 sports shoes for men | Latest Stylish Casual sport shoes for men | running shoes for boys | Lace up Lightweight navy shoes for running, walking, gym, trekking, hiking & party Running Shoes For Men"
		},
		{
		  "price": "574",
		  "title": "Men's Century-12 Running,Walking,Sports Shoes"
		},
		{
		  "title": "Men's Maxico Running Shoes"
		},
		{
		  "title": "Men's Go 600-Nile Running Shoe"
		},
		{
		  "title": "mens Sm-614 Running Shoe"
		},
		{
		  "title": "Men's Rso111 Walking Shoes"
		},
		{
		  "price": "1,679",
		  "title": "Men Starlight IDP Sneakers"
		},
		{
		  "price": "1,336",
		  "title": "Men's Running Shoe"
		},
		{
		  "price": "699",
		  "title": "Men's Running Shoes"
		},
		{
		  "price": "862",
		  "title": "Men's Sm-500 Running Shoe"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100",
	  "resume_dict": {}
	}
