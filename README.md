# State-growth
Population trends within a country can have a drastic impact on its future global economic, geopolitical positions, population trends will also drive the direction a countries development within its own borders. In the United States, population is recorded every 10 years by The United States Census Bureau. This data is then used by the government to make several very important decisions, one of them being allocation of seats in the House of Representatives.


Data was sourced from https://www.census.gov/data.html
 
Original data was stored as a excel document. Population data ranged from the year 2010-2020 separated by each state (including Washington D.C), and region of the country. Original data also contained official census data, along with estimates. Data was separated and transformed into four separate CVS files, official 2010 census for both states and regions, and 2010-2020 estimates for both states and regions. Data was loaded into Postgres SQL database if user would like to utilize in future.

Cleaned CSV files were loaded into Tableau. This visualization illustrates that the United States as a whole has grown steadily year over year since 2010.

<img src="/Visualizations/USA_growth.png" width="500">

As the United States is grows it is important to learn where exactly most of the growth is occurring. The Census Bureau divides the United States into four regions Northeast, Midwest, South, and West. Between the years of 2010-2020 it becomes clear that a majority of the population growth is happening in the Western (10.25%) and Southern (7.5%) regions. The slowest growing region was the Northeast (1.2%).

<img src="/Visualizations/region_growth.png" width="500">

The United States geographically is a very large county. Dividing into four large regions still does not give an accurate picture of which state within the region is contributing to growth. The state that grew the most from 2010-2020 was the state of Utah (17.10%) and the state that shrunk was West Virginia (-3.75%).
<img src="/Visualizations/pop_change_state.png" width="500">

Certain unforeseen such as natural disasters can cause a break in a trend or accelerate existing trends in population. The COVID-19 pandemic of 2020 caused significant population movement within the United States. When comparing 2018-2019 and 2019-2020, certain trends become noticeable. For example, in 2018-2019 California population change was net zero, however 2019-2020 CA lost .2% of its population which amounts to ~79,000 people. The state of New York lost .4% of its population from 2018-2019 and then lost .6% of its population from 2019-2020

<img src="/Visualizations/2018-2019.png" width="500"> 
<img src="/Visualizations/2019-2020.png" width="500">

As stated previously growing or shrinking populations need to be carefully tracked by local governments in order to prepare. In the United States the top five states have grown the most are Utah, Idaho, Arizona, Nevada, and Texas. States such as Arizona and Nevada in dry, desert will have to navigate growing water scarcity due to increased demand and decreasing supply due to climate change. Other challenges posed will be increased demand for housing, and decreasing amount of buildable land due to mountainous terrain. These factors could cause an increase in housing prices that will price out lower income residents.

<img src="/Visualizations/az_forecast.png" width="500">
<img src="/Visualizations/tx_forecast.png" width="500">
