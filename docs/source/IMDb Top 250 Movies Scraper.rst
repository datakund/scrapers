IMDb Top 250 Movies Scraper
********************************

IMDb is the world's most popular and authoritative source for movie, TV and celebrity content. Find ratings and reviews for the newest movie and TV shows. With the help of IMDb Top Movies Scraper you can scrape the title and rating of top 250 movies.

.. image:: images/imdb_scrape_top_movies.*

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.imdb_scrape_top_movies()

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.imdb_scrape_top_movies()
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"imdb_scrape_top_movies~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "rating": "9.2",
		  "title": "The Shawshank Redemption"
		},
		{
		  "rating": "9.1",
		  "title": "The Godfather"
		},
		{
		  "rating": "9.0",
		  "title": "The Godfather: Part II"
		},
		{
		  "rating": "9.0",
		  "title": "The Dark Knight"
		},
		{
		  "rating": "8.9",
		  "title": "12 Angry Men"
		},
		{
		  "rating": "8.9",
		  "title": "Schindler's List"
		},
		{
		  "rating": "8.9",
		  "title": "The Lord of the Rings: The Return of the King"
		},
		{
		  "rating": "8.8",
		  "title": "Pulp Fiction"
		},
		{
		  "rating": "8.8",
		  "title": "The Good, the Bad and the Ugly"
		},
		{
		  "rating": "8.8",
		  "title": "The Lord of the Rings: The Fellowship of the Ring"
		},
		{
		  "rating": "8.7",
		  "title": "Fight Club"
		},
		{
		  "rating": "8.7",
		  "title": "Forrest Gump"
		},
		{
		  "rating": "8.7",
		  "title": "Inception"
		},
		{
		  "rating": "8.7",
		  "title": "The Lord of the Rings: The Two Towers"
		},
		{
		  "rating": "8.7",
		  "title": "Star Wars: Episode V - The Empire Strikes Back"
		},
		{
		  "rating": "8.7",
		  "title": "The Matrix"
		},
		{
		  "rating": "8.6",
		  "title": "Goodfellas"
		},
		{
		  "rating": "8.6",
		  "title": "One Flew Over the Cuckoo's Nest"
		},
		{
		  "rating": "8.6",
		  "title": "Seven Samurai"
		},
		{
		  "rating": "8.6",
		  "title": "Spider-Man: No Way Home"
		},
		{
		  "rating": "8.6",
		  "title": "Seven"
		},
		{
		  "rating": "8.6",
		  "title": "The Silence of the Lambs"
		},
		{
		  "rating": "8.6",
		  "title": "City of God"
		},
		{
		  "rating": "8.6",
		  "title": "It's a Wonderful Life"
		},
		{
		  "rating": "8.6",
		  "title": "Life Is Beautiful"
		},
		{
		  "rating": "8.6",
		  "title": "Saving Private Ryan"
		},
		{
		  "rating": "8.5",
		  "title": "Star Wars: Episode IV - A New Hope"
		},
		{
		  "rating": "8.5",
		  "title": "Interstellar"
		},
		{
		  "rating": "8.5",
		  "title": "Spirited Away"
		},
		{
		  "rating": "8.5",
		  "title": "The Green Mile"
		},
		{
		  "rating": "8.5",
		  "title": "Parasite"
		},
		{
		  "rating": "8.5",
		  "title": "Leon"
		},
		{
		  "rating": "8.5",
		  "title": "Harakiri"
		},
		{
		  "rating": "8.5",
		  "title": "The Pianist"
		},
		{
		  "rating": "8.5",
		  "title": "Terminator 2: Judgment Day"
		},
		{
		  "rating": "8.5",
		  "title": "Back to the Future"
		},
		{
		  "rating": "8.5",
		  "title": "The Usual Suspects"
		},
		{
		  "rating": "8.5",
		  "title": "Psycho"
		},
		{
		  "rating": "8.5",
		  "title": "The Lion King"
		},
		{
		  "rating": "8.5",
		  "title": "Modern Times"
		},
		{
		  "rating": "8.5",
		  "title": "Grave of the Fireflies"
		},
		{
		  "rating": "8.5",
		  "title": "American History X"
		},
		{
		  "rating": "8.5",
		  "title": "Whiplash"
		},
		{
		  "rating": "8.5",
		  "title": "Gladiator"
		},
		{
		  "rating": "8.5",
		  "title": "City Lights"
		},
		{
		  "rating": "8.5",
		  "title": "The Departed"
		},
		{
		  "rating": "8.5",
		  "title": "Untouchable"
		},
		{
		  "rating": "8.5",
		  "title": "The Prestige"
		},
		{
		  "rating": "8.4",
		  "title": "Casablanca"
		},
		{
		  "rating": "8.4",
		  "title": "Once Upon a Time in the West"
		},
		{
		  "rating": "8.4",
		  "title": "Rear Window"
		},
		{
		  "rating": "8.4",
		  "title": "Cinema Paradiso"
		},
		{
		  "rating": "8.4",
		  "title": "Alien"
		},
		{
		  "rating": "8.4",
		  "title": "Apocalypse Now"
		},
		{
		  "rating": "8.4",
		  "title": "Memento"
		},
		{
		  "rating": "8.4",
		  "title": "Raiders of the Lost Ark"
		},
		{
		  "rating": "8.4",
		  "title": "The Great Dictator"
		},
		{
		  "rating": "8.4",
		  "title": "Django Unchained"
		},
		{
		  "rating": "8.4",
		  "title": "The Lives of Others"
		},
		{
		  "rating": "8.4",
		  "title": "Paths of Glory"
		},
		{
		  "rating": "8.4",
		  "title": "Sunset Blvd."
		},
		{
		  "rating": "8.4",
		  "title": "WALL·E"
		},
		{
		  "rating": "8.4",
		  "title": "Avengers: Infinity War"
		},
		{
		  "rating": "8.4",
		  "title": "Witness for the Prosecution"
		},
		{
		  "rating": "8.4",
		  "title": "The Shining"
		},
		{
		  "rating": "8.4",
		  "title": "Spider-Man: Into the Spider-Verse"
		},
		{
		  "rating": "8.4",
		  "title": "Dr. Strangelove or: How I Learned to Stop Worrying and Love the Bomb"
		},
		{
		  "rating": "8.3",
		  "title": "Princess Mononoke"
		},
		{
		  "rating": "8.3",
		  "title": "Oldboy"
		},
		{
		  "rating": "8.3",
		  "title": "Joker"
		},
		{
		  "rating": "8.3",
		  "title": "Your Name."
		},
		{
		  "rating": "8.3",
		  "title": "Coco"
		},
		{
		  "rating": "8.3",
		  "title": "The Dark Knight Rises"
		},
		{
		  "rating": "8.3",
		  "title": "Aliens"
		},
		{
		  "rating": "8.3",
		  "title": "Once Upon a Time in America"
		},
		{
		  "rating": "8.3",
		  "title": "Avengers: Endgame"
		},
		{
		  "rating": "8.3",
		  "title": "Capernaum"
		},
		{
		  "rating": "8.3",
		  "title": "Das Boot"
		},
		{
		  "rating": "8.3",
		  "title": "High and Low"
		},
		{
		  "rating": "8.3",
		  "title": "3 Idiots"
		},
		{
		  "rating": "8.3",
		  "title": "Toy Story"
		},
		{
		  "rating": "8.3",
		  "title": "Amadeus"
		},
		{
		  "rating": "8.3",
		  "title": "American Beauty"
		},
		{
		  "rating": "8.3",
		  "title": "Braveheart"
		},
		{
		  "rating": "8.3",
		  "title": "Inglourious Basterds"
		},
		{
		  "rating": "8.3",
		  "title": "Good Will Hunting"
		},
		{
		  "rating": "8.3",
		  "title": "Hamilton"
		},
		{
		  "rating": "8.3",
		  "title": "Star Wars: Return of the Jedi"
		},
		{
		  "rating": "8.3",
		  "title": "Come and See"
		},
		{
		  "rating": "8.3",
		  "title": "2001: A Space Odyssey"
		},
		{
		  "rating": "8.3",
		  "title": "Reservoir Dogs"
		},
		{
		  "rating": "8.3",
		  "title": "Like Stars on Earth"
		},
		{
		  "rating": "8.3",
		  "title": "Vertigo"
		},
		{
		  "rating": "8.3",
		  "title": "M"
		},
		{
		  "rating": "8.3",
		  "title": "The Hunt"
		},
		{
		  "rating": "8.3",
		  "title": "Citizen Kane"
		},
		{
		  "rating": "8.3",
		  "title": "Requiem for a Dream"
		},
		{
		  "rating": "8.3",
		  "title": "Singin in the Rain"
		},
		{
		  "rating": "8.3",
		  "title": "North by Northwest"
		},
		{
		  "rating": "8.3",
		  "title": "Eternal Sunshine of the Spotless Mind"
		},
		{
		  "rating": "8.3",
		  "title": "Ikiru"
		},
		{
		  "rating": "8.3",
		  "title": "Bicycle Thieves"
		},
		{
		  "rating": "8.3",
		  "title": "Lawrence of Arabia"
		},
		{
		  "rating": "8.2",
		  "title": "The Kid"
		},
		{
		  "rating": "8.2",
		  "title": "Full Metal Jacket"
		},
		{
		  "rating": "8.2",
		  "title": "Dangal"
		},
		{
		  "rating": "8.2",
		  "title": "Incendies"
		},
		{
		  "rating": "8.2",
		  "title": "The Apartment"
		},
		{
		  "rating": "8.2",
		  "title": "Double Indemnity"
		},
		{
		  "rating": "8.2",
		  "title": "Metropolis"
		},
		{
		  "rating": "8.2",
		  "title": "The Father"
		},
		{
		  "rating": "8.2",
		  "title": "Taxi Driver"
		},
		{
		  "rating": "8.2",
		  "title": "A Clockwork Orange"
		},
		{
		  "rating": "8.2",
		  "title": "A Separation"
		},
		{
		  "rating": "8.2",
		  "title": "The Sting"
		},
		{
		  "rating": "8.2",
		  "title": "Scarface"
		},
		{
		  "rating": "8.2",
		  "title": "Snatch"
		},
		{
		  "rating": "8.2",
		  "title": "1917"
		},
		{
		  "rating": "8.2",
		  "title": "Amélie"
		},
		{
		  "rating": "8.2",
		  "title": "To Kill a Mockingbird"
		},
		{
		  "rating": "8.2",
		  "title": "Toy Story 3"
		},
		{
		  "rating": "8.2",
		  "title": "Pather Panchali"
		},
		{
		  "rating": "8.2",
		  "title": "For a Few Dollars More"
		},
		{
		  "rating": "8.2",
		  "title": "Up"
		},
		{
		  "rating": "8.2",
		  "title": "Indiana Jones and the Last Crusade"
		},
		{
		  "rating": "8.2",
		  "title": "Heat"
		},
		{
		  "rating": "8.2",
		  "title": "L.A. Confidential"
		},
		{
		  "rating": "8.2",
		  "title": "Ran"
		},
		{
		  "rating": "8.2",
		  "title": "Yojimbo"
		},
		{
		  "rating": "8.2",
		  "title": "Die Hard"
		},
		{
		  "rating": "8.2",
		  "title": "Green Book"
		},
		{
		  "rating": "8.2",
		  "title": "Rashomon"
		},
		{
		  "rating": "8.2",
		  "title": "Downfall"
		},
		{
		  "rating": "8.2",
		  "title": "Monty Python and the Holy Grail"
		},
		{
		  "rating": "8.2",
		  "title": "All About Eve"
		},
		{
		  "rating": "8.2",
		  "title": "Some Like It Hot"
		},
		{
		  "rating": "8.2",
		  "title": "Batman Begins"
		},
		{
		  "rating": "8.2",
		  "title": "Unforgiven"
		},
		{
		  "rating": "8.2",
		  "title": "Children of Heaven"
		},
		{
		  "rating": "8.2",
		  "title": "Jai Bhim"
		},
		{
		  "rating": "8.2",
		  "title": "Howl's Moving Castle"
		},
		{
		  "rating": "8.2",
		  "title": "The Wolf of Wall Street"
		},
		{
		  "rating": "8.2",
		  "title": "Judgment at Nuremberg"
		},
		{
		  "rating": "8.2",
		  "title": "There Will Be Blood"
		},
		{
		  "rating": "8.2",
		  "title": "The Great Escape"
		},
		{
		  "rating": "8.2",
		  "title": "Casino"
		},
		{
		  "rating": "8.2",
		  "title": "The Treasure of the Sierra Madre"
		},
		{
		  "rating": "8.1",
		  "title": "Pan's Labyrinth"
		},
		{
		  "rating": "8.1",
		  "title": "A Beautiful Mind"
		},
		{
		  "rating": "8.1",
		  "title": "The Secret in Their Eyes"
		},
		{
		  "rating": "8.1",
		  "title": "Raging Bull"
		},
		{
		  "rating": "8.1",
		  "title": "Chinatown"
		},
		{
		  "rating": "8.1",
		  "title": "My Neighbour Totoro"
		},
		{
		  "rating": "8.1",
		  "title": "Shutter Island"
		},
		{
		  "rating": "8.1",
		  "title": "Lock, Stock and Two Smoking Barrels"
		},
		{
		  "rating": "8.1",
		  "title": "No Country for Old Men"
		},
		{
		  "rating": "8.1",
		  "title": "Klaus"
		},
		{
		  "rating": "8.1",
		  "title": "Dial M for Murder"
		},
		{
		  "rating": "8.1",
		  "title": "Dersu Uzala"
		},
		{
		  "rating": "8.1",
		  "title": "The Gold Rush"
		},
		{
		  "rating": "8.1",
		  "title": "The Thing"
		},
		{
		  "rating": "8.1",
		  "title": "Three Billboards Outside Ebbing, Missouri"
		},
		{
		  "rating": "8.1",
		  "title": "The Seventh Seal"
		},
		{
		  "rating": "8.1",
		  "title": "The Elephant Man"
		},
		{
		  "rating": "8.1",
		  "title": "The Sixth Sense"
		},
		{
		  "rating": "8.1",
		  "title": "The Truman Show"
		},
		{
		  "rating": "8.1",
		  "title": "Jurassic Park"
		},
		{
		  "rating": "8.1",
		  "title": "Wild Strawberries"
		},
		{
		  "rating": "8.1",
		  "title": "The Third Man"
		},
		{
		  "rating": "8.1",
		  "title": "Memories of Murder"
		},
		{
		  "rating": "8.1",
		  "title": "V for Vendetta"
		},
		{
		  "rating": "8.1",
		  "title": "Blade Runner"
		},
		{
		  "rating": "8.1",
		  "title": "Trainspotting"
		},
		{
		  "rating": "8.1",
		  "title": "The Bridge on the River Kwai"
		},
		{
		  "rating": "8.1",
		  "title": "Inside Out"
		},
		{
		  "rating": "8.1",
		  "title": "Fargo"
		},
		{
		  "rating": "8.1",
		  "title": "Finding Nemo"
		},
		{
		  "rating": "8.1",
		  "title": "Kill Bill: Vol. 1"
		},
		{
		  "rating": "8.1",
		  "title": "Warrior"
		},
		{
		  "rating": "8.1",
		  "title": "Gone with the Wind"
		},
		{
		  "rating": "8.1",
		  "title": "Tokyo Story"
		},
		{
		  "rating": "8.1",
		  "title": "On the Waterfront"
		},
		{
		  "rating": "8.1",
		  "title": "My Father and My Son"
		},
		{
		  "rating": "8.1",
		  "title": "Wild Tales"
		},
		{
		  "rating": "8.1",
		  "title": "Prisoners"
		},
		{
		  "rating": "8.1",
		  "title": "Stalker"
		},
		{
		  "rating": "8.1",
		  "title": "The Grand Budapest Hotel"
		},
		{
		  "rating": "8.1",
		  "title": "The Deer Hunter"
		},
		{
		  "rating": "8.1",
		  "title": "Sherlock Jr."
		},
		{
		  "rating": "8.1",
		  "title": "The General"
		},
		{
		  "rating": "8.1",
		  "title": "Gran Torino"
		},
		{
		  "rating": "8.1",
		  "title": "Persona"
		},
		{
		  "rating": "8.1",
		  "title": "Dune"
		},
		{
		  "rating": "8.1",
		  "title": "Before Sunrise"
		},
		{
		  "rating": "8.1",
		  "title": "Mary and Max"
		},
		{
		  "rating": "8.1",
		  "title": "Catch Me If You Can"
		},
		{
		  "rating": "8.1",
		  "title": "Z"
		},
		{
		  "rating": "8.1",
		  "title": "Mr. Smith Goes to Washington"
		},
		{
		  "rating": "8.1",
		  "title": "Barry Lyndon"
		},
		{
		  "rating": "8.1",
		  "title": "In the Name of the Father"
		},
		{
		  "rating": "8.1",
		  "title": "Gone Girl"
		},
		{
		  "rating": "8.1",
		  "title": "Hacksaw Ridge"
		},
		{
		  "rating": "8.1",
		  "title": "Room"
		},
		{
		  "rating": "8.1",
		  "title": "The Passion of Joan of Arc"
		},
		{
		  "rating": "8.1",
		  "title": "Andhadhun"
		},
		{
		  "rating": "8.1",
		  "title": "Le Mans '66"
		},
		{
		  "rating": "8.1",
		  "title": "12 Years a Slave"
		},
		{
		  "rating": "8.1",
		  "title": "To Be or Not to Be"
		},
		{
		  "rating": "8.1",
		  "title": "The Big Lebowski"
		},
		{
		  "rating": "8.1",
		  "title": "Dead Poets Society"
		},
		{
		  "rating": "8.1",
		  "title": "Harry Potter and the Deathly Hallows: Part 2"
		},
		{
		  "rating": "8.1",
		  "title": "Ben-Hur"
		},
		{
		  "rating": "8.1",
		  "title": "How to Train Your Dragon"
		},
		{
		  "rating": "8.1",
		  "title": "Mad Max: Fury Road"
		},
		{
		  "rating": "8.1",
		  "title": "Autumn Sonata"
		},
		{
		  "rating": "8.1",
		  "title": "Million Dollar Baby"
		},
		{
		  "rating": "8.1",
		  "title": "The Wages of Fear"
		},
		{
		  "rating": "8.1",
		  "title": "Stand by Me"
		},
		{
		  "rating": "8.1",
		  "title": "Network"
		},
		{
		  "rating": "8.1",
		  "title": "The Handmaiden"
		},
		{
		  "rating": "8.1",
		  "title": "Logan"
		},
		{
		  "rating": "8.1",
		  "title": "La Haine"
		},
		{
		  "rating": "8.0",
		  "title": "Cool Hand Luke"
		},
		{
		  "rating": "8.0",
		  "title": "Hachi: A Dog's Tale"
		},
		{
		  "rating": "8.0",
		  "title": "A Silent Voice"
		},
		{
		  "rating": "8.0",
		  "title": "The 400 Blows"
		},
		{
		  "rating": "8.0",
		  "title": "Gangs of Wasseypur"
		},
		{
		  "rating": "8.0",
		  "title": "Platoon"
		},
		{
		  "rating": "8.0",
		  "title": "Spotlight"
		},
		{
		  "rating": "8.0",
		  "title": "Monsters, Inc."
		},
		{
		  "rating": "8.0",
		  "title": "Rebecca"
		},
		{
		  "rating": "8.0",
		  "title": "Life of Brian"
		},
		{
		  "rating": "8.0",
		  "title": "In the Mood for Love"
		},
		{
		  "rating": "8.0",
		  "title": "Hotel Rwanda"
		},
		{
		  "rating": "8.0",
		  "title": "The Bandit"
		},
		{
		  "rating": "8.0",
		  "title": "Rush"
		},
		{
		  "rating": "8.0",
		  "title": "Rocky"
		},
		{
		  "rating": "8.0",
		  "title": "Amores perros"
		},
		{
		  "rating": "8.0",
		  "title": "Into the Wild"
		},
		{
		  "rating": "8.0",
		  "title": "Nausicaä of the Valley of the Wind"
		},
		{
		  "rating": "8.0",
		  "title": "It Happened One Night"
		},
		{
		  "rating": "8.0",
		  "title": "Before Sunset"
		},
		{
		  "rating": "8.0",
		  "title": "Fanny and Alexander"
		},
		{
		  "rating": "8.0",
		  "title": "The Battle of Algiers"
		},
		{
		  "rating": "8.0",
		  "title": "Neon Genesis Evangelion: The End of Evangelion"
		},
		{
		  "rating": "8.0",
		  "title": "Andrei Rublev"
		},
		{
		  "rating": "8.0",
		  "title": "Nights of Cabiria"
		},
		{
		  "rating": "8.0",
		  "title": "Demon Slayer the Movie: Mugen Train"
		},
		{
		  "rating": "8.0",
		  "title": "The Princess Bride"
		},
		{
		  "rating": "8.0",
		  "title": "Drishyam"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100",
	  "resume_dict": {}
	}
