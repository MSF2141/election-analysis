# Election Audit using Python and VS Code

## **Overview of Project**
Assisting a Colorado Board of Election employee, Tom, in an election audit of the tabulated results for a U.S. congressional precinct in Colorado. The main task is to report the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate, and the winner of the election based on the popular vote. Data processing is usually done in Excel; however, Tom wanted to know whether there is a way to automate the process using Python. 

### Purpose
Specifically, the purpose of this analysis is to create and run a Python script using a VS Code for election data analysis and complete the following tasks: 

1. Calculate the total votes cast.
2. Get a complete list of counties which received votes. 
3. Calculate the voter turnout for each county.
4. Calculate the percentage of votes from each county out of the total count.
5. Determine the county with the highest turnout.
6. Get a complete list of candidates who received votes. 
7. Calculate the total number of votes each candidate received.
8. Calculate the percentage of votes each candidate won.
9. Determine the winner of the election based on popular vote.


## **Analysis**
Softwares: Python 3.7.6.7 and Visual studio Code (VS Code) 1.72.2

Data source can be found here as a *.csv file: [election_results](https://github.com/MSF2141/election-analysis/blob/f3555399e3f34aa2e7c59b239359e56b726efc69/resources/election_results.csv)  and as a *.xlsx file: [election_results](https://github.com/MSF2141/election-analysis/blob/19c04d0dfbc2644c263757acf624e8c4d2005abd/resources/election_results.xlsx).

Complete Python script can be found here: [PyPoll_Challenge](https://github.com/MSF2141/election-analysis/blob/0c4dd0e0e08adde640c2937e66c999f796bbf494/PyPoll_Challenge.py).


## **Results**
Results are printed here as a *.txt file: [election_analysis](https://github.com/MSF2141/election-analysis/blob/3066d208893af15b7448dfd2b48e40b37a8ce9c4/analysis/election_analysis.txt).

![results_analysis](https://github.com/MSF2141/election-analysis/blob/caabce88a2b68e45f244786ecb33190989fd43db/analysis/results_analysis.png)

The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
     - Charles Casper Stockham
     - Diana DeGette
     - Raymon Anthony Doane
-  The candidate results were:
     - Candidate Charles Casper Stockham received 85,213 votes; which is 23.0% of total votes.
     - Candidate Diana DeGette received 272,892 votes; which is 73.8% of total votes.
     - Candidate Raymon Anthony Doane received 11,606 votes; which is 3.1% of total votes. 
- The winner of the election was Diana DeGette who received 272,892 votes; which is 73.8% of total votes.


## **Summary**
Completing tasks using the Python script in a VS Code was very fast and effective. It may be useful to know that current Python script can be modified in order to be used for other elections. For example, the initial part of the script can be modified to introduce any variables that are relevant for other elections.

![example_future_use_1](https://github.com/MSF2141/election-analysis/blob/c07103ab0bdfe0eaea797f1ebc8c70eabb70d085/analysis/example_future_use_1.png)

In addition, throughout the script, one can choose which results should be printed in the terminal and which should be exported to a text file.

![example_future_use_2](https://github.com/MSF2141/election-analysis/blob/d245fe5b30614702ce919079b17bab8a9a6c1111/analysis/example_future_use_2.png)

