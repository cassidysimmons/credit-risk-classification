
## Overview of the Analysis

For this assignment we were tasked with analysing some lending data; the csv we were provided included several columns containing borrower candidate information such as loan size, income, interest rate, etc. The feature we were most interested in was 'loan status' which contains two variables: 0, which indicates a 'healthy loan' and 1, which indicates a 'high-risk loan'. The main goal of this assignment was to create a logistic regression algorithm to predict which candidates are classified as 'healthy' and which are classified as 'high-risk'.

## Results

* accuracy score: 99%

* precision:
    * healthy: 100%
    * high-risk: 87%

* recall:
    * healthy: 100%
    * high-risk: 89%

## Summary

Based on my findings, I would recommend this model as a first sweep of potential candidates. Obviously, I would not recommend any algorithm as the end-all-be-all decision maker, but with such high scores across the board, you are bound to get pretty accurate results. The accuracy score alone, at a 99%, shows that the algorithm is making correct predictions the vast majority of the time. This fact is reenforced when we look at the precision and recall scores, which are both very high as well. The only issue I can see is that the algorithm seems to struggle a bit when it comes to 'high-risk' (1) candidates, the precision and recall scores average 88%, which is not bad by any means, but definitely lower than other aspects.

