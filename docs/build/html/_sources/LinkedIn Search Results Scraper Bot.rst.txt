LinkedIn Search Results Scraper Bot
************************************************

LinkedIn search results is a python library to scrape LinkedIn search results, using browser automation. It currently runs only on windows.

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	datakund.linkedin_login(email="email",password="pass")
	#or
	linkedin_login_cookies(cookies="cookies")
	response = linkedin_search_results(keyword="apple")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.linkedin_login("email","password")
	 //or
	 datakund.linkedin_login_cookies("cookies")
     datakund.linkedin_search_results("apple")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"linkedin_login~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"email":"email","password":"pass"}}'
		 				or
	  curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"linkedin_login_cookies~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"cookies":"cookies"}}'

		 
	  curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"linkedin_search_results~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"keyword":"Apple"}}'
		 
Response Data
##############

.. code-block:: json

		{
	  "body": [
		{
		  "link": "https://www.linkedin.com/in/trishabhc?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAAAFUTigBXV7yFcR3wR5F7XQnGu7rTWSFybY",
		  "location": "Delhi, India",
		  "position": "Principal Engineering Manager at Microsoft",
		  "title": "Trishabh ChaddaView Trishabh Chadda’s profile"
		},
		{
		  "link": "https://www.linkedin.com/in/nitin-vohra-05796a6?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAAAE1tcMBl7ZUfH5yIzEp-pzyJkXHP_eTvi0",
		  "location": "Faridabad",
		  "position": "Head - Business Development",
		  "title": "Nitin VohraView Nitin Vohra’s profile"
		},
		{
		  "link": "https://www.linkedin.com/in/ramanpreet-kr?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAACpLUBsBpYhPe8bRrIvxm-IR0ZjS9akmWBE",
		  "location": "Hyderabad",
		  "position": "Software Engineer at Apple",
		  "title": "Ramanpreet KaurView Ramanpreet Kaur’s profile"
		},
		{
		  "link": "https://www.linkedin.com/in/shyam-agarwal-31a57814b?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAACQ2msYBILkHSLK6sh_rHbyBUNV9MyWes5U",
		  "location": "West Delhi",
		  "position": "Data Science & Analytics Intern at Apple",
		  "title": "Shyam AgarwalView Shyam Agarwal’s profile"
		},
		{
		  "link": "https://www.linkedin.com/in/apple-education-12977bab?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAABdtxfEBgCaYp8tOsUyY5dZCpgYBkGUoH2w",
		  "location": "Kerala, India",
		  "position": "Managing Director",
		  "title": "Apple EducationView Apple Education’s profile"
		},
		{
		  "link": "https://www.linkedin.com/in/sahil-jain-365467153?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAACTotz0Btj9A81anjxJeO5cbIK27BbW0ZrU",
		  "location": "Indore",
		  "position": "SDE at Apple | Ex- Amazon | BITS, Pilani",
		  "title": "Sahil JainView Sahil Jain’s profile"
		},
		{
		  "link": "https://www.linkedin.com/in/amitbhatnagar1?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAAADJdXEBjLlVEnotJTTeyJgfbUFKL10E1Wo",
		  "location": "Gurgaon",
		  "position": "Product Leader at Nykaa | Stanford grad | Ex-DineOut, OYO, Apple, Microsoft",
		  "title": "Amit Bhatnagar (Hiring rockstar PMs at all levels. Inmails open)View Amit Bhatnagar (Hiring rockstar PMs at all levels. Inmails open)’s profile"
		},
		{
		  "link": "https://www.linkedin.com/in/aleema-khan-8a318521a?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAADcy2rsBSzGF5pUpzaGJXTPeHy5n_tWOdDo",
		  "location": "Mumbai",
		  "position": "Software Engineer at Apple",
		  "title": "Aleema KhanView Aleema Khan’s profile"
		},
		{
		  "link": "https://www.linkedin.com/in/sargun99?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAACcYwNoBMmejOdi-Ny14BWmtb-YGWpzwfos",
		  "location": "Delhi, India",
		  "position": "Software Engineer at Apple",
		  "title": "Sargun SinghView Sargun Singh’s profile"
		},
		{
		  "link": "https://www.linkedin.com/in/apple-hub-4964a6212?miniProfileUrn=urn%3Ali%3Afs_miniProfile%3AACoAADXSZTIBRAIEsVvEmB5yvK5N6dpxurC20ls",
		  "location": "Gurugram",
		  "position": "custom mobile company",
		  "title": "Apple HubView Apple Hub’s profile"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100",
	  "resume_dict": {}
	}
	 
