# Bangalore's Population and Bus Stop Distribution

In this repository you will find all the files used in this project.

## Table of contents
* General Info
* Technologies
* Files Directory
* Sources	
* Acknowledgements

## General Info
This is a repository of the data files that were used and created to visualise the population distribution in Bangalore and the distribution of bus stops across the city. 

This is part of the7th Semester Pre-Thesis project.
	
## Technologies
Project is created with:
* RStudio version: 1.4.1717

## Files Directory
* HTML files - Frontend
  * NoCodeFile.html - This file is the file linked in my app prototype. It had written content and charts, with no code being displayed. [Preview of HTML](https://htmlpreview.github.io/?https://github.com/envy-881/CAC_Sem7_PreThesis/blob/main/NoCodeFile.html)
  * CodeFile.html - This file is an explanation of the code written to produce the charts. It includes the code chunks and output. [Preview of HTML](https://htmlpreview.github.io/?https://github.com/envy-881/CAC_Sem7_PreThesis/blob/main/CodeFile.html)
  
* R Markdown files - Backend
  * NoCodeFile.rmd - The RMarkdown file for the HTML file of the same name.
  * CodeFile.rmd - The RMarkdown file for the HTML file of the same name.

* R files - Backend
  * DataCharts.R - The R file for the Rmarkdown file.

* CSV files
  * 2012_Bus_Stops.csv - Dataset containing BMTC bus stops with the wards they belong to and coordinates.
  * 2014_BBMP_Ward_Details.csv - Dataset containing the ward details of Bangalore.
  * 2016_Ward_Roads.csv - Dataset containing the roads lengths per ward.
  * ProjectDf.csv - Dataset that was created by merging the above datasets using the R code as the final dataset used for the charts.

## Sources
* [2012 Bus Stops](https://github.com/openbangalore/bmtc/blob/master/data/misc/bmtc_bus_stops_with_location_details_2012.csv)
* [2014 Ward Details](https://data.opencity.in/dataset/bengaluru-bbmp-ward-details/resource/bbmp-2014-ward-delimitation-details-)
* [2016 Ward Road Lengths](https://data.opencity.in/dataset/bengaluru-bbmp-ward-details/resource/bbmp-ward-area-and-road-length)

## Acknowledgements
I would like to give credit to the following sitesfor providing information and resources for this project:
* Stack Overflow - Troubleshooting 
* RDocumentation - Information and syntaxes
* R Graph Gallery - Information and code chunks
