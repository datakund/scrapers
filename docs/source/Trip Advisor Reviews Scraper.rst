Trip Advisor Reviews Scraper
********************************

Scrape reviews from Trip Advisor Link

.. image:: images/trip_advisor_reviews.*

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.trip_advisor_reviews(trip_advisor_link="https://www.tripadvisor.in/AttractionProductReview-g304551-d11455849-Four_Day_Private_Luxury_Golden_Triangle_Tour_to_Agra_and_Jaipur_From_New_Delhi-New.html")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.trip_advisor_reviews("https://www.tripadvisor.in/AttractionProductReview-g304551-d11455849-Four_Day_Private_Luxury_Golden_Triangle_Tour_to_Agra_and_Jaipur_From_New_Delhi-New.html")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"trip_advisor_reviews~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"trip_advisor_link":"https://www.tripadvisor.in/AttractionProductReview-g304551-d11455849-Four_Day_Private_Luxury_Golden_Triangle_Tour_to_Agra_and_Jaipur_From_New_Delhi-New.html"}}'

Response Data
##############

.. code-block:: json

	{
	  "body": [
		{
		  "review": "Excellent tour, great sites, good hotels (we stayed in Jaypee Palace in Agra and Holiday in City Center in Jaipur - 5 stars). The driver, Raj, was excellent (it is very difficult to drive in India), always on time, kept us safe. We had three guides with different styles, very professional, knowledgeable of the history and art associated to the different sites. The tour coordinator, Amit, communicated with us before, during, and after the trip, providing information and answers to all our questions. Amit has very high standards.",
		  "reviewer": "Victor Daniel E",
		  "time": "Written 16 December 2021",
		  "title": "Fantastic tour of Delhi, Agra, Jaipur"
		},
		{
		  "review": "I was slightly apprehensive as a lone female taking this trip but I shouldn’t have worried as I felt very well looked after by my driver, all the guides and staff in the hotels.  It was a fabulous trip with my it was all fabulous with my favourite part being the Amber Fort and the City Palace in Jaipur!  Mr Rawat was my driver and he was always punctual and I felt so safe as his driving skills were excellent unlike some of the other drivers on the road.  All the guides at each location really brought the places to life and were all very knowledgeable, spoke excellent English and took great photos too!!  My trip in March was just before lockdown and the guides were all instructed to wear face masks which they did.  The hotels were all really good in particular the Jaypee Palace in Agra.  There were options to go shopping which I chose not to do and there was no hard sell on this which I really did appreciate.  I would definitely recommend this trip to anyone-it exceeded my expectations.",
		  "reviewer": "Wendy of Wokingham",
		  "title": "Fabulous trip"
		},
		{
		  "review": "TLDR:Highlights: Qutub Minar, Sikh temple, Agra Fort, Taj Mahal, Amber Fort, Panna Meena step well, countryside drive, safety, great guides and drivers.Lowlights: closed Lotus temple bc of poor timing, lunch on the roadFrom start to finish this tour was well organized with a fantastic driver (ask if Mr. Ram Singh is available) and knowledgeable, clear guides throughout. We wanted a few changes made here and there the driver and the guides were happy to do so. For example, the Lotus Temple is actually closed in Delhi at certain times (this was the only poor planning), and it was closed when we arrived. We asked to do something else instead and went to a Sikh temple which was amazing! I do wish Red Fort in Delhi was on the agenda, but friends of ours had said to avoid Old Delhi during the time we were there (riots).We felt safe and well taken care of during our journey with a comfortable, nice air conditioned car and plenty of water. The driver and guides really cared about our experience and helped us out if there was anything we needed. The tour guide in Agra was like a professional photographer and historian all in one, amazing! The guides were good about warning us about scams and other uncomfortable situations we, as tourists might find ourselves in.You should consider booking your own hotels as it can be more affordable. On our journey, there were a few times we needed to stop for lunch. The restaurants we were taken to in Delhi (can't remember the name) and Jaipur (The Grand Peacock) were great but the one on the road to Jaipur was pretty overpriced and not very good. Have an idea of your journey route and tell the driver where to take you to eat via Google Maps, Zomato, etc- they are on your time and can take you anywhere along the way! Lastly, Amit, our tour manager with the company, was super responsive both before the trip and during the trip. For the great price and value and an overall fantastic time,I would recommend this tour to anyone wanting a taste of all three cities in a quick time.",
		  "reviewer": "Amber F",
		  "time": "Written 16 April 2020",
		  "title": "Excellent tour, highly recommend!"
		},
		{
		  "review": "The fine travelling facility and comfortable stay made the holiday superb with so much on the itinerary to enjoy and understand with authentic history. The monuments are beyond compare specially the Swami Bag Temple (must visit) in Agra for its three dimensional as well engraved art.",
		  "reviewer": "MUKUL GUPTA, ADVOCATE",
		  "time": "Written 14 April 2020",
		  "title": "Fascinating Taj, Mesmirizing Jaipur and Busting Delhi"
		},
		{
		  "review": "I did a lot of research before our trip and then highly customized our trip according to what appealed to us the most. We love culture and history so our trip focused mostly on that. We spent 7 nights/8 days in India, starting off with 2 nights in Delhi, 1 night in Agra, 2 nights in Jaipur and then ending the tour with another 2 nights back in Delhi. Day 1: We did our own thing and started off the morning with a quick tuk tuk ride to Lodhi Gardens (loads of photo ops here) which was very close to the hotel we were staying at. The Claridges Hotel was a fabulous base to stay in, lovely green part of the city. A lot of embassies in the area so very upmarket, and safe! We then visited the India Gate (ladies please dress VERY modestly here, no tight gym pants unless bum is covered...), took a tuk tuk to Connaught Place which was unfortunately closed and then took an uber all the way out to the fabulous Hindu Akshardham Temple. Loved the temple! So much to look at. No backpack type bags allowed in the temple, and no photos either. There are lockers for your bags. Day 2: We were collected promptly at 8am and spent a good few hours exploring Delhi. Just driving around the city is an experience itself! Watching every day people going about their day, animals and people all over the place, no obvious traffic rules or traffic lights... We visited the largest Sikh temple in Delhi - Gurudwara Bangla Sahib, a beautiful Muslim temple - Fatehpuri Masjid, explored Chandni Chowk on a rickshaw, spent some time at the stepwells (small but absolutely beautiful) and managed to see Humayans Tomb which was just stunning! Everything is quite close to each other in Delhi so it’s possible to fit a lot in. It just depends on your tolerance levels. Day 3: An early morning start to see the Taj Mahal. Arrived just after 6am, already crowds waiting. C/card machine wasn’t working so make sure you have cash in case. Separate lines for men and women to buy tickets. Also no backpacks. Early morning shots with the hazy background and sun filtering through makes for stunning photos! We spent almost 3hrs here, couldn’t tear ourselves away. Then it was on to the Agra Fort and MORE amazing things to see and photograph. If you love symmetry, lines, pillars, detailed motifs, colour then India is for you! We drove through to Jaipur at about lunch time stopping at the Chand Biori stepwells en route. Before arriving at our hotel we went to the Monkey temple. It’s very dirty compared to the other temples we visited but still very interesting. We arrived quite close to closing time and I would have preferred to have got there earlier or with a guide as it was pretty empty and we felt slightly unsafe. Day 4: Got to Amber Fort just after 8:30, and it was already hectic! We didn’t do the elephant ride but managed to get some great shots of them. This fort is just amazing and we ended up spending almost 3hrs here too.",
		  "reviewer": "SouthAfricaFiona",
		  "time": "Written 13 March 2020",
		  "title": "Fantastic Mom & teen son Trip"
		},
		{
		  "reviewer": "Dpsenior2605",
		  "time": "Written 13 March 2020",
		  "title": "Highly recommended"
		},
		{
		  "review": "5 of us, they provided at least an 8 seater mini bus, which was great. Very big. Driver was very friendly stopped at good toilets and good restaurants along the way. The 3 guides were very friendly, good English. 5 star hotels were really nice. Would highly recommend.",
		  "reviewer": "John H",
		  "time": "Written 13 March 2020",
		  "title": "Great tour"
		},
		{
		  "review": "We had excellent 4 day tour of Agra and Jaipur from New Delhi.Guides were excellent. Hotel Jaypee Palace in Agra was superb and our travel in luxury car with driver Shivraj Singh was best.Overall we really enjoyed the tour.",
		  "reviewer": "Vinod P",
		  "time": "Written 13 March 2020",
		  "title": "Dr Vinoda Porobo"
		},
		{
		  "review": "We had an amazing trip, everything from start to finish was perfect.  The only thing we didn't like, it was the fact that they brought us into some shops to buy stuff that we didn't need nor we didn't want to buy. However the overall experience was great, Our driver Rajesh was great and always available. He always had refreshments available for us on those hot Indian days.  The hotels were fantastic, we got upgraded in Jaipur to the Jaipur Palace.  that hotel itself made our trip special. From the moment we checked in to the checkout process.Overall I'd recommend this tour if you want to visit India for a brief tour.",
		  "reviewer": "herby g",
		  "time": "Written 12 March 2020",
		  "title": "Amazing Tour!!!"
		},
		{
		  "reviewer": "jennifermusella",
		  "title": "Golden triangle"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100"
	}
