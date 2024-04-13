# **Understanding Airbnb Prices in Boston: A Simple Guide**

**Motivation:**
Finding an accommodation is the most typical problem to be solved, when traveling to another city or country. And one of the most important things in choosing an accommodation is the reservation price. What are the main factors, which affect the reservation prices? Does time of the year influence prices and what are the busiest times of the year to visit a particular city? How can we save money on the reservation?

**File Description:**
listings.csv - summary information on listing in Seattle such as: location, host information, cleaning and guest fees, amenities etc.
calendar.csv - calendar data for the listings: availability dates, price for each date.
reviews.csv - summary review data for the listings. This dataset won't be used in further analysis.

**Summary of the results:**
In this analysis, we tried to understand what influences the reservation prices with the help of AirBnB data for Boston. Of course, the results may be different for each city, but the current approach still can be used for other cities' data. The main takeaways of the Boston data analysis include:
Basic characteristics of the place (number of bedrooms, bathrooms, beds and accommodates) affect the reservation price.
The reservation price varies depending on the time of the year. For example, the busiest time to visit Boston is summer.
The host policies (minimum night, cancellation and phone number requirement) might also affect the reservation price. 
Therefore, if you were to visit Boston try to book in summer when it is less crowded and be certain of your trip as there may not be a cancel option for lower price listing. So now that we know how to choose between places offered by AirBnB and save money, it is time to travel and test it in practice!

**Acknowledgements:**
Boston Airbnb Data: https://www.kaggle.com/datasets/airbnb/boston
AirBnB official website information: https://www.airbnb.com.sg/help/article/125

**Model:**
Random Forest regressor: https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html
XGBoost regressor: https://xgboost.readthedocs.io/en/stable/


More detailed analysis can be found in the Medium blog: 
https://medium.com/@hthientam2402/understanding-airbnb-prices-in-boston-a-simple-guide-232da5712ff5

git config user.name "thien8226"
git config user.email "hthientam2402@gmail.com"
