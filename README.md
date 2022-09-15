# Amazon Vine Analysis

## Overview 
The purpose of this project was to determine if there is a bias of favorable reviews with the Amazon Vine program or members through analysis. This analysis uses PySpark to perform the ETL(extract, transform, and load) process, connects it to a Relational Database, for this project we used AWS, and loaded the transformed data into PGAdmin to apply SQL methodologies to the data. This particular project focuesed on video game reviews.

## Results

### Total Number of Reviews

![total paid](https://github.com/tsmtruong/amazon_vine_analysis/blob/main/Resources/total_paid_reviews.jpg)


![total unpaid](https://github.com/tsmtruong/amazon_vine_analysis/blob/main/Resources/total_unpaid.jpg)



### Total Number of 5-Star Reviews

![5-star paid](https://github.com/tsmtruong/amazon_vine_analysis/blob/main/Resources/paid_5_star.jpg)


![5-star unpaid](https://github.com/tsmtruong/amazon_vine_analysis/blob/main/Resources/Screen%20Shot%202022-09-14%20at%207.03.53%20PM.jpg)



### Percentage of 5-Star Reviews


![paid percent](https://github.com/tsmtruong/amazon_vine_analysis/blob/main/Resources/paid_5-star_percent.jpg)


![unpaid percent](https://github.com/tsmtruong/amazon_vine_analysis/blob/main/Resources/unpaid_5-star_percent.jpg)


## Summary

51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program. While this does show bias there is a disproportionate number of reviews that were unpaid versus paid. There were 94 paid reviews within this dataset vs. 40,471 unpaid reviews. I would recommend that we could filter the results down to the same amount of reviews on both sides and rerun the analysis to truely see if there is any correlation to biases when the number of data is the same. Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.