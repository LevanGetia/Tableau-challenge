# Tableau-challenge

Project Overview
———————————-

This project tries to analyze CitiBike data for New York City, hopefully to provide valuable insights for city officials involved in Bike program, which can be further used in development and improvement of the CitiBike service. Firstly, data from two csv files was combined and cleaned using jupyter notebook. Afterwards, data is laoded to Tableau and using Tableau’s variosu features such as Visualizations, Dashboards, Story, Calculated Felds etc. analysis is drawn. Tableau public workbook link is provided in seperate file 

Instructions 
———————————

Step 1. CloneGitHub Repository to the local machine
Step 2. Run links from seperate file named URL to access reports in Tableau.
Step 3. Complement Tableau report with the Analysis and story notes given in this file


Analysis
———————————


After conducting the comprehensive review and analysis, the data reflects upon several insights that can be useful for public officials, to conduct future improvements for the program.  Selected period is one month in the season of winter, January, and one month in the season of summer, August.  For given timeframe, it was clear that summer month enjoyed higher numbers in terms of bike rentals, both from the side of the members or just casual users. Usage from non-members roughly doubles in the month of August compared to January. It would be sensible to assume from the data, that busiest hours are around 5-6pm. Moreover, ride type usage data suggest that classic bikes, are exactly the ride type which should be looked over in terms of maintennce and repairing, as it the most utilized/driven one. Nevertheless, both electric and classic bike accounted for nearly all of 2,5 million miles driven in just 2 month period, hence it would be reasonable to assume that some electric bikes might need attending to as well.  
To review the infrastructure of CitiBike, we can start by the busiest stations. Manhattan, houses most of the busiest stations with brooklyn’s Kent Avenue and Metropolitan Avenue recording start of rides in excess of 6000. This trend is followed in both periods (summer and winter). However, whilst Manhattan stays busiest throughout the year, there is greater activity along bigger geographical area during summer month. 
Most of the rides taken fall under the lenght of 1.3 miles, but it is interesting to note that during summer there is slight increase miles driven per ride. Moreover, data revealed that during given period, docked bikes were chosen the least, but they were taken for the greatest lenght of period with single ride averaging 57 minutes, whereas both electric and classic bike average 13,2 and 14,3 minutes per ride respectively.

Story Notes

Story Page 1
CitiBike data is modelled to understand the difference in usage in terms of member type or winter and summer seasons. As expected, both member and non-member usage for bike rentals increases sharply in summer. However, number of non member users doubles during the summer month, whereas increase in rides for members sees increase of around 15%. Furthermore, there is an interactive map which marks stations according to their usability (in terms of number of rides taken from that specific station), as well as providign quick representation of what part of the data is electric, classic or docked bike according to its colours. For enhanced usability, map has a filtering opportunity via number of starts from station to see  exactly where on map are most or least used stations in a quick fashion. Map also has functionality to switch between total (year) data or to view entries via month. Peak hours for both summer and winter months are 17:00 and 18:00.  However, there is also significant activity during 8:00AM. 

Story Page 2
First two bar chart visualizations depict top and bottom 10 start  and end stations respectively. Next bar chart represents rideable type utilization variability, or in another words, which rides are used at the same pace and what type is most prone to usage fluctuation. Lastly, sized circles represent average lenght of bike trip and average duration in terms of miles and minutes respectively. Whilst, most of the data falls within 1.3 miles radius for all types, docked  bikes tend to be used for much longer than either electric or classical bikes.. 
 
Story Page 3
It is also interesting to note that classic bikes accounted for 1,6 million miles travelled for given period out of total of 2.5 million . Given that classic bikes have accounted for more than 64% of total mielage incurred, it strenghtens our prediction that classic bikes would require maintenance at the earliest point, compared to other types.
