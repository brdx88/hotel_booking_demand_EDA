# Exploratory Data Analysis of Hotel Booking Demand
This data set contains booking information for a city hotel, a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.

We found this data set on [Kaggle](https://www.kaggle.com/jessemostipak/hotel-booking-demand) but the data is originally from the article [Hotel Booking Demand Datasets - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S2352340918315191) written in journal named [Data in Brief](https://www.sciencedirect.com/journal/data-in-brief), Volume 22, February 2019. 
The subject area of this data is **hospitality management**. This data was acquired by extraction from hotel's Property Management System (PMS) SQL databases from 2015 to 2017. **Both hotels are located in Portugal**.

Since this is hotel real data, all data elements pertaining hotel or customer identification were deleted. Due to the scarcity of real business data for scientific and educational purposes, these datasets can have an important role for research and education in revenue management, machine learning, as well as in other fields.

# Problems
1. One in four hotel guests are canceling their booking ahead of a stay - an increase being driven by the sales tactics of online travel agencies.
The trend is causing problems for hoteliers who are unable to accurately forecast occupancy within their revenue management departments and creates headaches when organizing distribution across various channels. [PhocusWire](https://www.phocuswire.com/Hotel-distribution-market-share-distribution-analysis#:~:text=The%20average%20cancelation%20rate%20in,of%206.4%25%20over%20four%20years)
2. Resource management in the hotel is one of the strategies that should be focused on. Imagine if a restaurant’s team has expired groceries. Imagine if many workers like waiters or waitresses have much their own idle time. 
We, as a management level of the hotel, do not want these inefficient resources as we could lose our money and increase many costs, especially on humans and food.

# Goals
1. Find out what lead into high cancelation rate for hotels.
2. Maximize resources within hotels.


![market problems](https://github.com/brdx88/hotel_booking_demand_EDA/blob/main1.png)




# Conclusion
1. Number Booking have a positive correlation with the number of cancellation
2. Group Booking is the only market segment that have a higher cancellation  arrival  compared to it’s confirmed arrival
3. Customer who has 7 month or more lead time have a higher tendencies to cancel their booking
4. Traveler that has cancelled 1 time before has the highest tendencies to cancel again
5. Guests tend to book their rooms with breakfast instead of lunch or dinner.
6. Most guests come and start to stay in June, July, and August.
7. In Portugal, the busiest month in the hotels are July and August, especially on Saturday and Monday when guests start to check-in.

# Recommendations
1. **More Rigid /Stricter  Cancellation T&C  For Customer Who has Cancelled Before.** This is  one way to  reducing the tendencies of customers who have cancelled before to cancelled again.
2. **Non Refundable Only for Group Booking.** Group Booking has a higher cancellation rate compared to the confirmed rate,  with this policy hotel would not suffer  any loss revenue caused by cancelled group booking.
3. **Non Refundable Booking Only For Booking with More than 210 lead days.** Since Customer who has more than 210  lead days has a higher chance of cancellation, having this policy will protect the hotel from losing revenue.
4. **Breakfast Awareness.** Guests tend to have their bedrooms with breakfast package, so it might be good if management place more workers in the morning instead of noon or night. Even workers at the noon can be reduced and moved into the night shift. 
5. **Resources Efficiency.** Resources are precious, especially when it comes to food and humans. July and August are the best time to stock more food especially on Saturday and Sunday where guests start to check-in the room. The restaurant team could increase the number of workers too, to handle guests when meal time has come. This is good for cost efficiency so the resources either humans or food might not be wasted.
