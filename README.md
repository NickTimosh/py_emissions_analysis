# GLOBAL GHG EMISSIONS
*The project where I combined my energy and environmental engineering experience with coding skills and data analysis techniques*

## The project
One of the negative impacts on the environment from human activities is greenhouse gas (GHG) emissions, which lead to global warming with catastrophic consequences. The performed analysis allows to dive deeper into the problem and intend to assess the impact of different countries and sectors of economy in global GHG emissions. The analysis also aims to compare these data with the population of countries and GDP in order to identify existing patterns. This can be useful for benchmarking, forecasting, developing national and sectoral energy managenent plans and issuing other strategical documents and legislative framework related to environmental policy.

![image](https://user-images.githubusercontent.com/116592259/225337781-e5153e21-0492-43a1-8ef1-8ad58dba272b.png)

## Credits
The [CAIT dataset](https://www.climatewatchdata.org/about/faq/ghg) includes historical country-level and sectoral GHG emission data from 1990 to 2018, which allows to perform the analysis of the trends of global GHG emissions, including also sector-specific trends. 

## The Approach:
The analysis performed within the following steps:
- importing data from a csv file to Google Colabratory 
- importing pandas, numpy and matplotlib for further data processing and visualization
- data sorting and filtering
- unpivoting tables
- global historical emissions trend analysis using cumulative line chart
- share of different sectors (Energy, Industrial Processes etc.) within 30-year evolution of the emissions with a stacked column chart
- analysis of GHG emissions in sectors reported in 2018 compare to 1990 with the bar chart
- country-level analysis, considering GDP, population and corresponding emissions using scatter chart
scscscscsc
## Key Insights:
- The Database provides emission time series from 1990 until 2018 for 194 countries, covering a total population of 7.5 billion inhabitansts
- In 2018, reported emissions totaled 47.5 thouthand MtCO2e (excluding the effects of land use and forestry), which represents a 55 percent increase since 1990
- In 2018, Energy sector (including fuels used by transport and buildings) represent the largest source of greenhouse gas emissions worldwide (78.3 %), followed by agriculture (12.2 %), Industrial Processes (6.1%) and Waste (3.4 %)
- To be more specific, the five most emitting sub-sectors are responsible for 33 % (Electricity / Heat), 17 % (Transportation) and 13 % (Manufacturing/Construction) and 12 % (Agriculture) of the total CO2-eq emissions
- Higher GHG emissions recorded for countries with higher GDP per capita, as expected.
