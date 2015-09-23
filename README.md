## soda-backend

The goal : Create a quick and dirty json data file for all data needed to run the opencalifornia application.

Information to import:


"agency_id"									
	"agency_name""agency_name",					
	"election""date",								
	"ballot_id"1,									
	"ballot_short_name""short name for ballot",	
	"ballot_long_name""full official title",		
	"ballot_supporters" 
		
			"committee_name""Committee Name",		
			"total_contributions"100.0, 			
			"by_committee_type"
				"candidate_committee"100.0, 		
				"independent_expenditures"100.0	
			,
			"by_donor_type"
				"individual"				
				"recipient_committee"		
				"other"100.0,						
				"political_party"			
				"small_contributor_committee"
			,
			"by_geography"
				"local"						
				"in_metro"					
				"out_metro"					
			
		

	],
	"ballot_opponents"
				
			"committee_name""Committee Name",		
			"total_contributions"100.0, 			
			"by_committee_type"
				"candidate_committee"100.0, 		
				"independent_expenditures"100.0	
			,
			"by_donor_type"
				"individual"100.0,				
				"recipient_committee"100.0,		
				"other"100.0,						
				"political_party"100.0,			
				"small_contributor_committee"100.0	
			,
			"by_geography"
				"local"100.0,						
				"in_metro"100.0,					
				"out_metro":


Using soda to get data as json

Based on work from Asha John used for [transparent voting](transparentvoting.com).

SF's Socrata Data

[Campaign Finance](https://data.sfgov.org/City-Management-and-Ethics/Campaign-Finance-Data-Key/wygs-cc76)

[More Campaign Finance](https://data.sfgov.org/data?search=campaign+finance)

Oakland's Socrata Data

[Campaign Finance](https://data.oaklandnet.com/browse?limitTo=datasets&q=campaign+finance&sortBy=relevance&utf8=%E2%9C%93&page=1)

