# EDA-hotel_bookings


## About the dataset-

Count of rows= 119390
Count of columns= 32


## Dataset features-

1. hotel Two hotels are given: Resort Hotel City Hotel
2. is_canceled 1: Canceled 0: Not canceled
3. cancelation 0 as not_canceled 1 as canceled
4. df_not_canceled_guests dataframe with just not_canceled bookings
5. lead_time gap between booking and arrival
6. arrival_date_year arrival year
7. arrival_date_month arrival month
8. arrival_date_week_number arrival week
9. arrival_date_day_of_month arrival date
10. stays_in_weekend_nights count of nights the guests booked the hotel during Sat-Sun
11. stays_in_week_nights count of nights the guests booked the hotel during Mon-Fri
12. total_stay_nights duration of stay including weekend nights and week nights stay
13. adults count of adults
14. children count of children
15. babies count of babies
16. meal meal type (no meal package; BB; HB; FB)
17. country country of guests
18. df_country_guests_top10 top10 countries with most visitors
19. market_segment TA: Travel agents TO: Tour operators
20. distribution_channel
21. is_repeated_guest 1: Yes 0: No
22. previous_cancellations count of previous bookings that were cancelled by the customer before final booking
23. previous_bookings_not_canceled count of no canceled bookings
24. reserved_room_type booked room category
25. assigned_room_type assigned room category
26. booking_changes count of changes made by the customer before final booking
27. deposit_type type of deposit made by the customer
28. agent travel agent id
29. company booking company id
30. days_in_waiting_list count of days the booking was in the waiting list before it was confirmed
31. customer_type Transient Contract Group Transient-party
32. adr average daily rate for the booking
33. price total price spent by a guest entity
34. required_car_parking_spaces count of car parking spaces alloted by the customer
35. total_of_special_requests count of special requests made by the customer
36. reservation_status status of reservation
37. reservation_status_date date corresponding to status of reservation


## Summary of Conclusions-

1. 'City hotels' and 'Resort hotels' are two types of hotels present in the dataset, out of which, 'City hotels'are more preffered by the customers than the latter. (66.4% customer prefers 'City hotels' whereas 33.6% customer prefers 'Resort hotels').

2. Out of all months, 'August' witnessed highest number of hotel bookings whereas 'January' witnessed the least.

3. Among all the countries in the dataset, PRT(Portugal) has got the maximum number of hotel bookings.

4. Its observed that 'City hotels' was more cancelled as compared to 'Resort hotels'.

5. Coming to the analysis of market segment, 'Online TA' brings maximum bookings.

6. Considering all the three years, 'August' has got the highest average ADR in each year.

7. After analysing the meal data, its found that 77.3% of customers prefers BB(Bread & Breakfast).

8. Its observed that most of the customers rather guests do not repeat their bookings on which the hotel management must look into.

9. We can observe that Room type G of 'City Hotel' and Room type C of 'Resort Hotel' have highest outlier value which is around 500. We can observe that room type 'G' of City hotel has highest mean rates among all. In resort hotels room type 'H' has highest mean rate.

10. It is observed that average daily count rate has decreasing trend after having peak value in August. This decreasing trend continues till month of January and after month of January ADR starts to increase and this trend is again observed till the month of August.

11. Also on comaparing year wise we notice that each year ADR has been consistently increasing.
