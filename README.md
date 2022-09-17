# Amazon_Vine_Analysis

## Overview of Analysis
The purpose of this analysis was to find out if there was a possibility of bias toward favorable reviews left by Amazon Vine members who are sponsored. Companies are allowed to pay Vine users to review their products and can send members their products to review. I examined the reviews left on apparel purchases. I used Pyspark to clean up the data and calculate the percentages of favorable Vine paid reviews and non-paid Vine reviews.

## Results
The first part of my analysis involved determining how many of the reviews were Vine reviews and how many were just normal reviews.
I separated the data into two different dataframes.
* First all Vine reviews, using the count function I was able to find that there  were only 33 paid Vine reviews.
![yesvine](https://user-images.githubusercontent.com/106573185/190876349-358f9451-3b3f-449d-aa95-b22094957ba2.PNG)

* Second, all the of the rest of the reviews. With the same process, I was able to find that there were 45,246 unpaid reviews, this is a huge difference in the amounts of reviews.
![novine](https://user-images.githubusercontent.com/106573185/190876387-7cf448d2-7c65-494a-b535-658b2430094a.PNG) 

I found that of the 33 Vine Reviews, only 15 were 5 Star Ratings and 23,639 of unpaid reviews were 5 Star ratings.

In addition the percentages for users leaving 5 Star Ratings was about 45.5% for Vine reviews and 52.3% for unpaid. 
![5star](https://user-images.githubusercontent.com/106573185/190876624-f642605c-90a2-4d6e-bab9-01e1c9667cf3.PNG)
