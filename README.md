# Berkeley Machine Learning Course. Module 5 Asssignment
## Case Study
In this project a survey data on coupons send to drivers are analyzed to predict acceptance rate.

## Data Cleanup
The Car column has many missing data. Since the type of car does affect drivers decision to accept coupon, missing values are  replaced with value 'unknown'.
The columns Bar, CoffeeHouse, CarryAway, RestaurantLessThan20 and Restaurant20To50 also have missing values. These are also decided to replace with value 'unknown'
since it will not affect much.

## Data analysis
Most of the data are catagorical in nature. So barcharts and histograms are used for analisys.

## Insights
Coupons 'Restaurant(<20)' and 'Carry out & Take away' have higher acceptance rate.
Drivers who already visited bar are likely to accept Bar coupons. Age above 30 is a factor. Also passanger being a kid also affecting decision to going to Bar.
Attributes like age, marital status, occupation does not seems much effect in accepting coupons.
