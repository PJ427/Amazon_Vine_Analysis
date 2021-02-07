# Amazon_Vine_Analysis

## Overview of the analysis:
        
    We are to analyze an Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service
    that allows manufacturers and publishers to receive reviews for their products.  After selecting our dataset we are to
    perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed
    data into pgAdmin. Next, you’ll use PySpark, to determine if there is any bias toward favorable reviews from Vine members in
    your dataset.
    
    The dataset I chose: amazon_reviews_us_Books_v1_02.tsv.gz

## Results:

    o How many Vine reviews and non-Vine reviews were there?

        - Our analysis shows there were zero Vine Reviews and 403,807 non-vine reviews

    o How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    
        - There were zero 5 star Vine reviews and 242,889 non-vine reviews
    
    o What percentage of Vine reviews were 5 stars?
    
        - There were zero paid 5 star vine reviews
    
    o What percentage of non-Vine reviews were 5 stars?
    
        - 60% of the non-Vine reviews were 5 stars

![](https://github.com/PJ427/Amazon_Vine_Analysis/blob/main/Resources/step_5.PNG)
    
## Summary: 

    The dataset I selected had absolutely zero Vine reviews. Due to this I do not see a bias in the number of Vine reviews. 
    Non-vine 5 star reviews had a positive 60% which demonstrates an unbias.
