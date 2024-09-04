# e-Bike-Sharing-App-in-R

In this project, a linear regression model was applied to predict the demand for e-bike sharing services. An interactive R Shiny dashboard was also created to visualize the predictions and enhance user interaction.

## Methodology:

### Data Collection:

-Web Scraping: Extracted data from a Wiki page containing an HTML table of bike-sharing systems, which was converted into a data frame and saved as raw_bike_sharing_systems.csv.

-OpenWeather API: Issued an HTTP request to a live weather API, converted the resulting JSON file into a dataframe, and saved it as cities_weather_forecast.csv.

-IBM Cloud Storage Downloads: Downloaded aggregated datasets from IBM cloud storage, including raw_worldcities.csv and raw_seoul_bike_sharing.csv.

### Data Wrangling: 
Cleaned and transformed the collected data to ensure consistency and suitability for analysis.

### Exploratory Data Analysis (EDA): 
Utilized SQL and data visualization techniques to explore the datasets, identify trends, and uncover key relationships between variables.

### Predictive Analysis: 
Employed linear regression models to predict e-bike demand. The process involved building a baseline model and refining it through feature selection and model tuning.

### R Shiny Dashboard: 
Developed an interactive R Shiny dashboard app to display prediction results and provide users with an intuitive interface for exploring demand forecasts.
