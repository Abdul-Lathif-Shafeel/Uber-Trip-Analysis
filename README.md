# Uber-Trip-Analysis
The core aim is to analyze Uber trip data including ride times, pickup/drop-off locations, revenue, distances, and vehicle types to identify key trends such as peak ride times, high-demand locations, customer preferences, and operational performance indicators.
UBER TRIP ANALYSIS

Data Set Overview:
	This data sourced from Kaggle captures 148,770 total bookings across multiple vehicle types and provides a complete view of ride-sharing operations including successful rides, cancellations, customer behaviors, and financial metrics. This comprehensive dataset contains detailed ride-sharing data from Uber operations for the year 2024.
The dataset contains the following columns:
Column Name	Description
Date	Date of the booking
Time	Time of the booking
Booking ID	Unique identifier for each ride booking
Booking Status	Status of booking (Completed, Cancelled by Customer, Cancelled by Driver, etc.)
Customer ID	Unique identifier for customers
Vehicle Type	Type of vehicle (Go Mini, Go Sedan, Auto, E - Bike/Bike, Uber XL, Premier Sedan)
Pickup Location	Starting location of the ride
Drop Location	Destination location of the ride
Avg VTAT	Average time for driver to reach pickup location (in minutes)
Avg CTAT	Average trip duration from pickup to destination (in minutes)
Cancelled Rides by Customer	Customer-initiated cancellation flag
Reason for cancelling by Customer	Reason for customer cancellation
Cancelled Rides by Driver	Driver-initiated cancellation flag
Driver Cancellation Reason	Reason for driver cancellation
Incomplete Rides	Incomplete ride flag
Incomplete Rides Reason	Reason for incomplete rides
Booking Value	Total fare amount for the ride
Ride Distance	Distance covered during the ride (in km)
Driver Ratings	Rating given to driver (1-5 scale)
Customer Rating	Rating given by customer (1-5 scale)
Payment Method	Method used for payment (UPI, Cash, Credit Card, Uber Wallet, Debit Card)



Objectives & Outcomes:
•	Help stakeholders optimize resource allocation, improve driver scheduling, and plan routes more efficiently.
•	Uncover insights into rider behavior and service demand, supporting data-driven strategic decisions.
•	Enhance understanding of ride-sharing performance trends for operational improvements and better customer experience.

Project overview:
The core aim is to analyze Uber trip data including ride times, pickup/drop-off locations, revenue, distances, and vehicle types to identify key trends such as peak ride times, high-demand locations, customer preferences, and operational performance indicators.

Tools Used:
MS EXCEL: collecting data and importing it into Power BI
POWER BI: Visualizing data with useful charts to gain insights.
POWER QUERY:
Power Query is a data connection and transformation tool that enables users to import, transform, and manipulate data from various sources within Excel and Power BI. It simplifies and automates the process of cleaning, reshaping, and merging data, making it easier to prepare data for analysis or reporting purposes. With Power Query, users can perform tasks such as removing duplicates, splitting columns, merging tables, and aggregating data, all within a user-friendly interface, without the need for complex formulas or coding.
DAX:
It’s designed to perform calculations, create custom measures, and manipulate data within these platforms, enabling users to derive insights and make data-driven decisions efficiently.

Dashboard:
Uber Trip Analysis:
	Provides an interactive overview of trip data, using key performance indicators (KPIs) like total bookings, revenue, and distance to track performance and identify operational insights. It features interactive charts and filters for month and month to visualize trends, analyze payment methods and vehicle types, and pinpoint high-demand areas and popular pickup/drop-off points.

 

Filters:
By Quarter: Helps to filter all the insights by quarterly (Q1, Q2, Q3 and Q4).
By Month: Helps to filter all the insights by Month wise (Jan…… Dec).
Cards:
	Total Revenue: Shows the total revenue for the specified time.
	Total Rides: Shows the total number of rides for the specified time.
	Avg Revenue: Shows the average revenue for the specified time.
	Trip Distance: Shows the overall distance travelled for the specified time.
	Avg waiting time: Shows the average waiting time of the customer.
	Avg Trip Duration: Shows the average travel time to the drop-off location.



  Revenue, Rides and Distance by payment method: (filters provided for each parameter at top middle)
	Take away: Identify which payment method is used widely. UPI is the top payment method with 42%, followed by Cash with 23%, and Uber wallet with 11%.
	Suggestions: We can provide some rewards like vouchers and cash back offers at next ride who are all using Uber wallet to increase the uber wallet payment method.
Revenue, Rides and Distance by Time period: (filters provided for each parameter at top middle)
	Takeaway: Helps to determine the busiest period. Evening (04 PM to 08 PM) is the top busiest period with 28% of revenues, followed by Morning (08 AM to 12 PM) with 21%, and Noon (12PM to 04 PM) with 18%.
	Suggestions: We can add some incentive for the rides completed on the period of Evening for more rides and revenues.
 
Revenue, Rides and Distance by payment method: (filters provided for each parameter at top middle)
	Takeaway: Assists in identifying the most booked vehicle among customers. Auto is the most booked vehicle that earns 12.9 M of revenue, followed by Go mini earns 10.3 M, and Go sedan with 9.4 M.
	Suggestions: We can completely drop off the uber-XL vehicle as its total revenue stands at $ 1.5 M, which is only 0.03% of total revenue. Customers can use bikes and e-bikes, which are similar to Uber XL.
 
Revenue, Rides and Distance by Month and date: (filters provided for each parameter at top middle)
	Takeaway: Provides the data of Total revenue, Total rides and total distance by month and date. For the month of January 2024 – 26th of Jan (republic day) is the busiest day of the month earns 211 K of revenue,
	Suggestions: We can provide some discounts on the festival day to increase the revenue and rides.
 
Most frequent pickup point & Most frequent drop point:
	Takeaway: 
•	Provide the topmost pickup point. Khandsa is the topmost pickup point with 946 pickups.
•	Provide the topmost drop point. Ashram is the topmost drop point with 845 pickups.
	Suggestion: We can have a Waiting hub/place around these locations to reduce the waiting time, which can make customers happy and we can be able to hit more rides.

 
Cancelled trips by cancel reason:
	Takeaway: It provides the total cancelled rides by cancel reason. Cancelled by driver with 47.33% of rides, Followed by Cancelled by customer with 18.19%, and No driver found 18.02%.
 
Reason for cancellation and incomplete rides:
	Takeaways: Helps to find the breakdown why cancellation happens. Personal & Car related issues at top with 609 cancelled rides, followed by customer coughing/sick with 590, and followed by More than permitted people in there with 571.
	Suggestion:
•	Personal & Car related issues  we can have a maintenance history of the vehicle and notify the drivers if there are any pending service visits.
•	Customer was coughing/sick  so we might provide them with a clinical mask to prevent infections and make them feel safe.
  
Cancelled by customer, cancelled by driver, Incomplete and no driver found details by Month and date: (filters provided for each parameter at top middle)
Takeaway: Provides the data of number of rides cancelled by customer, cancelled by driver, Incomplete and no driver found by month and date.
 
Total revenue by incomplete rides reason:
Takeaway: Provides the data of total revenue earned incompletely by reason.

Conclusion:
The insights gained from the analysis can help stakeholders make informed decisions related to operational efficiency, resource allocation, and customer service improvements. For instance, identifying peak hours and busiest zones can guide driver deployment strategies and promotional planning.
Overall, this project demonstrates how business intelligence tools like Power BI can enhance data visibility, improve decision-making, and support strategic planning in the transportation and ride-sharing industry. It lays a strong foundation for further analysis, such as revenue forecasting, customer segmentation, and performance benchmarking.
