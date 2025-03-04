# AIMLBerkeley2025 - Coupon Acceptance behaviour

<ins>Introduction</ins>

We are provided with a data set that contains information on whether or not a driver accepts a coupon - the dataset includes different categories of coupon and various attributes defining each coupon acceptance/rejection behaviour. A total of 12,684 observations were provided that were spread across multiple coupon categories in the below fashion, out of which 56% coupons were accepted:

'Bar' - 2017 entries
'Carry out & Take away' - 2393 entries
'Coffee House' - 3996 entries
'Restaurant(<20)'	- 2786 entries
'Restaurant(20-50)'	- 1492 entries

The notebook uploaded here analyzes Bar and Coffee House where different attributes from the dataset are studied to understand coupon adoption trends. For the analysis null attributes were replaced with 'NA'. 

<ins>Findings</ins>

a) Bar Coupons
Acceptance ratio is the number of coupons accepted vs the total number of coupons provided.
Analysing Bar coupons:
Among 2017 Bar coupons provided, 41% of coupons were accepted.
Tried  studying the influence of following factors in Bar coupon acceptance behavior:
Age, Frequency of visit to bars in a month, whether or not there is a kid passenger ,Occupation, Marital status

Inference:

a) Acceptance rate of drivers who went to a bar more than 3 times is 40% higher than others
b) Acceptance rate of drivers 25 and above who went to a bar more than once a month is 40% higher than others
c) Acceptance rate of drivers who go to bars more than once a month, had passengers that were not a kid and had occupations other than farming, fishing, or forestry is 41% higher than others
Looking at the above, it was inferred than drivers who are aged 25+, who go to bars 3 or more times and who do not have a kid have a very high acceptance rate (78% as calculated)
Investigating Coffee House Coupons

b) Coffee House Coupons
3996 Coffee House coupons were provided and 49.92% was accepted.
Tried  studying the influence of following factors in Coffee House coupon acceptance behavior:
Frequency of visit to coffee house in a month, time at which the coupon was given and Age.
Inferences:
a.	Acceptance rate of drivers who went to Coffee House 4 or more times is  22.54%  more than all others
b.	Acceptance rate of drivers under 21 years of age is  20.55%  more than all others
c.	Acceptance rate of drivers to which the coupon was provided before 10 am is is  7.91%  more than all others

Looking at the above it was inferred that drivers visiting coffee house at or before 10 AM and visit 4 or more times a month have a high acceptance ratio of 81%
