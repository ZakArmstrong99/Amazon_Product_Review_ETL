# Amazon_Product_Review_ETL
## Overview:
The purpose of this project was to perform an ETL on an Amazon review dataset using Pyspark and Pgadmin. The dataset contained data related to video games and information that comes with products on Amazon such as the star rating and if it was a verfied purchase. After the ETL, another notebook was made with the intention of finding bias from the Amazon vine program, which pays people to leave reviews. This was done by finding out how many reviews were paid and unpaid, how many of the vine reviews were five stars, and there percentage.
## Results:
- How many Vine reviews and non-Vine reviews are there?

![paid_unpaid_count](https://user-images.githubusercontent.com/107213807/193126442-fec792fe-568a-40b0-a315-fcb46336d2b7.png)

There are a total of 4,291 paid reviews and 1,781,706 total unpaid reviews.

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![paid_unpaid_fivestar_count](https://user-images.githubusercontent.com/107213807/193126448-5ed4a22f-1282-4ba4-bd1f-27326f6c319f.png)

There are 1,607 total five star paid reviews and 1,025,317 total five star unpaid reviews.

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![final_df](https://user-images.githubusercontent.com/107213807/193126472-92776c0d-f895-436b-b732-5fdcc9f644a2.png)

about 57% of the reviews are unpaid five star reviews and .09% reviews are paid five star reviews.

## Summary:
