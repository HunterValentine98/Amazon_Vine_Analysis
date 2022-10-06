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
### Positivity Bias
The main goal of this project was to determine that if the people who were part of the Vine program would wrtie better reviews about the product. Weirdly enough, the percentage of 5 star reviews from the Vine group was 34.1 percent while the non-Vine group had a percentage of 48.3% 5 star reviews. This could be because Vine clients were annoyed about the requirement of being forced to write a review. I do not believe that any positivity bias exists within the reviews.

### Additional Analysis
Similar to positivity bias, I would do an additional analysis about negativity bias. I would compare the percentage of 1 star reviews. As stated in the above section, Vine clients could be annoyed and feel "forced" to write reviews for products when they don't want to. This agitation could lead to them putting more 1 star reviews than we would predict.

