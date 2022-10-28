# Python Election Analysis

##Overview of Election Audit

- The purpose of this election analysis audit is well defined. 

    With this election analysis i did in python the purpose is to show the actual 
numbers behind the election and show if there is any reasonable doubt in the 
results of the winner of the election. In the results file we were given to audit 
there was too much data in there to perform any of these calculations by hand or 
using mental math so we had to use python to automate the process for us.

##Election Audit Results

- There is a bulleted list where each election outcome is addressed. 

- First is the total votes output we can clerly see that there are 369,711 total votes cast in 
the election. this number is important because this is a number used in out percentage statistics.

- The next section we have is our votes based on county. This section shows us how people voted 
based on where they live. Our analysis shows us that of the 369,711 total voters 10.5% (or 38,855
votes) are from Jefferson county, 82.8% (or 306,055 votes)are from Denver county, and 6.7% (or 
24,801 votes ) are from Arapahoe county.  

- The next section is the county with the largest turnout of voters. This section obviously has 
Denver as the output because denver had 306,055 voters to turn out to the polls.

- The next section gives us the data for votes based on candidate. Our analysis has shown that
Charles Casper Stockham got 23.0% (or 85,213 votes) of the total votes, Diana DeGette got 
73.8%(or 272.892 votes) of the total votes, and Raymon Anthony Doane got 3.1% (or 11,606 votes)
of the total votes.

- Finally we have the winners statistics this shows us that our winner is Diana DeGette with a 
total vote count of 272,892 votes and 73.8% of the total votes. This section is meant to tell us 
who won the popular vote.

##Election Audit Summary

- There is a statement to the election commission that explores how this script 
can be used for any election, with two examples for modifying the script.

    This script is increadibly useful for any election. The primary reason this is so 
useful is because it can be as complex or as simple as you want it to be. The way it is built 
supports many candidates and counties on account of the dictionaries and lists python 
allows you to take advantage of.
    There are many ways this can be improved like for example we can have data by identified race 
and/or gender and/or age. This would give us a ton of useful data that can be used to gather how 
the indvidual candidates performed in the polls for all different demographics from teens to 
geriatrics, males and females, and so on for as many different demographics you can add to the 
analysis.
    Another way this script could be improved is by showing where the candidates polled the best.
In order to see where the candidate if elected should spend more of their time focusing on. The 
current way the code is made we dont have a way to tell our winner who voted for her the most.
if we could gather the informaion in the columns for what county voted for which candidate the 
most this can help the candidate see who voted them in at a higher percentage.
