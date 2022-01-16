<h2><p align=center> UFO Analysis </p> </h2>

<h3><p> Background & Purpose: </p></h3>
This assignment enables us to view and filter UFO sightings information one a webpage. JavaScript enables us to display the UFO sightings data on the webpage as a table and also lets us manipulate i.e. filter out just the required data using filter functionality.

<h3><p> Resources: </p></h3>

Data Source: data.js 

Software: javascript, HTML, CSS, CSS-Bootstrap

<h3><p> Analysis Overview: </p></h3>

The technical analysis of this project can be roughly divided into following steps:

- Incorporating all the data into a table format on the webpage.
- Making filters to manipulate the data we are viewing.
- Adding the bootstrap elements to enhance the visual appearance of the webpage.

The detailed code for populating the data from the source file onto the webpage can be referred to in the app.js file in this repository. The filter boxes are added from HTML and the ability to listen to the events or any changes is then linked with calling the filtering functions. The data entered into filters is captured and passed on as parameters to filter the exact data.

<h2> Results </h2>

Here is how the final webpage for UFO sightings information is looking like:
<p></p>

<kbd>
 <img width="1591" alt="FinalPage" src="https://user-images.githubusercontent.com/90424752/149646837-38c19795-c6fc-4ce1-bc55-7b2c46256e20.png">
</kbd>
<p></p>

The above page contains all the data in the source data file and it is difficult to look at all the information at once. For which we have added 5 filters. Using these filters we can filter the sightings for specific date, city, state, country & the shape of UFO observed.

<h4> Instructions for using the filters: </h4>

- At the start the table conatins and displays all of the available data. To filter the data by specific filter, go and click inside the filter box & type the information for that specific filter in the format provided in the filter box.
- The default values displayed in the boxes, only show the format for entering the filter criteria into the respective box. 
- For example, to filter the data out for the state of Alaska, click into the box under state and type ak (abbreviation for the state of Alaska) and either press enter or click outside the box. Here is how the filtered results should look like:
<p> </p>

<kbd>
<img width="1370" alt="Screen Shot 2022-01-15 at 8 26 26 PM" src="https://user-images.githubusercontent.com/90424752/149647286-a4ad3642-64b6-4571-ac65-e58fb8e1b3c8.png">
</kbd>
<p> </p>

- To clear all the filters, manually clear out all the typed values inside the boxes.
- Having applied one criteria for filtering, you can also add other filters by then typing the parameter values inside the filter boxes. 
- Let us look at an example for using multiple filtering criteria:
- After clearing any previous filters, let us filter the UFO sightings for the state of California by entering ca into the state filter box. 

<p></p>

<kbd>

<img width="1380" alt="Screen Shot 2022-01-15 at 8 36 38 PM" src="https://user-images.githubusercontent.com/90424752/149647460-4cf14bf4-ddc3-4715-b489-d7dbd99b1377.png">

</kbd>

<p></p>

- All the sightings for the state of california should be filtered as seen above. You can now further analyze the results for cities, specific dates or type of shape recorded by the observers.
- Let us see how many triangular UFOs were observed by typing the word 'triangle' into the shape filter.

<p></p>

<kbd>

<img width="1378" alt="Screen Shot 2022-01-15 at 8 43 35 PM" src="https://user-images.githubusercontent.com/90424752/149647591-1ed1535b-a6fe-449b-a86e-338e8e551c2f.png">

</kbd>

<p></p>


<h2><p align=center> Summary </p></h2>

The filter system allows us to navigate through the data and look at it with increased granularity. However, there are a few drawbacks to this system & the whole design could be made more efficient.

<p></p>
<h4>Drawbacks:</h4>
<p></p>

- The filters do not have a clear button and everytime we need to search with fresh set of criteria, we need to manually delete the entries in the filter boxes.
- If the entries are not in exact formats as shown in the  place-holder, the filtering system does not work and the result area returns 0 rows.
- The available options for all the filters are not possible to know prior to filtering.

<p></p>
Following recommendations should be considered to improve the design & function of the webpage and enhance the quality of the user experience.
<p></p>
<p></p>
<h4>Recommendations:</h4>
<p></p>

- Clear filter button can be added which will clear all the filters upon clicking.
- To avoid error due to format mis-match the input can be type-casted (converted to lowercase in this case) before matching it with the available data options.
- To give an idea of what options are available for filtering a field, a dropdown menu of all the unique options can be added to each filter.

