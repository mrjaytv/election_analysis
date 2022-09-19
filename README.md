# Election Analysis: Data from small county 

## Background
Tom and Seth hired by US election commissioner officer. They've been tasked to help the commissioner generate a vote count report in efforts to yield efficient and readily accessible election data for the U.S. congressional districts,senatorial districts and other local elections. Tom and Seth decided to leverage Python scripts to automate the election process. 

#### Data Requirements:  
* Voter turnout for each county
* Percentage of votes from each county out of the total count
* Identify the counties with the highest turnout
* Total number of votes cast
* Total number of votes for each candidate
* Percentage of votes for each candidate
* Identify the winner of the election based on the popular vote

## Overview Election Audit Project 

The purpose of this project is to assist Tom and Seth display a few sample data to the comissioner that meets his requirements. With the Python script, the commissioner can easily run the script to help tell a data driven story of the election results. This is achieved by using for loops and conditional statements with membership and logical operators to find the requested results then print the results to the command line. 

## Election-Audit Results 
Once all ballots casted have been submitted, the data showed that a total number of votes cast was 369,711. The county with the largest number of votes was Denver. 

### County Results

#### Total Number of Votes Cast in the Congressional Election 
Below is the terminal's results of each county and the total number and percentage of votes counted.

![This is an image] (election_analysis/Resources/Total_Election_Votes.png)

#### Largest County with Number of Votes Cast
Below displays the terminal's results of all counties votes and percentage as well as identifying the county with the largest number of voters.

![This is an image] (election_analysis/Resources/County_Results.png)

###  Candidate Results
The candidate that received the largest amount of votes was Diana DeGette. Their total vote count was 272,892 which was 73.8 % of the total votes.  Charles Casper Stockham was the candidate runner up who received only 85,213 votes which was 23.0%.

#### Total Number and percentage of Votes Cast for Each Candidate 

![This is an image] (election_analysis/Resources/Candiates_Results.png)

## Election-Audit Summary 
At the end of meeting with the election commissioner, Tom and Seth recommended two script modiciations that can be used for other elections. 

### Modification 1 
One script that can easily be modify is the file path. When selecting assigning the variable for the file to load and the path, the file name can change to align with the file dataset used as shown below. 

![This is an image] (election_analysis/Resources/File_modify.png)

### Modification 2
Another script that can easily be modify is the county variable names. They can be modified to targeted regions such as city or state. By slightly modifying this script will allow the commissioner to expand his results from county level to state or even national level.  

