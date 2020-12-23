# Project One: Food Deserts and Food Environments 
##### Mary Bellavia, David Fournie, Janelle Goddard, and Eric Evans
##### 12/23/2020

### Question One: What are the demographics for food deserts in Missouri?
The racial demographics analysis of the data on the overall population, the low access population, and the low access low income population for Missouri yielded some concrete numbers. The bar graph and total population percentages pie chart show the white population in the largest population in Missouri. 

![Population Demographics Bar Chart](output_data/PopulationDemographics.png)
![Population Demographics Pie Chart](output_data/PopulationPercentageDemographics.png)

The last bar chart shows the percentages for the populations who live in low access areas by race and who live in low access low income tracts by race. This bar chart shows that a greater percentage of the white population is affected by low access to grocery stores. In addition, those in the black, hispanic, or other population, if they live in a low access area are far more likely to also be affected by low income. This bar graph shows that food deserts disproportionately affects black, hispanic, and multiracial or other populations in Missouri.

![Low Access Population Demographics Bar Chart](output_data/PopulationPercentagesDemographics.png)

### Question Two: What is the relationship between the poverty rate for a given county in Missouri and low access populations?
Besides looking at the Demographic Breakdown, we wanted to answer if there was correlation between the Poverty Rate for Missouri Census Tracts, and the Low Access population. This proved difficult as the poverty rate is measured in percentages, while the Low Access population is measured in population count. In order to offset the difference in values, we converted the Low Access population count into log(base 10) values. With the values of our scatterplot balanced, we were able to plot an accurate linear regression of the values. The first scatterplot plotted the mean(s) of the Poverty Rates vs Low Access population. Using a linear regression model, we found that the rvalue was -.18 which is at the very most, a weak, if not null, correlation between the two data sets plotted. Next, we wanted to make sure that the mean of the Poverty rate did not skew our linear regression model, so we also plotted a linear regression of the medians of the Poverty Rates vs Low Access population. We found that the rvalue of the second linear regression was -.33 which shows a slightly more, but still weak correlation. Finally, we plotted boxplots in order to see potential outliers. The scatterplots of our data were not condensed, so we were unable to see if outliers were affecting our plots. The boxplots showed that there were few outliers in the datasets. These findings went against our initial hypothesis that Poverty Rate and Low Access Populations are correlated. However, there are a variety of reasons that the correlation may not be apparent in the data that we used. 
One shortcoming of our data was the lack of measured vehicle registration per household. There was a measurement for low access vehicles that defined the count as >= 100 households (per tract) lacking vehicle access and living beyond 1/2 mile from supermarket. However, since we were looking at the population that lived 1 mile or more from healthy food access, and not households per tract, this would not have produced the data sets that we were looking for. Another shortcoming was that the datasets for demographics were only conducive to Low Access and Total Population Measurements. This excluded age breakdown, population vehicle access, or low income, which would have perhaps answered our inquiries about Food Desert correlations more definitively.


### Question Three: What is the food environment for the counties that comprise Missouri’s two largest cities, St. Louis and Kansas City?
After looking over the data, we decided to break the two largest cities in Missouri down into their 4 largest counties. We are now able to see what types of food environments make up the majority of each county and how this relates to the food desert. In our first bar chart, we compared total supermarkets to just standard fast food restaurants. As you can see, the amount of fast food restaurants nearly doubles the amount of supermarkets in every county. Our second bar chart, breaks down the percentage of convenience stores, fast food restaurants, full service restaurants, and supermarkets. This chart also showing that supermarkets makes up a small percentage of each county versus the percentages of fast food and full service restaurants. Although each county has plenty of food options available there is still a lack of supermarkets available based on our data provided. All the other options of fast food and full services restaurants aren't necessarily the healthiest of options, and individuals with lower income could have a difficult time purchasing food from these types of restaurants on regular basis.

### Definition of Terms
from the United States Department of Agriculture Economic Research Service and Census Bureau
* Food Desert: “[A] food desert [is] a low-income census tract where a substantial number or share of residents has low access to a supermarket or large grocery store.”
What does low access mean?
* Low Access: “[Living] more than 1 mile from a supermarket or large grocery store in urban areas and as more than 10 miles from a supermarket or large grocery store in rural areas.”
How is low income determined?
* Low Income: “[T]he poverty rate for that tract is at least 20 percent”
How is the poverty rate determined? :
* Poverty Rate: “[A] family's total income is less than the family's threshold, then that family and every individual in it is considered in poverty”	

### Sources
* https://www.ers.usda.gov/data-products/food-access-research-atlas/download-the-data/
* https://www.census.gov/topics/income-poverty/poverty/guidance/poverty-measures.html 