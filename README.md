# UFOs
## Overview of Project

In this module a dynamic webpage was built by inserting JavaScript into an HTML page for easy viewing. A table was built to hold and neatly display UFO data that is stored in a JavaScript array. The dynamic webpage works by accepting user inputs and visually adjusting to reflect user interactions or choices. Initially, a date filter for the table was created to filter the entire table by date.This filter is to enable users refine their search. in more than ne level. 
Bootsrap and CSS was used to customize the webpage. 

Continuing further, in this project more in-depth analysis of the UFO sightings will be provided by allowing users to filter for multiple criteria at the same time. In addition to the date filter, filters for the city, state, country, and shape will be included. The new webpage will be updated with the search criteria after pressing "Enter".

## Results
To see the final dynamic webpage developed, one can [click here](https://gerlechjen.github.io/UFOs/). Upon getting to the webpage, what the user will see is a page header,article title, and brief article as shown below:

![image1](https://github.com/GerlechJen/UFOs/blob/main/static/images/UFO%20Webpage.png)

As the user scrolls down the page a table of sightings data can be seen, as well as the filters for the table. 

![image5](https://github.com/GerlechJen/UFOs/blob/main/static/images/table%20with%20filter.png)

There are 5 different filters to choose from; the date, city, state, country & shape. 

![image2](https://github.com/GerlechJen/UFOs/blob/main/static/images/UFO%20Webpage%20Filter.png)

The user can choose any of the filters he/ she would want to search by, fill in the data then press enter. The webpage will show all of the sightings for the applied filter. Multiple filters can be entered at the same time to narrow down the search criteria even further. 

For example when the table was filtered based on these specified filters for el cajon city, just two results were obtained as shown below:

![image3](https://github.com/GerlechJen/UFOs/blob/main/static/images/Webpage%20Filtered.png)

To do a new filter or search, the user can clear out the previously entered data and input new one. The table will go back to default if the user clears every entered data from the search or refreshes the browser. 

## Summary
One drawback of this current design is that after a user has filtered the table based on a search criteria, if the user wants to mae another search he/she would have to:
1. take time to clear out everything that had previously been inputted in the different criteria.
2. refresh or reload the webpage by clicking on the link at the top and pressing enter.

This is not the best and my recommendations for further development are that: 
1. A "Filter Table" button should be added to the webpage using the html code: 

```html
<li class="list-group" class="btn-dark">
    <button id="filter-btn" type="button" class="btn-dark">Filter Table</button>
</li>

```

This way when the user is done inputting the different search criteria, the "Filter Table" button can be clicked and the search criteria used will appear in the dynamic table. 

2. A "Clear Table" button be added to the webpage just underneath the "Filter Table" button. The code that would create this button is shown below:

```html
<li class="list-group" class="btn-dark">
    <button id ="clear-btn" type="button" class="btn-dark"> Clear Table</button>
</li>
```

This button would be clicked to clear all filters applied so a new search can be done. Using thsi button, the table would go back to the default state without the user having to manually delete every single entry. 

These added features will make the table more interactive compared to what we have currently. The buttons have their decriptive names on them that explains to any visitor to the webpage what they do once clicked. As such, any user will know exactly what to do while navigating and filtering the webpage. 
