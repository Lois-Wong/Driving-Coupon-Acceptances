# Will-the-Customer-Accept-the-Coupon

Project Description

The goal of this project is to distinguish between customers who accepted a specific type of driving coupon and those that did not, using visualizations, plots, and probability distributions. A brief report highlighting the features of drivers who accepted either bar or take away coupons is presented along with recommended trajectories of actions that can be taken.

Motivation

This project is completed to fulfill the requirements of UC Berkeley's Professional Certificate in Machine Learning and Artificial Intelligence.  

Data

This data is from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’.  There are five different types of coupons -- less expensive restaurants (under \\$20), coffee houses, carry out & take away, bar, and more expensive restaurants (\\$20 - \\$50).

Findings

#### Summary and Conclusions on Drivers who accepted the bar coupons

Of the 41% of bar coupons that were accepted, 
- Drivers that go to a bar more than three times a month had a far greater coupon acceptance rate (.76) than drivers who go to a bar three times or less (.37)
- The acceptance rate of drivers who go to a bar at least once a month and are older than the age of 25 (.69) are roughly twice that of the acceptance rate of all other individuals in the sample (.34)
- Drivers who go to a bar at least once a month, did not have kids as passengers, and did not work in the farming, fishing, or forestry industries had an acceptance rate (.71) over twice that of all other individuals (.30) 
- The majority of individuals who visit the bar more than once, did not have kids as passengers, and were not widowed accepted the coupon (.71)
- Similarly, the majority of individuals under the age of 30 and visit the bar at least once a month accepted the coupon (.72)
- On the other hand, individuals who visited cheap restaurants more than four times a month and had an income under $50,000 largely did not accept the coupon (acceptance rate .46)

Based on these observations, it is reasonable to hypothesize that the the number of times someone visits a bar in a month is positively correlated with the likelihood of their accepting a bar coupon: Drivers that go to the bar at least three times a month are more likely to accept a bar coupon than drivers that go to the bar at least once a month, who are more likely to accept than those who visit the bar less than once a month. Actions to take include **targetting individuals who go to a bar at least once a month and prioritizing those who visit the bar at least three times a month. Additionally, those who do not have kids in the passenger and are between the ages 25-30 should be prioritized.**

Of the 74% of takeaway coupons that were accepted, 

- Drivers going home have the highest acceptance rates of takeaway coupons (.79), followed by those going to no urgent place (.76), and those heading to work (.66)
- Individuals who get takeaway more than 3x a month have a slightly higher acceptance rate (.75) than those who get takeaway 3x or less (.72)
- There is a wider gap between the acceptance rates of drivers who buy takeout food less than once a month vs at least once a month. A greater proportion of those who get takeaway at least once a month accept the takeaway coupon (.75) compared to those who get takeaway less than once a month (.69)
- The biggest group of individuals who buy takeout food less than once a month are single, while those those buy takeout food more than once a month are mostly married 

- The acceptance rate of married individuals going home who get takeout less than once a month (.67) is lower than that of all others (.74), and married individuals going home who get takeout at least once a month (.74) have a slightly higher acceptance rate than all other groups (.73)
- Single individuals on their way to work who get takeout less than once a month are more likely to reject a takeaway coupon (.34) than all others (.26)

As such, it is reasonable to hypothesize that the likelihood of someone accepting a takeaway coupon increases with the number of times they buy takeout food each month, as well as that individuals on their way home are the most likely to accept a takeaway coupon. Actions to take include **prioritizing individuals who buy takeout food at least once a month and are either on their way to no urgent place or going home**.  

Access

Link: http://localhost:8888/lab/tree/ML/Module%205/Practical%20Application%20Assessment.ipynb

Link to download: http://localhost:8888/files/ML/Module%205/Practical%20Application%20Assessment.ipynb?_xsrf=2%7C0eb03af8%7Ced1915e9f177137b047d1b99e0ae5482%7C1648959711

Link to data: https://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation
