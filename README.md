# UFOs

## Overview of Project:
Dana's goal is to create an interactive webpage that allows readers to parse the data around UFO sightings. So, she essentially needs to build two things: the webpage that will allow users to view the data (HTML) and a dynamic table that will present it (JavaScript).

Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

## Results:
The Filter Search fields allow for inputs in each of the fields (Date, City, State, Country, and Shape) and monitored to listen for a change in the input field. Once an input is entered in the table will then filter and return records that match the criteria if any have been logged.

- In the image below the table is being filtered be certain criteria with the table dynamically displaying it on the right

<p align="center">  
<img src="https://github.com/mcgibbenyd1/UFOs/blob/main/static/images/UFOs%20site%20filtered.png" width="95%"/>
</p>

## Summary:
Some of the drawbacks and improvements of this design are that with each input must match the data exactly which could lead to possible null searches due to capitalization.

Two improvements that could be made to improve the approach:
- Accept an input and format in a way that maches the column formatting
- Change the Text input fields to drop down selections so mistyped entries do not happen
