# Election Audit
## Overview of Election Audit
### Purpose
The Election Commission has requested an audit on the recent election.  They have requested to include the voter turnout for each county, percentage of votes from each county and the county with the highest turnout. A breakdown by candidate was also requested to include votes per candidate and the percentage of the total votes.

The polling data was provided in a csv file to be reviewed and through this analysis we will be able to show the new results to satisfy the Election Commission.

## Election Audit Results

-  There were 360,711 total votes casted in the election.

-  The image below shows the breakdown and percentage of votes by county.

<img src="https://github.com/andralobo/Module3-Challenge/blob/main/Resources/election_county.png?raw=true">

-  Denver county had the highest turnout out of the three counties at 82%, Jefferson had the 2nd highest turn out at 38,855 and Arapahoe was in third with 24,801.

-  The image below shows the breakdown and percentage of votes by candidate.

<img src="https://github.com/andralobo/Module3-Challenge/blob/main/Resources/election_candidate.png?raw=true">

-  After reviewing Diana DeGette had the highest number of votes at 73.8% of the total votes. Charles Casper Stockham came in second at 23% and Raymond Anthony Doane’s was third with only 3.1% of the votes.


## Election Audit Summary
The script used for this analysis can be used for future election audits and would only need minor modifications.  It currently can run through any number of candidates and counties an a csv file.  The code can easily be updated use another file name by updating the path and file name shown below.

<img src="https://github.com/andralobo/Module3-Challenge/blob/main/Resources/changing_filenames.png?raw=true">

The current script pulls in the csv file and uses column 2 which is the county and column 3 from the csv but can be modified if the columns do not match.  See below where the value in the square brackets can be easily updated to pull from different columns from the csv file.

<img src="https://github.com/andralobo/Module3-Challenge/blob/main/Resources/changing_columns.png?raw=true">


