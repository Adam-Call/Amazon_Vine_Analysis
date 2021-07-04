<!-- Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists and images of DataFrames as support, address the following 

Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement. -->

# Amazon_Vine_Analysis

## Overview of Analysis

In this analysis we will be looking to find if there is any bias within the vine review program. By comparing the 5 star reviews for the product dataset We will be using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin, and then using pandas to analyize the data.  

## Results

-![helpful reviews]('\Resources\helpful_reviews.png')
-How many Vine reviews and non-Vine reviews were there?
-![vine reviews]('\Resources\vine_reviews')
-![non vine reviews]('\Resources\non_vine_reviews')
-How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
-![5 star reviews]('\Resources\5_star_reviews')
-What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
-![percent vine reviews]('\Resources\percent_vine_reviews)

## Summary

Based on the results above there does not does not seem to be a strong positive bias in the vine reviews. However by looking a little deeper and pulling the 4 star reviews as well.
    -![total vines]('\Resources\total_vine)
    -![4 star]('\Resources\4_star_reviews)

There are 80% of the vine reviews that are 4 and 5 stars. This would seem to skew pretty heavily that vine reviews are mostly positive. 