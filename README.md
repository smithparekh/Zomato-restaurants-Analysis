##Zomato_Insights_Dashboard

This dataset and dashboard provide insights into restaurant data from Zomato across various countries and cities, with details on restaurant characteristics, cuisine types, and geographic locations. The Power BI dashboard (Zomato_Insights_Dashboard.pbix) visualizes this data to facilitate analysis of restaurant trends, geographical distributions, and popular cuisines.

Files
zomato_data.xlsx: Contains raw data about restaurants, including detailed attributes such as location, cuisines, and opening dates.
Zomato_Insights_Dashboard.pbix: A Power BI dashboard that visualizes the data for analytical purposes.
Data Dictionary
The Excel file contains two sheets:

Sheet1: Main restaurant data with the following columns:

RestaurantID: Unique identifier for each restaurant.
RestaurantName: Name of the restaurant.
CountryCode: Code representing the restaurant's country, corresponding to countryID in Sheet2.
City, Address, Locality, LocalityVerbose: Details of the restaurant's location.
Longitude, Latitude: Geographic coordinates of the restaurant.
Cuisines: Primary cuisine offered by the restaurant.
Additional columns for up to eight specific cuisines (Cuisines 1 through Cuisines 8).
Datekey_Opening: Date the restaurant opened.
Other metadata fields related to ratings, votes, and restaurant attributes.
Sheet2: Country reference data with the following columns:

countryID: Code representing the country.
country name: Name of the country.
Dashboard Insights
The Power BI dashboard visualizes the restaurant data across multiple dimensions, including:

Geographical Analysis: Maps showing restaurant distribution across cities and countries.
Cuisines Popularity: Analysis of popular cuisines in different regions.
Restaurant Details: Filters to view specific restaurant characteristics, such as opening dates, ratings, and types of cuisines.
Usage Instructions
Excel Data: This file can be used for direct data analysis in Excel or can be imported into BI tools for more advanced analytics.
Power BI Dashboard: Load the Zomato_Insights_Dashboard.pbix file in Power BI Desktop to view and interact with the visualizations.
