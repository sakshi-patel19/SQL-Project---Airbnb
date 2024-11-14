# SQL Project - Airbnb

Airbnb is a leading online market place that provides accommodation options across various neighborhoods in New York City and around the globe. To ensure their business operations run smoothly, Airbnb has developed a cutting-edge Hospitality Intelligence Hub that analyzes data from various sources for better insights and trends.

## Purpose of the Hospitality Intelligence Hub
The primary objectives of the Hospitality Intelligence Hub are:

-Business Operations Insight: Analyze data to gain valuable insights into business operations.

-Informed Decision Making: Utilize data-driven insights to make informed decisions.

## Data Analysis with MySQL
The Hospitality Intelligence Hub uses MySQL to analyze data, which includes information on various neighborhoods in New York City. This data analysis focuses on:

-Types of Listings: Information on the various types of accommodation listings available.

-Price Trends: Analysis of price trends for listings in specific neighborhoods.

-Availability: Tracking the availability of different listings.

## Query to identify frequently booked room types:
-SELECT room_type, COUNT(*) as Booking_Frequency
FROM Booking_Data
GROUP BY room_type
ORDER BY Booking_Frequency DESC;

-SELECT neighborhood, AVG(price) as Average_Price
FROM Listings_Data
GROUP BY neighborhood
ORDER BY Average_Price DESC;

-SELECT listing_id, available_dates
FROM Availability_Data
WHERE neighborhood = 'NEIGHBORHOOD_NAME';


## Results and Insights
By leveraging MySQL, the Hospitality Intelligence Hub tracks trends in customer behavior and preferences, such as:

-Frequently Booked Room Types: Identifying the room types that are most frequently booked by customers.

-Neighborhood Price Trends: Analyzing price trends for accommodation listings across different neighborhoods.

-Customer Preferences: Understanding customer preferences to enhance service offerings.

-Optimize Listings: Improve the types and availability of listings based on customer demand.

-Price Strategically: Set competitive prices for listings based on trend analysis.

-Enhance Customer Satisfaction: Tailor services to better meet customer preferences and enhance their experience.
