# Congressional Election Analysis
## Overview
### Purpose
To have the program grab the data from the Election Results excel file and extract the following information from the file.
* Voter turnout for each county
* Percentage of votes and the total count for the counties
* Which county had the highest turnout
## Analysis
### Election-Audit Results
* The congressional election had 369,711 votes in total
![Total_votes](https://user-images.githubusercontent.com/108701073/180079342-42ef26f8-e065-47d4-98f9-16972ddccb4c.png)

* Jefferson county – 38,855 votes 10.5%, Denver – 306,055 votes 82.8%, Arapahoe 24,801 votes 6.7%
![County_breakdown](https://user-images.githubusercontent.com/108701073/180078749-a1d0d83f-4d2d-43b6-b5fa-f168e3fce901.png)

* Denver had the largest
![Largest_turnout](https://user-images.githubusercontent.com/108701073/180080261-5ba1565b-897c-43d8-b050-4477c983d2a7.png)
 turnout

* Charles Stockham 85,213 votes 23%, Diana DeGette 272,892 votes 73.8%, Raymon Doane 11,606 3.1%
 ![Candidate_results](https://user-images.githubusercontent.com/108701073/180078560-061dad94-a4b7-4939-88df-051b2b8b87c5.png)

* The Winner was Diana Degette with 272,892 votes and had a winning percentage of 73.8%
 ![Winning_candidate](https://user-images.githubusercontent.com/108701073/180078657-a56f4011-0296-4e24-9bb9-0183ec10d455.png)


## Summary
### Election-Audit Summary
Overall, the program was able to provide the required results for the congressional election, as we were given the total votes, votes in each county, the results for the candidates, and which county had the highest turnout.

For the program to be used for later years the following lines of code would need to be adjusted. The first line would be file_to_load = os.path.join("Resources", "election_results.csv") you would need to change the file name that it searches for or you could try to add code that would get the user input on which file it examine. Another line that can change is file_to_save = os.path.join("analysis", "election_analysis.txt") here we could have it save the results for each year as an individual file ie election_analysis_2017, election_analysis_2018, etc.

