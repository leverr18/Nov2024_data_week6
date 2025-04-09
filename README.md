# Nov2024_data_week6
Data Bootcamp Week Six API's

Project Overview
This project explores how to leverage weather data and location-based services to identify cities with ideal weather conditions and find nearby hotels using the Geoapify API. The primary goal is to analyze weather data for cities worldwide and create an interactive map that not only visualizes weather patterns but also suggests nearby hotels based on specific weather criteria.

Key Insights
Weather Data: Cities are analyzed based on parameters such as temperature, humidity, and cloudiness, which help identify optimal weather conditions for various preferences.

Hotel Search: The Geoapify API is used to find hotels within 10 kilometers of each city, facilitating the discovery of accommodation options for cities with ideal weather.

Interactive Map: The project culminates in an interactive map where users can hover over cities to view weather details (e.g., humidity) and the name of the nearest hotel, providing real-time insights for potential travelers.

Data Sources
OpenWeatherMap API: Provides real-time weather data, including temperature, humidity, and cloudiness, for cities around the world.

Geoapify API: Used to search for hotels near specific coordinates, providing relevant information such as hotel names and distances.

Features
Weather Filtering: Cities are filtered based on user-defined criteria (e.g., temperature range, humidity level) to showcase cities with the most favorable conditions.

Hotel Search Integration: For each city that matches the weather conditions, the nearest hotel is retrieved using the Geoapify API.

Interactive Visualization: An interactive map is generated with cities plotted based on latitude and longitude, where points vary in size according to humidity levels. Hovering over a point provides key information about the city and the nearest hotel.