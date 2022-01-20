Worldometer COVID Stats Scraper
********************************

Run the bot, enter the country name and click submit
Bot will visit worldometer.info and scrape the COVID stats of that particular country.

.. image:: images/worldometer_corona_countrywise.*

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.worldometer_corona_countrywise()

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.worldometer_corona_countrywise()
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"worldometer_corona_countrywise~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "active_case": "23,591,203",
		  "country": "USA",
		  "death_per_million": "2,618",
		  "total_cases": "67,631,191",
		  "total_deaths": "874,321"
		},
		{
		  "active_case": "1,736,605",
		  "country": "India",
		  "death_per_million": "347",
		  "total_cases": "37,618,271",
		  "total_deaths": "486,784"
		},
		{
		  "country": "Brazil"
		},
		{
		  "active_case": "3,655,733",
		  "country": "UK",
		  "death_per_million": "2,222",
		  "total_cases": "15,305,410",
		  "total_deaths": "152,075"
		},
		{
		  "country": "France"
		},
		{
		  "active_case": "633,899",
		  "country": "Russia",
		  "death_per_million": "2,205",
		  "total_cases": "10,834,260",
		  "total_deaths": "321,990"
		},
		{
		  "country": "Turkey"
		},
		{
		  "country": "Italy"
		},
		{
		  "active_case": "3,002,335",
		  "country": "Spain",
		  "death_per_million": "1,945",
		  "total_cases": "8,424,503",
		  "total_deaths": "90,993"
		},
		{
		  "country": "Germany"
		},
		{
		  "active_case": "885,619",
		  "country": "Argentina",
		  "death_per_million": "2,579",
		  "total_cases": "7,197,323",
		  "total_deaths": "118,231"
		},
		{
		  "country": "Iran"
		},
		{
		  "active_case": "178,734",
		  "country": "Colombia",
		  "death_per_million": "2,535",
		  "total_cases": "5,568,068",
		  "total_deaths": "131,130"
		},
		{
		  "country": "Mexico"
		},
		{
		  "active_case": "421,122",
		  "country": "Poland",
		  "death_per_million": "2,708",
		  "total_cases": "4,323,482",
		  "total_deaths": "102,309"
		},
		{
		  "country": "Indonesia"
		},
		{
		  "active_case": "105,007",
		  "country": "Ukraine",
		  "death_per_million": "2,270",
		  "total_cases": "3,759,530",
		  "total_deaths": "98,361"
		},
		{
		  "country": "Netherlands"
		},
		{
		  "active_case": "91,611",
		  "country": "South Africa",
		  "death_per_million": "1,546",
		  "total_cases": "3,560,921",
		  "total_deaths": "93,451"
		},
		{
		  "country": "Philippines"
		},
		{
		  "active_case": "40,619",
		  "country": "Malaysia",
		  "death_per_million": "964",
		  "total_cases": "2,810,689",
		  "total_deaths": "31,808"
		},
		{
		  "country": "Canada"
		},
		{
		  "active_case": "N/A",
		  "country": "Peru",
		  "death_per_million": "6,044",
		  "total_cases": "2,631,826",
		  "total_deaths": "203,550"
		},
		{
		  "country": "Czechia"
		},
		{
		  "active_case": "484,214",
		  "country": "Belgium",
		  "death_per_million": "2,456",
		  "total_cases": "2,484,027",
		  "total_deaths": "28,661"
		},
		{
		  "country": "Thailand"
		},
		{
		  "active_case": "24,055",
		  "country": "Iraq",
		  "death_per_million": "583",
		  "total_cases": "2,118,779",
		  "total_deaths": "24,252"
		},
		{
		  "active_case": "262,040",
		  "country": "Vietnam",
		  "death_per_million": "363",
		  "total_cases": "2,045,290",
		  "total_deaths": "35,788"
		},
		{
		  "country": "Romania"
		},
		{
		  "active_case": "331,158",
		  "country": "Portugal",
		  "death_per_million": "1,905",
		  "total_cases": "1,906,891",
		  "total_deaths": "19,334"
		},
		{
		  "country": "Japan"
		},
		{
		  "active_case": "95,016",
		  "country": "Chile",
		  "death_per_million": "2,035",
		  "total_cases": "1,885,540",
		  "total_deaths": "39,426"
		},
		{
		  "country": "Australia"
		},
		{
		  "country": "Switzerland"
		},
		{
		  "active_case": "291,293",
		  "country": "Greece",
		  "death_per_million": "2,135",
		  "total_cases": "1,679,705",
		  "total_deaths": "22,087"
		},
		{
		  "country": "Bangladesh"
		},
		{
		  "active_case": "301,944",
		  "country": "Sweden",
		  "death_per_million": "1,517",
		  "total_cases": "1,560,363",
		  "total_deaths": "15,470"
		},
		{
		  "country": "Austria"
		},
		{
		  "active_case": "152,018",
		  "country": "Serbia",
		  "death_per_million": "1,508",
		  "total_cases": "1,449,192",
		  "total_deaths": "13,098"
		},
		{
		  "country": "Hungary"
		},
		{
		  "active_case": "39,881",
		  "country": "Pakistan",
		  "death_per_million": "128",
		  "total_cases": "1,333,521",
		  "total_deaths": "29,029"
		},
		{
		  "country": "Denmark"
		},
		{
		  "active_case": "458,342",
		  "country": "Ireland",
		  "death_per_million": "1,202",
		  "total_cases": "1,109,818",
		  "total_deaths": "6,035"
		},
		{
		  "country": "Jordan"
		},
		{
		  "active_case": "84,406",
		  "country": "Kazakhstan",
		  "death_per_million": "684",
		  "total_cases": "1,071,130",
		  "total_deaths": "13,087"
		},
		{
		  "country": "Morocco"
		},
		{
		  "active_case": "17,502",
		  "country": "Cuba",
		  "death_per_million": "737",
		  "total_cases": "1,002,499",
		  "total_deaths": "8,341"
		},
		{
		  "country": "Georgia"
		},
		{
		  "active_case": "34,734",
		  "country": "Slovakia",
		  "death_per_million": "3,176",
		  "total_cases": "880,671",
		  "total_deaths": "17,352"
		},
		{
		  "country": "Nepal"
		},
		{
		  "active_case": "160,761",
		  "country": "Bulgaria",
		  "death_per_million": "4,695",
		  "total_cases": "830,604",
		  "total_deaths": "32,247"
		},
		{
		  "country": "Lebanon"
		},
		{
		  "active_case": "48,441",
		  "country": "Croatia",
		  "death_per_million": "3,236",
		  "total_cases": "818,832",
		  "total_deaths": "13,157"
		},
		{
		  "country": "UAE"
		},
		{
		  "active_case": "58,179",
		  "country": "Tunisia",
		  "death_per_million": "2,149",
		  "total_cases": "788,012",
		  "total_deaths": "25,803"
		},
		{
		  "country": "Bolivia"
		},
		{
		  "active_case": "1,272",
		  "country": "Belarus",
		  "death_per_million": "618",
		  "total_cases": "717,034",
		  "total_deaths": "5,836"
		},
		{
		  "country": "S. Korea"
		},
		{
		  "active_case": "23,981",
		  "country": "Guatemala",
		  "death_per_million": "878",
		  "total_cases": "653,555",
		  "total_deaths": "16,179"
		},
		{
		  "country": "Azerbaijan"
		},
		{
		  "country": "Saudi Arabia"
		},
		{
		  "active_case": "47,796",
		  "country": "Costa Rica",
		  "death_per_million": "1,437",
		  "total_cases": "620,587",
		  "total_deaths": "7,421"
		},
		{
		  "country": "Sri Lanka"
		},
		{
		  "active_case": "57,203",
		  "country": "Panama",
		  "death_per_million": "1,703",
		  "total_cases": "580,324",
		  "total_deaths": "7,528"
		},
		{
		  "country": "Lithuania"
		},
		{
		  "active_case": "70,772",
		  "country": "Slovenia",
		  "death_per_million": "2,744",
		  "total_cases": "538,325",
		  "total_deaths": "5,705"
		},
		{
		  "country": "Myanmar"
		},
		{
		  "active_case": "433,090",
		  "country": "Norway",
		  "death_per_million": "252",
		  "total_cases": "523,424",
		  "total_deaths": "1,382"
		},
		{
		  "country": "Uruguay"
		},
		{
		  "active_case": "37,866",
		  "country": "Dominican Republic",
		  "death_per_million": "388",
		  "total_cases": "504,914",
		  "total_deaths": "4,269"
		},
		{
		  "country": "Paraguay"
		},
		{
		  "active_case": "43,356",
		  "country": "Kuwait",
		  "death_per_million": "567",
		  "total_cases": "470,478",
		  "total_deaths": "2,477"
		},
		{
		  "country": "Ethiopia"
		},
		{
		  "active_case": "12,536",
		  "country": "Venezuela",
		  "death_per_million": "190",
		  "total_cases": "456,641",
		  "total_deaths": "5,383"
		},
		{
		  "country": "Palestine"
		},
		{
		  "active_case": "96,005",
		  "country": "Mongolia",
		  "death_per_million": "622",
		  "total_cases": "411,350",
		  "total_deaths": "2,089"
		},
		{
		  "country": "Egypt"
		},
		{
		  "active_case": "7,127",
		  "country": "Libya",
		  "death_per_million": "834",
		  "total_cases": "398,055",
		  "total_deaths": "5,853"
		},
		{
		  "country": "Finland"
		},
		{
		  "active_case": "13,091",
		  "country": "Moldova",
		  "death_per_million": "2,600",
		  "total_cases": "390,742",
		  "total_deaths": "10,452"
		},
		{
		  "country": "Honduras"
		},
		{
		  "active_case": "6,110",
		  "country": "Armenia",
		  "death_per_million": "2,699",
		  "total_cases": "347,785",
		  "total_deaths": "8,020"
		},
		{
		  "country": "Kenya"
		},
		{
		  "active_case": "111,633",
		  "country": "Bosnia and Herzegovina",
		  "death_per_million": "4,260",
		  "total_cases": "317,692",
		  "total_deaths": "13,841"
		},
		{
		  "country": "Oman"
		},
		{
		  "active_case": "21,185",
		  "country": "Bahrain",
		  "death_per_million": "780",
		  "total_cases": "310,906",
		  "total_deaths": "1,398"
		},
		{
		  "country": "Latvia"
		},
		{
		  "active_case": "41,717",
		  "country": "Qatar",
		  "death_per_million": "223",
		  "total_cases": "303,240",
		  "total_deaths": "627"
		},
		{
		  "country": "Zambia"
		},
		{
		  "active_case": "7,591",
		  "country": "Singapore",
		  "death_per_million": "142",
		  "total_cases": "293,014",
		  "total_deaths": "843"
		},
		{
		  "country": "Estonia"
		},
		{
		  "active_case": "23,439",
		  "country": "Nigeria",
		  "death_per_million": "15",
		  "total_cases": "251,178",
		  "total_deaths": "3,110"
		},
		{
		  "country": "North Macedonia"
		},
		{
		  "active_case": "10,312",
		  "country": "Botswana",
		  "death_per_million": "1,045",
		  "total_cases": "239,887",
		  "total_deaths": "2,534"
		},
		{
		  "country": "Albania"
		},
		{
		  "active_case": "103,827",
		  "country": "Cyprus",
		  "death_per_million": "560",
		  "total_cases": "228,881",
		  "total_deaths": "684"
		},
		{
		  "country": "Algeria"
		},
		{
		  "active_case": "13,090",
		  "country": "Zimbabwe",
		  "death_per_million": "346",
		  "total_cases": "226,460",
		  "total_deaths": "5,258"
		},
		{
		  "country": "Mozambique"
		},
		{
		  "active_case": "5,411",
		  "country": "Uzbekistan",
		  "death_per_million": "44",
		  "total_cases": "206,122",
		  "total_deaths": "1,518"
		},
		{
		  "country": "Montenegro"
		},
		{
		  "active_case": "7,227",
		  "country": "Kyrgyzstan",
		  "death_per_million": "424",
		  "total_cases": "191,288",
		  "total_deaths": "2,836"
		},
		{
		  "country": "Afghanistan"
		},
		{
		  "active_case": "56,295",
		  "country": "Uganda",
		  "death_per_million": "71",
		  "total_cases": "158,676",
		  "total_deaths": "3,424"
		},
		{
		  "country": "Namibia"
		},
		{
		  "country": "Luxembourg"
		},
		{
		  "active_case": "78,635",
		  "country": "Rwanda",
		  "death_per_million": "105",
		  "total_cases": "125,568",
		  "total_deaths": "1,411"
		},
		{
		  "country": "Laos"
		},
		{
		  "country": "Cambodia"
		},
		{
		  "active_case": "43,630",
		  "country": "Jamaica",
		  "death_per_million": "851",
		  "total_cases": "113,438",
		  "total_deaths": "2,536"
		},
		{
		  "active_case": "3,530",
		  "country": "China",
		  "death_per_million": "3",
		  "total_cases": "105,258",
		  "total_deaths": "4,636"
		},
		{
		  "country": "Maldives"
		},
		{
		  "country": "Trinidad and Tobago"
		},
		{
		  "active_case": "7,466",
		  "country": "Angola",
		  "death_per_million": "54",
		  "total_cases": "93,974",
		  "total_deaths": "1,866"
		},
		{
		  "country": "Senegal"
		},
		{
		  "active_case": "30,776",
		  "country": "DRC",
		  "death_per_million": "14",
		  "total_cases": "82,984",
		  "total_deaths": "1,278"
		},
		{
		  "country": "Malawi"
		},
		{
		  "active_case": "3,620",
		  "country": "Ivory Coast",
		  "death_per_million": "28",
		  "total_cases": "79,273",
		  "total_deaths": "761"
		},
		{
		  "active_case": "57,776",
		  "country": "French Guiana",
		  "death_per_million": "1,130",
		  "total_cases": "69,381",
		  "total_deaths": "351"
		},
		{
		  "country": "Eswatini"
		},
		{
		  "active_case": "14,905",
		  "country": "Suriname",
		  "death_per_million": "2,045",
		  "total_cases": "65,282",
		  "total_deaths": "1,216"
		},
		{
		  "country": "Malta"
		},
		{
		  "active_case": "3,803",
		  "country": "Fiji",
		  "death_per_million": "823",
		  "total_cases": "59,785",
		  "total_deaths": "746"
		},
		{
		  "active_case": "4,277",
		  "country": "Madagascar",
		  "death_per_million": "41",
		  "total_cases": "55,827",
		  "total_deaths": "1,169"
		},
		{
		  "country": "Mauritania"
		},
		{
		  "active_case": "2,482",
		  "country": "Cabo Verde",
		  "death_per_million": "665",
		  "total_cases": "54,367",
		  "total_deaths": "376"
		},
		{
		  "country": "Guyana"
		},
		{
		  "active_case": "8,085",
		  "country": "Sudan",
		  "death_per_million": "75",
		  "total_cases": "51,802",
		  "total_deaths": "3,388"
		},
		{
		  "country": "Syria"
		},
		{
		  "active_case": "9,664",
		  "country": "Iceland",
		  "death_per_million": "128",
		  "total_cases": "48,482",
		  "total_deaths": "44"
		},
		{
		  "country": "French Polynesia"
		},
		{
		  "active_case": "5,217",
		  "country": "Gabon",
		  "death_per_million": "130",
		  "total_cases": "45,405",
		  "total_deaths": "299"
		},
		{
		  "country": "Belize"
		},
		{
		  "active_case": "3,155",
		  "country": "Channel Islands",
		  "death_per_million": "692",
		  "total_cases": "36,852",
		  "total_deaths": "122"
		},
		{
		  "active_case": "5,614",
		  "country": "Barbados",
		  "death_per_million": "934",
		  "total_cases": "35,734",
		  "total_deaths": "269"
		},
		{
		  "country": "Guinea"
		},
		{
		  "active_case": "31,405",
		  "country": "Mayotte",
		  "death_per_million": "657",
		  "total_cases": "34,555",
		  "total_deaths": "186"
		},
		{
		  "country": "Curaçao"
		},
		{
		  "active_case": "5,049",
		  "country": "Seychelles",
		  "death_per_million": "1,410",
		  "total_cases": "32,846",
		  "total_deaths": "140"
		},
		{
		  "active_case": "N/A",
		  "country": "Tanzania",
		  "death_per_million": "12",
		  "total_cases": "31,395",
		  "total_deaths": "745"
		},
		{
		  "country": "Aruba"
		},
		{
		  "active_case": "3,638",
		  "country": "Mali",
		  "death_per_million": "33",
		  "total_cases": "28,755",
		  "total_deaths": "692"
		},
		{
		  "country": "Haiti"
		},
		{
		  "country": "Mauritius"
		},
		{
		  "country": "Congo"
		},
		{
		  "active_case": "1,118",
		  "country": "Burkina Faso",
		  "death_per_million": "16",
		  "total_cases": "20,249",
		  "total_deaths": "339"
		},
		{
		  "country": "Timor-Leste"
		},
		{
		  "active_case": "935",
		  "country": "Taiwan",
		  "death_per_million": "36",
		  "total_cases": "17,885",
		  "total_deaths": "851"
		},
		{
		  "active_case": "3,285",
		  "country": "Saint Lucia",
		  "death_per_million": "1,698",
		  "total_cases": "17,531",
		  "total_deaths": "314"
		},
		{
		  "active_case": "3,463",
		  "country": "South Sudan",
		  "death_per_million": "12",
		  "total_cases": "16,533",
		  "total_deaths": "136"
		},
		{
		  "country": "Brunei"
		},
		{
		  "active_case": "1,604",
		  "country": "Equatorial Guinea",
		  "death_per_million": "121",
		  "total_cases": "15,492",
		  "total_deaths": "178"
		},
		{
		  "country": "New Zealand"
		},
		{
		  "active_case": "571",
		  "country": "Djibouti",
		  "death_per_million": "187",
		  "total_cases": "14,984",
		  "total_deaths": "189"
		},
		{
		  "active_case": "801",
		  "country": "New Caledonia",
		  "death_per_million": "973",
		  "total_cases": "13,829",
		  "total_deaths": "282"
		},
		{
		  "active_case": "508",
		  "country": "Hong Kong",
		  "death_per_million": "28",
		  "total_cases": "13,048",
		  "total_deaths": "213"
		},
		{
		  "active_case": "1,381",
		  "country": "Gambia",
		  "death_per_million": "138",
		  "total_cases": "11,572",
		  "total_deaths": "347"
		},
		{
		  "country": "Gibraltar"
		},
		{
		  "active_case": "1,641",
		  "country": "San Marino",
		  "death_per_million": "3,026",
		  "total_cases": "10,639",
		  "total_deaths": "103"
		},
		{
		  "country": "Faeroe Islands"
		},
		{
		  "active_case": "1,271",
		  "country": "Yemen",
		  "death_per_million": "65",
		  "total_cases": "10,308",
		  "total_deaths": "1,991"
		},
		{
		  "country": "Grenada"
		},
		{
		  "active_case": "1,953",
		  "country": "Bermuda",
		  "death_per_million": "1,776",
		  "total_cases": "9,144",
		  "total_deaths": "110"
		},
		{
		  "country": "Eritrea"
		},
		{
		  "country": "Niger"
		},
		{
		  "active_case": "5,261",
		  "country": "Greenland",
		  "death_per_million": "53",
		  "total_cases": "8,025",
		  "total_deaths": "3"
		},
		{
		  "active_case": "512",
		  "country": "Comoros",
		  "death_per_million": "177",
		  "total_cases": "7,767",
		  "total_deaths": "159"
		},
		{
		  "active_case": "N/A",
		  "country": "Sierra Leone",
		  "death_per_million": "15",
		  "total_cases": "7,544",
		  "total_deaths": "125"
		},
		{
		  "country": "Liechtenstein"
		},
		{
		  "country": "Guinea-Bissau"
		},
		{
		  "active_case": "1,828",
		  "country": "Chad",
		  "death_per_million": "11",
		  "total_cases": "6,887",
		  "total_deaths": "185"
		},
		{
		  "country": "Monaco"
		},
		{
		  "active_case": "903",
		  "country": "St. Vincent Grenadines",
		  "death_per_million": "780",
		  "total_cases": "6,599",
		  "total_deaths": "87"
		},
		{
		  "country": "Caribbean Netherlands"
		},
		{
		  "active_case": "1,438",
		  "country": "Sao Tome and Principe",
		  "death_per_million": "293",
		  "total_cases": "5,569",
		  "total_deaths": "66"
		},
		{
		  "country": "British Virgin Islands"
		},
		{
		  "country": "Turks and Caicos"
		},
		{
		  "active_case": "1,217",
		  "country": "Saint Kitts and Nevis",
		  "death_per_million": "521",
		  "total_cases": "4,968",
		  "total_deaths": "28"
		},
		{
		  "country": "Bhutan"
		},
		{
		  "active_case": "254",
		  "country": "Saint Pierre Miquelon",
		  "total_cases": "494",
		  "total_deaths": ""
		},
		{
		  "active_case": "133",
		  "total_cases": "152",
		  "total_deaths": ""
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100",
	  "resume_dict": {}
	}
