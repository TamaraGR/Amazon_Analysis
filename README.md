# Amazon Product Reviews Analysis 

## Overview of the Analysis
In this analysis we are looking at whether those reviewers who have paid vine accounts are biased in their reviews as opposed to those who are users of the unpaid accounts. We are specifically focusing on the five star reviews, and this analysis is focusing on the reviews of the digital music downloads. 

## Resources 

- [x] AWS (including RDS and S3)
- [x] Postgres, pgAdmin
- [x] Google Colaboratory
- [x] PySpark, Python. 

## Results

To look at the analysis results refer to the below screenshot of the calculations and to the two ipynb files in this repository.

![calculations](https://github.com/TamaraGR/Amazon_Vine_Analysis/blob/main/calculations.png)

- [x] How many Vine reviews and non-Vine reviews were there?
In our particular category of goods (digital music) we had zero (0) paid Vine reviews. And we had a total of 4532 reviews from unpaid Vine accounts. 

- [x] How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
Zero (0) reviews from paid Vine users had 5 stars. Non-vine reviews with 5 starts were at 2507. 

- [x] What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Zero (0) % of Vine reviews were 5 stars. And slightly over 55% of non-Vine reviews were at 5 stars. 

## Summary 

Based on the fact that we don't have any paid Vine users in this category, it's hard to say whether being a paid or unpaid user affects people when they give a 5 star review. However, more than half of the reviewers (all unpaid) gave 5 sar reviews, which speaks volumes about the fact that one doesn't necessarily have to be a paid user. 

Additionally it'd be interesting to review paid and unpaid users across multiple categories of goods, especially digital versus tangible physical goods. People tend to be more picky about the physical goods than they are about the digital goods (although they would pay less for the digital goods, accoridng to Inc.)

It would also be interesting to compare reviews from recent Vine paid customers versus those who have been customers for a long time. 

The screenshots below help provide more understanding of what data we were working with. 

![image1](https://github.com/TamaraGR/Amazon_Vine_Analysis/blob/main/customers_table.png)
![image2](https://github.com/TamaraGR/Amazon_Vine_Analysis/blob/main/products_table.png)
![image3](https://github.com/TamaraGR/Amazon_Vine_Analysis/blob/main/review_id_table.png)
![image4](https://github.com/TamaraGR/Amazon_Vine_Analysis/blob/main/vine_table.png)
