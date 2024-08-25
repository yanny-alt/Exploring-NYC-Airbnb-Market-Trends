# Exploring the NYC Airbnb Market

## Introduction
Welcome to New York City, one of the most visited cities in the world. With its high demand for temporary lodging, the NYC Airbnb market offers a rich dataset for exploration. In this project, we aim to analyze various aspects of Airbnb listings to provide insights into the short-term rental market, specifically focusing on private rooms.

## Problem Statement
As a consultant for a real estate start-up, we are tasked with analyzing Airbnb data in New York City to provide insights on private rooms and overall market trends. This analysis will help the company make informed decisions about the short-term rental market.

## Objectives
- Determine the earliest and most recent review dates for Airbnb listings.
- Identify the number of private rooms available.
- Calculate the average listing price.
- Combine the results into a summarized DataFrame.

## Skills Demonstrated / Technologies Used
- **Data Importing:** Handling CSV, TSV, and Excel files.
- **Data Cleaning:** Handling missing values, data type conversions, and data formatting.
- **Data Analysis:** Calculating statistics, aggregating data, and visualizing results.
- **Libraries:** `pandas`, `numpy`, `matplotlib`

## The Data
The data consists of three files in different formats:
1. `airbnb_price.csv`: Contains listing prices and locations.
2. `airbnb_room_type.xlsx`: Contains descriptions and room types.
3. `airbnb_last_review.tsv`: Contains host names and review dates.

You can download the data files from this repository: [Data Folder](./data)

## Project Methodology
1. **Data Importing:** Load data from CSV, TSV, and Excel files into DataFrames.
2. **Data Cleaning:** Prepare data for analysis by handling missing values and converting data types.
3. **Data Analysis:** Perform various analyses to derive insights, including calculating review dates, identifying private rooms, and analyzing price distributions.
4. **Results Aggregation:** Combine results into a summarized DataFrame for comprehensive insights.
5. **Visualization:** Create plots to visualize key findings and trends.

## Results Interpretation

**Review Activity**
The analysis revealed that reviews on Airbnb listings in New York City peaked at 12,000 in June 2019, indicating a high level of activity during that period.

**Average Time Between Reviews**
The average time between reviews is 0.01 days, suggesting very frequent reviews, likely due to multiple reviews being submitted within the same day.

**Private Room Listings**
The dataset shows that 28.72% of the listings are private rooms. The top neighborhoods with the most private room listings are:

- **Brooklyn, Bedford-Stuyvesant**: 717 private rooms
- **Brooklyn, Williamsburg**: 549 private rooms
- **Manhattan, Harlem**: 512 private rooms
- **Brooklyn, Bushwick**: 495 private rooms
- **Manhattan, Hell's Kitchen**: 278 private rooms
- **Manhattan, East Harlem**: 225 private rooms
- **Brooklyn, Crown Heights**: 212 private rooms
- **Manhattan, Upper West Side**: 182 private rooms
- **Manhattan, Washington Heights**: 176 private rooms
- **Queens, Astoria**: 165 private rooms

**Average Price of Private Rooms by Neighborhood**
The neighborhoods with the highest average prices for private rooms are:

- **Queens, Holliswood**: $239.00
- **Manhattan, West Village**: $224.03
- **Queens, Belle Harbor**: $212.50
- **Manhattan, NoHo**: $208.00
- **Queens, Breezy Point**: $195.00
- **Brooklyn, Coney Island**: $192.50
- **Manhattan, Theater District**: $183.51
- **Manhattan, Midtown**: $173.01
- **Manhattan, Financial District**: $160.90
- **Manhattan, Tribeca**: $158.88

**Average Price by Room Type**
- **Entire Home/Apt**: The highest average prices range between $195.88 and $199.58, reflecting the premium cost of booking an entire property, offering more space and privacy.
- **Private Room**: Average prices for "Private room" range around $80 to $82, indicating a budget-friendly option compared to an entire home.
- **Shared Room**: The lowest average prices, ranging from $52.90 to $54.61, are found in shared rooms, which are the most economical choice.

**Top 10 Most Expensive Neighborhoods**
- **Brooklyn, Sea Gate**: $805.00
- **Manhattan, Tribeca**: $396.70
- **Manhattan, Flatiron District**: $342.06
- **Manhattan, NoHo**: $335.02
- **Manhattan, SoHo**: $299.16
- **Queens, Neponsit**: $274.67
- **Manhattan, Midtown**: $272.21
- **Manhattan, West Village**: $258.76
- **Staten Island, Willowbrook**: $249.00
- **Manhattan, Murray Hill**: $240.37

**Neighborhood Summary**
- **Bronx, Allerton**: 30 total listings, 11 private rooms, average price $98.93, earliest review date January 01, 2019, most recent review date May 12, 2019.
- **Bronx, Baychester**: 5 total listings, 0 private rooms, average price $78.60, earliest review date July 01, 2019, most recent review date June 30, 2019.
- **Bronx, Belmont**: 16 total listings, 6 private rooms, average price $91.88, earliest review date July 01, 2019, most recent review date May 19, 2019.
- **Bronx, Bronxdale**: 10 total listings, 3 private rooms, average price $53.60, earliest review date July 05, 2019, most recent review date May 23, 2019.
- **Bronx, Castle Hill**: 2 total listings, 0 private rooms, average price $74.00, earliest review date June 10, 2019, most recent review date June 23, 2019.

**Price Correlation**
The correlation analysis showed a perfect positive correlation for price (corr = 1.0), confirming that price is a consistent metric across the dataset.

## Conclusion
This analysis provides valuable insights into the NYC Airbnb market, focusing on private rooms. The data reveals trends in pricing, review dates, and room distribution across neighborhoods, which can help the real estate start-up make informed decisions about their rental strategies.

## Future Recommendations / Moving Forward
- Explore the impact of location on pricing by analyzing neighborhood data.
- Investigate trends over time by comparing data from multiple years.
- Consider sentiment analysis on reviews to understand guest satisfaction.

## Contact
For any questions or feedback, please contact me at thefavourokechukwu@example.com.
