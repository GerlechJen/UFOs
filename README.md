# UFOs
## Overview
In this project, using JavaScript, an HTML table was built to organize UFO data that is stored in a JavaScript array. A date filter was created to filter the entire table by date.This filter is to enable users refine their search. The table was then placed into an HTML file for easy viewing. The dynamic webpage was customized using Bootstrap.

Continuing further with the project, more in-depth analysis of UFO sightings will be provided by allowing users to filter for multiple criteria at the same time. In addition to the date filter, filters for the city, state, country, and shape will be included.

The new webpage will be updated with the search criteria after pressing "Enter".

## Results
![image1](https://github.com/GerlechJen/UFOs/blob/main/static/images/UFO%20Webpage.png)


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
