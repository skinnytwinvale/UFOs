# UFOs

## Project Overview
This project focuses on building a dynamic webpage that accepts user inputs and adjusts accordingly to display information about UFO sightings.\
In order to perform their analysis, users will be able to filter the UFO sightings table based on multiple criteria such as the event date, city, state, country and shape. 

## Overview of the analysis
Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

1. ***Deliverable 1***: Filter UFO sightings on multiple criteria
-Using JavaScript and HTML, you’ll modify the code in your index.html file to create more table filters. In addition to the date filter you created in this module, you’ll add filters for the city, state, country, and shape. Using JavaScript, you’ll replace the handleClick() function in your app.js file with a new function that saves the element, value, and id of the filter that was changed. Then, you’ll create a new function to loop through the dataset and keep only the results that match the search criteria.

2. ***Deliverable 2***: A written report on the UFO analysis 

## Results
- How someone might use the new webpage is by first the user enters the desired date, the change is detected and the table is updated accordingly. Then you would have to update the desired city, country, state, and shape. The parameters would have to be entered simultaneously and the table will be updated accordingly.
![name-of-you-image](https://github.com/skinnytwinvale/UFOs/blob/913ef82d5aed9f0d9315659b0216519d017ea532/static/images/Screen%20Shot%202022-06-19%20at%209.40.27%20PM.png)

## Summary
- One of the drawbacks of this design is the difficulty of the parameter, the user won't know which parameter to use. One example is if the user wanted to use the city he would have to go through the table to find out which one is desired for the analysis.
- The best way to include the parameter would be to include a drop down that shows you the possible options to choose from
- Some minor adjustment would also to include button that clears the tables
