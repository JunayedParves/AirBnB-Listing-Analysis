# AirBnB-Listing-Analysis
Welcome to the Airbnb Data Analysis project focusing on Paris listings! In this project, I explore a comprehensive dataset containing information on 250,000+ Airbnb listings across 10 major cities, coupled with approximately 5 million guest reviews. The primary goal is to derive meaningful insights and create visualizations related to Paris listings.

# Objective
 1. Data Cleaning and Profiling:
    - Import the Listings.csv file.
    - Convert date columns to datetime format.
    - Filter data to include only Paris listings, retaining essential columns: 'host_since', 'neighborhood', 'city', 'accommodates', and 'price'.
    - Perform quality assurance by checking for missing values and calculating basic statistics (minimum, maximum, average) for numeric fields.

2. Data Aggregation for Visualization:
    - Create a table named paris_listings_neighbourhood grouping Paris listings by 'neighborhood' and calculating the mean price (sorted low to high).
    - Create a table named paris_listings_accommodations for the most expensive neighborhood, grouping by the 'accommodations' column and adding the mean price for each 'accommodates' value (sorted low to high).
    - Build a table named paris_listings_over_time grouped by the 'host_since' year, calculating the average price and count of new hosts.

3. Visualization:
    - Develop a horizontal bar chart depicting the average price by neighborhood in Paris, ensuring clear titles and appropriate axis labels.
    - Construct another horizontal bar chart illustrating the average price by 'accommodates' in Paris' most expensive neighborhood, with informative titles and axis labels.
    - Create two line charts representing the count of new hosts over time and the average price, both with y-axis limits set to 0 and clear titles and axis labels.
    - Investigate the impact of 2015 regulations on new hosts and prices, presenting insights.
    - Build a dual-axis line chart to showcase both new hosts and average price trends over time.

# Conclusion:
This project aims to provide a comprehensive analysis of Airbnb listings in Paris, offering valuable insights into pricing trends, accommodation preferences, and the impact of regulatory changes in 2015. Through meticulous data cleaning, aggregation, and visualization, we hope to unravel patterns and contribute to a deeper understanding of the Parisian Airbnb market.

Feel free to explore the Jupyter notebook provided to dive into the code and visualize the results!
