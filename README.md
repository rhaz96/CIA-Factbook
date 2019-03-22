# Analyzing CIA Factbook Data

![Alt text](https://www.cia.gov/portlet_content/home-slider-images/WFBslider2016.jpg/image.jpg)

This is an examination of 2015 CIA statistics about all the countries on Earth.  The data dictionary for relevant columns is below.

* ```name``` - The name of the country
* ```area``` - The total land and sea area of the country
* ```area_land``` - The country's land area in square kilometers
* ```area_water``` - The country's water area in square kilometers
* ```population``` - The country's population as of 2015
* ```population_growth``` - The country's population growth as a percentage
* ```birth_rate``` - The country's birth rate, or the number of births a year per 1,000 people
* ```death_rate``` - The country's death rate, or the number of death a year per 1,000 people

The data's source can be found in this [repo](https://github.com/factbook/factbook.sql/releases).

This exploratory data analysis is done in R, and it demonstrates (among other things) that the CIA is no less dirty in their datasets.  

The actual dataset is a .db file, so it's meant to be analyzed in SQL. However, R has wonderful extensions to popular databases like SQLite and Postgres.  Tables can be converted to data frames to take advantage of the ```dplyr``` package, as well as R's functionality in general.  We don't have to be confined to SQL's analytical and syntactical limitations.

The packages in the ```tidyverse``` package are used, and can be found in the final report.  For more information on integrating R with SQL, check out *Data Carpentry*'s article [here](https://datacarpentry.org/R-ecology-lesson/05-r-and-databases.html).
