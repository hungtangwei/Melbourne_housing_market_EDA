# Melbourne_housing_market_EDA
Exploratory data analysis of Melbourne housing market

Melbourne, Australia’s second-biggest city and world’s most liveable city, attracts tourists, students, immigrant, and investors such as real estate investors etc. from all over the world. Therefore, a lot of people want to live and settle down in Melbourne and it will cause the booming of market for real estate in Melbourne.

In this report, I will try to explore the trend of the housing market in Melbourne and to find the relationship between features and the home prices in the Melbourne housing market from 2016 to 2018. Here are three main parts we will focus on. The first part is the suburb vs. price. The second is the price trend in Melbourne housing market from 2016 to 2018. The final part is whether the distance to CBD, distance to nearest train station, and average travel time to CBD (southern cross station) will affect the price of real estate.

## Analysis code

Key elements of the analysis code are as follows:
- *Wrangling.ipynb* - a Python script used to wrangling the data. In this script, delete the null data and calculate some features, such as the travel time from house to CBD from original data and then ouput the file as housing_final.csv.
- *EDA.ipynb* - an R script used to do the exploratory data analysis task.
- *VIC_LOCALITY_POLYGON_shp* – The VIC Suburb/Locality Boundaries.
- *housing_final.csv* - a csv file containing the housing market information from 2016 to 2018 in Victoria.

## Other resources

Several resources proved invaluable when building this app, including:
- 1. Melbourne Housing Data from 2016 to 2018 (34858 rows x 21columns) (URL: https://www.kaggle.com/anthonypino/melbourne-housing-market)
- 2. Victoria crime incident data from 2009 to 2018(284098 rows x 7 columns) (URL: https://www.crimestatistics.vic.gov.au/crime-statistics/historical-crime-data/year-ending-31-december-2018/download-data)
- 3. PTV timetable and Geographic Information (GTFS format)
(URL: https://discover.data.vic.gov.au/dataset/ptv-timetable-and-geographic-information-2015-gtfs)
- 4. Victoria State Boundary (shapefile)
(URL: https://data.gov.au/data/dataset/vic-suburb-locality-boundaries-psma-administrative-boundaries/resource/4d6ec8bb-1039-4fef-aa58-6a14438f29b1)

## Authors

Tangwei, Hung

## Contact
hung.tangwei@gmail.com
