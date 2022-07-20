# UFOs
## Overview
In this project, using JavaScript, an HTML table was built to organize UFO data that is stored in a JavaScript array. A date filter was created to filter the entire table by date.This filter is to enable users refine their search. The table was then placed into an HTML file for easy viewing. The dynamic webpage was customized using Bootstrap.

Continuing further with the project, more in-depth analysis of UFO sightings will be provided by allowing users to filter for multiple criteria at the same time. In addition to the date filter, filters for the city, state, country, and shape will be included.

The new webpage will be updated with the search criteria after pressing "Enter".

## Results
Upon getting to the website, what the user will see is the title 
![image1](https://github.com/GerlechJen/UFOs/blob/main/static/images/UFO%20Webpage.png)

As the user scrolls down the page the data can be seen as well as the filter search which shows all the different filters possible. 
As seen from the image below we have 5 different filters to choose from; the date, city, state, country & shape. 
![image2](https://github.com/GerlechJen/UFOs/blob/main/static/images/UFO%20Webpage%20Filter.png)
You can fill in data for any of the filters press enter, then the HTML page will show all of the sightings for the applied filter. Multiple filters can be entered at to narrow down teh search criteria. 

When the table was filtered based on these specified filters for el cajon city, just two results were obtained as shown below:

![image3](https://github.com/GerlechJen/UFOs/blob/main/static/images/Webpage%20Filtered.png)

## Summary
In this new design a filter button should have been included using the code 

```html
<li class="list-group" class="btn-dark">
    <button id="filter-btn" type="button" class="btn-dark">Filter Table</button>
</li>

```

so that when the user is done entering the filters needed, the button can be clicked to update the table. For the current webpage a user has to click "enter" or anywhere outside the "Filter Search" area for the filters to be applied. This might not be very obvious to new users and a "Filter Table" button would have been a better option. 

Also, an additional "Clear Table" button should have been created to clear all filters applied once clicked by the user. With that, the table would go back to the default state. With this current webpage for the table to go back to default, all filters that have been applied would have to be manually deleted. The code that could have created the 'Clear Tabl"e button is shown below:

```html
<li class="list-group" class="btn-dark">
    <button id ="clear-btn" type="button" class="btn-dark"> Clear Table</button>
</li>
```
Also the filters like city, state and country should not be case sensitive. As it stands now it is case sensitive and if the city for instance is spelt capitalized, 
