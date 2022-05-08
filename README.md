# UFOs

## Overview
- pupose is well-defined

## Results
### Searching by Date
Input date into "Enter Date" box using M/D/YYYY format. If month or day value is a single digit, only include the single digit (ie: Do not write January as 01). 
For example, January 1st, 2010 would be written 1/1/2010. December 12th, 2010 would be written 12/12/2010. 
![Search By Date](static/images/date.png)
### Searching by City
Input city name into "Enter City" box. Do not capitalize the names of the city. 
For example, "Fort Worth" should be written as "fort worth". 
![Search By City](static/images/city.png)
### Searching by State
Input state name into "Enter State" box using XX format. Do not capitalize the abbreviations. Standard abbreviations apply. 
If you're not sure about which abbreviation to use, view [this](https://www.faa.gov/air_traffic/publications/atpubs/cnt_html/appendix_a.html) link to lookup the proper abbreviation. 
For example, "Texas" should be written as "tx". 
![Search By State](static/images/state.png)
### Searching by Country
![Search By Country](static/images/country.png)
### Searching by Shape
![Search By Shape](static/images/shape.png)
### Searching by Multiple Parameters
![Search By Multiple Params](static/images/multiple.png)

## Summary

### Drawback of Current Webpage Design
The largest drawback of this webpage as it has currently been designed is that there is no way to update the data utilized. 
Since the data comes from a status .js file, it cannot access any new UFO sightings that may occur. 
As such, this webpage will become outdated very quickly, and will only be useful as a time-capsule of when the initial data was collected. 

### Further Development Advice
1. Incorporate API calls or website scraping to improve the longevity of the site. 
Utilizing up-to-date information will make the site more useful for users across the board and will prevent the website from becoming outdated. 
API calling/Website scraping will allow the webpage to utilize the most up-to-date information available on the web, and would provide a more accurate user experience than a static data set. 

2. Introduce a date-range filter. Allow for users to include filtered data from a range of dates (ex: 1/1/2015-1/1/2020) to better serve user needs. 
Instead of limiting users to one specific date, this will allow for a more dynamic user experience. 