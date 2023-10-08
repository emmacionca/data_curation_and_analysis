# Countries and Dependencies by Population 
## Data Curation And Analysis
This project scrapes data from the table in the Wikipedia article: https://en.wikipedia.org/wiki/List_of_countries_and_dependencies_by_population and transforms the HTML into a CSV file. The CSV file is then used to create some graphical representations of the data. 

API Documentation: 
- pandas: https://pandas.pydata.org/docs/
- BeautifulSoup: https://www.crummy.com/software/BeautifulSoup/bs4/doc/
- matplotlib: https://matplotlib.org/stable/index.html
- seaborn: https://seaborn.pydata.org/
- numpy: https://numpy.org/doc/

Wikipedia data is available under the [Creative Commons Attribution-ShareAlike License 4.0.](https://en.wikipedia.org/wiki/Wikipedia:Text_of_the_Creative_Commons_Attribution-ShareAlike_4.0_International_License). 

My data is available under the MIT license. 

Data type and descriptions for data attributes:

**Country / Dependency**
- Data type: `string`
- Description: The name of the country 

**Population**
- Data type: `int`
- Description: The number value of the population of each country

**% of world**
- Data type: `float` between 0-100
- Description: The number value of the percentage of the world each population represents 

**Date**
- Data type: `string`
- Description: The date at which the population estimate was published

**Source (official or from the United Nations)**
- Data type: `string`
- Description: The source from which the population data comes from. 

There are no known issues in the dataset. Potential issues include different data sources and data collection dates. 

Analysis: analysis (what you are showing, and why)
There are five data visualizations produced. 
* Country vs. Population: A bar graph of 7 randomly selected countries and their populations to show the large difference in population size of different countries.
* Population vs. Percentage of world: A scatterplot showing population in correlation with percentage of world to show their expected perfect correlation.
* Population boxplot: A boxplot showing the distribution of population to illustrate the skewdness of the data, as there are many outliers present. It also shows the minimum, maximum, and mean of the population data.
* Countries and their Populations histogram: A histogram representing populations to see the number of countries falling into each category. It was adjusted to represent a more normal distribution on the plot so the data is more easily perceivable.
* Sources of Data and their Frequency of Use histogram: A histogram representing the 30 different sources of data to see how many of the data points cite each source, and which source most of the data comes from. 
