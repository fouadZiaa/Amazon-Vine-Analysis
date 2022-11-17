# Amazon Vine Analysis

## Overview 
This project utilized Amazons RDS and data was uploaded into PostgreSQL to run queries either in SQL or in Jupyter Notebook. The task at hand is to determine if there is a bias with Amazon reviews on Sports Items for the Vine Program. The Vine Program for Amazon is an invitation-only based program in which Amazon wants to get the most trusted reviewers on Amazon to post their opinions about new and pre-release items to help their fellow customers make informed purchase decisions. 

## Results
!

### How many Vine reviews and non-Vine reviews were there?
- Vine: 334  
- Not-Vine: 61614

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Vine: 139
- Not-Vine: 32665

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- Vine: 41.62%
- Not-Vine: 53.02%

## Summary 
In conclusion, for the Sports Items in the Vine Program the test is inconclusive since our number of total reviews for Vine is significantly lower than Not-Vine Reviews.  From the surface one could say that there is negative bias since it is about 12 percentage points lower than non-Vine revewis. We would need to have equal or signtly less Vine reviews to gather a more insightful answer to this problem. We could use ANOVA testing but this would still need a larger sample to use statistical test. Another way is that we could randomly select reviews on both groups then determine their percentages and see if there is a positive bias in the Vine Program reviews.
