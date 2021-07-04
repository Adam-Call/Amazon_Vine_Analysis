# Amazon_Vine_Analysis

## Overview of Analysis

In this analysis we will be looking to find if there is any bias within the vine review program. By comparing the 5 star reviews for the product dataset We will be using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin, and then using pandas to analyize the data.  

## Results

    -!![helpful_reviews](https://github.com/Adam-Call/Amazon_Vine_Analysis/blob/main/Resources/helpful_reviews.png)

-How many Vine reviews and non-Vine reviews were there?

    -![vine_reviews](https://user-images.githubusercontent.com/80363261/124392284-408de180-dcba-11eb-9db0-0f74435ddc85.png)
    -!![non_vine_reviews](https://user-images.githubusercontent.com/80363261/124392286-44b9ff00-dcba-11eb-8cf9-44a28f3b0fd9.png)
-How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

    -![5_star_reviews](https://user-images.githubusercontent.com/80363261/124392289-48e61c80-dcba-11eb-8fcd-11c3d7b08c78.png)
-What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

    -![percent_vine_reviews](https://user-images.githubusercontent.com/80363261/124392296-500d2a80-dcba-11eb-87f7-233fe3724bb3.png)
## Summary

Based on the results above there does not does not seem to be a strong positive bias in the vine reviews. However by looking a little deeper and pulling the 4 star reviews as well.

    -![total_vine](https://user-images.githubusercontent.com/80363261/124392304-569ba200-dcba-11eb-888f-5977e3e54cb5.png)
    -![4_star_reviews](https://user-images.githubusercontent.com/80363261/124392309-5ac7bf80-dcba-11eb-997f-cdff049866d0.png)

There are 80% of the vine reviews that are 4 and 5 stars. This would seem to skew pretty heavily that vine reviews are mostly positive. 
