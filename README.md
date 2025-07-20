# Crime_analysis_eMindGuard
Small project undertaken for the eMindGuard project to analyze and visualize crime data across the City of Chicago for the application


**Strong** __Project Aim:__ Analyze crime data from the Chicago Crime Data Portal from October 1, 2024, to November 14, 2024.

Focus area: Six major crime types:
ROBBERY, HOMICIDE, CRIMINAL SEXUAL ASSAULT, BURGLARY, MOTOR VEHICLE THEFT, ASSAULT


**Strong** __Data Processing Techniques:__
  - Normalization
  - Principal Component Analysis (PCA)
    
Key Outcome: Visualized crime distribution across Chicago neighborhoods.


**Strong** __Methodology:__
1. Data Preprocessing: Datetime formats, null value and empty row removal, and data type adjustment
2. Geolocation and Zip Codes: Geocoding API to retrieve Census-tracts based on latitude and longitude, FIPS to census tracts for GeoID
3. Data Analysis: Normalized crime frequencies using Min-Max normalization, (PCA) to summarize crime data into a single normalized value
4. Visualization: Heatmap (Choropleth map) using GeoPandas to visualize normalized summary values across census tracts





Plan to integrate findings into the eMindguard project for:
- Enhancing community awareness.
- Supporting informed decision-making.


Heatmap:

![alt text](https://github.com/SayeVikram/Crime_analysis_eMindGuard/blob/main/heatmap.png "Heatmap of crime rates in Chicago")


Sample Frequencies for 3 census tracts:

![alt text](https://github.com/SayeVikram/Crime_analysis_eMindGuard/blob/main/freqs.png "Sample Frequencies for 3 census tracts")



References: 
1. Department, C. P . (2022, January 10). Crimes - 2022: City of chicago: Data Portal. Chicago Data Portal. https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2

