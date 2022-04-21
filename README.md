
# Election_Analysis
Use VBA to refactor code and measure performance

![Voted](https://user-images.githubusercontent.com/30667001/164519318-68ee9fac-b835-4e91-b590-e3856a048d0f.png)

### Resources
  - Data Source: election_results.csv
  - Software: Python 3.7.6, Visual Studio Code 1.63

### Project Overview
A Colorado Board of Elections employee requested an election audit of a recent local congressional election.
Initial tasks included:

1. Calculating the total number of votes cast.
2. Compiling a complete list of candidates who received votes.
3. Calculating the total number of votes each candidate received.
4. Calculating the percentage of votes each candidate won.
5. Determining the winner of the election based on popular vote.
 
### Election Commission Follow-Up Request (Challenge)
 The Commission requested three additional pieces of information following analysis submission:
 
 1. The voter turnout for each county.
 2. The percentage of votes from each county out of the total count.
 3. The county with the highest turnout.
 
 Additional Commission questions were addressed by modifying existing code.
 
![Alt text](https://user-images.githubusercontent.com/30667001/148059079-fd8a686e-912e-419b-b2ff-55189dac7c38.png)

### Election Analysis Summary
- There were 369,711 votes cast in the election.
- Of the three counties, the greatest number of votes was cast in Denver County (306,055 or 82.8% of the vote).
  - Votes cast in Arapahoe (24,801 at 6.7%) and Jefferson (38,855 at 10.5%) counties were much fewer than that of Denver County.
- Of the three candidates running:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.
  
### This Code: Future Use
This script can be applied to future elections in different ways. For example:

 1. Existing county-specific code can be modified for state-specific use by creating a list of states and a dictionary of votes for those states, tracking where votes were greatest. Any related coding would also have to be updated. Advanced python coding (eg: numpy, pandas) can be used to look at regional differences.

![Alt text](https://user-images.githubusercontent.com/30667001/148101578-d14bba25-9295-4d96-8408-c8d11653573e.png)

 2. Sometimes election results aren't immediately obvious. According to Ballotpedia(https://ballotpedia.org/Too_close_to_call), an election is too close to call when the vote totals are within 5%.

  Existing winner-specific code can be modified to:
  - Include mathematical calculations to check for counts and percentages within 5%.
  - Pair if-else statements and MsgBox coding (eg: "This election is too close to call.") to alert auditors to potential issues.

![Alt text](https://user-images.githubusercontent.com/30667001/148104066-42d0dcc7-5d97-4548-8888-5b7cdf86e2be.png)
  
