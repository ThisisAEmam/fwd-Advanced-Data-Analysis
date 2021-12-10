# Ford GoBike System Data Exploration
## by AbdelRahman Emam


## Dataset

There are 183,412 Ford goBike rides in this dataset. The dataset has, initially, 16 features, such as:
1. **Numerical features:**
    * duration_sec
    * start_station_id
    * start_station_latitude
    * start_station_longitude
    * end_station_id
    * end_station_latitude
    * end_station_longitude
    * bike_id
    * member_birth_year
2. **Categorical (object-typed) features:**
    * user_type
    * member_gender
    * start_station_name
    * end_station_name
3. **Datetime features:**
    * start_time
    * end_time
4. **Boolean features:**
    * bike_share_for_all_trip


## Summary of Findings

> Trip duration depends on the member's age. Members aged between **30** and **40** years old have higher percentage of taking longer rides compared to other age ranges. While getting older, members are getting to take shorter rides. I can't tell that wasn't expected. As people age up, they can't do the same effort as before.

> 'Male' gender doesn't have higher trip duration than 'Female' and 'Other', as it may be expected. Surprisingly,'Others' gender aged between 55~60 years old have high trip durations.

## Key Insights for Presentation
> For member age: the distribution is more concentrated between 30 to 40 years old.

> For user type: the distribution for both types are almost the same.