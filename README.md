# UFOs
Project Overview
This project focuses on building a dynamic webpage that accepts user inputs and adjusts accordingly to display information about UFO sightings.
In order to perform their analysis, users will be able to filter the UFO sightings table based on multiple criteria such as the event date, city, state, country and shape.

Resources
Data Source: UFO data
Software: HTML/CSS, JavaScript, Visual Studio Code 1.49.1, BootStrap 4.0.0
Results
Link to UFO Sightings webpage
The deployed webpage is accessible at https://cedoula.github.io/UFOs.

Search Criteria Procedure
This is the initial page. The user can re-initialize the page by clicking on the navbar at the top.

Filtering by event date
The user enters the desired date, the change is detected and the table is updated accordingly.

Filtering by city
The user enters the desired city, the change is detected and the table is updated accordingly.

Filtering by country
The user enters the desired country, the change is detected and the table is updated accordingly.

Filtering by state and shape
The user enters the desired state and shape observed, the changes are detected and the table is updated accordingly.

All filter parameters can be entered simultaneously.
Summary
One drawback of this design is the difficulty for the user to know what parameter to use for the filtering. For example to pick a city, the user would have to go through the table a find the city desired for the analysis.
A way to address this would be to present drop-down lists including all filter values in place of the input fields.
Each list would need to update after a parameter is selected in any filter.
Including a button to clear the filters is also needed. The button would be located below the last filter.
