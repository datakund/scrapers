Yelp Review Scraper
********************************

Scrape Yelp Review from Listing Link

Code
######
.. tabs::

   .. code-tab:: py 

        from bot_studio import *
	datakund = bot_studio.new()
	
	response = datakund.yelp_review(yelp_link="https://www.yelp.com/biz/saffron-grill-san-francisco")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.yelp_review("https://www.yelp.com/biz/saffron-grill-san-francisco")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"yelp_review~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"yelp_link":"https://www.yelp.com/biz/saffron-grill-san-francisco"}}'

Response Data
##############

.. code-block:: json

	{
	  "body": [
		{
		  "address": "Laurel Heights, San Francisco, CA",
		  "date": "12/21/2021",
		  "review": "My partner and I LOVE saffron grill. We used to order takeout from them at least twice a month (and the only reason why we stopped is bc we left sf). It was probably our favorite place in the city. To this day I've never had a better fish masala. When/if we ever come back to sf, we're coming for ya first thing, Saffron Grill!  sincerely, your biggest fans",
		  "review_by": "Eimi O.",
		  "reviewed": "0"
		},
		{
		  "date": "8/7/2021",
		  "review": "Good Indian food! Decent portions and prices are right in the sweet spot, $11 for vegetarian. I feel like a lot of places are $15-$16 so this is a great bang for your buck option. Be aware they don't give rice so if you want some you'll have to order it separately. Ordered garlic naan, yellow lentil curry and mixed vegetable curry. All really good with strong flavors. I should've asked for spicier. It was very mild when ordering generically off the website.",
		  "review_by": "Isaac A.",
		  "reviewed": "269"
		},
		{
		  "address": "New York, NY",
		  "date": "1/6/2022",
		  "review": "Saffron Grill has THE best naan in the Bay Area. I also love Saffron's chicken tikka masala and basmati rice! Definitely a great Indian spot in NoPa!",
		  "review_by": "Kate E.",
		  "reviewed": "2"
		},
		{
		  "address": "Baton Rouge, LA",
		  "date": "11/10/2021",
		  "review": "I used to love this place years ago. I moved back to sf recently and loved the idea of having a good neighborhood Indian spot nearby. Today was disappointing though. For $28 I ordered just a chicken korma and chicken tikka masala. The sauce for the tikka masala was very watery. The worst part was the chicken in both dishes, many pieces were very hard/chewy. Maybe not properly cooked? Maybe just bad quality? Either way it ruined the whole dish, and we couldn't even finish it.Sad to have lost what I once a considered a good neighborhood spot, but won't be going back.",
		  "review_by": "Emily T.",
		  "reviewed": "11"
		},
		{
		  "address": "San Francisco, CA",
		  "date": "12/23/2021",
		  "review": "This is my go to Indian food place in San Francisco. I usually get take out and order the paneer makhni (spicy), naan, and vegetable pakoras. The food is always consistently good and I get it at least once a month. The price is pretty fair as well. 10/10 recommend!",
		  "review_by": "Jashan K.",
		  "reviewed": "93"
		},
		{
		  "date": "11/15/2020",
		  "review_by": "Matt Y.",
		  "reviewed": "25"
		},
		{
		  "address": "Washington, DC",
		  "date": "2/24/2021",
		  "review_by": "Jillian J.",
		  "reviewed": "373"
		},
		{
		  "date": "7/24/2021",
		  "review": "Great food all around. Got samosas, raita, tandoori chicken, lamb curry....picked it up so everything was hot and fresh. Also naan. Will order again.",
		  "review_by": "Jordan C.",
		  "reviewed": "171"
		},
		{
		  "date": "1/29/2021",
		  "review": "So far this is the best Indian food in the city. My hometown is in the south bay and tInhe Indian community is more in abundance down where I am. I've gone to like one other place in the city. And it wasn't bad (I honestly can't remember too much of it). They didn't have Butter Chicken on their menu though which is one of my favorite dishes.My boyfriend randomly choose this spot while driving towards his usual Indian spot. And they happened to have not only Chicken Tikka Masala, but Butter Chicken as well. The meat honestly was whatever but the sauces here were some of the best I've ever had. Especially that Butter Chicken. Oof. Recommend their Butter Chicken.My boyfriend got the Chicken Vindaloo which was also really great in both of our opinions. (I think he liked my dish a tad bit more so I let him have the rest of my sauce). Their garlic and onion naan were the perfect companions to our dishes. My boyfriend says this place is better than his other normal spot and will be coming back again.",
		  "review_by": "Lilian L.",
		  "reviewed": "160"
		},
		{
		  "date": "4/18/2021",
		  "review": "Ordered the butter chicken and basmati rice with garlic nan and vegetable pakora. I have mixed feelings about my order. I loveeeeed the vegetable pakora and it was so crispy which is my favorite especially when it's take out. But when I received my order it was still crisp! But... I wasn't a huge fan of the butter chicken because it was too sweet for me. I will be back to try the chicken tikka masala instead to see how it compares!(:",
		  "review_by": "Alissa H.",
		  "reviewed": "446"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100"
	}