# Election-Analysis

## Overview of Election Audit: 
The purpose of the audit was to see if we could leverage Python to create a tool to automate the calculation of election results.

## Election Audit Results:

![election analysis](https://user-images.githubusercontent.com/68127033/89742605-4e66c280-da69-11ea-9b01-98b7e9827c4d.PNG)

1. There were a total of 369,711 votes cast in this election.
	
2. The breakdown by county is as follows:
	- Jefferson: 10.5% (38,855)
	- Denver: 82.8% (306,055)
	- Arapahoe: 6.7% (24,801)
		
3. Denver County had the most votes in the precinct. 
	
4. The breakdown of votes by candidate is as follows:
	
	- Charles Casper Stockham: 23.0% (85,213)
	- Diana DeGette: 73.8% (272,892)
	- Raymon Anthony Doane: 3.1% (11,606)
		
5. Diana DeGette won the election with 272,892 votes.  She received 73.8% of all the votes cast in the precinct.

## Election Audit Summary:
Although the analysis was only performed on 3 counties, the iterations in the script make the code (as written)
flexible enough to allow for calculations on any number of counties and/or candidates.  Also, designing this tool 
in Python would also allow us to account for extra dimensions in our data of data (i.e.,precinct, zip code) by
simply adding more loops to calculate the extra variables, so the tool can be scaled up to calculate results
on a statewide basis with minimal effort.
