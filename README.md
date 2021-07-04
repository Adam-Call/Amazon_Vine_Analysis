# Amazon_Vine_Analysis

## Overview of Analysis

In this analysis we will be looking to find if there is any bias within the vine review program. By comparing the 5 star reviews for the product dataset We will be using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin, and then using pandas to analyize the data.  

## Results

    -![helpful_reviews](https://user-images.githubusercontent.com/80363261/124392167-cd846b00-dcb9-11eb-92a3-d2201a67c5c1.png)

-How many Vine reviews and non-Vine reviews were there?

    -![vine_reviews](https://user-images.githubusercontent.com/80363261/124392119-9615be80-dcb9-11eb-996d-6e1e1d52220b.png)
    -![non_vine_reviews](https://user-images.githubusercontent.com/80363261/124392124-9ca43600-dcb9-11eb-94fc-2ed4d9bce884.png)
-How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

    -![5_star_reviews](https://user-images.githubusercontent.com/80363261/124392128-a463da80-dcb9-11eb-98b4-f27cea333249.png)
-What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

    -![percent_vine_reviews](https://user-images.githubusercontent.com/80363261/124392134-ab8ae880-dcb9-11eb-9b5e-9e972bd999c1.png)
## Summary

Based on the results above there does not does not seem to be a strong positive bias in the vine reviews. However by looking a little deeper and pulling the 4 star reviews as well.

    -![total_vine](https://user-images.githubusercontent.com/80363261/124392140-afb70600-dcb9-11eb-835b-63ed93aeb74f.png)
    -![4_star_reviews](https://user-images.githubusercontent.com/80363261/124392148-b3e32380-dcb9-11eb-993f-73b68e029d8e.png)

There are 80% of the vine reviews that are 4 and 5 stars. This would seem to skew pretty heavily that vine reviews are mostly positive. 
