#Election Analysis

##Overview
The purpose of this analysis is to get the overall vote counts, counts within each county, along with the winners and counties with the largest turnout. We used the csv data package in order to read the proper documents and in order to export our report into a txt file. 

##Audit Results
The audit results were successfully extracted by reading the csv, creating a few dictionaries and lists for the counties and candidates. We then integrated nested for loops that runs through the provided csv, gathering the data and counting the votes. 

https://github.com/ecregger/ChallengeElection/blob/main/Election_ForLoop1.png
https://github.com/ecregger/ChallengeElection/blob/main/Election_ForLoop2.png

##1: Total votes: 
369,711

##2: County Votes:
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)

##3: Largest Turnout: 
Denver

##4: Candidate Vote Breakdown: 
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

##5: Winning Results:
Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%

##Summary
This script can be used as a base model for any elections where county-level data is needed. As long as the for loop and count remains in place you can adjust the variables to read state, county, and country level election files to quickly perform the analysis that can determine an election winner. 
