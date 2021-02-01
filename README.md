# Amazon_Vine_Analysis
# Overview of the analysis of the Vine program:

The purpose of this analysis is analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. 

In this project, I’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. I’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in my dataset.

# Results:

There is a bulleted list that addresses the three questions for unpaid and paid program reviews:

1,How many Vine reviews and non-Vine reviews were there?

There are 94 vine reviews and 40,471 non-vine reviews for a total of 40,565 reviews.


2,How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

There were 48 5-star vine reviews and 15663 5-star non-vine reviews for a total of 15,711 5-star reviews.

3,What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

51.06% of paid reviews are 5-stars and 38.7% of unpaid reveiws are 5-stars.



# Summary:

After I had come up with my analysis there does not appear to be any sort of positivity bias because the percentages shown above are very similar at 38%. To conclude the analysis the vine program does not show any bias.
