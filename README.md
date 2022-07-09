# Amazon_Vine_Analysis

# OVerview
The purpose of this analysis is to determine if there is a bias towards Amazon Vine members to write a positive review.

# Results

The Video_Games_v1 dataset was chosen from the [Amazon Review Datasets](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt).



![image](https://github.com/courtneysims/Amazon_Vine_Analysis/blob/bd44867aeb3f090cfd1dcc51f34a44ef61a34613/Resources/reviews_distribution_vine_non_vine.PNG)

* Distribution of reviews that were Vine (paid member) and non-Vine.

    * Vine (paid members): 94 reviews

    * non-vine: 40,471 reviews

*  Distribution of reviews that were 5-star.

    * Vine (paid member) reviews that were 5-stars: 48 reviews

    * Non-Vine  reviews that were 5-stars: 15,663 reviews


* Percentage of Vine (paid members) that are 5-star: 51.06% reviews

* Percentage of non-Vine that are 5-star: 38.70% reviews




# Summary

The analysis shows that within this dataset there is a possibility of bias in reviews with Amazon Vine member. Of the reviews posted by Vine members, 51.06% were 5-stars. However, out of the 40,565 reviews only 94 reviews are posted by Amazon Vine members. Therefore, further analysis of different datasets focusing on different categories and products is recommended to determine if positivity bias overall is present towards Amazon Vine members. If a similar trend of Amazon Vine member's review is predominately positive then a stronger level of bias may be present for the program.

* # Recommended further analysis:
The premise of this analysis is to evaluate if a bias of vine members to post positive reviews is present. A 4-star review is also considered positive. To capture a better understanding of how vine members tend to review products within this dataset, it is recommended to include 4-star reviews of vine and non-vine members. If the percentage of 4-star reviews is also high for Vine members, then that would provide a stronger argument that there is a positivity bias for Vine members to post positive reviews.

The dataset is also limited to one type of product, videogames, that is not able to represent the full scope of products Amazon entails and that customers are reviewing. An analysis of reviews on different product categories and the distribution of those reviews as part of the Amazon Vine program is recommended. 

