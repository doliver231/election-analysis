# Election-Analysis: PyPoll with Python

## Project Overview

Tom, a Colorado Board of Elections employee, has given the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Calculate the voter turnout for each county.
7. Calculate the percentage of votes out of the total votes from each county
8. Determine the county with the highest turnout

### Purpose of Election Audit

In order to analyze this data, we are tasked to create a code to automate the process with the use of Python. By this means we hope to be able to not only audit other congressional districts, but also senatorial districts and local elections as well.

## Resources

- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.72.2

## Election Audit Results

The analysis of the election show that:
- There were "369,711" votes cast in the election.
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
    - Diana  DeGette, who received 73.8% of the vote and 272,892 number of votes.
- The counties were:
    - Jefferson
    - Denver
    - Arapahoe
- The county turnouts:
    - Jefferson County received 10.5% of the vote and 38,855 number of votes
    - Denver County received 82.8% of the vote and 306,055 number of votes
    - Arapahoe County received 6.7% of the vote and 24,801 number of votes
- The county with the highest turnout was:
    - Denver, which had 82.8% of the vote and 306,055 number of votes

## Election Audit Summary

The Python script that was created was successful in gathering the vast amounts of data in the csv file and outputting the necessary information in a concise and simple format. The same code, with a few modifications, can be utilized for other similar elections with larger data sets and more candidate participants. 

For a more detailed analysis in this specific congressional election, one can take into account that there were three primary voting methods taken: mail-in ballots, punch cards, and direct recording electronic counting machines (DRE). If the original data set in the csv file contained voting methods, we would be able to add a section in the code to read through the data, extract the count of votes for each method, and calculate a percentage of each voting method out of the total number of votes casted. It would be an interesting detail to depict which method people prefer or tend to use at elections like this one. Let's say mail-in ballots were the most used methods for a specific county, for example. This would possibly suggest that certain districts are lacking the resources that can possibly attract more voters using the other voting methods.

If it were federal elections, this Python script can be verstaile and utilized in larger regions and states, not only counties. As far as the Colorado congressional election goes, one can modify the script by adding conditional statements in order to obtain percentages of counties that voted for each individual candidate. These small modifications in our code can give us a better overview of the polls and with that knowledge, possibly make necessary changes to the way things are being ran.