![eu_covid_pic](https://www.schengenvisainfo.com/news/wp-content/uploads/2021/05/europe-corona-covid.jpg)

# An Investigation into the Coronavirus in the European Union

<br>

## Overview

### Part 1
This is an investigation into the following variables within EU memeber states:

1. Confirmed cases of covid-19.
2. Confirmed covid-19 related deaths.
3. Percentage of population fully vaccinated.
4. Percentage of population partially vaccinated.

### Part 2
Re-creation of data using the pandas module. I do this by using numpy to generate random numbers to use in the pandas dataframe. This simulation is based on random data and is therefore, not an accurate visualisation of the current state. 

<br>

## Quick steps

### Install the following:
1. python
2. anaconda
3. cmder

<br>

### How to run a jupyter notebook:
1. Open cmder. 
2. Run `jupyter lab` or `jupyter notebook` on the command line.
3. Jupyter notebook should automatically open on your browser.
4. If it doesn't automatically open, copy the http link shown in cmder and paste into the url bar in your browser. 
5. Click on ipynb file to open the notebook.
6. On the tool bar click on kernel and then restart kernel and run all cells. 

<br>

## Explore
- During my research I discovered an interesting timeline dashboard on the ECDC's website found [here](https://www.ecdc.europa.eu/en/covid-19/timeline-ecdc-response). I found this to be quite informative as it gives an overview of the developments of covid-19 within the EU and the ECDC's reponse to this pandemic. 


- I also discovered an interactive data explorer found [here](https://ourworldindata.org/explorers/coronavirus-data-explorer?facet=none&pickerSort=asc&pickerMetric=location&Interval=7-day+rolling+average&Relative+to+Population=true&Align+outbreaks=false&country=AUT~BEL~BGR~HRV~CYP~CZE~DNK~EST~FIN~FRA~DEU~GRC~HUN~IRL~ITA~LVA~LTU~LUX~MLT~NLD~POL~PRT~ROU~SVK~SVN~ESP~SWE&Metric=People+fully+vaccinated). This explorer allows the user to filter by country and also by variable. This is a very interesting tool created by Our World in Data. However, an important element is that the data is based on each countries individual figures. This became an issue when I was comparing vaccination figures on December 15th 2021. I noticed that Bulgaria did not feature on the chart and the reason for this was that they had not submitted any data for this date. This may have an impact on my findings as my research is solely based on the data provided on this website.  


- Finally, I use the pandas module to simulate this data. This was a tedious process as I was using numpy to generate random data but when I tried to load this data with a list of the 27 EU countries, it casued as error. This was because the data being loaded wasn't the same type and lenght. As a result, I had to create different dataframes and join them togther into one. 

<br>

## Credits
My research for this investigation is heavily based on data collected from the following two websites:

- https://www.ecdc.europa.eu/en/covid-19/timeline-ecdc-response

- https://ourworldindata.org/coronavirus#coronavirus-country-profiles

<br>

## Badges

### NB viewer
You can view this notebook on nbviewer by clicking on the following badge:

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/SarahMcN25/programming_for_D.A.project/blob/main/project.ipynb)


### Binder
You can view this repository on mybinder by clicking on the following badge:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SarahMcN25/programming_for_D.A.project.git/HEAD)

<br>

## Conclusion
This project gave me an insight into how the EU approached the coronavirus pandemic and how the variables affected each of the EU member states. Next year, I would like to compare the current results from December 2021 with the results in December 2022. This would indicate if my findings in this notebook regarding the links between the variables were in fact accurate. 

<br>

## References
All references and code used in this notebook have been sourced in Nov/Dec 2021 and cited at the end of the notebook.

<br>

## End