# Election_Analysis

## Overview of Election Audit
The purpose of this project was to build on the previous code that was used initially to pull voting results from a csv file and to analyze it using to python to get particular information.  Originally we calculated the number of total votes, the candidates in the election, the percentage of votes for the candidates, and who won the election.  For this project there was additional information that was requested to be added on the original analysis of the data.  The information requested was:
- The voter turnout for each county
- The percentage of votes for each county based on the total number of votes
- The county with the highest turnout

## Election Audit Results
The analysis of the data given on the election provided the following information:
- How many votes were cast in this congressional election?
  369,711
- A breakdown of the number of votes per county and the percentages
    - Jefferson: 38,855 votes (10.5%)
    - Denver: 306,055 votes (82.8%)
    - Arapahoe: 24,801 votes (6.7%)
- The county with the largest number of votes was Denver
- A breakdown of the number of votes per candidate and the percentages
    - Charles Casper Stockham: 85,213 votes (23%)
    - Diana DeGette: 272,892 votes (73.8%)
    - Raymon Anthony Doane:  11,606 (3.1%)
- Winnner of the election, their vote count and percentage
    - Diana DeGette: 272,892 votes (73.8%)

## Election Audit Summary
After completing the analysis of the data that has been provided, it is necessary to point out that the code that was used to can be used in any election to provide the same results and more.  The code that was used in this analysis could be used to analyze even more complex and detailed information if it is available in the sample data.  For example, if this were an even larger analysis where information needed to be given by state or groups of states (south, north, midwest, etc.) the code in the "for loop" that actually pulled the data from particular columns could be modified to add in variable for state name.  Then it would require running an additional "if statement" to categorize the states by which ever region you wanted to group them by. After this is done for whatever demographic you want, the analysis of the vote totals and percentages would remain the same with updated variables based on the section you are looking for. 
