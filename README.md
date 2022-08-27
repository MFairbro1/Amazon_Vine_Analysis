# Amazon_Vine_Analysis

## Overview:

### The purpose of this project is to analyze Amazon reviews written by members of the paid Vine program. Using PySpark, we perform the ETL process to load data from one of 50 datasets into pgAdmin. After this, we analyze the Vine reviews for bias.

## Results:

![Capture](https://user-images.githubusercontent.com/104467100/187014912-3043aa8d-600f-4965-aca9-9285743eb4dc.PNG)

### From the above screenshot depicting elements of the Vine review analysis, we can see the following:

### - 94 Vine reviews 

### - 40,471 unpaid reviews

### - Number of Vine reviews with more than 5 stars is 48

### - There are 15,663 unpaid reviews that give 5 star

### - 51% of the Vine reviews give 5 stars

### - 38% of unpaid reviews give 5 stars

## Summary:

### From the results we can see that slightly more than half of (51%) of Vine reviews taken from the filtered selection in our analysis are 5 star reviews. Comparatively, only 38% of unpaid reviews are 5 star reviews. This could indicate bias in the Vine reviews. It is worth noting that the sample size for Vine reviewers is very small compared to the unpaid reviewers, however. Small sample size can lead to bias.

### For some visual clarification we could plot the distribution of the star rating data and look at the mean and median for both paid and unpaid reviews.
