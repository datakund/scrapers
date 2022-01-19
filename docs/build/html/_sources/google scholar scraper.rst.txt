Google Scholar Scraper 
********************************

Google scholar scraper is a python library to scrape for a google scholar result using browser automation.


Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.google_scholar_scraper(search="science")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.google_scholar_scraper("search")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"google_scholar_scraper~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"search":"science"}}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "Description": "… science will become increasingly concerned with enhancing the biological value of traditional \nfoods and with elaborating entirely new sources of nourishment, as the pressure of world \npopulation grows. Moreover, a closer association of food science … with which food science is …",
		  "Link": "https://books.google.com/books?hl=en&lr=&id=b7xQAwAAQBAJ&oi=fnd&pg=PP1&dq=science&ots=sJvlLFuPz6&sig=2H7eRheyBg-QPg9UViPZJMoF2rI",
		  "Title": "Lawrie's meat science"
		},
		{
		  "Description": "This new edition of the bestselling Microlithography: Science and Technology provides a \nbalanced treatment of theoretical and operational considerations, from elementary concepts \nto advanced aspects of modern submicron microlithography. Each chapter reflects the current …",
		  "Link": "https://www.taylorfrancis.com/books/mono/10.1201/9781420051537/microlithography-bruce-smith-kazuaki-suzuki",
		  "Title": "Microlithography: science and technology"
		},
		{
		  "Description": "… Harré shows how various views about the nature of science are related to the great historical \nschools of philosophy. He sets out his argument in terms of concrete episodes in the history \nof science. Harré also examines the theory that science is a form of art, and looks at the way …",
		  "Link": "https://philpapers.org/rec/HARTPO-90",
		  "Title": "The Philosophies of Science An Introductory Survey"
		},
		{
		  "Description": "This major work, by one of the key figures in cultural studies, critically examines the theory, \nhistory and practice of culture. It is a comprehensive review of the main debates in cultural \nstudies that is grounded in an historical account of the modern relations between culture and …",
		  "Link": "https://books.google.com/books?hl=en&lr=&id=dhiy_CjJlRYC&oi=fnd&pg=PR7&dq=science&ots=yUXv6sAQfS&sig=jys_6qS2njWj2IEhf_8AT2Ugyx8",
		  "Title": "Culture: A reformer's science"
		},
		{
		  "Description": "… science but to scientists and members of the public who wish to understand science studies \nconcepts. It is a sympathetic account of how science studies can ``help science … The book \nlargely is laid out following the Mertonian norms of science, which it investigates in some detail. …",
		  "Link": "https://iopscience.iop.org/article/10.1088/0963-6625/10/1/701/meta",
		  "Title": "Real science: What it is, and what it means"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100",
	  "resume_dict": {}
		}
