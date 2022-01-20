Gaana Scraper
****************

Gaana Scraper extract data from gaana playlist

.. image:: images/gaana_playlist.*

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.gaana_playlist(playlist_link="https://gaana.com/playlist/gaana-dj-hindi-top-50-1")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.gaana_playlist("https://gaana.com/playlist/gaana-dj-hindi-top-50-1")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"gaana_playlist~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"playlist_link":"https://gaana.com/playlist/gaana-dj-hindi-top-50-1"}}'

Response Data
##############

.. code-block:: json

	{
	  "body": [
		{
		  "album": "Shershaah",
		  "artists": "Jubin Nautiyal",
		  "duration": "03:50",
		  "track": "Raataan Lambiyan",
		  "track_link": "/song/raataan-lambiyan-from-shershaah"
		},
		{
		  "duration": "03:11",
		  "track": "Pyaar Karte Ho Na",
		  "track_link": "/song/pyaar-karte-ho-na"
		},
		{
		  "duration": "03:43",
		  "track": "Dance Meri Rani",
		  "track_link": "/song/dance-meri-rani-1"
		},
		{
		  "duration": "04:51",
		  "track": "Rait Zara Si",
		  "track_link": "/song/rait-zara-si-from-atrangi-re"
		},
		{
		  "duration": "04:20",
		  "track": "Aashiqui Aa Gayi",
		  "track_link": "/song/aashiqui-aa-gayifrom-radhe-shyam"
		},
		{
		  "duration": "04:43",
		  "track": "Soch Liya",
		  "track_link": "/song/soch-liya-from-radhe-shyam"
		},
		{
		  "duration": "03:44",
		  "track": "Srivalli",
		  "track_link": "/song/srivalli-from-pushpa-the-rise-part-01"
		},
		{
		  "artists": "Jubin Nautiyal",
		  "duration": "04:44",
		  "track": "Meri Zindagi Hai Tu",
		  "track_link": "/song/meri-zindagi-hai-tu-from-satyameva-jayate-2"
		},
		{
		  "artists": "Jubin Nautiyal",
		  "duration": "04:33",
		  "track": "Dil Galti Kar Baitha Hai (Feat. Mouni Roy)",
		  "track_link": "/song/dil-galti-kar-baitha-hai-feat-mouni-roy"
		},
		{
		  "duration": "03:16",
		  "track": "Kusu Kusu",
		  "track_link": "/song/kusu-kusu"
		},
		{
		  "duration": "03:19",
		  "track": "Phoonk Le",
		  "track_link": "/song/phoonk-le"
		},
		{
		  "duration": "03:40",
		  "track": "Slow Slow",
		  "track_link": "/song/slow-slow-23"
		},
		{
		  "artists": "Jubin Nautiyal",
		  "duration": "04:18",
		  "track": "Udd Jaa Parindey",
		  "track_link": "/song/udd-jaa-parindey-from-radhe-shyam"
		},
		{
		  "duration": "03:51",
		  "track": "Jugnu",
		  "track_link": "/song/jugnu-18"
		},
		{
		  "duration": "04:46",
		  "track": "Mere Yaaraa",
		  "track_link": "/song/mere-yaaraa"
		},
		{
		  "album": "Shershaah",
		  "duration": "03:48",
		  "track": "Ranjha",
		  "track_link": "/song/ranjha-from-shershaah"
		},
		{
		  "duration": "03:55",
		  "track": "Mohabbat Hai",
		  "track_link": "/song/mohabbat-hai-3"
		},
		{
		  "duration": "03:46",
		  "track": "Oo Bolega Ya Oo Oo Bolega",
		  "track_link": "/song/oo-bolega-ya-oo-oo-bolega-from-pushpa-the-rise-part-01"
		},
		{
		  "duration": "04:10",
		  "track": "Tip Tip",
		  "track_link": "/song/tip-tip-from-sooryavanshi"
		},
		{
		  "duration": "03:47",
		  "track": "Saami Saami",
		  "track_link": "/song/saami-saami-from-pushpa-the-rise-part-01"
		},
		{
		  "duration": "03:34",
		  "track": "Panghat",
		  "track_link": "/song/madhuban-3"
		},
		{
		  "duration": "05:19",
		  "track": "Tumse Bhi Zyada",
		  "track_link": "/song/tumse-bhi-zyada-from-tadap"
		},
		{
		  "artists": "Jubin Nautiyal",
		  "duration": "05:09",
		  "track": "Tu Mera Hogaya Hai",
		  "track_link": "/song/tu-mera-hogaya-hai-from-tadap"
		},
		{
		  "duration": "04:07",
		  "track": "Tenu Lehenga",
		  "track_link": "/song/tenu-lehenga-from-satyameva-jayate-2"
		},
		{
		  "duration": "03:25",
		  "track": "Ni Jana",
		  "track_link": "/song/ni-jana-1"
		},
		{
		  "duration": "04:00",
		  "track": "Heartfail",
		  "track_link": "/song/heartfail"
		},
		{
		  "duration": "03:52",
		  "track": "Maiyya Mainu",
		  "track_link": "/song/maiyya-mainu"
		},
		{
		  "duration": "04:13",
		  "track": "Tera Hua",
		  "track_link": "/song/tera-hua-from-cash"
		},
		{
		  "duration": "03:48",
		  "track": "Mehram",
		  "track_link": "/song/mehram-32"
		},
		{
		  "duration": "03:12",
		  "track": "Najaa",
		  "track_link": "/song/najaa"
		},
		{
		  "duration": "03:26",
		  "track": "Tere Siva Jag Mein",
		  "track_link": "/song/tere-siva-jag-mein-from-tadap"
		},
		{
		  "duration": "03:22",
		  "track": "Saawariya",
		  "track_link": "/song/saawariya-37"
		},
		{
		  "album": "Shershaah",
		  "duration": "04:26",
		  "track": "Mann Bharryaa 2.0",
		  "track_link": "/song/mann-bharryaa-20-from-shershaah"
		},
		{
		  "duration": "03:20",
		  "track": "Param Sundari",
		  "track_link": "/song/param-sundari"
		},
		{
		  "duration": "03:20",
		  "track": "Baarish Ban Jaana",
		  "track_link": "/song/baarish-ban-jaana"
		},
		{
		  "duration": "02:46",
		  "track": "Ghana Kasoota",
		  "track_link": "/song/ghana-kasoota"
		},
		{
		  "album": "Shershaah",
		  "duration": "03:50",
		  "track": "Kabhii Tumhhe",
		  "track_link": "/song/kabhii-tumhhe"
		},
		{
		  "duration": "02:55",
		  "track": "Paani Paani",
		  "track_link": "/song/paani-paani-3"
		},
		{
		  "duration": "04:11",
		  "track": "Baarish Ki Jaaye",
		  "track_link": "/song/baarish-ki-jaaye"
		},
		{
		  "artists": "Jubin Nautiyal",
		  "duration": "03:46",
		  "track": "Rim Jhim",
		  "track_link": "/song/rim-jhim-49"
		},
		{
		  "duration": "05:00",
		  "track": "Filhaal2 Mohabbat",
		  "track_link": "/song/filhaal2-mohabbat"
		},
		{
		  "duration": "02:58",
		  "track": "Sakhiyan2.0",
		  "track_link": "/song/sakhiyan-20"
		},
		{
		  "duration": "02:44",
		  "track": "Nadiyon Paar (Let the Music Play Again)",
		  "track_link": "/song/nadiyon-paar-let-the-music-play-again-from-roohi"
		},
		{
		  "duration": "03:27",
		  "track": "Kanta Laga",
		  "track_link": "/song/kanta-laga-5"
		},
		{
		  "artists": "Jubin Nautiyal",
		  "duration": "04:19",
		  "track": "Barsaat Ki Dhun",
		  "track_link": "/song/barsaat-ki-dhun-1"
		},
		{
		  "duration": "03:46",
		  "track": "Is Qadar",
		  "track_link": "/song/is-qadar-2"
		},
		{
		  "duration": "03:03",
		  "track": "Bachpan Ka Pyaar",
		  "track_link": "/song/bachpan-ka-pyaar-3"
		},
		{
		  "duration": "02:38",
		  "track": "Sajna, Say Yes To The Dress",
		  "track_link": "/song/sajna-say-yes-to-the-dress"
		},
		{
		  "duration": "02:36",
		  "track": "Aila Re Aillaa",
		  "track_link": "/song/aila-re-aillaa-from-sooryavanshi"
		},
		{
		  "duration": "03:16",
		  "track": "Majnu",
		  "track_link": "/song/majnu-11"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100",
	  "resume_dict": {}
	}
