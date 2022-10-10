# Election_Analysis

### 1.	Overview of Election Audit

For this project we assisted Tom, a Colorado board of elections employee in an election audit of the tabulated results for a U.S. congressional precinct in Colorado. After the votes were counted, we generated a vote count report to certify this U.S. congressional race. 
The objective is to automate the process for getting the report using Python because If this audit is done successfully, the code will be used to audit not only other congressional districts, but also senatorial districts and local elections.
To deliver our report, we made a Python script that delivers the following data:
* Total number of votes cast
* Total number of votes each candidate received
* Percentage of votes for each candidate 
* The winner of the election based on popular vote
* Total votes cast by county
* Percentage of votes for each county
* The largest county turnout

### 2.	Election-audit Results

* **How many votes were cast in this congressional election?**

In this election they were cast a total of 369,711 votes, as we can see in the below image of our file where we output the results we coded in Python:

<img width="442" alt="Election_Results" src="https://user-images.githubusercontent.com/113747210/194956429-bad56768-f3af-4f56-b8ae-c08872e0e3ca.png">

* **Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct**

We extracted three counties from the csv file, Arapahoe, Denver, and Jefferson. We got the total votes cast by county and its percentage as we can see in the following image:

<img width="442" alt="County_Results" src="https://user-images.githubusercontent.com/113747210/194956723-c83d846e-4173-4596-acbb-aaf77aaa6463.png">

* **Which county had the largest number of votes?**

The county with the largest number of votes was Denver, with a total of 306,055 votes cast.

<img width="442" alt="Largest_County_Turnout" src="https://user-images.githubusercontent.com/113747210/194956838-95e30e31-e4e0-4cbe-8599-1439912ea5eb.png">

* **Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.**

We extracted three candidates and count the total votes they received. In the next picture we can see the name of the candidates, the total votes they received and their percentage.

<img width="442" alt="Candidate_results" src="https://user-images.githubusercontent.com/113747210/194956911-f2563660-ba45-4bfc-b87b-b69955655881.png">

* **Which candidate won the election, what was their vote count, and what was their percentage of the total votes?**

The winner candidate was Diana DeGette with a total of 272,892 votes which represents the 73.8%. We can see the output results in the next image:

<img width="442" alt="Winner_candidate" src="https://user-images.githubusercontent.com/113747210/194956996-56018e12-af0d-4dd1-854f-fbb3fe9e958d.png">

### 3.	Election-Audit Summary
















