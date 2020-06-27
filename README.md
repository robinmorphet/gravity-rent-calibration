# Rproject Gravity model calibration by rent

### About
This repository contains the method for analysis used for the CASA Working Paper "Gravity model calibration by rent". Please reference this published version whenever possible using the reference "Morphet, R. and Shabrina, Z., 2020. Gravity Model Calibration by Rent. CASA Working Paper 223".

The analysis is carried out using a set of data as follows:
#### Data:
##### 1. base_destination_data.csv
Airbnb data aggregated to Lower Super Output Area (LSOA) level (2018 - from Inside Airbnb http://insideairbnb.com) as "origins"
##### 2. sorted_base_origin_data.csv
Number of visits to tourists attraction points (from Visit Britain 2015 https://www.visitbritain.org/annual-survey-visits-visitor-attractions-archive) as "destinations"
##### 3. trip_cost_matrix_stripped.csv
Travel time data calculated by generating travel time between the origins centroid and the destinations points using Open Trip Planner application as "trip costs"

To run the R code in RStudio you will need to load the R packages 'here' and 'rlist'


