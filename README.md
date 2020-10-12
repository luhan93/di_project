I downloaded the LA foreclosure datasets from 2017 to 2020. 
I merged the four dataframes and extracted the longitude and latitude. 
Since the formats are slighly different among the four datasets, I had to swap the latitude and longitude for part of the data. 
Then I grouped the data by zip code and time to generate the two plots.

Fig. 1: Total number of foreclosures across LA 2017-2020. The data here are grouped by zipcode. Multiple factors 
(e.g. population, average salary, unemplyment rate, crime, etc) could contribute to the regional difference of foreclosures, 
which provide some guidance to further pursue this project.
The figure is an interactive map saved as "Total_Number_of_Foreclosure_map.html"

Fig 2: Number of foreclosures in LA in different months from 2017 to 2020. In Jan ~ April, the number of foreclosures are much higher in 2020 compared to the other three years, suggesting Covid-19 could be another important factor. However, in May ~ September, the number of foreclosures are slightly lower in 2020 compared to the earlier years, possibly due to the CARES Act Mortgage Forbearance. This suggests that policy impact on housing market should also be considered. The figure is saved as "foreclosures_each_year.png".

The notebook is saved in both ipynb and html.
