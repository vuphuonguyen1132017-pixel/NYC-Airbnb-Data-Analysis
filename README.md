# NYC-Airbnb-Data-Analysis
Data analysis of NYC Airbnb listings using Pythion, Pandas, SQL, and Matplotlib.

## Overview
This project analyzes Airbnb listings in New York City using Python and SQL to uncover pricing trends, borough-level differences, and room type popularity.

## Tools Used
- Python, Pandas, Matplotlib
- SQL (SQLite) - including GROUP BY, aggregate functions, and window functions (RANK)

## Dataset
New York City Airbnb Open Data (Kaggle, 2019) - 48,895 listings.

## Main Questions
1. Which borough has the most Airbnb listings?
2. What is the average price by borough?
3. Which room type is most common and most expensive?
4. Which neighborhood has the highest average price within each borough?

## Key Findings
1. Manhattan and Brooklyn dominate the NYC Airbnb market, accounting for nearly 85% of all listings (21,643 and 20,089 listings respectively).

2. Manhattan has the highest average price (USD 196.90 night), more than double that of the Bronx (USD 87.47 night).

3. Entire home/apt is both the most common (25,393 listings) and most expensive room type (USD 211.81/night on average), while Shared rooms are the least common and cheapest (USD 70.08/night).

4. Borough-level averages can hide extreme outliers at the neighborhood level: while Stalen Island has the lowest average price in the entire city (USD 800/night), even surpassing Manhattan's Tribeca (USD 490.64/night).

## Conclusion
This analysis of NYC Airbnb listings reveals a market heavily concentrated in Manhattan and Brooklyn, with clear pricing differences driven by both borough location and room type. While Manhattan has the highest average price overall, a closer look at the neighborhood level reveals that Fort Wadsworth in Stalen Island has the highest average listing price in the dataset. This demonstrates that borough-level averages do not always reflect local market conditions. Combining SQL queries, including the RANK() window function, with pandas made it possible to identify these patterns and gain more detailed insights into the data
