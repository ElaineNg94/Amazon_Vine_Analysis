# Amazon_Vine_Analysis
**Overview of the analysis:**

The purpose of this analysis was to help Jennifer at Big Market. Jennifer needed help with the client SellBy since SellBy wanted to know how the reviews of their products compares with the reviews of similar products sold by their competitors. I used ETL, AWS RDS, pgAdmin, PySpark, and Google Colab to do this analysis of these multiple datasets. After doing this analysis, I had to see if there is any bias between the reviews from the Vine members and the non-Vine members, since the purpose was to determine if Vine members would result in more 5 star reviews than non-Vine members.

**Results:**

<img width="647" alt="vine_reviews1" src="https://user-images.githubusercontent.com/79742633/124380365-27147780-dc71-11eb-947a-de7221b014c0.png">
<img width="717" alt="vine_reviews2" src="https://user-images.githubusercontent.com/79742633/124380366-28de3b00-dc71-11eb-97a0-679ab3d7ab8c.png">

How many Vine reviews and non-Vine reviews were there?

- Number of Vine reviews: 162
- Number of non-Vine reviews: 35,568

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- Number of 5 stars Vine reviews: 63
- Number of 5 stars non-Vine reviews: 19,437

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- Percentage of 5 stars Vine reviews: 38.888
- Percentage of 5 stars non-Vine reviews: 54.647

**Summary:**

In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

There wasn’t any bias for reviews in the Vine program because the Vine program only had a 38.888% of 5-star reviews from the Vine reviews program, while non-Vine reviews had 54.647%. The non-Vine reviews had a percentage that was higher than the Vine program reviews, so there isn’t a positive bias in the Vine program.

An additional analysis I could do with this dataset to support my statement would be to have an equal number of reviews from the Vine program and the non-Vine program members. According to my results above, it showed there are a lot more reviews from non-Vine, which can affect the percentage. This shows that the percent of 5 stars could be more accurate if we compared the same amount of reviews from both the Vine program and non-Vine program reviews.
