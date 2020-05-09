# Data

## Airbnb Open Data

The Airbnb open data include listings, reviews and calendar. The Airbnb listing data including listing geological information, housing condition, pricing and customer review for each listing data, are scraped from [Inside Airbnb](http://insideairbnb.com/get-the-data.html). There are 51097 rows of listings in NYC and 38851 in LA scraped by February 13th, 2020 (before COVID-19 widely recognized). The reviews data includes detailed contents, customer id and related listing information. The calendar data consists of the prices and maximum and minimum nights to stay for each listing throughout the year.

## Census Data

For further research, we collect census data for a better conclusion of how some major social components will influence the pricing of Airbnb. For the income and education indicators, we collect income per capita and percentage of population over 25 years old with education over high school in each zip code of NYC in 2018 from [U.S. Census ACS](https://www.census.gov/programs-surveys/acs/), and collect median household income and calculate percentage of population over 25 years old with education over high school in each council district of LA in 2018 from [Los Angeles Office of the Controller](https://controllerdata.lacity.org/Statistics/Economy-Panel-LA-Data/4ndk-mmc8/data). For the crime indicator, we calculate the counts of arrests in 2019 in each zip code of NYC and LA based on the arrest data from [New York Police Department (NYPD)](https://data.cityofnewyork.us/Public-Safety/NYPD-Arrests-Data-Historic-/8h9b-rp9u) and [Los Angeles Police Department (LAPD)](https://data.lacity.org/A-Safe-City/Arrest-data-2016-present/sniz-4n2f).

## Spatial Data

To involve neighborhood indicators in the correlation analysis, boundaries of zip codes of New York City and Los Angeles from [U.S. Census](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html) and council districts of Los Angeles from [the Bureau of Engineering](https://data.lacity.org/A-Well-Run-City/Council-Districts/5v3h-vptv) are collected. 

## Others

We also use US federal holidays data from 2011 to 20208 from [the U.S. Office of Personnel Management (OPM)](https://data.world/sudipta/us-federal-holidays-2011-2020) for time series analysis.
