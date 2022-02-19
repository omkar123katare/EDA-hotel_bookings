# EDA-hotel_bookings

We are given a dataset that contains information about guests of two types of hotels City hotels and Resort hotels. We have defined various milestones for this projects and also achieve those.

## About the dataset-

Count of rows= 119390
Count of columns= 32


## Dataset features-

1. hotel: Type - Resort Hotel City Hotel
2. is_canceled: 1- Canceled 0- Not canceled
3. cancelation: 0 - not_canceled 1 - canceled
4. lead_time: gap between booking and arrival
5. arrival_date_year: arrival year
6. arrival_date_month: arrival month
7. arrival_date_week_number: arrival week number
8. arrival_date_day_of_month: arrival date
9. stays_in_weekend_nights: count of nights the guests booked the hotel for Saturday and Sunday
10. stays_in_week_nights: count of nights the guests booked the hotel between Monday to Friday
11. total_stay_nights: duration of stay including weekend nights & week nights 
12. adults: number of adults
13. children: number of children
14. babies: number of babies
15. meal: meal type 1. no meal package 2. BB 3. HB 4. FB
16. country: country of guests
17. market_segment :TA- Travel agents TO- Tour operators
18. is_repeated_guest: 1- Yes 0- No
19. previous_cancellations: number of previous bookings that were cancelled
20. previous_bookings_not_canceled: number of no canceled bookings
21. reserved_room_type: booked room type
22. assigned_room_type: assigned room type
23. booking_changes: Number of changes made by the customer before booking
24. deposit_type: type of deposit
25. days_in_waiting_list: Number of days the booking was in the waiting list before it was confirmed
26. customer_type: Transient Contract Group Transient-party
27. adr: average daily rate of booking
28. price: total price spent 
29. required_car_parking_spaces: Number of car parking spaces alloted by the customer
30. total_of_special_requests: Number of special requests made by the customer
31. reservation_status: status of reservation
32. reservation_status_date: date corresponding to status of reservation

## Milestone 1: Handling the null values in the dataset and also preparing the dataset for anlysis.
## Milestone 2: Count of number of bookings received for a type of hotel.
![Screenshot (190)](https://user-images.githubusercontent.com/92416952/154811867-a177df67-0999-4dec-b4a6-9f0dec4bef34.png)
We can observe that city hotels received 66.7 % of total hotel bookings and Resort hotels received 33.3% of total hotel bookings.
## Milestone 3: Count of Booking cancellations according to hotel types
![Screenshot (191)](https://user-images.githubusercontent.com/92416952/154811919-09dab136-a59a-4036-a6e6-f6f8e77ee6a9.png)
![Screenshot (192)](https://user-images.githubusercontent.com/92416952/154811956-63281e22-c520-48b1-9219-64c7c88a92b4.png)
From above graph we can observe that number of booking cancellations are higher in City Hotels. Also based on bar plot plotted to show % of bookings cancelled in Resort Hotels and City Hotels, We can see that almost 42% of the bookings made for city hotels are cancelled and almost 28% of bookings made for Resort Hotels are cancelled.
## Milestone 4: Most preffered month for hotel booking
![Screenshot (193)](https://user-images.githubusercontent.com/92416952/154811997-caafba51-7750-4cbd-ae3a-3a6e10814a8b.png)
We can observe that guests preferred August month more than other months.
## Milestone 5: Country wise guests of hotels
![Screenshot (194)](https://user-images.githubusercontent.com/92416952/154812074-2b0bde62-036c-4383-9ab2-f9391673508d.png)
Large number of guests came from Portugal
## Milestone 6:  Visualizing above information on global map to see if any pattern is present depending on regions.
![Screenshot (195)](https://user-images.githubusercontent.com/92416952/154812117-3faa36c2-9f3d-46c2-a6d3-229c46f13b86.png)
We can observe that most number of bookings are from Europian countries,USA,Brazil.
## Milestone 7: Which segment brings in the most of the bookings?
![Screenshot (196)](https://user-images.githubusercontent.com/92416952/154812157-7cb1f1f7-49ec-414e-8602-070e6c40bd2d.png)
We can observe that most bookings received are Online
## Milestone 8: Analyzing according to meals ordered
![Screenshot (197)](https://user-images.githubusercontent.com/92416952/154812189-f158593b-22d1-4800-beba-4c7fb81fd3f9.png)
We can observe that most of the guests have booked BB (Bread and Breakfast)
## Milstone 9: Repeated guests Analysis
![Screenshot (198)](https://user-images.githubusercontent.com/92416952/154812232-d0a187c8-a45f-4fa4-b5b2-4e15c4e6f768.png)
We can observe that number of repeated guests is very less
## Milestone 10: Analysis on the basis of ADR(average daily rate)
![Screenshot (199)](https://user-images.githubusercontent.com/92416952/154812288-4ad14873-01af-4f53-b596-3fb51839a8cf.png)
We can observe that in city hotels highest room ADR was for room type G and was lowest for the room type K. In case of Resort Hotels highest ADR was for room type H and was lowest for room type I.
![Screenshot (200)](https://user-images.githubusercontent.com/92416952/154812315-68579459-e019-484e-8a7a-cf6133c4d885.png)
We can also observe that average daily count rate has decreasing trend after having peak value in August. This decreasing trend continues till month of January and after month of January ADR starts to increase and this trend is again observed till the month of August. ALso on comaparing year wise we notice that each year ADR has been consistently increasing.


## Summary of Conclusions-

1. 'City hotels' and 'Resort hotels' are two types of hotels present in the dataset. city hotels received 66.7 % of total hotel bookings and Resort hotels received 33.3% of total hotel bookings.

2. we can observe that number of booking cancellations are higher in City Hotels. Also based on bar plot plotted to show % of bookings cancelled in Resort Hotels and City Hotels, We can see that almost 42% of the bookings made for city hotels are cancelled and almost 28% of bookings made for Resort Hotels are cancelled.

3. 'August' witnessed highest number of hotel bookings whereas 'January' witnessed the least.

4. Guests from PRT(Portugal) have got the maximum number of hotel bookings.

5. We can observe that most number of bookings are from Europian countries,USA,Brazil.

6. 'Online TA' brings maximum bookings.

7. 'August' has got the highest average ADR in each year.

8. Its found that 77.3% of customers prefers BB(Bread & Breakfast).

9. Its observed that most of the customers rather guests do not repeat their bookings.

10. We can observe that in city hotels highest room ADR was for room type G and was lowest for the room type K. In case of Resort Hotels highest ADR was for room type H and was lowest for room type I.

11. It is observed that average daily count rate has decreasing trend after having peak value in August. This decreasing trend continues till month of January and after month of January ADR starts to increase and this trend is again observed till the month of August.

12. Each year ADR has been increasing consistently.
