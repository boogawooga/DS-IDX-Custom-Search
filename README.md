# DS-IDX-Custom-Search-Widget

An effort is to create a custom widget with the DS IDX API that will allow custom filtering outside of the global filter settings 

This might be an extension of the DS IDX product 

The DS IDX Plugin provides a "Search Widget" but it doesn't allow specific filtering outside of the global site-wide 
filtering. 

Why: Site is at Twilliamsrealty.com - the header form "Search Orcas Island" is a text widget with form code that returns 
property listings from ORCAS ISLAND only. I had to do it this way instead of using the Plugin's available Search Widget due to problems with global filtering - basically, the Search Widget that is provided by this plugin does NOT allow us to create a specific results filter such as city/town, listing status, etc. but this is what the client wants on their home page. 

As a workaround, I used a text widget with form code and hard-coded it to only return listings from Orcas Island - however, it doesn't NOT send mobile users to the Diverse Solutions mobile results, and the results include "SOLD" listings. 

For this specific project / client We need this property search widget to show / filter: 
1. Properties in Orcas Island ONLY 
2. Will NOT return "sold" properties 
3. Will redirect to mobile results if user is using a mobile device 

For future projects or to be used as an extension for this plugin, outside this first client-needed project, additionally:
4. Will have the ability to create / change custom filters when inserting the Search Widget - outside of the global filtering that is part of the plugin settings - city/town, listing status, specific zip codes, etc. 

