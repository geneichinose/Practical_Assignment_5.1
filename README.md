# Practical_Assignment_5.1
Practical Application Assignment 5.1: Will the Customer Accept the Coupon? 

https://github.com/geneichinose/Practical_Assignment_5.1

Files included:
  
  	1. geneichinose_assignment_5_1_2.ipynb (Python Notebook)
  
  	2. data/coupons.csv (CSV data file)
  
  	3. README.md (this file)
  
Summary of findings (Prompt questions 1-7)

We first checked the dataset for nan's and found 6 columns. We dropped the car column because it had over 99% nan's. The other 5 columns had less than 1.5% nan's which were related questions about number of times business were visited. In these cases of missing values, we represented them the value of 'never' assuming that was the drivers intent. 

We then cleaned the dataset by renaming the column="Y" to "TookCoupon". We also modified the responses using pandas.Categorical() to set the ordering.

We find that 41% drivers accepted coupons and 59% rejected the Bar coupon out of a group of 2017 number of drivers offered or selected the Bar coupon. 

In the group of 967 drivers that went to the bar 3 or fewer times a month accepted the Bar coupon at a rate of 52.7%. In the group of 199 drivers that went to the bar more than 3 times a month accepted the Bar coupon at a rate of 76.9%.

The acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 is 69.5% The acceptance rate of all others is 39.3%. There is a 30.2% increase for those who frequent bars more than once a month and are over the age of 25 compared to all others.

The acceptance rate between drivers who go to a bar more than once a month, had one passanger that were not kids, and had occupations that were not in farming, fishing, or forestry, is 71.3%. This is a 2% higher rate than the previous above rate.

The acceptance rate for drivers who go to bars more than once a month, had passengers that were not a kid, and were not widowed is 71.3%. This is the same rate as above in question #6.

Based on these observations, I hypothesize that drivers who accepted the bar coupons are more likely to visit bars more than once a month, dont have kids, over the age of 25, than others that received but rejected the Bar coupon.

Independent Investigation

Drivers accepted coffee house coupons in the morning at 10AM and also in the afternoon at 2PM. 

Drivers also accepted restaurant coupons for < $20 at 2PM and 6PM.

Drivers accepted mostly carry out at 7AM and 10PM which were the earliest and latest times outside of traditional dine-in hours.

More drivers accepted coupons that were for carry out and restaurants(< $20), while the acceptance rates were similar to rejected rates for other Bar and coffee house coupons.

See interesting comparison between income and coupon acceptance, low to middle income earners were more likely to accept coupons.

See interesting comparison between age and coupon acceptance, younger adults are more likely to accept coupons. These were also more likely in college or had college degree. 
