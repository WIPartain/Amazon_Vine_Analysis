# Amazon_Vine_Analysis

## Overview

In this project, we analyzed various datasets containing Amazon product reviews to determine the ratio of positive to non positive reviews between Vine and non-Vine users. Vine is a program where companies will pay various fees and even provide free products for consumers in return for positive website reviews. In order to determine if there is any bias towards favorable reviews from Vine members vs. non-members, we need to identify the percentage of 5 star ratings to total rating.  We utilized AWS , pgAdmin, and PySpark in order to effectively sort and transform our datasets. I selected the "sports" category as the sample for this project.

## Results
![](https://github.com/WIPartain/Amazon_Vine_Analysis/blob/main/images/paidreview.png)

![](https://github.com/WIPartain/Amazon_Vine_Analysis/blob/main/images/unpaidreview.png)

There were 334 Vine customers compared to 61614 unpaid users. Therefore, the Vine users in this particular category are a very small sample size of the overall population.  

![](https://github.com/WIPartain/Amazon_Vine_Analysis/blob/main/images/paidfivestar.png)

![](https://github.com/WIPartain/Amazon_Vine_Analysis/blob/main/images/unpaidfivestar.png)

There were 139 5 star reviews from Vine users compared to 32665 made by unpaid users.  From this data, you can see the percentage decrease is much more severe for Vine users as opposed to non vine users.

![](https://github.com/WIPartain/Amazon_Vine_Analysis/blob/main/images/paidpercent.png)

![](https://github.com/WIPartain/Amazon_Vine_Analysis/blob/main/images/unpaidpercent.png)

Roughly 42% of vine users gave a 5 star review while 53% of non vine users issued 5 star reviews in this product category.

## Summary
There is a big distinction between Vine and non-Vine users.  However, it is not the kind of difference we initially hypothesized.  The 5 star review percentage among paid reviewers was actually much lower than unpaid users which would indicate there is no positivity bias.  It is possible that the sample size may be too small, and different categories may yield different results.  It is also possible that the Vine users put more time and effort into their reviews, and they more accurately captured the quality of the products in their reviews.  I am curious that if we counted the average number of words per review, we may find a correlation between the number of stars, whether or not the user is part of the vine program, and the number words used in the reviews.
