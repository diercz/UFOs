# UFO's
## Project Overview
The purpose of the UFO project is to create a webpage that contains a dynamic table of UFO sightings.  I designed a table utilizing Javascript as the primary coding language.  Via the webpage, the end user is able to filter the data by varioius criteria and instantly see the results.

## Resources
- Data Source: data.js
- Software: E6+, HTML, CSS, Bootsrap, D3

## Results

The results of the project is a webpage that details UFO sightings based on the data provided.  Within the table the data will provide you:
- Date of Occurance
- Location
- UFO descriptive data
- Comments from the witness

![webpage](https://github.com/diercz/UFOs/blob/main/UFOs/static/images/Screenshot%202022-06-18%20135558.png)

Any user will be able to enter date, location and descriptive data to filter the table and see results that match the criteria they entered.  

## Summary
### Drawback
The data entered in the filter search must match extaclty was is within the data in order for the data to appear in the table.  The search bar is case sensitive and the date must match exactly.
Example:
- Date: 01/01/2010 will not register as the date in the table is 1/1/2010
- Case sensitive: must enter the name of city, etc as it appears in table or the results will be blank within the table.

### Recommendations
Recommendations I have would be to create a calendar for the user to select the date vs. having to type in the data exactly.  This will alleviate any issues with typing in the syntax of the date incorrectly.
Another recommendation I have is to create dropdown options for the other filters to ensure they are selecting the correct city, state, etc that they are wanting to review.  As the same recommendation above this would avoid the user typing in the information incorrectly into the filter search bars.  
