Reddit Post Scraper
********************************

Reddit Post Scraper scrapes  awards, community, description, post_date, post_link, posted_by and upvotes

Code
######
.. tabs::

   .. code-tab:: py

        from bot_studio import *
	datakund = bot_studio.new()
	response = datakund.reddit_post_keyword(keyword="delta")

   .. code-tab:: javascript
		 NodeJS
   
         var datakund=require("datakund")
	 datakund.reddit_post_keyword("keyword")
	
   .. code-tab:: bash
		 Curl

         curl -X POST http://127.0.0.1:5000/run -H 'cache-control: no-cache' -H 'content-type: application/json' -d '{"user":"apiKey","bot":"reddit_post_keyword~D75HsPTUIeOmN0bLp5ulrwB7F1f2","publicbot":true,"outputdata":{"keyword":"delta"}}'

Response Data
##############

.. code-block:: json

			
	{
	  "body": [
		{
		  "awards": "1 awards",
		  "comments": "150 comments",
		  "community": "r/trees",
		  "description": "my mom just ate a 750 mg delta 8 gummy",
		  "post_date": "22 days ago",
		  "post_link": "/r/trees/comments/rp7e4s/my_mom_just_ate_a_750_mg_delta_8_gummy/",
		  "posted_by": "u/seaturtles5288",
		  "upvotes": "187 upvotes"
		},
		{
		  "awards": "5 awards",
		  "comments": "1.3k comments",
		  "community": "r/Coronavirus",
		  "description": "Omicron associated with 91% reduction in risk of death compared to Delta, study finds",
		  "post_date": "3 days ago",
		  "post_link": "/r/Coronavirus/comments/s3r8sx/omicron_associated_with_91_reduction_in_risk_of/",
		  "posted_by": "u/FatFuckinLenny",
		  "upvotes": "19.9k upvotes"
		},
		{
		  "awards": "8 awards",
		  "comments": "3.0k comments",
		  "community": "r/Coronavirus",
		  "description": "Leaders urge Americans to cancel New Year’s plans: ‘Omicron and delta are coming to your party’",
		  "post_date": "19 days ago",
		  "post_link": "/r/Coronavirus/comments/rr7div/leaders_urge_americans_to_cancel_new_years_plans/",
		  "posted_by": "u/zsreport",
		  "upvotes": "25.4k upvotes"
		},
		{
		  "awards": "0 awards",
		  "comments": "1.4k comments",
		  "community": "r/PublicFreakout",
		  "description": "Woman kicked off Delta flight for wearing a closed vent respirator.",
		  "post_date": "2 days ago",
		  "post_link": "/r/PublicFreakout/comments/s4kdh0/woman_kicked_off_delta_flight_for_wearing_a/",
		  "posted_by": "u/Veenendaler",
		  "upvotes": "6.6k upvotes"
		},
		{
		  "awards": "0 awards",
		  "comments": "66 comments",
		  "community": "r/trees",
		  "description": "Thoughts on delta 8",
		  "post_date": "1 month ago",
		  "post_link": "/r/trees/comments/r9hyok/thoughts_on_delta_8/",
		  "posted_by": "u/Saintbirdyy",
		  "upvotes": "13 upvotes"
		},
		{
		  "awards": "6 awards",
		  "comments": "4.0k comments",
		  "community": "r/news",
		  "description": "Delta plane makes emergency landing after passenger assaults flight attendant and air marshal, police say",
		  "post_date": "1 month ago",
		  "post_link": "/r/news/comments/rd7kem/delta_plane_makes_emergency_landing_after/",
		  "posted_by": "u/anyonmoussource",
		  "upvotes": "43.7k upvotes"
		},
		{
		  "awards": "1 awards",
		  "comments": "799 comments",
		  "community": "r/news",
		  "description": "Delta loses $408 million; 8,000 employees contract Covid over the last four weeks",
		  "post_date": "4 days ago",
		  "post_link": "/r/news/comments/s31pyv/delta_loses_408_million_8000_employees_contract/",
		  "posted_by": "u/Lord-AG",
		  "upvotes": "8.4k upvotes"
		},
		{
		  "awards": "0 awards",
		  "comments": "101 comments",
		  "community": "r/Drugs",
		  "description": "The truth about Delta 8",
		  "post_date": "3 months ago",
		  "post_link": "/r/Drugs/comments/qhy1jt/the_truth_about_delta_8/",
		  "posted_by": "u/CDCpup",
		  "upvotes": "57 upvotes"
		},
		{
		  "awards": "1 awards",
		  "comments": "963 comments",
		  "community": "r/Coronavirus",
		  "description": "Omicron has a 91% lower chance of death than delta variant of COVID-19: study",
		  "post_date": "4 days ago",
		  "post_link": "/r/Coronavirus/comments/s2qtiy/omicron_has_a_91_lower_chance_of_death_than_delta/",
		  "posted_by": "u/ankermouse11",
		  "upvotes": "4.4k upvotes"
		},
		{
		  "awards": "4 awards",
		  "comments": "1.4k comments",
		  "community": "r/PublicFreakout",
		  "description": "Obnoxious drunk guy not wearing his mask fights another passenger on Delta flight",
		  "post_date": "23 days ago",
		  "post_link": "/r/PublicFreakout/comments/roa3pc/obnoxious_drunk_guy_not_wearing_his_mask_fights/",
		  "posted_by": "u/tefunka",
		  "upvotes": "16.7k upvotes"
		},
		{
		  "awards": "20 awards",
		  "comments": "1.1k comments",
		  "community": "r/mildlyinteresting",
		  "description": "Flew on a new Delta plane, and they put a window in the lavatory",
		  "post_date": "27 days ago",
		  "post_link": "/r/mildlyinteresting/comments/rln9ek/flew_on_a_new_delta_plane_and_they_put_a_window/",
		  "posted_by": "u/MaximumEngineering8",
		  "upvotes": "36.2k upvotes"
		},
		{
		  "awards": "14 awards",
		  "comments": "1.6k comments",
		  "community": "r/Coronavirus",
		  "description": "U.K. Study Finds No Evidence Omicron Cases Are Less Severe Than Delta",
		  "post_date": "1 month ago",
		  "post_link": "/r/Coronavirus/comments/rii6vj/uk_study_finds_no_evidence_omicron_cases_are_less/",
		  "posted_by": "u/Fearless-Cricket3297",
		  "upvotes": "15.8k upvotes"
		},
		{
		  "awards": "1 awards",
		  "comments": "171 comments",
		  "community": "r/trees",
		  "description": "I tried Delta-8",
		  "post_date": "4 months ago",
		  "post_link": "/r/trees/comments/q0oa7j/i_tried_delta8/",
		  "posted_by": "u/boonkdocksaints",
		  "upvotes": "463 upvotes"
		},
		{
		  "awards": "1 awards",
		  "comments": "580 comments",
		  "community": "r/EverythingScience",
		  "description": "Cyprus reportedly discovers a Covid variant that combines omicron and delta",
		  "post_date": "8 days ago",
		  "post_link": "/r/EverythingScience/comments/rzj7ru/cyprus_reportedly_discovers_a_covid_variant_that/",
		  "posted_by": "u/malcolm58",
		  "upvotes": "2.6k upvotes"
		},
		{
		  "awards": "4 awards",
		  "comments": "219 comments",
		  "community": "r/mildlyinfuriating",
		  "description": "Had time to go to bed and wake up in the morning … still on hold. Thanks Delta",
		  "post_date": "4 days ago",
		  "post_link": "/r/mildlyinfuriating/comments/s2pc7e/had_time_to_go_to_bed_and_wake_up_in_the_morning/",
		  "posted_by": "u/Juggernaut06",
		  "upvotes": "9.2k upvotes"
		},
		{
		  "awards": "15 awards",
		  "comments": "607 comments",
		  "community": "r/askscience",
		  "description": "Do we have evidence that Omicron is \"more mild\" than Delta coronavirus?",
		  "post_date": "18 days ago",
		  "post_link": "/r/askscience/comments/rs3cn1/do_we_have_evidence_that_omicron_is_more_mild/",
		  "posted_by": "u/jdtrouble",
		  "upvotes": "7.5k upvotes"
		},
		{
		  "awards": "133 awards",
		  "comments": "352 comments",
		  "community": "r/Superstonk",
		  "description": "GME Delta Neutral Update - Hedgies R F'd",
		  "post_date": "10 days ago",
		  "post_link": "/r/Superstonk/comments/rxtqpg/gme_delta_neutral_update_hedgies_r_fd/",
		  "posted_by": "u/yelyah2",
		  "upvotes": "6.2k upvotes"
		},
		{
		  "awards": "5 awards",
		  "comments": "2.1k comments",
		  "community": "r/Coronavirus",
		  "description": "First stats for Omicron in Israel: protection for vaccinated similar to Delta, twice as dangerous for unvaccinated",
		  "post_date": "2 months ago",
		  "post_link": "/r/Coronavirus/comments/r5ueps/first_stats_for_omicron_in_israel_protection_for/",
		  "posted_by": "u/benben83",
		  "upvotes": "23.3k upvotes"
		},
		{
		  "awards": "1 awards",
		  "comments": "576 comments",
		  "community": "r/entertainment",
		  "description": "'Karen' who slapped Delta passenger is ex-'Baywatch' actress Patricia Cornwall",
		  "post_date": "20 days ago",
		  "post_link": "/r/entertainment/comments/rql0oz/karen_who_slapped_delta_passenger_is_exbaywatch/",
		  "posted_by": "u/nimobo",
		  "upvotes": "4.5k upvotes"
		},
		{
		  "awards": "3 awards",
		  "comments": "701 comments",
		  "community": "r/Coronavirus",
		  "description": "U.S. hospitals are once again 'at a breaking point' with delta and omicron",
		  "post_date": "26 days ago",
		  "post_link": "/r/Coronavirus/comments/rlrch6/us_hospitals_are_once_again_at_a_breaking_point/",
		  "posted_by": "u/Dirtyfaction",
		  "upvotes": "6.1k upvotes"
		},
		{
		  "awards": "0 awards",
		  "comments": "511 comments",
		  "community": "r/Coronavirus",
		  "description": "Omicron Cases Pass U.S. Peak Seen With Delta, But With Fewer Hospitalizations",
		  "post_date": "21 days ago",
		  "post_link": "/r/Coronavirus/comments/rpntx6/omicron_cases_pass_us_peak_seen_with_delta_but/",
		  "posted_by": "u/jsinkwitz",
		  "upvotes": "3.9k upvotes"
		},
		{
		  "awards": "3 awards",
		  "comments": "875 comments",
		  "community": "r/canada",
		  "description": "Omicron carries 80% less risk of hospitalization vs. Delta, study suggests",
		  "post_date": "26 days ago",
		  "post_link": "/r/canada/comments/rmceub/omicron_carries_80_less_risk_of_hospitalization/",
		  "posted_by": "u/NilbyBC",
		  "upvotes": "2.8k upvotes"
		},
		{
		  "awards": "4 awards",
		  "comments": "400 comments",
		  "community": "r/collapse",
		  "description": "New Variant \"Deltacron\" discovered in Cyprus, 8 January 2022. \"...Shares the genetic background of the Delta variant along with some of the mutations of Omicron...\"",
		  "post_date": "9 days ago",
		  "post_link": "/r/collapse/comments/rzblwr/new_variant_deltacron_discovered_in_cyprus_8/",
		  "posted_by": "u/fkaneko",
		  "upvotes": "1.1k upvotes"
		},
		{
		  "awards": "0 awards",
		  "comments": "210 comments",
		  "community": "r/news",
		  "description": "Three women charged for allegedly assaulting Delta Airlines employees",
		  "post_date": "3 days ago",
		  "post_link": "/r/news/comments/s3fojc/three_women_charged_for_allegedly_assaulting/",
		  "posted_by": "u/Bonboniru",
		  "upvotes": "1.8k upvotes"
		}
	  ],
	  "errors": [],
	  "resume_variable": "n",
	  "success_score": "100"
	}