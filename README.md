# UFO
## Overview of Project: Explain the purpose of this analysis.
The purpose of this analysis is to create an interactive webpage based on UFO sighting data (saved in a js file). The original data file is pulled from data.js, and another file app.js is used to rebuild the table based on user criteria. User can filter mulitple criteria by typing in date, city, etc and press "Enter" key. The webpage will then re-populate the table based on user filters using the filterTable function in app.js to pull the appropriate key and value from the object "data". User can also choose to click on "Reset Table" at the end of the search criteria to reset any searches, and the webpage will bring back the original table with data.

## Results: Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your 
User will first observe that all the UFO sightings will populate on the page named index.html. To narrow down any searches based on a specific date or location or other criteria, user will need to use the "Filter Search" feature on the left hand side. Keep in mind that the search criteria will need to follow the same format as the "placeholder text". For example, the correct format to search for a state will need to be typed in as the state abbreviation in lower case. Specifically, the user will need to type in "ca" if they want to look up any sightings that occurred in California. The user can type in as many search criteria as needed, and then press "enter" key to re-populate the table based on search. To reset the table, the user will need to click on "Reset table" provided at the end of the Filter Search.

Example shown below using the correct format for search criteria: "ca" for state and "triangle" for shape
![Correct use of "ca" and "triangle"](/../main/static/images/UFO-Search-%20Example-ca-triangle.PNG)

Example shown below for the incorrect format for search criteria: "CA" for state and the table does not re-populate
![Incorrect use of "CA"](/../main/static/images/UFO-Search-Example-CA.PNG)

## Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.

As discussed earlier, users have to type using the exact format that's stored in the data object for the results to populate correctly. For example, typing in "CA" instead of "ca" will not work. Improvements can be made to accept words in both upper and lower cases (words do not have to be case-sensitive). Other suggestion can be to accept both either partial matches to the state names (accepting "Cali" for California), or full matches to the state names. If user types in "New", all states with "New" will be filtered (New York, New Jersey, New Mexico, etc). The "date" filter can also be improved by adding a range to the search property. For example, user can choose to filter out sights that occurred between two date ranges, or user can choose to filter out any sightings that occur either before or after a specific date.
