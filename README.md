# Election_Analysis

## Project Overview

A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3.Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.


## Resources
- [Data source](Resources/election_results.csv) 
- Software : Python 3.9 ; Visual Studio Code :1.49.3 


## Summary
### The Analysis of the election show that:
- There were 369, 711 votes in the election.
- The candidates and results were:
  - Charles C. Stock received 23% and 85,213 of votes.
  - Diana DeGette received 73.8% and 272,892 of votes.
  - Raymon A. Doane received 3.1% and 11,606 of votes.

- Which county had the largest number of votes?
  - Denver who received 82.8% of the vote and 306,055 votes.
  
- The winner of the election:
  - Dian DeGette who received 73.8% of the vote and 272,892 of votes.
  
## Challenge Overview  

This python script is useful for reading a CSV file containing "Ballot IDS" and "Candidate" names. Within the script there are quotes to follow and explain the script.  

In the challenge we wanted to find votes by counties' names. With a data set that has States' names we can modify this script easily by initializing the same way we did the counties. As seen in the code snippet below where we have counties we can modify it to shows states instead. By adding states columns we can see the counties in each state with larger voting communities.

![image_name](Resources/Code.png)

This script can also be used to target lower voting counties and educate those counties the importance of voting. 

Another modification we can do is adding a voting party column. Then the script can be used for political parties to try to swing counties to their political party.

There are many modifications one can do to election results. 

