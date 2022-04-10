# Election Analysis

## Project Overview
I have been given a project by the Colorado Board of Elections to audit a congressional precinct's recent election. The audit 
includes the following:

1. Calculate the total number of votes cast.
2. Get a complete list of the counties involved
3. Calculate the total amount of votes and the percentage of the total amount of votes from the precinct for each county.
4. Determine which county had the highest amount of votes for the precinct.
5. Calculate the total number of votes each candidate receieved.
6. Calculate the percentage of votes each candidate won from the overall total.
7. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.66.0

## Analysis

The election analysis shows that :
  - 369,711 total votes were cast
  - The counties involved in the election were:
    - Arapahoe County
    - Denver County
    - Jefferson County
  - Election results for each county:
    - Arapahoe County had 6.7% of the vote and 24,801 of the total votes
    - Denver County had 82.8% of the vote and 306,055 of the total votes
    - Jefferson County had 10.5% of the vote and 38,855 of the total votes
  - The county with the highest number of votes cast:
    - Denver County with 82.8% of the vote and 306,055 votes cast
  - Election candidates were:
    - Charles Casper Stockham
    - Diana Degette
    - Raymon Anthony Doane
  - Election results for each candidate:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 of the total votes
    - Diana Degette received 73.8% of the vote and 272,892 of the total votes
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 of the total votes
  - The election winner was:
    - Diana Degette, who received 73.8% of the vote and 272,892 votes
![results](https://github.com/mein0819/Election_Analysis/blob/main/readMeImages/resultsImage.png)

## Summary

The script created for this project could easily be repurposed to be used for any election. The script reads in 
a CSV file with election data. Using a loop and if statements it creates lists and dictionaries to hold the data for each candidate and the location from which the vote came, in this case a county. Using another loop it performs calculations
to determine vote percentages and a conditional statement to determine the outcome, or the winner. With a couple of 
modifications, this code can be used for any election of any local, state or national election. First, changing the 
CSV file from this line of code will give the correct data to be read:

Next, change the the list and dictionary names, and any coresponding variables associated with them, to match where the 
data was collected from, such as a precinct, district, or state. 

Finally, check that the CSV columns have the proper index when searching for the candidate name and location of the vote.
It shouldn't be assumed that every will be organized in the same way
