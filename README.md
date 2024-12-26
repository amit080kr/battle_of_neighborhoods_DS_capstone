# Battle of Neighborhood: A Data Science Approach

## Overview

This project aims to help individuals and families relocating from Padova/Padua, Italy to Las Vegas, USA, find suitable neighborhoods and homes that match their lifestyle preferences. The solution leverages geospatial data and real estate listings to identify areas in Las Vegas with similar venues, including parks, shopping venues, and theaters, while considering housing and school needs.

## Problem Statement

The goal is to find a suitable location in Las Vegas with the following criteria:

Venues: Similar venues to those in Padova (parks for children, shopping venues for the family, and theatres).
Housing: A single house with at least:
2 bedrooms
2 bathrooms
Garage
Garden with swimming pool
No HOA fees
Built after 2009
Budget of $500k
Schools: Nearby primary, middle, and high schools.
Proximity to Job: Maximum distance of 10 miles from Caesars Palace Casino (job location in Las Vegas).

## Potential Audience

Relocating Families: People planning to move to Las Vegas from other cities, either within the same country or internationally.
Businesses: Organizations evaluating potential relocation for employees based on their lifestyle needs.
Real Estate Evaluators: For individuals or businesses considering new business opportunities in different areas.
Data Science Enthusiasts: Anyone interested in using data science to solve real-world problems like relocation or venue matching.

## Key Features

Geospatial Analysis: Using Nominatim, Geocode, and Foursquare to gather venue and neighborhood data for both Padova and Las Vegas, including surrounding cities and Census-designated places.
Real Estate Listings: Integration with Zillow and other APIs to gather housing data for the Las Vegas area, including specific features like price, size, and amenities.
Visualization: Using Folium for visualizing neighborhood venues and available real estate options in Las Vegas.

## Data Sources

Padova/Padua: Geospatial data from Nominatim, Geocode, Foursquare, and Folium.
Las Vegas Area: Geospatial data from Wikipedia, Nominatim, Geocode, Foursquare, and Folium, covering the main city and surrounding areas like North Las Vegas, Henderson, Enterprise, etc.
Real Estate Listings: Data from Zillow, Nominatim, Geocode, and Folium for house listings that match the specified criteria.
