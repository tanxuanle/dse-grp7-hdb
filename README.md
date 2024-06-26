# Exploring HDB Resale Prices 

## Introduction
Welcome to our repository!

Our web application serves as a comprehensive resource for all prospective buyers of resale flats and elderly residents seeking financial solutions through downsizing or the Lease Buyback Scheme offered by the Housing & Development Board (HDB). Whether you're navigating the resale market or exploring options to maximize savings, our platform offers essential guidance and tools to streamline your decision-making process. From understanding resale flat dynamics to evaluating the benefits of downsizing or participating in the Lease Buyback Scheme, our one-stop hub empowers users with the data and insights they need to make informed choices tailored to their housing and retirement goals.

## How can you access our RShiny Application?
**1. Download the data files**
* Visit our Google Drive to access the app.R file and all other data files required for our application.
https://drive.google.com/drive/folders/1rVIPNjGgv1XRqYiTPv0tMLv75ieVhhzr?usp=sharing

**2. Save all downloaded files in the same directory.**

**3. Run the application app.R on your local system using RStudio.**
* Ensure that you have the required packages installed.
The packages required are: shiny, plotly, dplyr, shinyWidgets, tidyverse, sf, leaflet, RColorBrewer, stringr, DT, bslib, shinythemes, fastDummies, ipred.

* Run the application code file in your RStudio.

## Repository Structure
* /backend → Files used for data handling and modelling
  * best-model → File for the final selected model (bagging)
  * data-manipulation → File on how data was tidied and used
  * model-building-selection → File on training and testing of other models
* /data → Raw datasets used before data cleaning manipulation
* /frontend → File for our Rshiny application
* README.md → Contains instructions on downloading and running our application.

## Data Sources:
1. Resale HDB data: data.gov.sg <br>
https://beta.data.gov.sg/collections/189/datasets/d_ebc5ab87086db484f88045b47411ebc5/view <br> 
Data wrangling is conducted to obtain the summarised dataset ("resale_prices.csv") for HDB Resale data from 2010 to 2024.

2. Master Plan 2019 Subzone Boundary (No Sea): data.gov.sg <br>
https://beta.data.gov.sg/collections/1749/datasets/d_8594ae9ff96d0c708bc2af633048edfb/view

3. Sample Household Survey: HDB Resident Population by Geographical Distribution: data.gov.sg <br>
https://beta.data.gov.sg/collections/179/datasets/d_0a6c6d71f6fa14e2d27e406f1d018439/view

4. Average and Median Monthly Household Income from Work Among Resident and Resident Employed Households: singstat.gov.sg 
https://tablebuilder.singstat.gov.sg/table/CT/17870#!

6. Hawker Centres: nea.gov.sg <br>
https://www.nea.gov.sg/docs/default-source/hawker-centres-documents/list-of-hcs_28-sep-2023.pdf

7. General information of schools: data.gov.sg <br> 
https://beta.data.gov.sg/datasets/d_688b934f82c1059ed0a6993d2a829089/view 

8. Supermarkets: data.gov.sg <br> 
https://beta.data.gov.sg/datasets/d_11edd0117280c5776651d7891114c88c/view

9. Shopping Malls: wikipedia.org <br> 
https://en.wikipedia.org/wiki/List_of_shopping_malls_in_Singapore

10. Hospitals and Polyclinics: wikipedia.org <br> 
https://en.wikipedia.org/wiki/List_of_hospitals_in_Singapore 

11. Parks: data.gov.sg <br> 
https://beta.data.gov.sg/collections/1491/datasets/d_e7289d9a50e45bf1174590e184e6631c/view 

12. Buses: wikipedia.org <br> 
https://en.wikipedia.org/wiki/List_of_bus_routes_in_Singapore

13. MRT and LRT: mrtmapsingapore.com <br> 
MRT: https://mrtmapsingapore.com/mrt-stations-singapore/ <br> 
LRT:  https://mrtmapsingapore.com/lrt-stations/ 


## References: 
* Kaplan, J. & Schlegel, B. (2023). fastDummies: Fast Creation of Dummy (Binary) Columns and Rows from Categorical Variables. Version 1.7.1. URL: https://github.com/jacobkap/fastDummies, https://jacobkap.github.io/fastDummies/.
* (2023).HDB Image [Photograph]. Gov.sg. 

