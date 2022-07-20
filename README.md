# UFOs
## Overview of Project
  The dynamic webpage was customized using Bootstrap.

In this module a dynamic webpage was built by inserting JavaScript into an HTML page for easy viewing. A table was built to hold and neatly display UFO data that is stored in a JavaScript array. The dynamic webpage works by accepting user inputs and visually adjusting to reflect user interactions or choices. Initially, a date filter for the table was created to filter the entire table by date.This filter is to enable users refine their search. in more than ne level. 
Bootsrap and CSS was used to customize the webpage. 

McMinnville, Oregon

Continuing further, in this project more in-depth analysis of the UFO sightings will be provided by allowing users to filter for multiple criteria at the same time. In addition to the date filter, filters for the city, state, country, and shape will be included. The new webpage will be updated with the search criteria after pressing "Enter".

## Results
To see the final dynamic webpage developed, one can [click here](https://gerlechjen.github.io/UFOs/). Upon getting to the webpage, what the user will see is a page header,article title, and brief article as shown below:

![image1](https://github.com/GerlechJen/UFOs/blob/main/static/images/UFO%20Webpage.png)

As the user scrolls down the page a table of sightings data can be seen, as well as the filters for the table. As seen from the image below we have 5 different filters to choose from; the date, city, state, country & shape. 

![image2](https://github.com/GerlechJen/UFOs/blob/main/static/images/UFO%20Webpage%20Filter.png)

You can fill in data for any of the filters press enter, then the HTML page will show all of the sightings for the applied filter. Multiple filters can be entered at to narrow down teh search criteria. 

When the table was filtered based on these specified filters for el cajon city, just two results were obtained as shown below:

![image3](https://github.com/GerlechJen/UFOs/blob/main/static/images/Webpage%20Filtered.png)

## Summary
One draw back of this current design is that after a user has filtered the table based on a criteria search criteria if the user wants to search for another criteria he/she would have to take time to either clear out everything that has been inputted in the different criteria or reload the webpage by clicking on the link and pressing enter.
This is not the best and my recommendation is that a "Filter Table" button and should have been included using the code: 

```html
<li class="list-group" class="btn-dark">
    <button id="filter-btn" type="button" class="btn-dark">Filter Table</button>
</li>

```

This way when the user is done inputting the different search criteria, the "Filter Table" button can be clicked to update the table. 

For further development, I will also recommend that a "Clear Table" button be included underneath the "Filter Table" button. The code that would create this button is shown below:

```html
<li class="list-group" class="btn-dark">
    <button id ="clear-btn" type="button" class="btn-dark"> Clear Table</button>
</li>
```

This button would be clicked to clear all filters applied. With that, the table would go back to the default state without manually deleting every single entry. 

These added features are also more interactive compared to what we have currently. The two additional buttons suggested, have names on them that  explain their use. Therefore, any new visitor to the webpage knows exactly what to do while navigating the webpage. 


Also the filters like city, state and country should not be case sensitive. As it stands now it is case sensitive and if the city for instance is spelt capitalized, 





