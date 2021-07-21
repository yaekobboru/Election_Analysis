# Overview of Election Audit

  The purpose of this analysis is to complete the election audit of a recent local congressional election in colorado.
  election results csv file, python 3.7.1, and visual code utilized to apply codes and generate final reports.
  Tom a Colorado board of election employee require to see the output of the following.
    
   1. Reporting total number of votes cast.
   2. Voter count for each county and percentage of votes from each county out of the total count
   3. The county with the highest turnout will be reported.
   4. Total numbers of votes for each candidate and percentage of vote for each candidate. 
   5. Winner of the elections.

## Election-Audits Results:
  
  The analysis of the election show that:
   * There were 369,711 votes cast in the election.
   * The county results were:
     * Jefferson county received 10.5% of the vote and 38,855 number of votes.
     * Denver county received 82.8% of the vote and 306,055 number of votes.
     * Arapahoe county received 6.7% of the vote and 24,801 number of votes.
   * Denver was county with the largest number of votes.  
   * The candidate results were:
     * Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
     * Diana DeGette received 73.8% of the vote and 272,892 number of votes.
     * Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
   * The winner of the election was:
     * Diana DeGette, who received 73.8% of the vote and 272,892 number of votes.
     
![Election_Results](https://user-images.githubusercontent.com/86446609/126049877-e0bb1bdb-f017-4388-92c2-980ffd912ef4.JPG)        

## Election-Audit Summary:

  This script can be used for coming elections to analyze the county with least number of votes.

  First using **"ctrl+F"** and Replace on visual code , Tom can replace the variable name for largest_county with least_county.
  
![Largest_County_Var](https://user-images.githubusercontent.com/86446609/126049932-96325a35-f37c-44da-a9c8-753d02b037a2.JPG)  

  Second on the conditional statement the greater than sign should be replaced with less than. If (votes < least_county_count) and (vote_percentage > least_county_percentage)
  
![Conditional_statement](https://user-images.githubusercontent.com/86446609/126049940-44cfc45b-ee30-47c3-ad58-5113b78c5b2f.JPG)



