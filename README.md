Election Audit Analysis (Deliverables 1 and 2)

Overview
The purpose of this election audit was to go through data provided of a local election and write a script that would tally up each vote for each individual candidate and give the results per vote, and percentage of the vote. Furthermore, it was also used to go through the data set provided (election_results.csv) and tell us the votes per county as well as which county had the largest number of votes cast.

Audit Results
After the script ran through the data and tallied all of the votes, the results are as follows.
•	Overall there were 369,711 votes cast in this local election
•	There was a total of three counties in this election, and the individual results came out like this
o	Jefferson County accounted for 10.5% of the total with 38,855 votes cast
o	Denver County accounted for 82.8% of the total with 306,055 votes cast
o	Arapahoe County accounted for 6.7% of the total with 24.801 votes cast
•	With these results it is clear that thee county with the largest number of votes was Denver

•	In this election, there were three candidates on the ballot, the results for each shows this
o	Charles Casper Stockham collected 85,213 votes, equaling 23.0% of the total
o	Diana DeGette collected 272,892 votes, equaling 73.8% of the total
o	Raymon Anthony Doane collected 11,606 votes, equaling 3.1% of the total
•	After the results were compiled, the data shows that the winner of the election was Diana DeGette
o	This candidate received a commanding 272,892 votes across all three counties, which in turn equaled up to 73.8% of the total votes cast.
Summary
This script was able to sort and analyze a very large data set in mere seconds. The implications being that this script could be used in any election with only some minor changes to the code. 
For example: If given a different file to pull data from, you could modify the code to pull different information from different locations to come up with the results with relative ease.
•	In this data set for example, the candidate_name variable pulled its information from the second row, and the county_name came from row 1. In other sets of data there may be more rows of data but the code would still work as long as the names or counties were changed to the corresponding rows.
In another example: If there was more precise information that one wanted to pull from a larger data set, with the already laid out code it would be easy adapt it to show other statistics.
•	As an example, say your data was across multiple states and you wanted to show what state instead of county the votes were cast in.
•	You could take the current code lines for the county and change some variables to be able to formulate that.
•	county_list = []
•	county_votes = {}
Could be changed to state_list, and state_votes respectively. Going through the entire code and changing any word of county to state would allow the script to print the results in that fashion. Taking into account the location of the states in the data and setting the variable to the corresponding row.












Election_Analysis (Vote count only)

Project Synopsis
An employee for the Colorado Board of Elections gave me a project with multiple tasks to complete the election audit of a local congressional election.
1.	Calculate the total number of votes cast in the election.
2.	Get a complete list of candidates who received votes.
3.	Calculate the total number of votes cast for each candidate.
4.	Calculate the percentage of votes each candidate won.
5.	And finally, determine the winner of the election based on the popular vote.

Resources
•	Data Source for the entirety of the project was : election_results.csv
•	Software used: Python 3.7.6, Visual Studio Code, 1.60.2

Summary of results
After compiling all of the results for the election it shows that:
	There was a total of 369,711 votes cast in the entirety of the election.
	The candidates were:
  o	Charles Casper Stockham
  o	Diana DeGette
  o	Raymon Anthony Doane
The candidates’ individual results were as follows:
  o	Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
  o	Dianna Degette received 73.8% of the vote and 272,892 number of votes.
  o	Raymon Anthony Doane received 3.1% of the vote and11,606 number of votes.
With the results compiled, the winner of the election was:
  	Dianna Degette received 73.8% of the vote and 272,892 number of votes.

Challenge Overview
This challenge required me to take data provided and write a working code that sorted through it, and tallied up vote counts for each candidate. The most efficient way of doing that involved creating various lists and dictionaries within VScode to be able to reference them when writing different parts of the subroutine. Using said variables, I was able to make the program sort through the over 360 thousand votes and give me an accurate count and percentage of vote for each candidate in under one second. The hardest part of this challenge was trying to write the correct code to not only pull information from the data provided, but then also count and show the results in a clean and easily understandable format.

Challenge Summary
In summation, this challenge pushed me to think of different ways to pull information from the data to accurately count and come up with percentages of vote for each candidate. Overall, I would say the challenge was fun to work through, even with various parts of it being more difficult than others.










	


