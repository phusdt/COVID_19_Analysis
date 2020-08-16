<h1>🚀 COVID_19_Analysis </h1>
<body>
This project built to analyze covid-19 data.<br>
Coronavirus is a family of viruses that are named after their spiky crown. The novel coronavirus, also known as SARS-CoV-2, is a contagious respiratory virus that first reported in Wuhan, China. On 2/11/2020, the World Health Organization designated the name COVID-19 for the disease caused by the novel coronavirus. This assignment aims at exploring COVID-19 through data analysis and projections.<br>
Coronavirus is a family of viruses that can cause illness, which can vary from common cold and cough to sometimes more severe disease. Middle East Respiratory Syndrome (MERS-CoV) and Severe Acute Respiratory Syndrome (SARS-CoV) were such severe cases with the world already has faced.<br>
SARS-CoV-2 (n-coronavirus) is the new virus of the coronavirus family, which first discovered in 2019, which has not been identified in humans before.\n
It is a contiguous virus which started from Wuhan in December 2019. Which later declared as Pandemic by WHO due to high rate spreads throughout the world. Currently (on the date 10 June 2020), this leads to a total of 500K+ Deaths across the globe.\n
Pandemic is spreading all over the world; it becomes more important to understand about this spread. This NoteBook is an effort to analyze the cumulative data of confirmed, deaths, and recovered cases over time.
<h2>📚 Why this Project?</h2>
Pandemic is spreading all over the world; it becomes more important to understand about this spread.
<h2>📊 Content:
  <h3>1. Global Analysis</h3>
<body>Problem 1: Calculate the number of total cases, total deaths, total recovered, and total active by time (day units).\
Problem 2: Visualize the number and the log(10) of total cases, total deaths, total recovered, and total active by time (day units) in 2 graph (one for the number and the other for the log(10)) using line chart.
Problem 3: Visualize the number of total cases, total deaths, total recovered, and total active by time (day units) in 4 separated graphs using line chart.
Problem 4: Calculate the number of daily increases in total cases, total deaths, total recovered, and total active by time (day units).
Problem 5: Visualize the number of daily increases in total cases, total deaths, total recovered, and total active by time (day units) in 4 separate graphs using the bar chart.
Problem 6: Calculate the global mortality and recovered rate in percentage by time.
Problem 7: Visualize the mortality rate in by time (day units) using the line chart. Using the dashline to visualize the average mortality rate of all the time.
</body>
  <h3>2. Continent Analysis</h3>
    <body>
Problem 8:  Add the field "continent" into the confirm_df, deaths_df and recorveries_df dataset.
Problem 9: Create the countries_df data frame with the index as the "Country/Region" field. These column infor will be:  - continent: Country continent.
- Deaths: Total number of confirmed.
- Deaths: Total number of deaths.
- Recoveries: Total number of recoveries.
- Active: Total number of active.
- Mortality Rate: Mortality rate in percentage.
Problem 10: Create the continents_df data frame with the index as the "continent" field.
    These column infor will be: - Confirmed: Country continent.
- Deaths: Total number of deaths.
- Recoveries: Total number of recoveries.
- Active: Total number of active.
- Mortality Rate: Mortality rate in percentage.
Problem 12: Build the pie chart to compare proportions of the number of confirmed, deaths, recoveries, and active of the 7 continents.
Problem 13: Build a folium map to show up the number of confirmed, deaths, recovered and mortality rate of each country based on countries' location. The radius of the cicle is proportional to the number of confirmed.
  </body>
  <h3>3. Country Analysis</h3>
  <body>
Problem 14: Build a folium map to show up the number of confirmed, deaths, recovered and mortality rate of each country based on countries' location. The radius of the cicle is proportional to the number of confirmed. 
Problem 15: Build a px (plotly.express: https://plotly.com/python/plotly-express/) map to show up the number of active of each country in log(10) based on countries' name using the "spectral" color.
Problem 16: Filter the top 10 countries baseđ on the number of confirmed cases.
Problem 17: Visualize the top 10 confirmed countries with number active, recoveries and deaths cases using the stacked bar chart.
  </body>
  <h3>4.  Advanced Analysis</h3>
  <body>
Problem 18: Based on the data visualization on global part, does the COVID 2019 epidemic in the world has reached its peak?
Problem 19: Based on the data visualization on the continent part:
19.1 Which continent has the highest death rate over continents' active cases?

19.2 Which continent has the highest rate on COVID 2019 spread rate over continents' active cases?

19.3 Which continent has the highest recoveries rate over continents' dataset?
(Note: COVID 2019 Spread rate = Number of new confirmed in the last 10 days / number of active before).
Problem 20: Based on the data visualization on the country part:
20.1 Which country has the highest death rate over countries' dataset?

20.2 Which country has the highest rate on COVID 2019 spread rate over countries' dataset?

20.3 Which country has the highest recoveries rate over countries' dataset?
Problem 21: USA Dataset
Problem 22: Build a regression model (or more than 1 model) to predict the number of new confirmed in the top 10 states which have the highest number of confirmed cases in the USA.
  </body>
</h2>
