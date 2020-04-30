# Data-Science-Project-Using-Python-Airbnb-Data-Analysis
### 1 Data Description
## 1.1 Data Source
        I downloaded the most recent datasets “reviews.csv”, “listing.csv”, and “calendar.csv” containing reviews, listings, and time information in Los Angeles, California from http://insideairbnb.com/get-the-data.html. The data was collected on September 14, 2019, which has already been cleansed and aggregated where appropriate to facilitate this project. 

## 1.2 Dimensions
        There are three datasets, including “reviews.csv”, “listing.csv”, and “calendar.csv”. 
        The “reviews.csv” is the detailed review data for listings in Los Angeles. It has 1,509,564 rows and 6 columns. Its attributes include “listing_id”, “id”, “date”, “reviewer_id”, “reviewer_name”, and “comments”. 
        The “listings.csv” is the detailed listings data for Los Angeles. It has 44,986 rows and 106 columns. Its attributes include “id”, “listing_url”, “scrape_id”, “last_scraped”, “name”, “summary”, “space”, “description”, “experiences_offered”, “neighborhood_overview”, “reviews_per_month”, etc. 
        The “calendar.csv” is the detailed calendar data for listings in Los Angeles. It has 16,444,345 rows and 7 columns. Its attributes include “listing_id”, “date”, “available”, “price”, “adjusted_price”, “minimum_nights”, and “maximum_nights”. 

### 2 Mission
## 2.1 Insights Plan to Get
(1) Does the total number of each type of room vary significantly, and how much does the average price for each room type vary?
(2) What is the average price in the top 20 most expensive neighborhoods, and does this overlap with the top 20 neighborhoods with the most listings?
(3) Is there any relationship between "number_of_reviews" and "price"? What is the implication?
(4) What are the 20 most popular amenities in the most expensive listing in Los Angeles according to price?
(5) Is the type of beds and number of beds offered in Airbnb listings correlated with the price? Does offering more beds in a listing result in more bookings?

## 2.2 Business Insights Summary
        Our team’s analysis sought to find key features of successful Airbnb listings in order to provide recommendations for potential new Airbnb hosts. In the Los Angeles area, entire homes and apartments appear to dominate the market and, on average, are the most expensive per night. This indicated that these types of listing are the most lucrative. However, we found that lower cost listings had significantly more reviews than listings above 1000 per night, and reviews can be interpreted as a conservative estimate for bookings. Hosts may find it easier to enter the market by offering lower-cost private or shared rooms for solo travelers and younger guests. Besides, we found that listings with 0-3 beds had the most bookings, and those that had real beds types had a higher average price. This indicated the importance of quality of bed type offerings over the number of beds offered. We also found that several neighborhoods with the highest average price per listing also overlapped with the top 20 neighborhoods with the most listings. This indicated that potential Airbnb hosts should purchase property or list their spaces in a neighborhood such as Beverly Hills, Bel Air/Beverly Crest, and Marina Del Rey. More expensive Airbnb listings had unique amenities such as air hockey tables, shuffleboard, stand-alone rain shower, and a reading nook, which can be offered by the new host to differentiate themselves from other listings in addition to more common amenities such as Wi-Fi.
