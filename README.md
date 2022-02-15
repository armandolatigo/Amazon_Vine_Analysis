### Overview of Analysis

Analysis of Amazon Videogame dataset to determine to analyze the performance of unpaid and paid reviews via the Vine program using PySpark, AWS, and Postgres.  Results yield was pulled from Video Game reviews with

Analysis of U.S. Amazon luggage review dataset, which among others includes star rating, number of helpful votes, total votes, and whether or not the review was part of the paid Vine program. Initially filtering for reviews that have received at least 20 votes and helpful votes exceeded 50%.

## Results

Nonpaid Vine reviews far exceed the amount of reviews procured by the Vine program.

![Screen Shot 2022-02-14 at 7 29 10 PM](https://user-images.githubusercontent.com/92451164/153976767-0fca3252-c5d4-4b27-89dd-ddfea0499724.png)


-There were 102 total Vine votes against 64,000 non Vine votes.  
-Only 48 of the Vine votes were five star reviews and 20,282 were non Vine votes.
-However, the percentage of five star review sfor Vine is 47% and the non Vine reviews five star percentage is 32%

### Summary

Vine reviews appears to have a neutral bias. Out of 102 Vine reviews, 48 were five star reviews. Just about half.  When comparing to the non Vine review dataset however, it's rather small dataset compared the 64,000 non Vine reviews. 

Further analysis to determine if the Vine reviews are statistically significant is recommended as well as using different criteria to make a more accurate analysis  
