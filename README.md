# Amazon_Vine_Analysis
## Overview
I've been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

I have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. Ipicked one of these datasets and used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used Pandas to determine if there is any bias toward favorable reviews from Vine members in your dataset. 

## Results
-How many Vine reviews and non-Vine reviews were there?
Vine reviews = 1266
non-Vine reviews =62028
-How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
Vine reviews that were 5 stars = 432
non-Vine reviews that were 5 stars = 29982
-What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Percentage of Vine reviews that were 5 stars = 34.1%
Percentage of non-Vine reviews that were 5 stars = 48.3%

## Summary

