# Important Links
Link to deployed [website.](https://datavisproject2.herokuapp.com/)
Link to [project repository.](https://github.com/TheGreekGoddess/Project_2)

# Analysing_US_Land_Fires

The project included analysis and visualisation of US Land-fire dataset between 2013-2017.

### WHAT WE DID

Steps in Data Extraction, Transformation and Load:
- Load raw data into PostgreSql
- Clean data in Python and SQL
- Create Rest APIs which gives results based on Causes, Locations, State, Year

### HOW WE VISUALISED THE DATA

- Created interactive dashboard using Index html and Bootstrap CSS
- Choropleth by State with a color gradient by count of fires
- Plotly Pie chart: Filter by State and Year
- Data table using Plotly
- GeoMap with a marker cluster group layer: Filter by Year
- Plotly Charts: Bar, Bubble and Stacked Bar

### WHAT WE FOUND OUT

- In the states most affected by fires, humans are the major contributor with 68%, followed by Undetermined 19% and Natural 13%
- The West coast has significantly higher counts of fires than the East coast which could be a result of drought in certain areas
- Top 5 states with high count of fires: Arizona, California, Montana, Oregon and Minnesota
- New Hampshire and Vermont did not have any reported fires and hence are excluded from the dataset
- Fires tend to be the highest in the summer months
- 2013 recorded the highest count of land fires
