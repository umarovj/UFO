# UFO

## Overview of Project: Explain the purpose of this analysis.

Dana is a data journalist who is tasked to write about UFO sightings around the world. This analysis explores data through an HTML web page. The code, powered by javascript, allows the user to filter through all the data by date, city, state, country, and shape. 


## Results: Describe to Dana how someone might use the new webpage by walking her through the process of using the search criteria. Use images of your webpage during the filtering process to support your explanation.

The UFO Finder page can be accessed by opening the index.html file. The page displays a title, description, and filtered data. The filter search criteria can be found at the bottom left side with placeholders inside the text boxes to give users examples of what to search for. With no input from the user, the page will display all the data. Once the user types in any of the filter boxes, the data is auto-populated with results that satisfy the filters. The user can input multiple filters to display specific searches. Here is an example of search results of UFO sightings in Alabama. 

![al search](https://github.com/XSR700/UFO/blob/main/al%20search.PNG)

Notice that the search input must be in the same format as the placeholders. Typing "Alabama" will not show results. 



## Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.

While this page functions successfully and is ready for Dana to use, there are still drawbacks and improvements that can be made. 

The drawback of this design was mentioned earlier about the formats of the filters. The results only populate when the user inputs the exact format. for example, Alabama needs to be searched as its state shorthand "al" or United States needs to be "us". The script is also sensitive to capital letters and searches like "Ca" will not display results in the state of California. 

An improvement can be made to the HTML script. The filter button is not functional when pressed. We can modify the event change in the .js file to populate the results once clicked. This will make it more user-friendly. 

Another improvement can be made inside the data. There seems to be some sort of conversion error occurring inside the description. We can find strange characters like these:

![improvement 2](https://github.com/XSR700/UFO/blob/main/improvement%202.PNG)

The data text can be parsed and cleaned up. One way is to implement reg ex into the code to eliminate combinations of special characters. 

