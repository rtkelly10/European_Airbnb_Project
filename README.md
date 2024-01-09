# Airbnb Pricing Dynamics Analysis Project

## Project Premise and Objectives
This project aims to analyze Airbnb pricing dynamics in popular European cities. We delve into various factors shaping rental rates, leveraging a dataset that provides insights into attributes such as room types, cleanliness and satisfaction ratings, person capacity, and distance from the city center. Our goal is to capture a comprehensive understanding of Airbnb pricing trends and their determinants.

## Source of Data
The data is sourced from a wide range of Airbnb listings across several major European cities. This dataset, provided by Airbnb, encompasses diverse listings from various hosts and regions.

[Link to Dataset](https://www.kaggle.com/datasets/thedevastator/airbnb-prices-in-european-cities)

## Data Contents
Each entry in the dataset represents an Airbnb listing, providing information on:

- Room type
- Pricing
- Cleanliness
- Satisfaction ratings
- Location-related attributes

These variables contribute to a holistic understanding of the factors influencing Airbnb prices across European cities.

## Data Limitations and Considerations
The dataset may lack certain critical variables that influence outcomes, such as local events or specific host characteristics. Additionally, its temporal span may limit its ability to capture current market dynamics.

## Guiding Questions
What factors most significantly impact Airbnb rental prices in major European cities?
How do variables like location, room type, and host status interact to influence pricing and guest satisfaction?


## Data Profile
| Variable | Description | Time Variant/Invariant | Structured/Unstructured | Quantitative/Qualitative | Nominal/Ordinal/Discrete/Continuous |
| --- | --- | --- | --- | --- | --- |
| City | Name of the city | Invariant | Structured | Qualitative | Nominal |
| Time of Week | Weekend or weekday | Variant | Structured | Qualitative | Nominal |
| Room Type | Type of room offered | Invariant | Structured | Qualitative | Nominal |
| Room Shared | Whether the room is shared | Invariant | Structured | Qualitative | Nominal |
| Room Private | Whether the room is private | Invariant | Structured | Qualitative | Nominal |
| Person Capacity | Capacity of the room in terms of people | Invariant | Structured | Quantitative | Continuous |
| Multiple Rooms | Availability of multiple rooms | Invariant | Structured | Qualitative | Nominal |
| Business Listing | If it's a business listing | Invariant | Structured | Qualitative | Nominal |
| Number of Bedrooms | Number of bedrooms in the listing | Invariant | Structured | Quantitative | Discrete |
| Total Price | Total price of the listing | Invariant | Structured | Quantitative | Continuous |
| Cleanliness Rating | Cleanliness rating given by guests | Invariant | Structured | Quantitative | Continuous |
| Overall Guest Satisfaction | Overall satisfaction rating by guests | Invariant | Structured | Quantitative | Continuous |
| Distance from City Centre | Distance from the city center | Invariant | Structured | Quantitative | Continuous |
| Distance from Nearest Metro Station | Distance from the nearest metro station | Invariant | Structured | Quantitative | Continuous |
| Attraction Index | Attraction index of the city | Invariant | Structured | Quantitative | Continuous |
| Normalized Attraction Index | Normalized version of the attraction index | Invariant | Structured | Quantitative | Continuous |
| Restaurant Index | Restaurant index of the city | Invariant | Structured | Quantitative | Continuous |
| Normalized Restaurant Index | Normalized version of the restaurant index | Invariant | Structured | Quantitative | Continuous |
| Longitude | Longitude coordinates of the listing | Invariant | Structured | Quantitative | Continuous |
| Latitude | Latitude coordinates of the listing | Invariant | Structured | Quantitative | Continuous |

