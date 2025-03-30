**Context** 
•	Data is from a survey describing driving scenarios (time of day, weather, passenger, destination, etc.) and asking if a driver would use a coupon. 
•	https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation
•	Types of coupons: 
o	Inexpensive restaurant (under $20)
o	Coffee houses
o	Carry out/takeaway
o	Bars
o	Expensive restaurant ($20 - $50)
•	Target Variable: 
o	Y = 1 if the respondent says they would drive there “right away” or later (before expiration)
o	Y = 0 if the respondent says no to using the coupon


**Objective:**
•	Highlight differences between customers who accepted (Y=1) vs those who did not accept (Y=0) the coupons.


**Initial data findings:**
•	25 Categories/columns
•	12,684 Response requests/rows
•	12,576 responses are missing for car. This is nearly 99%
•	Bar – 107 missing
•	CoffeeHouse – 217 missing
•	CarryAway – 151 missing
•	RestaurantLessThan20 – 130 missing
•	Restaurant20To50 – 189 missing 
•	56.8% of responses would use coupon


**Categorical column findings:**
•	Direction: When people were going to “No Urgent Place” they were far more likely to use a coupon. Perhaps, going to work or home, one may feel they do not have the time to look for a coupon. 
•	Passenger: People are far more likely to use a coupon when traveling with friends.
•	Weather: On sunny days people were more lilkely to use a coupon than rainy or snowy days
•	Coupon: For restaurants under $20 and carry out people were more than twice as likely to use a coupon
•	Expiration: people were more likely to use a coupon if it was expiring in a day rather than two hours
•	Gender: Both genders were likely to use a coupon
•	Age: Younger population is far more likely to use a coupon 
•	Martial status: Singles and married people were more likely to use a coupon
•	Education: all groups used a coupon; however, people with some college education were more likely to use a coupon
•	Occupation: Unemployed students and comp & math professionals were more likely to use a coupon 
•	Income:  people making less than $63k and over 100k were more likely to use a coupon
•	Car: Mazda5 and old car drivers were far more likely to use a coupon 
•	Coffeehouse:  people who go to coffeehouses are more likely to use a coupon


