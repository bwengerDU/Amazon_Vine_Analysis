# Amazon_Vine_Analysis

## Project Overview

In this project I am working with pdAdmin4, Google Colab, and AWS in order to extract, transform, and load a dataset provided by Amazon. The dataset I worked from was a set of Amazon reviews for Automotive products. I used Pyspark in order to clean and sort through the data provided in order to examine Vine reviews and the distribution of 5 star reviews in order to determine whether Vine reviews have any positivity bias compared to non-Vine reviews. The filtered dataframes are then connected to pgAdmin4 and Amazon Web Services. 

## Results

![alt text](https://github.com/bwengerDU/Amazon_Vine_Analysis/blob/main/Deliverable%203.1.png)

- Of the total 24,824 reviews considered helpful for the analysis, Vine reviews comprised 18,153 of the reviews and non-Vine reviews were 6,671. 

![alt text](https://github.com/bwengerDU/Amazon_Vine_Analysis/blob/main/Deliverable%203.2.png)

- Of the total 24,824 reviews, there were 12,840 5-star reviews. 

-53.1% of the paid Vine reviews were 5-star, while 47.95% of the unpaid non-Vine reviews were 5-star. 

## Summary

From the surface level it does appear that there is a slight positive bias in Vine reviews. In order to determine whether this was truly a statistical positive bias it would be helpful to examine mean, median, mode, and standard deviations between the two groups. It would be important to also establish expectations and standards for acceptible deviation that would prove any bias. There is a 5% higher rate in Vine reviews so there is a difference between the two groups, but the degree of significance would need to be defined and assessed through these additional analyses. 
