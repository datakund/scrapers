Wikipedia GDP per Capita Scraper
********************************

Extract Wikipedia GDP per Capita country wise using UN data and IMF Data  from Wikipedia
.. image:: images/wikipedia_gdp_per_capita.*

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.wikipedia_gdp_per_capita()

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.wikipedia_gdp_per_capita()
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"wikipedia_gdp_per_capita~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "Imf_year": "190,532",
		  "country": "Monaco",
		  "imf_estimate": "N/A",
		  "region": "Europe",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "179,258",
		  "country": "Liechtenstein",
		  "imf_estimate": "N/A",
		  "region": "Europe",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "2021",
		  "country": "Luxembourg",
		  "imf_estimate": "131,301.599",
		  "region": "Europe",
		  "un_estimate": "115,481",
		  "un_year": "115,481"
		},
		{
		  "Imf_year": "117,768",
		  "country": "Bermuda",
		  "imf_estimate": "N/A",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "2021",
		  "country": "Switzerland",
		  "imf_estimate": "93,515.484",
		  "region": "Europe",
		  "un_estimate": "85,135",
		  "un_year": "85,135"
		},
		{
		  "Imf_year": "2021",
		  "country": "Ireland",
		  "imf_estimate": "102,394.017",
		  "region": "Europe",
		  "un_estimate": "81,637",
		  "un_year": "81,637"
		},
		{
		  "Imf_year": "92,692",
		  "country": "Cayman Islands",
		  "imf_estimate": "N/A",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "2021",
		  "country": "Norway",
		  "imf_estimate": "82,244.232",
		  "region": "Europe",
		  "un_estimate": "74,986",
		  "un_year": "74,986"
		},
		{
		  "Imf_year": "2021",
		  "country": "United States",
		  "imf_estimate": "69,375.375",
		  "un_estimate": "65,134",
		  "un_year": "65,134"
		},
		{
		  "Imf_year": "2021",
		  "country": "Denmark",
		  "imf_estimate": "67,919.585",
		  "region": "Europe",
		  "un_estimate": "60,657",
		  "un_year": "60,657"
		},
		{
		  "Imf_year": "2021",
		  "country": "Iceland",
		  "imf_estimate": "68,843.646",
		  "region": "Europe",
		  "un_estimate": "71,345",
		  "un_year": "71,345"
		},
		{
		  "Imf_year": "2021",
		  "country": "Singapore",
		  "imf_estimate": "66,263.418",
		  "un_estimate": "64,103",
		  "un_year": "64,103"
		},
		{
		  "Imf_year": "2021",
		  "country": "Australia",
		  "imf_estimate": "62,618.587",
		  "un_estimate": "54,763",
		  "un_year": "54,763"
		},
		{
		  "Imf_year": "2021",
		  "country": "Qatar",
		  "imf_estimate": "61,790.572",
		  "un_estimate": "64,782",
		  "un_year": "64,782"
		},
		{
		  "Imf_year": "2021",
		  "country": "Sweden",
		  "imf_estimate": "58,639.194",
		  "region": "Europe",
		  "un_estimate": "52,896",
		  "un_year": "52,896"
		},
		{
		  "Imf_year": "2021",
		  "country": "Macau",
		  "imf_estimate": "42,106.564",
		  "un_estimate": "84,097",
		  "un_year": "84,097"
		},
		{
		  "Imf_year": "2021",
		  "country": "Netherlands",
		  "imf_estimate": "57,714.876",
		  "region": "Europe",
		  "un_estimate": "53,053",
		  "un_year": "53,053"
		},
		{
		  "Imf_year": "2021",
		  "country": "Finland",
		  "imf_estimate": "53,522.565",
		  "region": "Europe",
		  "un_estimate": "48,678",
		  "un_year": "48,678"
		},
		{
		  "Imf_year": "2021",
		  "country": "Austria",
		  "imf_estimate": "53,793.367",
		  "region": "Europe",
		  "un_estimate": "49,701",
		  "un_year": "49,701"
		},
		{
		  "Imf_year": "53,353",
		  "country": "Greenland",
		  "imf_estimate": "N/A",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "2021",
		  "country": "Germany",
		  "imf_estimate": "50,787.859",
		  "region": "Europe",
		  "un_estimate": "46,232",
		  "un_year": "46,232"
		},
		{
		  "Imf_year": "2021",
		  "country": "Belgium",
		  "imf_estimate": "50,412.713",
		  "region": "Europe",
		  "un_estimate": "46,198",
		  "un_year": "46,198"
		},
		{
		  "Imf_year": "2021",
		  "country": "San Marino",
		  "imf_estimate": "50,934.189",
		  "region": "Europe",
		  "un_estimate": "47,313",
		  "un_year": "47,313"
		},
		{
		  "Imf_year": "2021",
		  "country": "Canada",
		  "imf_estimate": "52,791.228",
		  "un_estimate": "46,550",
		  "un_year": "46,550"
		},
		{
		  "Imf_year": "2021",
		  "country": "Hong Kong",
		  "imf_estimate": "49,485.084",
		  "un_estimate": "49,180",
		  "un_year": "49,180"
		},
		{
		  "Imf_year": "48,511",
		  "country": "British Virgin Islands",
		  "imf_estimate": "N/A",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "2021",
		  "country": "Israel",
		  "imf_estimate": "49,840.250",
		  "un_estimate": "46,376",
		  "un_year": "46,376"
		},
		{
		  "Imf_year": "2021",
		  "country": "New Zealand",
		  "imf_estimate": "48,348.994",
		  "un_estimate": "43,264",
		  "un_year": "43,264"
		},
		{
		  "Imf_year": "2021",
		  "country": "United Kingdom",
		  "imf_estimate": "46,200.258",
		  "region": "Europe",
		  "un_estimate": "41,855",
		  "un_year": "41,855"
		},
		{
		  "Imf_year": "2021",
		  "country": "France",
		  "imf_estimate": "45,028.265",
		  "region": "Europe",
		  "un_estimate": "40,319",
		  "un_year": "40,319"
		},
		{
		  "Imf_year": "2021",
		  "country": "Japan",
		  "imf_estimate": "40,704.304",
		  "un_estimate": "40,063",
		  "un_year": "40,063"
		},
		{
		  "Imf_year": "2021",
		  "country": "Andorra",
		  "imf_estimate": "40,417.265",
		  "region": "Europe",
		  "un_estimate": "40,887",
		  "un_year": "40,887"
		},
		{
		  "country": "Guam",
		  "imf_estimate": "N/A",
		  "un_estimate": "37,724",
		  "un_year": "37,724"
		},
		{
		  "Imf_year": "2021",
		  "country": "United Arab Emirates",
		  "imf_estimate": "43,537.689",
		  "un_estimate": "43,103",
		  "un_year": "43,103"
		},
		{
		  "Imf_year": "2021",
		  "country": "Italy",
		  "imf_estimate": "35,584.882",
		  "region": "Europe",
		  "un_estimate": "33,090",
		  "un_year": "33,090"
		},
		{
		  "Imf_year": "34,942",
		  "country": "New Caledonia",
		  "imf_estimate": "N/A",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "2021",
		  "country": "South Korea",
		  "imf_estimate": "35,195.522",
		  "un_estimate": "32,143",
		  "un_year": "32,143"
		},
		{
		  "Imf_year": "2021",
		  "country": "Brunei",
		  "imf_estimate": "33,979.373",
		  "un_estimate": "31,086",
		  "un_year": "31,086"
		},
		{
		  "Imf_year": "2021",
		  "country": "Puerto Rico",
		  "imf_estimate": "34,143.272",
		  "un_estimate": "35,791",
		  "un_year": "35,791"
		},
		{
		  "Imf_year": "2021",
		  "country": "Taiwan",
		  "imf_estimate": "33,401.709",
		  "un_estimate": "28,371",
		  "un_year": "28,371"
		},
		{
		  "Imf_year": "2021",
		  "country": "Malta",
		  "imf_estimate": "31,996.534",
		  "region": "Europe",
		  "un_estimate": "33,752",
		  "un_year": "33,752"
		},
		{
		  "Imf_year": "31,353",
		  "country": "Turks and Caicos Islands",
		  "imf_estimate": "N/A",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "2021",
		  "country": "Spain",
		  "imf_estimate": "30,536.858",
		  "region": "Europe",
		  "un_estimate": "29,816",
		  "un_year": "29,816"
		},
		{
		  "Imf_year": "2021",
		  "country": "Bahamas",
		  "imf_estimate": "27,437.197",
		  "un_estimate": "34,864",
		  "un_year": "34,864"
		},
		{
		  "Imf_year": "2021",
		  "country": "Cyprus",
		  "imf_estimate": "29,486.275",
		  "un_estimate": "28,285",
		  "un_year": "28,285"
		},
		{
		  "country": "Sint Maarten",
		  "imf_estimate": "N/A",
		  "un_estimate": "29,160",
		  "un_year": "29,160"
		},
		{
		  "Imf_year": "2021",
		  "country": "Slovenia",
		  "imf_estimate": "28,939.271",
		  "region": "Europe",
		  "un_estimate": "26,062",
		  "un_year": "26,062"
		},
		{
		  "Imf_year": "2021",
		  "country": "Estonia",
		  "imf_estimate": "27,100.736",
		  "region": "Europe",
		  "un_estimate": "23,740",
		  "un_year": "23,740"
		},
		{
		  "Imf_year": "2021",
		  "country": "Czech Republic",
		  "imf_estimate": "25,806.384",
		  "region": "Europe",
		  "un_estimate": "23,452",
		  "un_year": "23,452"
		},
		{
		  "Imf_year": "25,529",
		  "country": "Anguilla",
		  "imf_estimate": "N/A",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "2021",
		  "country": "Kuwait",
		  "imf_estimate": "27,927.163",
		  "un_estimate": "31,999",
		  "un_year": "31,999"
		},
		{
		  "Imf_year": "2021",
		  "country": "Portugal",
		  "imf_estimate": "24,457.144",
		  "region": "Europe",
		  "un_estimate": "23,350",
		  "un_year": "23,350"
		},
		{
		  "Imf_year": "2021",
		  "country": "Bahrain",
		  "imf_estimate": "26,293.947",
		  "un_estimate": "23,504",
		  "un_year": "23,504"
		},
		{
		  "Imf_year": "2021",
		  "country": "Aruba",
		  "imf_estimate": "25,700.865",
		  "un_estimate": "30,975",
		  "un_year": "30,975"
		},
		{
		  "Imf_year": "2021",
		  "country": "Saudi Arabia",
		  "imf_estimate": "23,762.420",
		  "un_estimate": "23,140",
		  "un_year": "23,140"
		},
		{
		  "Imf_year": "2021",
		  "country": "Lithuania",
		  "imf_estimate": "22,411.646",
		  "region": "Europe",
		  "un_estimate": "19,795",
		  "un_year": "19,795"
		},
		{
		  "Imf_year": "21,603",
		  "country": "Cook Islands",
		  "imf_estimate": "N/A",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "21,567",
		  "country": "French Polynesia",
		  "imf_estimate": "N/A",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "2021",
		  "country": "Slovakia",
		  "imf_estimate": "21,383.286",
		  "region": "Europe",
		  "un_estimate": "19,256",
		  "un_year": "19,256"
		},
		{
		  "country": "Northern Mariana Islands",
		  "imf_estimate": "N/A",
		  "un_estimate": "20,660",
		  "un_year": "20,660"
		},
		{
		  "Imf_year": "2021",
		  "country": "Greece",
		  "imf_estimate": "19,827.162",
		  "region": "Europe",
		  "un_estimate": "19,604",
		  "un_year": "19,604"
		},
		{
		  "Imf_year": "2021",
		  "country": "Latvia",
		  "imf_estimate": "19,538.902",
		  "region": "Europe",
		  "un_estimate": "17,885",
		  "un_year": "17,885"
		},
		{
		  "Imf_year": "18,980",
		  "country": "Curaçao",
		  "imf_estimate": "N/A",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "2021",
		  "country": "Hungary",
		  "imf_estimate": "18,527.592",
		  "region": "Europe",
		  "un_estimate": "16,879",
		  "un_year": "16,879"
		},
		{
		  "Imf_year": "2021",
		  "country": "Poland",
		  "imf_estimate": "17,318.497",
		  "region": "Europe",
		  "un_estimate": "15,727",
		  "un_year": "15,727"
		},
		{
		  "Imf_year": "2021",
		  "country": "Croatia",
		  "imf_estimate": "15,807.696",
		  "region": "Europe",
		  "un_estimate": "14,627",
		  "un_year": "14,627"
		},
		{
		  "Imf_year": "2021",
		  "country": "Oman",
		  "imf_estimate": "17,632.651",
		  "un_estimate": "15,343",
		  "un_year": "15,343"
		},
		{
		  "Imf_year": "2021",
		  "country": "Barbados",
		  "imf_estimate": "16,105.128",
		  "un_estimate": "18,149",
		  "un_year": "18,149"
		},
		{
		  "Imf_year": "2021",
		  "country": "Trinidad and Tobago",
		  "imf_estimate": "15,352.721",
		  "un_estimate": "16,637",
		  "un_year": "16,637"
		},
		{
		  "Imf_year": "2021",
		  "country": "Uruguay",
		  "imf_estimate": "16,965.081",
		  "un_estimate": "16,190",
		  "un_year": "16,190"
		},
		{
		  "Imf_year": "2021",
		  "country": "Chile",
		  "imf_estimate": "16,799.367",
		  "un_estimate": "14,896",
		  "un_year": "14,896"
		},
		{
		  "Imf_year": "2021",
		  "country": "Romania",
		  "imf_estimate": "14,863.887",
		  "region": "Europe",
		  "un_estimate": "12,914",
		  "un_year": "12,914"
		},
		{
		  "Imf_year": "2021",
		  "country": "Saint Kitts and Nevis",
		  "imf_estimate": "16,917.159",
		  "un_estimate": "19,896",
		  "un_year": "19,896"
		},
		{
		  "Imf_year": "2021",
		  "country": "Antigua and Barbuda",
		  "imf_estimate": "14,117.844",
		  "un_estimate": "17,113",
		  "un_year": "17,113"
		},
		{
		  "Imf_year": "2021",
		  "country": "Panama",
		  "imf_estimate": "13,861.061",
		  "un_estimate": "15,728",
		  "un_year": "15,728"
		},
		{
		  "Imf_year": "13,487",
		  "country": "Montserrat",
		  "imf_estimate": "N/A",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "2021",
		  "country": "Palau",
		  "imf_estimate": "11,835.178",
		  "un_estimate": "15,572",
		  "un_year": "15,572"
		},
		{
		  "Imf_year": "2021",
		  "country": "China",
		  "imf_estimate": "11,891.202",
		  "un_estimate": "10,004",
		  "un_year": "10,004"
		},
		{
		  "Imf_year": "2021",
		  "country": "Costa Rica",
		  "imf_estimate": "11,860.222",
		  "un_estimate": "12,238",
		  "un_year": "12,238"
		},
		{
		  "Imf_year": "2021",
		  "country": "Maldives",
		  "imf_estimate": "11,899.087",
		  "un_estimate": "10,626",
		  "un_year": "10,626"
		},
		{
		  "Imf_year": "2021",
		  "country": "Russia",
		  "imf_estimate": "11,273.242",
		  "region": "Europe",
		  "un_estimate": "11,606",
		  "un_year": "11,606"
		},
		{
		  "Imf_year": "2021",
		  "country": "Malaysia",
		  "imf_estimate": "11,124.670",
		  "un_estimate": "11,414",
		  "un_year": "11,414"
		},
		{
		  "country": "American Samoa",
		  "imf_estimate": "N/A",
		  "un_estimate": "11,535",
		  "un_year": "11,535"
		},
		{
		  "Imf_year": "2021",
		  "country": "Bulgaria",
		  "imf_estimate": "11,331.872",
		  "region": "Europe",
		  "un_estimate": "9,703",
		  "un_year": "9,703"
		},
		{
		  "Imf_year": "2021",
		  "country": "Nauru",
		  "imf_estimate": "10,138.196",
		  "un_estimate": "12,351",
		  "un_year": "12,351"
		},
		{
		  "Imf_year": "2021",
		  "country": "Kazakhstan",
		  "imf_estimate": "10,144.682",
		  "un_estimate": "9,793",
		  "un_year": "9,793"
		},
		{
		  "Imf_year": "2021",
		  "country": "Saint Lucia",
		  "imf_estimate": "9,419.272",
		  "un_estimate": "11,611",
		  "un_year": "11,611"
		},
		{
		  "Imf_year": "2021",
		  "country": "Seychelles",
		  "imf_estimate": "13,140.368",
		  "un_estimate": "17,382",
		  "un_year": "17,382"
		},
		{
		  "Imf_year": "2021",
		  "country": "Mauritius",
		  "imf_estimate": "8,681.608",
		  "un_estimate": "11,169",
		  "un_year": "11,169"
		},
		{
		  "Imf_year": "2021",
		  "country": "Turkey",
		  "imf_estimate": "9,406.575",
		  "un_estimate": "9,127",
		  "un_year": "9,127"
		},
		{
		  "Imf_year": "9,296",
		  "country": "Cuba",
		  "imf_estimate": "N/A",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "2021",
		  "country": "Mexico",
		  "imf_estimate": "9,967.388",
		  "un_estimate": "9,849",
		  "un_year": "9,849"
		},
		{
		  "Imf_year": "2021",
		  "country": "Guyana",
		  "imf_estimate": "9,369.011",
		  "un_estimate": "6,610",
		  "un_year": "6,610"
		},
		{
		  "Imf_year": "2021",
		  "country": "Grenada",
		  "imf_estimate": "9,575.343",
		  "un_estimate": "10,818",
		  "un_year": "10,818"
		},
		{
		  "Imf_year": "2021",
		  "country": "Argentina",
		  "imf_estimate": "9,929.154",
		  "un_estimate": "10,041",
		  "un_year": "10,041"
		},
		{
		  "Imf_year": "2021",
		  "country": "Montenegro",
		  "imf_estimate": "8,837.578",
		  "region": "Europe",
		  "un_estimate": "8,825",
		  "un_year": "8,825"
		},
		{
		  "Imf_year": "2021",
		  "country": "Turkmenistan",
		  "imf_estimate": "8,843.868",
		  "un_estimate": "8,124",
		  "un_year": "8,124"
		},
		{
		  "Imf_year": "2021",
		  "country": "Serbia",
		  "imf_estimate": "8,793.836",
		  "region": "Europe",
		  "un_estimate": "7,359",
		  "un_year": "7,359"
		},
		{
		  "Imf_year": "2021",
		  "country": "Gabon",
		  "imf_estimate": "8,569.216",
		  "un_estimate": "7,773",
		  "un_year": "7,773"
		},
		{
		  "Imf_year": "2021",
		  "country": "Iran",
		  "imf_estimate": "12,725.042",
		  "un_estimate": "7,282",
		  "un_year": "7,282"
		},
		{
		  "Imf_year": "2021",
		  "country": "Equatorial Guinea",
		  "imf_estimate": "8,625.763",
		  "un_estimate": "8,130",
		  "un_year": "8,130"
		},
		{
		  "Imf_year": "2021",
		  "country": "Dominican Republic",
		  "imf_estimate": "8,491.619",
		  "un_estimate": "8,282",
		  "un_year": "8,282"
		},
		{
		  "Imf_year": "2021",
		  "country": "Botswana",
		  "imf_estimate": "7,349.884",
		  "un_estimate": "7,961",
		  "un_year": "7,961"
		},
		{
		  "Imf_year": "2021",
		  "country": "Thailand",
		  "imf_estimate": "7,808.663",
		  "un_estimate": "7,785",
		  "un_year": "7,785"
		},
		{
		  "Imf_year": "2021",
		  "country": "Saint Vincent and the Grenadines",
		  "imf_estimate": "6,952.242",
		  "un_estimate": "7,464",
		  "un_year": "7,464"
		},
		{
		  "Imf_year": "2021",
		  "country": "Brazil",
		  "imf_estimate": "7,741.153",
		  "un_estimate": "8,755",
		  "un_year": "8,755"
		},
		{
		  "Imf_year": "2021",
		  "country": "Dominica",
		  "imf_estimate": "7,777.016",
		  "un_estimate": "8,111",
		  "un_year": "8,111"
		},
		{
		  "Imf_year": "2021",
		  "country": "Bosnia and Herzegovina",
		  "imf_estimate": "6,647.830",
		  "region": "Europe",
		  "un_estimate": "6,109",
		  "un_year": "6,109"
		},
		{
		  "Imf_year": "2021",
		  "country": "Peru",
		  "imf_estimate": "6,676.517",
		  "un_estimate": "6,978",
		  "un_year": "6,978"
		},
		{
		  "Imf_year": "2021",
		  "country": "North Macedonia",
		  "imf_estimate": "6,711.734",
		  "region": "Europe",
		  "un_estimate": "6,093",
		  "un_year": "6,093"
		},
		{
		  "Imf_year": "2021",
		  "country": "Belarus",
		  "imf_estimate": "7,032.477",
		  "region": "Europe",
		  "un_estimate": "6,674",
		  "un_year": "6,674"
		},
		{
		  "Imf_year": "2021",
		  "country": "Albania",
		  "imf_estimate": "5,837.180",
		  "region": "Europe",
		  "un_estimate": "5,303",
		  "un_year": "5,303"
		},
		{
		  "Imf_year": "2021",
		  "country": "Colombia",
		  "imf_estimate": "5,892.140",
		  "un_estimate": "6,432",
		  "un_year": "6,432"
		},
		{
		  "Imf_year": "2021",
		  "country": "Ecuador",
		  "imf_estimate": "5,884.147",
		  "un_estimate": "6,184",
		  "un_year": "6,184"
		},
		{
		  "Imf_year": "2021",
		  "country": "South Africa",
		  "imf_estimate": "6,861.166",
		  "un_estimate": "6,001",
		  "un_year": "6,001"
		},
		{
		  "Imf_year": "2021",
		  "country": "Jamaica",
		  "imf_estimate": "5,421.642",
		  "un_estimate": "5,369",
		  "un_year": "5,369"
		},
		{
		  "Imf_year": "2021",
		  "country": "Paraguay",
		  "imf_estimate": "5,028.217",
		  "un_estimate": "5,406",
		  "un_year": "5,406"
		},
		{
		  "Imf_year": "2021",
		  "country": "Tuvalu",
		  "imf_estimate": "6,004.100",
		  "un_estimate": "4,036",
		  "un_year": "4,036"
		},
		{
		  "Imf_year": "2021",
		  "country": "Tonga",
		  "imf_estimate": "5,009.784",
		  "un_estimate": "4,865",
		  "un_year": "4,865"
		},
		{
		  "Imf_year": "2021",
		  "country": "Fiji",
		  "imf_estimate": "5,127.440",
		  "un_estimate": "6,185",
		  "un_year": "6,185"
		},
		{
		  "Imf_year": "2021",
		  "country": "Azerbaijan",
		  "imf_estimate": "5,167.377",
		  "un_estimate": "4,782",
		  "un_year": "4,782"
		},
		{
		  "Imf_year": "2021",
		  "country": "Kosovo",
		  "imf_estimate": "4,986.263",
		  "region": "Europe",
		  "un_estimate": "4,473",
		  "un_year": "4,473"
		},
		{
		  "Imf_year": "2021",
		  "country": "Moldova",
		  "imf_estimate": "4,791.625",
		  "region": "Europe",
		  "un_estimate": "2,957",
		  "un_year": "2,957"
		},
		{
		  "Imf_year": "2021",
		  "country": "Iraq",
		  "imf_estimate": "4,892.964",
		  "un_estimate": "5,730",
		  "un_year": "5,730"
		},
		{
		  "Imf_year": "2021",
		  "country": "Guatemala",
		  "imf_estimate": "4,542.253",
		  "un_estimate": "4,363",
		  "un_year": "4,363"
		},
		{
		  "Imf_year": "2021",
		  "country": "Namibia",
		  "imf_estimate": "4,693.455",
		  "un_estimate": "4,957",
		  "un_year": "4,957"
		},
		{
		  "Imf_year": "2021",
		  "country": "Georgia",
		  "imf_estimate": "4,807.950",
		  "un_estimate": "4,439",
		  "un_year": "4,439"
		},
		{
		  "Imf_year": "2021",
		  "country": "Jordan",
		  "imf_estimate": "4,393.642",
		  "un_estimate": "4,405",
		  "un_year": "4,405"
		},
		{
		  "Imf_year": "2021",
		  "country": "Indonesia",
		  "imf_estimate": "4,224.982",
		  "un_estimate": "4,136",
		  "un_year": "4,136"
		},
		{
		  "Imf_year": "2021",
		  "country": "Marshall Islands",
		  "imf_estimate": "4,338.173",
		  "un_estimate": "4,038",
		  "un_year": "4,038"
		},
		{
		  "Imf_year": "2021",
		  "country": "Mongolia",
		  "imf_estimate": "4,185.536",
		  "un_estimate": "4,295",
		  "un_year": "4,295"
		},
		{
		  "Imf_year": "2021",
		  "country": "Armenia",
		  "imf_estimate": "4,594.912",
		  "un_estimate": "4,623",
		  "un_year": "4,623"
		},
		{
		  "Imf_year": "2021",
		  "country": "El Salvador",
		  "imf_estimate": "4,244.299",
		  "un_estimate": "4,187",
		  "un_year": "4,187"
		},
		{
		  "Imf_year": "2021",
		  "country": "Suriname",
		  "imf_estimate": "4,620.395",
		  "un_estimate": "6,360",
		  "un_year": "6,360"
		},
		{
		  "Imf_year": "2021",
		  "country": "Ukraine",
		  "imf_estimate": "4,384.237",
		  "region": "Europe",
		  "un_estimate": "3,496",
		  "un_year": "3,496"
		},
		{
		  "Imf_year": "2021",
		  "country": "Belize",
		  "imf_estimate": "4,457.886",
		  "un_estimate": "4,884",
		  "un_year": "4,884"
		},
		{
		  "Imf_year": "2021",
		  "country": "Egypt",
		  "imf_estimate": "3,851.746",
		  "un_estimate": "3,161",
		  "un_year": "3,161"
		},
		{
		  "Imf_year": "2021",
		  "country": "Sri Lanka",
		  "imf_estimate": "3,665.765",
		  "un_estimate": "3,940",
		  "un_year": "3,940"
		},
		{
		  "Imf_year": "2021",
		  "country": "Micronesia",
		  "imf_estimate": "3,855.223",
		  "un_estimate": "3,640",
		  "un_year": "3,640"
		},
		{
		  "Imf_year": "2021",
		  "country": "Vietnam",
		  "imf_estimate": "3,742.858",
		  "un_estimate": "2,715",
		  "un_year": "2,715"
		},
		{
		  "Imf_year": "2021",
		  "country": "Eswatini",
		  "imf_estimate": "3,965.426",
		  "un_estimate": "4,002",
		  "un_year": "4,002"
		},
		{
		  "Imf_year": "2021",
		  "country": "Tunisia",
		  "imf_estimate": "3,555.587",
		  "un_estimate": "3,318",
		  "un_year": "3,318"
		},
		{
		  "Imf_year": "2021",
		  "country": "Samoa",
		  "imf_estimate": "3,906.413",
		  "un_estimate": "4,285",
		  "un_year": "4,285"
		},
		{
		  "Imf_year": "2021",
		  "country": "Philippines",
		  "imf_estimate": "3,492.072",
		  "un_estimate": "3,324",
		  "un_year": "3,324"
		},
		{
		  "Imf_year": "2021",
		  "country": "Bolivia",
		  "imf_estimate": "3,266.690",
		  "un_estimate": "3,552",
		  "un_year": "3,552"
		},
		{
		  "Imf_year": "2021",
		  "country": "Libya",
		  "imf_estimate": "4,068.611",
		  "un_estimate": "4,810",
		  "un_year": "4,810"
		},
		{
		  "Imf_year": "2021",
		  "country": "Cape Verde",
		  "imf_estimate": "3,346.553",
		  "un_estimate": "3,604",
		  "un_year": "3,604"
		},
		{
		  "Imf_year": "2021",
		  "country": "Morocco",
		  "imf_estimate": "3,470.795",
		  "un_estimate": "3,282",
		  "un_year": "3,282"
		},
		{
		  "Imf_year": "2021",
		  "country": "Algeria",
		  "imf_estimate": "3,638.328",
		  "un_estimate": "3,976",
		  "un_year": "3,976"
		},
		{
		  "Imf_year": "2021",
		  "country": "Bhutan",
		  "imf_estimate": "3,296.106",
		  "un_estimate": "3,361",
		  "un_year": "3,361"
		},
		{
		  "Imf_year": "2021",
		  "country": "Djibouti",
		  "imf_estimate": "3,645.500",
		  "un_estimate": "3,252",
		  "un_year": "3,252"
		},
		{
		  "Imf_year": "2021",
		  "country": "Palestine",
		  "imf_estimate": "3,320.853",
		  "un_estimate": "3,424",
		  "un_year": "3,424"
		},
		{
		  "Imf_year": "2021",
		  "country": "Vanuatu",
		  "imf_estimate": "3,235.205",
		  "un_estimate": "3,023",
		  "un_year": "3,023"
		},
		{
		  "Imf_year": "2021",
		  "country": "Syria",
		  "imf_estimate": "2,807",
		  "un_estimate": "1,194",
		  "un_year": "1,194"
		},
		{
		  "Imf_year": "2021",
		  "country": "Lebanon",
		  "imf_estimate": "2,802",
		  "un_estimate": "7,784",
		  "un_year": "7,784"
		},
		{
		  "Imf_year": "2021",
		  "country": "Laos",
		  "imf_estimate": "2,625.610",
		  "un_estimate": "2,625",
		  "un_year": "2,625"
		},
		{
		  "Imf_year": "2021",
		  "country": "Papua New Guinea",
		  "imf_estimate": "2,951.977",
		  "un_estimate": "2,845",
		  "un_year": "2,845"
		},
		{
		  "Imf_year": "2021",
		  "country": "Honduras",
		  "imf_estimate": "2,602.170",
		  "un_estimate": "2,575",
		  "un_year": "2,575"
		},
		{
		  "Imf_year": "2021",
		  "country": "Ivory Coast",
		  "imf_estimate": "2,489.102",
		  "un_estimate": "2,276",
		  "un_year": "2,276"
		},
		{
		  "Imf_year": "2021",
		  "country": "Congo",
		  "imf_estimate": "2,655.719",
		  "un_estimate": "2,304",
		  "un_year": "2,304"
		},
		{
		  "Imf_year": "2021",
		  "country": "Solomon Islands",
		  "imf_estimate": "2,356.505",
		  "un_estimate": "1,945",
		  "un_year": "1,945"
		},
		{
		  "Imf_year": "2021",
		  "country": "Nigeria",
		  "imf_estimate": "2,272.844",
		  "un_estimate": "2,361",
		  "un_year": "2,361"
		},
		{
		  "Imf_year": "2021",
		  "country": "Ghana",
		  "imf_estimate": "2,413.095",
		  "un_estimate": "2,203",
		  "un_year": "2,203"
		},
		{
		  "Imf_year": "2021",
		  "country": "India",
		  "imf_estimate": "2,116.444",
		  "un_estimate": "2,116",
		  "un_year": "2,116"
		},
		{
		  "Imf_year": "2021",
		  "country": "Mauritania",
		  "imf_estimate": "2,161.279",
		  "un_estimate": "1,678",
		  "un_year": "1,678"
		},
		{
		  "Imf_year": "2021",
		  "country": "São Tomé and Príncipe",
		  "imf_estimate": "2,392.893",
		  "un_estimate": "1,961",
		  "un_year": "1,961"
		},
		{
		  "Imf_year": "2021",
		  "country": "Bangladesh",
		  "imf_estimate": "2,138.794[9]",
		  "un_estimate": "1,846",
		  "un_year": "1,846"
		},
		{
		  "Imf_year": "2021",
		  "country": "Kenya",
		  "imf_estimate": "2,198.593",
		  "un_estimate": "1,817",
		  "un_year": "1,817"
		},
		{
		  "Imf_year": "2021",
		  "country": "Angola",
		  "imf_estimate": "2,200.675",
		  "un_estimate": "2,671",
		  "un_year": "2,671"
		},
		{
		  "Imf_year": "2021",
		  "country": "Haiti",
		  "imf_estimate": "1,691.825",
		  "un_estimate": "715",
		  "un_year": "715"
		},
		{
		  "Imf_year": "2021",
		  "country": "Kiribati",
		  "imf_estimate": "1,927.077",
		  "un_estimate": "1,657",
		  "un_year": "1,657"
		},
		{
		  "Imf_year": "2021",
		  "country": "Nicaragua",
		  "imf_estimate": "2,047.097",
		  "un_estimate": "1,913",
		  "un_year": "1,913"
		},
		{
		  "Imf_year": "2021",
		  "country": "Uzbekistan",
		  "imf_estimate": "1,901.492",
		  "un_estimate": "1,756",
		  "un_year": "1,756"
		},
		{
		  "Imf_year": "2021",
		  "country": "Cambodia",
		  "imf_estimate": "1,647.019",
		  "un_estimate": "1,644",
		  "un_year": "1,644"
		},
		{
		  "Imf_year": "2021",
		  "country": "Zimbabwe",
		  "imf_estimate": "1,664.758",
		  "un_estimate": "1,464",
		  "un_year": "1,464"
		},
		{
		  "Imf_year": "2021",
		  "country": "Cameroon",
		  "imf_estimate": "1,645.807",
		  "un_estimate": "1,534",
		  "un_year": "1,534"
		},
		{
		  "Imf_year": "2021",
		  "country": "Senegal",
		  "imf_estimate": "1,602.898",
		  "un_estimate": "1,452",
		  "un_year": "1,452"
		},
		{
		  "Imf_year": "2021",
		  "country": "Venezuela",
		  "imf_estimate": "1,627.353",
		  "un_estimate": "4,733",
		  "un_year": "4,733"
		},
		{
		  "Imf_year": "2021",
		  "country": "Myanmar",
		  "imf_estimate": "1,246.318",
		  "un_estimate": "1,421",
		  "un_year": "1,421"
		},
		{
		  "Imf_year": "2021",
		  "country": "Comoros",
		  "imf_estimate": "1,390.061",
		  "un_estimate": "1,370",
		  "un_year": "1,370"
		},
		{
		  "Imf_year": "2021",
		  "country": "Benin",
		  "imf_estimate": "1,446.829",
		  "un_estimate": "1,220",
		  "un_year": "1,220"
		},
		{
		  "Imf_year": "2021",
		  "country": "East Timor",
		  "imf_estimate": "1,262.722",
		  "un_estimate": "1,561",
		  "un_year": "1,561"
		},
		{
		  "Imf_year": "2021",
		  "country": "Pakistan",
		  "imf_estimate": "1,260",
		  "un_estimate": "1,187",
		  "un_year": "1,187"
		},
		{
		  "Imf_year": "2021",
		  "country": "Nepal",
		  "imf_estimate": "1,172.638",
		  "un_estimate": "1,074",
		  "un_year": "1,074"
		},
		{
		  "Imf_year": "2021",
		  "country": "Lesotho",
		  "imf_estimate": "1,187.512",
		  "un_estimate": "1,158",
		  "un_year": "1,158"
		},
		{
		  "Imf_year": "2021",
		  "country": "Guinea",
		  "imf_estimate": "1,168.178",
		  "un_estimate": "967",
		  "un_year": "967"
		},
		{
		  "Imf_year": "2021",
		  "country": "Kyrgyzstan",
		  "imf_estimate": "1,224.745",
		  "un_estimate": "1,318",
		  "un_year": "1,318"
		},
		{
		  "Imf_year": "2021",
		  "country": "Tanzania",
		  "imf_estimate": "1,159.193",
		  "un_estimate": "1,084",
		  "un_year": "1,084"
		},
		{
		  "Imf_year": "2021",
		  "country": "Togo",
		  "imf_estimate": "1,000.438",
		  "un_estimate": "899",
		  "un_year": "899"
		},
		{
		  "Imf_year": "2021",
		  "country": "Mali",
		  "imf_estimate": "966.141",
		  "un_estimate": "887",
		  "un_year": "887"
		},
		{
		  "Imf_year": "2021",
		  "country": "Zambia",
		  "imf_estimate": "1,115.272",
		  "un_estimate": "1,292",
		  "un_year": "1,292"
		},
		{
		  "Imf_year": "2021",
		  "country": "Uganda",
		  "imf_estimate": "1,018.436",
		  "un_estimate": "737",
		  "un_year": "737"
		},
		{
		  "Imf_year": "2021",
		  "country": "Ethiopia",
		  "imf_estimate": "939.511",
		  "un_estimate": "828",
		  "un_year": "828"
		},
		{
		  "Imf_year": "2021",
		  "country": "Guinea-Bissau",
		  "imf_estimate": "858.040",
		  "un_estimate": "688",
		  "un_year": "688"
		},
		{
		  "Imf_year": "2021",
		  "country": "Burkina Faso",
		  "imf_estimate": "926.200",
		  "un_estimate": "787",
		  "un_year": "787"
		},
		{
		  "Imf_year": "2021",
		  "country": "Gambia",
		  "imf_estimate": "819.220",
		  "un_estimate": "776",
		  "un_year": "776"
		},
		{
		  "Imf_year": "2021",
		  "country": "Rwanda",
		  "imf_estimate": "802.264",
		  "un_estimate": "820",
		  "un_year": "820"
		},
		{
		  "Imf_year": "2021",
		  "country": "Tajikistan",
		  "imf_estimate": "839.180",
		  "un_estimate": "894",
		  "un_year": "894"
		},
		{
		  "Imf_year": "2021",
		  "country": "Sudan",
		  "imf_estimate": "789.448",
		  "un_estimate": "815",
		  "un_year": "815"
		},
		{
		  "Imf_year": "2021",
		  "country": "Yemen",
		  "imf_estimate": "585.003",
		  "un_estimate": "855",
		  "un_year": "855"
		},
		{
		  "Imf_year": "2021",
		  "country": "Chad",
		  "imf_estimate": "729.844",
		  "un_estimate": "707",
		  "un_year": "707"
		},
		{
		  "Imf_year": "2021",
		  "country": "Liberia",
		  "imf_estimate": "703.406",
		  "un_estimate": "523",
		  "un_year": "523"
		},
		{
		  "Imf_year": "640",
		  "country": "North Korea",
		  "imf_estimate": "N/A",
		  "un_estimate": "2019",
		  "un_year": "2019"
		},
		{
		  "Imf_year": "2021",
		  "country": "Niger",
		  "imf_estimate": "622.230",
		  "un_estimate": "555",
		  "un_year": "555"
		},
		{
		  "Imf_year": "2021",
		  "country": "Eritrea",
		  "imf_estimate": "625.974",
		  "un_estimate": "567",
		  "un_year": "567"
		},
		{
		  "Imf_year": "2021",
		  "country": "Afghanistan",
		  "imf_estimate": "592",
		  "un_estimate": "470",
		  "un_year": "470"
		},
		{
		  "Imf_year": "2021",
		  "country": "DR Congo",
		  "imf_estimate": "593.558",
		  "un_estimate": "545",
		  "un_year": "545"
		},
		{
		  "Imf_year": "2021",
		  "country": "Central African Republic",
		  "imf_estimate": "525.914",
		  "un_estimate": "468",
		  "un_year": "468"
		},
		{
		  "Imf_year": "2021",
		  "country": "Sierra Leone",
		  "imf_estimate": "541.063",
		  "un_estimate": "528",
		  "un_year": "528"
		},
		{
		  "Imf_year": "2021",
		  "country": "Madagascar",
		  "imf_estimate": "498.682",
		  "un_estimate": "523",
		  "un_year": "523"
		},
		{
		  "Imf_year": "2021",
		  "country": "Malawi",
		  "imf_estimate": "565.798",
		  "un_estimate": "435",
		  "un_year": "435"
		},
		{
		  "Imf_year": "2021",
		  "country": "Mozambique",
		  "imf_estimate": "492.273",
		  "un_estimate": "504",
		  "un_year": "504"
		},
		{
		  "Imf_year": "2021",
		  "country": "Somalia",
		  "imf_estimate": "350.361",
		  "un_estimate": "105",
		  "un_year": "105"
		},
		{
		  "Imf_year": "2021",
		  "country": "South Sudan",
		  "imf_estimate": "230.132",
		  "un_estimate": "448",
		  "un_year": "448"
		},
		{
		  "Imf_year": "2021",
		  "country": "Burundi",
		  "imf_estimate": "261.053",
		  "un_estimate": "260",
		  "un_year": "260"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100",
	  "resume_dict": {}
	}
