# tableau

Note 2019 and 2020 CSV files from Citi Bike Data too large to upload.

## Analysis

Tableau Public Link: 
https://public.tableau.com/views/CitiBikesWorkbook/Story1?:language=en&:display_count=y&publish=yes&:origin=viz_share_link 

For this assignment, two unexpected trends were explored: trips and ridership across a three-year period (2018 to 2019) and trends by generation (Post-War, Boomers, Gen X, Millennial, and Gen Z). Data were downloaded from the Citi Bike data webpage for four months for each of the three years: January, April, July, and October. These data were aggregated using Python/Pandas. The first approach involved exploring individual-level data, which resulted in over 2 million rows. After further exploration, six Pandas DataFrames were created and exported to CSVs to be loaded into Tableau. These resulted in nine total visualizations that were included across three dashboards and one story. 

The main variables for analysis were year (an added column to each table), trip duration, start and end location, start and end latitude/longitude, gender, user type, and generation. Generations were calculated by individual-level birth years. The resulting visualizations are:

    Total number of trips by generation (line and area graphs)
    Average trips per year by generation
    Average and maximum trip per year by generation
    Starting locations map
    Ending locations map
    User type information (subscriber vs. customer)
    Generation information
    Gender information

The three dashboards and their main findings illustrated are:

Generational Trends

    Interestingly, despite the COVID-19 pandemic taking place in 2020, maximum trip duration increased from 2018 to 2020 pretty steadily. This may be due to users keeping bikes longer than normal for personal use due to fear or sharing or giving up transport. As expected, average trip duration decreased across generations from 2018- 2020, with the exception of Gen Z users. That generation took longer trips in 2020 than in 2019.
    Gen Z users saw the greatest drop in trip duration between 2018-2019. All other users slightly increased throughout the time period.
    Millennials and Gen Xers took the most trips, while Gen Z users took among the fewest- despite being the group taking the consistently longest trips. This may be due to the fact that younger people are less likely to have their own transportation or the means for more expensive forms of transportation. 
    Yearly Demographics and Trends
    Both types of users (subscribers, users with a paid plan with Citi Bike, or customers, pay per ride users) greatly increased between 2018 and 2019, with 2020 seeing a drop in both types. This is likely due to the COVID-19 pandemic, and an increase in the percentage of Customers is an interesting trend here.
    Gen Z users grew the most in the 3-year period, indicating an increasing trend among younger users. This was true despite the COVID-19 pandemic and might be explained by a decreased desire to use public transportation such as the subway, cabs, or rideshare services.
    Male users increased at the highest rate between 2018 and 2019. All users decreased in 2020, likely due to the COVID-19 pandemic, with male users dropping at the highest rate.

Maps

    The Start Station map is based on Start Station Longitude and Start Station Latitude. Map coloring shows Male/Female Ratio by Zip Code. The map can be filtered by Year (2018-2020). The number of Start Stations increased across all 3 years but most significantly between 2018 and 2019. Zip codes with relatively equal Male/Female ratios had the most Start Stations.
    The End Station map is based on End Station Longitude and End Station Latitude. Map coloring shows Male/Female Ratio by Zip Code. The map can be filtered by Year (2018-2020). The number of End Stations increased across all 3 years but most significantly between 2018 and 2019. Zip codes with relatively equal Male/Female ratios had the most End Stations.

The story board illustrates the number of trips taken between 2018-2020 by generation. The key points are:

    In 2018, Millennials took more trips than other generations, followed by Gen Xers and then Boomers. Gen Zers and Post War users took the fewest trips- under 500 each.
    By 2019, overall trips grew exponentially: Millennial ridership grew by a 5,199%, Boomers by 7,155.6%, Gen X by 5,979%, Post War by 19,389%, and Gen Z ridership grew by a whopping 60,657.7%.
    In 2020,overall trips declined, likely due to the onset of the COVID-19 pandemic. However, despite the rates of decline, the period still ended with significantly higher ridership overall compared to 2018. 
