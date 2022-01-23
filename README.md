# Analysis of the Amazon Vine Program
## Overview
Our team was tasked with analyzing reviews that are initiated by Amazon and carried out by their Amazon Vine members. This service requires a fee and SellBy wants to determine if there is value in this service. We were given 50 datasets of Amazon reviews to choose from and we selected Automotive. However, this code can be repurposed to run any or all of these data sets with minimal refactoring of code and creation of databases.

## Analysis
![vine analysis](vine_analysis.png)

We found the following when analyzing Amazon's Automotive reviews that had 20 or more votes:
  - There were a total of 82 Vine reviews and 24,742 non-Vine reviews
  - There were only 33 five-star Vine program reviews that met the criteria as opposed to 12,807 that were generated outside of the Vine program
  - Five-star reviews accounted for 40% of the Vine reviews where as the non-Vine reviews had 52% at the five-star rating

## Summary
We have concluded that our data shows the Vine program does not have a significant impact on reviews. They make up a small portion of the overall reviews and their rate of five-star reviews is more than 20% less. We see no positive bias for the Vine program. We do advise capturing a wider view by analyzing other datasetand creating an aggregate to generate a broader picture. We also suggest comparing the ammoun of votes per standard review and per vine review to see if Amazon customers find value from these reviews at any higher rate. In conclusion, we feel like more analysis needs to be conducted before making a decision to participate in the Vine program.
 