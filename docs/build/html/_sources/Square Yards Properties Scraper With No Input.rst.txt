Square Yards Properties Scraper With No Input
************************************************

Bot will visit suareyard.com and scrape the price, location, name and link of square yard properties

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.square_yards_properties()

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.square_yards_properties()
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"square_yards_properties~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "features": "2 BHK-3 BHK Flat",
		  "location": "Sector 61",
		  "price": "1.25 Cr",
		  "property": "Smart World Orchard",
		  "sy_link": "https://www.squareyards.com/gurgaon-residential-property/smart-world-orchard/103238/project"
		},
		{
		  "features": "2 BHK-3 BHK Flat",
		  "location": "Sector 89",
		  "price": "68.00 Lac",
		  "property": "Smart World Gems",
		  "sy_link": "https://www.squareyards.com/gurgaon-residential-property/smart-world-gems/106590/project"
		},
		{
		  "features": "100 Sq. Ft. to 200 Sq. Ft. (Carpet)",
		  "location": "Sector 90",
		  "price": "8.78 Lac",
		  "property": "Alphathum",
		  "sy_link": "https://www.squareyards.com/noida-residential-property/alphathum/8681/project"
		},
		{
		  "features": "2 BHK-3 BHK Flat",
		  "location": "Budigere",
		  "price": "44.30 Lac",
		  "property": "Shriram Codename Yuva",
		  "sy_link": "https://www.squareyards.com/bangalore-residential-property/shriram-codename-yuva/101286/project"
		},
		{
		  "features": "1 BHK-2 BHK Flat",
		  "location": "Hinjewadi",
		  "price": "31.81 Lac",
		  "property": "Kolte Patil Life Republic Universe",
		  "sy_link": "https://www.squareyards.com/pune-residential-property/kolte-patil-life-republic-universe/102376/project"
		},
		{
		  "features": "3 BHK Flat",
		  "location": "Sector 89",
		  "price": "1.04 Cr",
		  "property": "M3M Soulitude",
		  "sy_link": "https://www.squareyards.com/gurgaon-residential-property/m3m-soulitude/106807/project"
		},
		{
		  "features": "2 BHK-3 BHK Flat",
		  "location": "Dhankawadi",
		  "price": "32.16 Lac",
		  "property": "4 Taljai Hills Phase 1",
		  "sy_link": "https://www.squareyards.com/pune-residential-property/4-taljai-hills-phase-1/102123/project"
		},
		{
		  "features": "1 BHK-2 BHK-3 BHK-4 BHK Flat",
		  "location": "Mulund West",
		  "price": "1.01 Cr",
		  "property": "Piramal Revanta Tower 3 and 4",
		  "sy_link": "https://www.squareyards.com/mumbai-residential-property/piramal-revanta-tower-3-and-4/100528/project"
		},
		{
		  "features": "1200 Sq. Ft. to 3200 Sq. Ft. (Carpet)",
		  "location": "Devanahalli",
		  "price": "56.39 Lac",
		  "property": "Puravankara Tivoli Hills",
		  "sy_link": "https://www.squareyards.com/bangalore-residential-property/puravankara-tivoli-hills/109172/project"
		},
		{
		  "features": "67 Sq. Ft. to 1098 Sq. Ft. (Carpet)",
		  "location": "Sector 150",
		  "price": "29.90 Lac",
		  "property": "Bhutani City Center",
		  "sy_link": "https://www.squareyards.com/noida-residential-property/bhutani-city-center/109184/project"
		},
		{
		  "features": "1 BHK-2 BHK-3 BHK-4 BHK Flat",
		  "location": "Powai",
		  "price": "1.25 Cr",
		  "property": "LnT Realty Emerald Isle",
		  "sy_link": "https://www.squareyards.com/mumbai-residential-property/lnt-realty-emerald-isle/2951/project"
		},
		{
		  "features": "1 BHK-2 BHK Flat",
		  "location": "Mira Bhayandar",
		  "price": "44.39 Lac",
		  "property": "JP Codename Hotcake",
		  "sy_link": "https://www.squareyards.com/mumbai-residential-property/jp-codename-hotcake/10457/project"
		},
		{
		  "features": "1163 Sq. Ft. to 3875 Sq. Ft. (Carpet)",
		  "location": "Sarjapur Road",
		  "price": "65.13 Lac",
		  "property": "Prestige Great Acres",
		  "sy_link": "https://www.squareyards.com/bangalore-residential-property/prestige-great-acres/111122/project"
		},
		{
		  "features": "3 BHK Flat",
		  "location": "Sector 150",
		  "price": "79.90 Lac",
		  "property": "Tata Eureka Park Phase 2",
		  "sy_link": "https://www.squareyards.com/noida-residential-property/tata-eureka-park-phase-2/112905/project"
		},
		{
		  "features": "2 BHK Flat",
		  "location": "Kandivali West",
		  "price": "1.34 Cr",
		  "property": "Ruparel Mumbai XL",
		  "sy_link": "https://www.squareyards.com/mumbai-residential-property/ruparel-mumbai-xl/111437/project"
		},
		{
		  "features": "1 BHK-2 BHK-3 BHK Flat",
		  "location": "Bavdhan",
		  "price": "51.00 Lac",
		  "property": "Goel Ganga Legend",
		  "sy_link": "https://www.squareyards.com/pune-residential-property/goel-ganga-legend/2123/project"
		},
		{
		  "features": "1 BHK-2 BHK-3 BHK Flat",
		  "location": "Mahalunge Ingale",
		  "price": "39.55 Lac",
		  "property": "Godrej Hillside",
		  "sy_link": "https://www.squareyards.com/pune-residential-property/godrej-hillside/10730/project"
		},
		{
		  "features": "1 BHK-2 BHK-3 BHK Flat",
		  "location": "Manjari",
		  "price": "25.07 Lac",
		  "property": "Godrej Park Ridge",
		  "sy_link": "https://www.squareyards.com/pune-residential-property/godrej-park-ridge/103462/project"
		},
		{
		  "features": "506 Sq. Ft. to 760 Sq. Ft. (Carpet)",
		  "location": "Baner",
		  "price": "70.54 Lac",
		  "property": "Mittal One Place",
		  "sy_link": "https://www.squareyards.com/pune-residential-property/mittal-one-place/111696/project"
		},
		{
		  "features": "1 BHK-2 BHK-3 BHK Flat",
		  "location": "Mundhwa",
		  "price": "19.54 Lac",
		  "property": "Purva Silversands",
		  "sy_link": "https://www.squareyards.com/pune-residential-property/purva-silversands/34407/project"
		},
		{
		  "features": "2 BHK-3 BHK Flat",
		  "location": "Hinjewadi",
		  "price": "49.55 Lac",
		  "property": "Mittal SkyHigh Towers",
		  "sy_link": "https://www.squareyards.com/pune-residential-property/mittal-skyhigh-towers/112990/project"
		},
		{
		  "features": "1 BHK-2 BHK Flat",
		  "location": "Bavdhan",
		  "price": "23.75 Lac",
		  "property": "Puraniks Abitante Fiore",
		  "sy_link": "https://www.squareyards.com/pune-residential-property/puraniks-abitante-fiore/100339/project"
		},
		{
		  "features": "2 BHK Flat",
		  "location": "Bhugaon",
		  "price": "59.28 Lac",
		  "property": "Paranjape Forest Trails Highland Tower 9 10 and 11",
		  "sy_link": "https://www.squareyards.com/pune-residential-property/paranjape-forest-trails-highland-tower-9-10-and-11/100539/project"
		},
		{
		  "features": "2 BHK-3 BHK Flat",
		  "location": "Pimple Nilakh",
		  "price": "96.80 Lac",
		  "property": "Yashada Epic Phase 2",
		  "sy_link": "https://www.squareyards.com/pune-residential-property/yashada-epic-phase-2/103650/project"
		},
		{
		  "features": "2 BHK-3 BHK-4 BHK Flat",
		  "location": "Bachupally",
		  "price": "57.14 Lac",
		  "property": "Urbanrise Codename Talk Of Hyderabad",
		  "sy_link": "https://www.squareyards.com/hyderabad-residential-property/urbanrise-codename-talk-of-hyderabad/101894/project"
		},
		{
		  "features": "2 BHK-3 BHK Flat",
		  "location": "Patancheru",
		  "price": "59.00 Lac",
		  "property": "Ramky One Symphony",
		  "sy_link": "https://www.squareyards.com/hyderabad-residential-property/ramky-one-symphony/103970/project"
		},
		{
		  "features": "2 BHK-3 BHK Flat",
		  "location": "Moti Nagar",
		  "price": "85.00 Lac",
		  "property": "Brigade Citadel Phase II",
		  "sy_link": "https://www.squareyards.com/hyderabad-residential-property/brigade-citadel-phase-ii/104062/project"
		},
		{
		  "features": "2 BHK-3 BHK Flat",
		  "location": "Sanath Nagar",
		  "price": "1.05 Cr",
		  "property": "Kalpataru Avante",
		  "sy_link": "https://www.squareyards.com/hyderabad-residential-property/kalpataru-avante/110954/project"
		},
		{
		  "features": "2 BHK-3 BHK Flat",
		  "location": "Hosahalli",
		  "price": "92.00 Lac",
		  "property": "Puravankara Purva Zenium",
		  "sy_link": "https://www.squareyards.com/bangalore-residential-property/puravankara-purva-zenium/10487/project"
		},
		{
		  "features": "1 BHK-2 BHK Flat",
		  "location": "Hinjewadi",
		  "price": "36.53 Lac",
		  "property": "Paranjape Trident Towers",
		  "sy_link": "https://www.squareyards.com/pune-residential-property/paranjape-trident-towers/9368/project"
		},
		{
		  "features": "1 BHK-2 BHK Flat",
		  "location": "Hinjewadi",
		  "price": "33.80 Lac",
		  "property": "Kolte Patil Life Republic Oro Avenue",
		  "sy_link": "https://www.squareyards.com/pune-residential-property/kolte-patil-life-republic-oro-avenue/10279/project"
		},
		{
		  "features": "1 BHK-2 BHK-3 BHK-4 BHK Flat",
		  "location": "Thanisandra Main Road",
		  "price": "33.71 Lac",
		  "property": "Bhartiya City Nikoo Homes 4",
		  "sy_link": "https://www.squareyards.com/bangalore-residential-property/bhartiya-city-nikoo-homes-4/109546/project"
		},
		{
		  "features": "1 BHK-2 BHK-3 BHK Flat",
		  "location": "Dahisar East",
		  "price": "83.54 Lac",
		  "property": "MICL Aaradhya Prime Park",
		  "sy_link": "https://www.squareyards.com/mumbai-residential-property/micl-aaradhya-prime-park/112326/project"
		},
		{
		  "features": "1 BHK-2 BHK-3 BHK Flat",
		  "location": "Andheri West",
		  "price": "1.26 Cr",
		  "property": "Transcon Triumph Tower 3",
		  "sy_link": "https://www.squareyards.com/mumbai-residential-property/transcon-triumph-tower-3/102847/project"
		},
		{
		  "features": "1 BHK-2 BHK Flat",
		  "location": "Mahim West",
		  "price": "1.46 Cr",
		  "property": "Prescon Midtown Bay",
		  "sy_link": "https://www.squareyards.com/mumbai-residential-property/prescon-midtown-bay/111905/project"
		},
		{
		  "features": "2 BHK Flat",
		  "location": "Wakad",
		  "price": "53.19 Lac",
		  "property": "Jhamtani Ace Almighty Phase I",
		  "sy_link": "https://www.squareyards.com/pune-residential-property/jhamtani-ace-almighty-phase-i/21761/project"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100"
	}