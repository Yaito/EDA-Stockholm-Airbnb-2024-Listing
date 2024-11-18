
## Title
Stockholm Airbnb 2024 Listing Exploratory Data Analysis (EDA)

## Overview
For this EDA we picked Stockholms 2024 listing to review and analyze, and the results showed that this region in 2024 had around **5400** listed properties, with a median price of **1300 USD**, varying between different neighbourhoods and property types (entire unit, single private rooms, shared rooms, hotel rooms, others). 

Within the listed properties **entire rental units** covered **50%** of all the listings, additionally there are private rooms, shared rooms and hotel rooms options. The latter group being more budget friendly in exchange for some level of privacy cost. Some of the neighbourhoods with the most listed properties are **Södermalms** and **Norrmalms** covering **around 36%**, with an **estimated annual median occupancy rate of around 79%**, indicating high demand for rental, another popular neighbourhood is **Skarpnäcks**, with only around **280-300 listed properties** covering about **5.3%**, but with an impressive **estimated annual median ocupancy rate of around 84%**. Additionally, the reviews are generally very positive with a median of **4.8 out of 5.0**. 

Overall, the analysis provides a comprehensive overview of the Stockholm Airbnb market in 2024, highlighting key trends, insights, and opportunities for both hosts and visitors. These insights can be valuable resources for understanding the dynamics of the short-term rental market in Stockholm and can contribute to informed decision-making for stakeholders involved in the Airbnb ecosystem or for local goverments to tackle tourism or housing. 


## Data Understanding
The dataset is originally from [**Inside Airbnb**](https://insideairbnb.com/about/),a project that provides data and advocacy about Airbnb's impact on residential communities, and allows interested parties to analyze and lookout for trends for different markets in which Airbnb operates. The dataset contains Airbnb's listings from Stockholm in 2024, containing 5400 records and 75 columns, with information regarding the property, the host, and the avaialability across different period of time.

## Data Insights
###  Pricing and Accomodation Types

* Stockholm´s Airbnb listings from 2024 exhibit a wide price range, from budget-friendly options to extremely expensive ones. The median price is around **1300 USD**, with a positively skewed distribution due to high-priced outliers.
* The most popular types of listings are entire homes/apartments, followed by private rooms. These also tend to be the more expensive options. 
* The price seems to be strongly influenced by the type of accommodation.

###  Neighbourhood Popularity

* **Södermalms** and **Norrmalms** are the most popular neighbourhoods with a high number of listings, suggesting high demand in these areas.
* **Skarpnäcks** also has a very high occupancy rate despite having fewer listings, indicating strong demand.

###  Review Scores & Customer Satisfaction
* Airbnb listings in Stockholm have generally high review scores, with most properties receiving a **4.5-5.0** rating.
* This suggests that overall, the properties and services provided by Airbnb hosts in Stockholm are highly satisfactory to guests.

### Correlation & Influencing Factors
* There is a strong correlation between the number of people a property can accommodate and its price, particularly after removing price outliers. This suggests that larger properties often command higher prices.
* Accommodates and bedrooms are highly correlated with price, indicating that size and number of rooms play a major role in determining price. 

### Occupancy & Availability
* The overall estimated annual occupancy rate for Stockholm Airbnb listings is **around 64.67%**.
* There are significant variations in occupancy rates across different neighbourhoods, likely due to varying levels of demand and attractiveness.
* Skarpnäcks has a very high occupancy rate (around 84%), while Skärholmens has a relatively low occupancy rate (around 49%).

## Insights for Potential Hosts and Visitors 

* **Hosts:** Understanding the popularity of different neighbourhoods and property types can be valuable for maximizing occupancy rates and setting competitive prices. 
* **Visitors:** The analysis provides insights into average prices, popular neighbourhoods, and available accommodation types, which can help them make informed decisions when planning their trips.

## Further Exploration

* **Seasonality:** Investigating how prices and occupancy rates change seasonally could provide more granular insights.
* **Amenities:** Analyzing the correlation between different amenities and prices would help understand what features contribute to higher value properties.
