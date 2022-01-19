All movie scraper
********************************

All movie scraper is a python library to search for movies details on all movies website, using browser automation


Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.horror_movie_scrapers(search="horrors")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.horror_movie_scrapers("horrors")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"horror_movie_scrapers~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"search":"horrors"}}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "directed by": "Frank Oz",
		  "genres": "Genres: Comedy, Horror, Musical",
		  "movie detailed page": "https://www.allmovie.com/movie/little-shop-of-horrors-v29673",
		  "movie name": "Little Shop of Horrors"
		},
		{
		  "movie detailed page": "https://www.allmovie.com/movie/galaxy-of-horrors-v681245",
		  "movie name": "Galaxy of Horrors"
		},
		{
		  "directed by": "Roger Corman",
		  "genres": "Genres: Horror",
		  "movie detailed page": "https://www.allmovie.com/movie/the-little-shop-of-horrors-v29672",
		  "movie name": "The Little Shop of Horrors"
		},
		{
		  "directed by": "Lucio Fulci",
		  "genres": "Genres: Horror",
		  "movie detailed page": "https://www.allmovie.com/movie/the-sweet-house-of-horrors-v265372",
		  "movie name": "The Sweet House of Horrors"
		},
		{
		  "directed by": "Makooto Ohtake",
		  "genres": "Genres: Horror",
		  "movie detailed page": "https://www.allmovie.com/movie/horny-house-of-horrors-v544571",
		  "movie name": "Horny House of Horrors"
		},
		{
		  "directed by": "Fritz Bottger",
		  "genres": "Genres: Horror",
		  "movie detailed page": "https://www.allmovie.com/movie/horrors-of-spider-island-v95621",
		  "movie name": "Horrors of Spider Island"
		},
		{
		  "movie detailed page": "https://www.allmovie.com/movie/horrors-of-the-third-reich-v23164",
		  "movie name": "Horrors of the Third Reich"
		},
		{
		  "movie detailed page": "https://www.allmovie.com/movie/horrors-of-the-black-zoo-v95623",
		  "movie name": "Horrors of the Black Zoo"
		},
		{
		  "directed by": "Jean Yarbrough",
		  "genres": "Genres: Crime, Horror",
		  "movie detailed page": "https://www.allmovie.com/movie/house-of-horrors-v95750",
		  "movie name": "House of Horrors"
		},
		{
		  "movie detailed page": "https://www.allmovie.com/movie/harvest-of-horrors-v728013",
		  "movie name": "Harvest of Horrors"
		},
		{
		  "movie detailed page": "https://www.allmovie.com/movie/horror-sci-fi-trailers-vol-3-classic-horrors-v23136",
		  "movie name": "Horror & Sci-Fi Trailers, Vol. 3: Classic Horrors"
		},
		{
		  "movie detailed page": "https://www.allmovie.com/movie/fangorias-weekend-of-horrors-v16739",
		  "movie name": "Fangoria's Weekend of Horrors"
		},
		{
		  "directed by": "Doug Waugh",
		  "genres": "Genres: Horror",
		  "movie detailed page": "https://www.allmovie.com/movie/treasure-chest-of-horrors-v562454",
		  "movie name": "Treasure Chest of Horrors"
		},
		{
		  "movie detailed page": "https://www.allmovie.com/movie/shadows-choose-their-horrors-v643415",
		  "movie name": "Shadows Choose Their Horrors"
		},
		{
		  "movie detailed page": "https://www.allmovie.com/movie/unspeakable-horrors-the-plan-9-conspiracy-v684389",
		  "movie name": "Unspeakable Horrors: The Plan 9 Conspiracy"
		},
		{
		  "directed by": "Toshio Hirata",
		  "genres": "Genres: Horror",
		  "movie detailed page": "https://www.allmovie.com/movie/pet-shop-of-horrors-daughter-v206671",
		  "movie name": "Pet Shop of Horrors: Daughter"
		},
		{
		  "movie detailed page": "https://www.allmovie.com/movie/pet-shop-of-horrors-delicious-v481988",
		  "movie name": "Pet Shop of Horrors: Delicious"
		},
		{
		  "movie detailed page": "https://www.allmovie.com/movie/pet-shop-of-horrors-despair-v481989",
		  "movie name": "Pet Shop of Horrors: Despair"
		},
		{
		  "movie detailed page": "https://www.allmovie.com/movie/pet-shop-of-horrors-dual-v481990",
		  "movie name": "Pet Shop of Horrors: Dual"
		},
		{
		  "movie detailed page": "https://www.allmovie.com/movie/treasure-chest-of-horrors-2-v577797",
		  "movie name": "Treasure Chest of Horrors 2"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100",
	  "resume_dict": {}
	}