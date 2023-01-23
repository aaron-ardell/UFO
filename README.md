# UFO Sightings Website
## Overview of Project

![This is an image](https://github.com/aaron-ardell/UFO/blob/main/website.png)

Our client's UFO Sightings webpage is working as intended, but she'd like to add more filters to her dynamic table in addition to the date. She would like to add filters for the city, state, country and shape of the UFO sightings. To meet this improvement, we'll need to:

- Create new input lines for city, state, country and shape.
- Remove the redundant filter button, instead making the inputs responsive to clicks of the 'enter' key.
- Ensure the filter can operate on multiple criteria.

![This is an image](https://github.com/aaron-ardell/UFO/blob/main/table.png)

## Results

The end user approaching the website is now exposed to five labeled entry boxes to the left of the table. Each input box is pre-loaded with a placeholder value added into the html to demonstrate an example of the type of input the table is looking for(date format, two-letter state code, etc). All they will need to do it input a value into one of the inputs and hit the 'enter' key. The table to the right of the inputs will update with the filtered table responding to the input values.

As in the picture below, the value "circle" was added to the shape input.

![This is an image](https://github.com/aaron-ardell/UFO/blob/main/filter1.png)

By adding "oh" to our state input, we will filter the table of circle shapes down to the only one that was recorded in the state of Ohio.

![This is an image](https://github.com/aaron-ardell/UFO/blob/main/filter2.png)

## Summary

We've successfully completed the revision of the website to create a variety of filter options for this website's dynamic table.

As with every project, there are drawbacks of this current version of the table as it is. One such issue, clarity on the limitations of the data when it comes to filters. Right now, we're relying on the end user knowing specifically what they want to find, or reviewing the initial list to find options. How many shapes are available and what are they? When is the earliest and latest date of the dataset? 

The addition of an html title element would be useful in providing information informing the end user of a filter choice without cluttering the interface. It can be scripted to reveal the information by simply hovering over an element with the mouse cursor, like the label elements. Though, enlarging the data would become complicated if the options for shapes increase or the date range were to change. This option would be more reliably applied to explain country options and state codes. Another option would be drop down boxes instead of text input lines to ease interface.

Lastly, we have two more keys to search in our current table: the duration and comments columns. Additional filters applicable to those columns would provide the option to filter each row of data based on every key available.






