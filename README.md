# Exploring HDB Resale Prices 

## Introduction
Welcome to our repository!

Our web application serves as a comprehensive resource for all prospective buyers of resale flats and elderly residents seeking financial solutions through downsizing or the Lease Buyback Scheme offered by the Housing & Development Board (HDB). Whether you're navigating the resale market or exploring options to maximize savings, our platform offers essential guidance and tools to streamline your decision-making process. From understanding resale flat dynamics to evaluating the benefits of downsizing or participating in the Lease Buyback Scheme, our one-stop hub empowers users with the data and insights they need to make informed choices tailored to their housing and retirement goals.

## How can you access our RShiny Application?
**1. Download the data files**
* Visit our Google Drive to access all data files required for our application.
https://drive.google.com/drive/folders/1rVIPNjGgv1XRqYiTPv0tMLv75ieVhhzr?usp=sharing

Note: Most data files are uploaded in /data except for model_bagging_9.rds and resale_prices.csv.

**2. Access our application code file under /frontend in the main branch.**
* Download the code file and save it in the same directory as the data files.

**3. Run the application on your local system using RStudio.**
* Ensure that you have the required packages installed.
The packages required are: shiny, plotly, dplyr, shinyWidgets, tidyverse, sf, leaflet, RColorBrewer, stringr, DT, bslib, shinythemes, fastDummies, ipred.

* Run the application code file in your RStudio. 


## Data Sources:
1. Resale HDB data: data.gov.sg <br>
Data wrangling is conducted to obtain the summarised dataset ("resale_prices.csv") for HDB Resale data from 2010 to 2024.


## References: 
* Kaplan, J. & Schlegel, B. (2023). fastDummies: Fast Creation of Dummy (Binary) Columns and Rows from Categorical Variables. Version 1.7.1. URL: https://github.com/jacobkap/fastDummies, https://jacobkap.github.io/fastDummies/.
* (2023).HDB Image [Photograph]. Gov.sg. 

