# Election_Analysis


## Project Overview
A Colorado Board of Elections employee requested your help in completing an election audit of a recent local congressional election. The following tasks are to be included in the completed election audit.

1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who received votes. 
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based on popular vote. 
## Resources
* Data Source: election_results.csv

* Software: Python 3.8.3, Visual Studio Code 1.46.0

## Summary
The analysis of the election show that:

* There were 369,711 votes cast in the election.

* The candidates were:

    * Charles Casper Stockham
    * Diana DeGette
    * Raymon Anthony Doane

* The candidate results were:

  * Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.

  * Diana DeGette received 73.8% of the vote and 272,892 number of votes.

  * Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.

* The winner of the election was:

  * Diana DeGette, who received 272,892 number of votes, 73.8% of the total votes cast in the election.

## Challenge Overview
Seth, a Colorado Board of Elections employee, requested your help in completing an election audit of a recent local congressional election.

You provided Seth and his team with the findings of the following tasks in your first draft of the election audit:

1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who received votes. 
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based on popular vote.
Although these outcomes are important, there are a few more key insights his team would like to review. The election commission of Seth's team asked if he could confirm the voter turnout for each county that voted in this congressional district.

The findings of the following tasks were added to the final election audit:

1. Calculate the voter turnout for each county.
2. Calculate the percentage of votes each county contributed to the election.
3. Determine which county had the largest turnout.

## Challenge Summary
### Election Results
Total Votes: 369,711

 County Results:

Jefferson: 10.5% (38,855)

Denver: 82.8% (306,055)

Arapahoe: 6.7% (24,801)

Largest County Turnout: Denver

Candidate Results:

Charles Casper Stockham: 23.0% (85,213)

Diana DeGette: 73.8% (272,892)

Raymon Anthony Doane: 3.1% (11,606)

Election Winner:

Diana DeGette

Vote Count: 272,892

Percentage: 73.8%

In this election, the winner had a supermajority, but the criteria was for a popular vote, greater than or equal to 50.1%. This script could be easily modified to run a check for a supermajority, greater than or equal to 66.7% of the votes as the election criteria. A second way to change the code, with the county data, weights could be assigned to the counties to represent the weights of the electoral college votes. With these 2 changes to the script, perhaps the election commission would consider a business proposal to make these two adjustments, and the script could calculate almost any election.

# Terminal Printout of Results 
<img width="333" alt="Terminal_Deliverable1" src="https://user-images.githubusercontent.com/107444390/187120736-ad0c0189-5d37-4647-ae6f-45970194de00.png">

# Textfile Printout of Results
<img width="356" alt="Text_Devliverable2" src="https://user-images.githubusercontent.com/107444390/187120850-caeaaf0f-db03-4cc7-a6e7-7621a4715a8a.png">
