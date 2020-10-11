# Election-Analysis

## Overview of Election Audit

The purpose of this project is to use Python to audit election results. Specifically, the script calculated 1) voter turnout for each county; 2) percentage of votes from each county; and 2) county with the highest turnout

## Election Audit Results

- How many votes were cast in this congressional election?

369,711 total votes were cast

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

County Votes:
Jefferson: 10.5% (38,855)
Denver: 82.8% (306,055)
Arapahoe: 6.7% (24,801)

- Which county had the largest number of votes?

Denver had the largest number of votes with 306,055.

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

Winner: Diana DeGette
Winning Vote Count: 272,892
Winning Percentage: 73.8%

## Election Audit Summary

This script can be used to analyze the results of any election data so long as they are in a csv file formatted in the same way. Going forward, the script can be modified to identify where certain data lives inside of a file to be read (as opposed to assuming that county is in column 2, for example). This could provide more flexibility in analyzing more complex election data. Furthermore, perhaps the script to be expanded to handle demographic data of voters.
