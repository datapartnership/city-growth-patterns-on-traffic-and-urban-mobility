<p><center> <img src="images/GOST_Logo_2021.png" width="700"/> </p></center>

# waze-romania
### Using Waze data to better understand mobility issues in Romania.
In this repository, we aggregate traffic data from Waze in Cluj from individual points to hexagons (from 36 km^2 to 0.015km^2 in size) for vizualization and analysis of traffic alerts in the city for the years 2019 until 2022.

## Workflow

1. Read in and clean data from waze: *clean_aggregate.ipynb*
2. Read in and clean spatial data for the city of Cluj: *Shape files.ipynb*
3. Web-scraping and final data manipulation for modeling: *modelling_data.ipynb*
4. Running the final models: *ML.ipynb*
