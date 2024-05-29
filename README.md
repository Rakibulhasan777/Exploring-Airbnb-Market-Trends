# Exploring-Airbnb-Market-Trends 

## Project Description 
New York City has a variety of Airbnb listings to meet the high demand for temporary lodging for travelers, with several different price levels, room types, and locations. This Data Analysis project aims to importing and cleaning data and data manipulation and report insights to a real estate start-up! I'll answer the several questions of my stakeholder. They are:
  * What are the dates of the earliest and most recent reviews?
  * How many of the listings are private rooms?
  * What is the average listing price?

## Data 
Three files containing data on 2019 Airbnb listings are available :

**data/airbnb_price.csv**
This is a CSV file containing data on Airbnb listing prices and locations.
- **`listing_id`**: unique identifier of listing
- **`price`**: nightly listing price in USD
- **`nbhood_full`**: name of borough and neighborhood where listing is located

**data/airbnb_room_type.xlsx**
This is an Excel file containing data on Airbnb listing descriptions and room types.
- **`listing_id`**: unique identifier of listing
- **`description`**: listing description
- **`room_type`**: Airbnb has three types of rooms: shared rooms, private rooms, and entire homes/apartments

**data/airbnb_last_review.tsv**
This is a TSV file containing data on Airbnb host names and review dates.
- **`listing_id`**: unique identifier of listing
- **`host_name`**: name of listing host
- **`last_review`**: date when the listing was last reviewed

## Prerequisites 
  * Python 3.6 or higher [Download_here](https://www.python.org/downloads/)
  * Pandas
  * Numpy

## Steps to complete 
  * Loading the data
  * Merging the three DataFrames
  * Determining the earliest and most recent review dates
  * Finding how many listings are private rooms
  * Finding the average price of listings
  * Creating a DataFrame with the four solution values

## Results/ Findings 
| Column     | Finding              |
|------------|--------------------------|
|`'first_reviewed'`| 2019-01-01|
|`'last_reviewed'`| 2019-07-09|
|`'nb_private_rooms'`| 11356|
|`'avg_price'`| 141.78|
