# Final-Project-Tableau

## Project/Goals
Look at the causes of death and the rates of death in various countries and see how it compares to the global death rate
as well as other countries.

## Process
### First I wanted to take a look at the total deaths each year for all causes and see how it changes using a percent difference
### in Total Deaths Each Year sheet. I also created a heatmap to see which countries had the largest amount of deaths to see if they would be interesting to look at
### With the above plots I decided to take a look at China, India and the US in the ChinaIndiaUs sheet and the Certain Timespans Sheet.
### The first of these is simply the total deaths of all of them combined with the percent difference each year. It seems that the death rate for these three countries
### is increasing faster than the global death rate is. Certain timespans allows you to look at the breakdown of causes of deaths over any year period from the data set and from any country.
### I wanted to find outliers in the other direction with a decreasing death rate or a stagnant death rate. This lead me to making the Latvia and Mauritania Sheets.
### Next I decided to take a deeper look at Canada's death rates in the Canada1, CanadaCardio and Canada Forecast sheets.
### Canada1 is the same as ChinaIndiaUS sheet but for Canada while CanadaCardio has graphs for both cardiovascular disease and neoplasms and how they affect Canada's death rate.
### Lastly Canada Forecast tries to predict the amount of deaths for the next 5 years from the data in CanadaCardio.

## Results
Option 2. Causes of Death. I created multiple line charts and bar charts to help visualize the amount of deaths
and the rate of change of deaths through percent difference. I did this for the total deaths across the world and for
multiple individual countries. I have a visualization as well that breaks down the causes of death for each country/region
in a bar chart and allows you to choose which countries/regions you want to look at. I also have a bar chart for two specific causes
of death in Canada which are colour coded to show the rate of change each year and then a line chart of the same data with a forecast
to see how the amount of deaths will change. I chose these visualizations to help illustrate how the death rates change for each country
as well as to give examples of outliers compared to global death rate.

I had multiple questions that I answered in my workbook:

### How do China, India and the US death rates percentage differences compare to the total rates and why could this be?

I used the ChinaIndiaUS sheet to see that the death rate seems to be increasing faster than the global death rate in Total Deaths Each Year.
A good reason for the increase is that all three of these countries have increasing populations and as your population increase there are more 
people who can die leading to more deaths. 

### What causes are the most influential to the death rates in the above 3 countries?

In Certain Timespans we can see that for China and the US most deaths are from cardiovascular disease and neoplasms although China also has 
a significant amount of respiratory cases. India on the other hand has a much more balanced causes of death coming from many different sources
on a similar level.

### What countries buck the trend of having an increasing death rate?

Latvia and Mauritania both buck the trend with Latvia doing this due to having a declining population while Mauritania on the other hand does not
have a declining population but has an increased human development index over this period so they most likely have a better access to healthcare as time
goes on.

### How does Canada compare to the total death rates?

Canada shows very similar to the ChinaIndiaUS sheet.

### What are the most important causes of Canada's death rate and how do they compare to the total death rates?

In CanadaCauses we see that cardiovascular and neoplasm related deaths make up the vast majority of deaths in Canada. 
Interestingly cardiovascular disease seems fairly steady over the years while neoplasms have increased significantly over
the time period. 

### How do the death rates of cardiovascular and neoplasm related deaths look like in the future?

In the Canada Forecast sheet I used a forecast to see how the death rates of the above diseases looked in a few years. The neoplasm deaths
seem to steadily increase to no surprise and should as the longer we live the more likely it is to contract neoplasm related deaths. On the other hand
cardiovascular disease seems to increase in the forecast as well even though in the earlier parts of the data it seemed to oscillate. The forecast must
more heavily favour recent data to give this conclusion.

## Challenges 
I had significant difficulty getting the plots to show up the way that I wanted to with the data. One example is that I wanted to do
a table calculation on a forecast plot but I was not allowed to due to the limitations of the program. Also there were a significant
amount of null values that I had to prune in Tableau since it was changing the plots. 

## Future Goals
I would spend more time refining these plots so that I can showcase the data better. I would also like to do some outside research 
regarding some of the data. For example the Latvia plot has an anomaly from 1992-94 which I could not find out the reason for. I would 
also look deeper at the causes of death for each country and try to aggregate them in a way that helps to enlighten about what are the 
most significant causes of death.
