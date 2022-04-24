# UFOs

# Overview of Project
This project is to retrieve UFO sightings data to build a functional table and to add the ability to filter the data on multiple criteria as input. In this research, JavaScript and html coding was used to achieve the web functions.

# Results
The index.html file was modified to create multiple table filters for the datetime, city, state, country, and shape as shown in the image below. The JavaScript file was developed incorporating a function that saves the element, value and filter id that was changed, as well as another function to loop through the dataset keeping only the data that matches searching criteria. 

![Multi_filters](https://github.com/hankai26/UFOs/blob/main/Resources/Multi_filters.png);

If any specific criteria were input in the web, for example, typing "el cajon" in the filter id of "city", a filter variable was created to store the information. The console webpage should be updated to show the input city name as well as the filter id, "city". Other critera can be used to filter search results in the same way. 

![loop_coding](https://github.com/hankai26/UFOs/blob/main/Resources/loop_coding.png);
![search_city](https://github.com/hankai26/UFOs/blob/main/Resources/city_filters_results.png);

Several search results are listed as in the following images.

![search_multi](https://github.com/hankai26/UFOs/blob/main/Resources/Multi_filters_results.png);


# Summary
The search web provides the entry to quickly find out the specfic events with given information and multiple criteria. However, the web needs to search again everytime when entering every single search information when we have multiple criteria to input. To fix this, we could modify the code and keep the search button. To click the button after inputing all searching criteria to triger the web searching. Another potential web development is to insert a ploting function to visualize the search results using plotly besides the table. That could help understand the filter results quicker and more straightforward.

