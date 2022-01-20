
Epoch Timestamp Converter Scraper
************************************************

Extract date and timezone with Timestamp

.. image:: images/epoch_timestamp_converter.*

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	
	response = datakund.epoch_timestamp_converter(time_stamp='1642480266')

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.epoch_timestamp_converter("1642480266")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"epoch_timestamp_converter~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"time_stamp":"1642480266"}}'

Response Data
##############

.. code-block:: json

	{
	 "body":{
	   "Review Terms": "sound quality noise cancellation battery life value for money extra bass price range battery backup call quality earbud stopped working right earbud listening to music charging case",
	   "NoOfRatings": "14,439 ratings",
	   "ReviewsLink": "https://www.amazon.in/Sony-WF-XB700-Wireless-Bluetooth-Headphones/product-reviews/B085VQFZ8Z/ref=cm_cr_dp_d_show_all_btm?ie=UTF8&reviewerType=all_reviews",
	   "Price": "7,886",
	   "Description": "Extra Bass: WF-XB700 features EXTRA BASS for seriously powerful, punchy low-end sound. Your favourite basslines never sounded so good with 12mm driver unit. Frequency Response (..............",
	   "Title": "Sony WF-XB700 Truly Wireless Extra Bass Bluetooth Earbuds with 18 Hours Battery Life, True Wireless Earbuds with Mic for Phone Calls, Quick Charge, BT Ver 5.0 (Black)"
	  }, 
	 "success_score": "100",
	 "errors": []
	}
	
