# Chicago-Public-Libraries-Data-Analysis
<img src="CPL-Logo.jpg" alt="CPL Logo" width="350" height="200">

This project provides an in-depth analysis of public libraries in the city of Chicago. It uses public data available through the City of Chicago Data Portal to perform an investigation into the distribution of libraries across the city and their usage patterns.

## Data Source
The data used in this analysis comes from multiple datasets available through the City of Chicago Data Portal:

1. [Libraries - Locations, Contact Information, and Usual Hours of Operation](https://data.cityofchicago.org/Education/Libraries-Locations-Contact-Information-and-Usual-/x8fc-8rcq): This data set provides detailed information about each library in the city of Chicago, including its name, hours of operation, address, and geographical location.

2. [Boundaries - Community Areas (current)](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Community-Areas-current-/cauq-8yn6): This data set provides geographical boundaries of different community areas in the city of Chicago.

3. Visitor count data for each library for the years 2011 to 2023:
    - [2011](https://data.cityofchicago.org/Education/Libraries-2011-Visitors-by-Location/xxwy-zyzu)
    - [2012](https://data.cityofchicago.org/Education/Libraries-2012-Visitors-by-Location/zh3n-jtnt)
    - [2013](https://data.cityofchicago.org/Education/Libraries-2013-Visitors-by-Location/x74m-smqb)
    - [2014](https://data.cityofchicago.org/Education/Libraries-2014-Visitors-by-Location/si8n-dg3u)
    - [2015](https://data.cityofchicago.org/dataset/Libraries-2015-Visitors-by-Location/7imc-umy4)
    - [2016](https://data.cityofchicago.org/dataset/Libraries-2016-Visitors-by-Location/cpc6-pxmp)
    - [2017](https://data.cityofchicago.org/dataset/Libraries-2017-Visitors-by-Location/bk6j-nu5x)
    - [2018](https://data.cityofchicago.org/dataset/Libraries-2018-Visitors-by-Location/i7zz-iiza)
    - [2019](https://data.cityofchicago.org/dataset/Libraries-2019-Visitors-by-Location/sw6v-npyj)
    - [2020](https://data.cityofchicago.org/Education/Libraries-2020-Visitors-by-Location/pb9h-bnh4)
    - [2021](https://data.cityofchicago.org/Education/Libraries-2021-Visitors-by-Location/8i46-4b7w)
    - [2022](https://data.cityofchicago.org/Education/Libraries-2022-Visitors-by-Location/ykhx-yxn9)
    - [2023](https://data.cityofchicago.org/Education/Libraries-2023-Visitors-by-Location/74j2-zzz4)

These data sets were used to analyze the spatial distribution of libraries across the city and to investigate the usage patterns of the libraries over time.

## Analysis
The analysis is divided into several sections:

1. **Spatial Analysis**: This section investigates the spatial distribution of libraries across the city of Chicago. This is achieved by using the Python library `folium` to generate interactive maps. The maps help visualize the density of libraries across different regions.

2. **Usage Patterns**: This section investigates the usage patterns of the libraries, focusing on the number of monthly visitors. The analysis visualizes the visitor count over the years and identifies any significant trends or patterns.

3. **Statistical Testing**: In this section, a hypothesis test (specifically, Welch's t-test) is performed to assess whether the observed decrease in visitor count after 2020 is statistically significant. The t-test compares the mean visitor count before and after 2020. The null hypothesis is that the means are equal, while the alternative hypothesis is that the mean visitor count after 2020 is lower. The analysis includes checks for the assumptions of the t-test, such as the normality of the data and the equality of variances.

## Libraries Used
The analysis utilizes the following Python libraries and packages:

- `folium`: For generating interactive maps.
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical computations.
- `geopandas`: For working with geospatial data.
- `matplotlib`: For data visualization.
- `seaborn`: For enhanced data visualization.
- `statsmodels`: For statistical analysis and modeling.
- `scipy`: For scientific computing and statistical testing.
- `geopy`: For geocoding and distance calculations.
- `shapely`: For geometric operations on geometries.
- `pandas_profiling`: For generating descriptive statistics and visualizations for pandas dataframe.
- `sklearn`: For machine learning models (specifically, `LinearRegression`).

The data was processed and analyzed using a variety of Python libraries, including `pandas` for data manipulation, `folium` for generating interactive maps, `matplotlib` and `seaborn` for data visualization, and `scipy` for statistical testing. The analysis provided strong evidence of a significant decrease in library usage after 2020.

## Key Achievements:
- Crafted interactive maps using `folium` to elucidate the spatial distribution of libraries, aiding in strategic decision-making related to library placements and resources.
- Highlighted a decline in library visitation in specific regions over the years, emphasizing the need for targeted initiatives.
- Offered data-driven insights that could potentially enhance user engagement and the overall library experience, considering external factors like the COVID-19 pandemic which had an everlasting impact on attendance.


## Conclusion
The results of this analysis could be beneficial for strategic decision-making related to the placement of new libraries, allocation of resources, and understanding the impact of factors like the COVID-19 pandemic on library usage. The analysis provides strong evidence of a significant decrease in library usage after 2020, both through visualization and statistical testing.

## Future Work
The analysis could be further improved by incorporating additional data such as population and temperature. Population data could help adjust the visitor counts by the population to get a per capita visitor count, providing a more accurate measure of library usage. Temperature data could help examine the correlation between (extreme) temperature and library usage. Incorporating these additional data would involve several steps including data collection, data cleaning and preprocessing, exploratory data analysis, modeling, and evaluation and interpretation.

## Note
To fully understand the conclusions drawn in this analysis, it is recommended to go through the entire notebook, including the code and its outputs. You can view the HTML version fo the notebook [here](https://rawcdn.githack.com/JESUSC1/Chicago-Public-Libraries-Data-Analysis/1df9b97597c4fbed337e4935efc9fd1ea821440a/CPL-Data-Analysis.html). 

## Author
Jesus Cantu Jr. 



