# UFO Sightings-- Fact or Fantasy?
## Overview
### Purpose
The purpose of this analysis is to assist Dana, a data journalist, who’s been given the opportunity to write her first own personal piece. Her choice—her hometown McMinnville, Oregon and its famous UFO sightings, something she’s been intrigued by since childhood. Dana has an enormous JavaScript file with UFO sighting information across the country. Her goal is to build a webpage that will display the information stored in the JavaScript array in an aesthetically pleasing table along with other UFO information. 

We also will create filters to make the table interactive and update based on user input. Customizing the webpage with Bootstrap tools also allows for more user-friendly visualizations. After the initial analysis we updated the webpage to provide a more in-depth analysis of UFO sightings data by allowing users to filter their searches for multiple criteria. We did so by adding search bars for City, State, Country, and Shape in addition to the original Date search bar. 

## Results
### Explantion
Initially the table may look intimidating to first time users with a plethora of excess information as can be seen in the snapshot of the initial webpage, prior to including search criteria in the search bars to the far left of the screen.

![overview.png](https://github.com/CristinaCod/UFOs/blob/main/resources/Screen%20Shot%202022-02-27%20at%206.07.30%20PM.png)

However, as one continues to narrow down their search with different criteria such as Date, City, State, Country, and Shape the table will be refined growing smaller only to show instances that correlate to said information entered. All the user has to do is simply press enter or click off the search bar for the results to be filtered. In this case I chose the date 1/5/2010 which took my initial table and filtered it down to just seven occurrences. 

![date.png](https://github.com/CristinaCod/UFOs/blob/main/resources/Screen%20Shot%202022-02-27%20at%206.08.22%20PM.png)

Again, this search is further refined when I add New Jersey as our desired state, leaving me with just two final results to peruse through.

![nj.png](https://github.com/CristinaCod/UFOs/blob/main/resources/Screen%20Shot%202022-02-27%20at%206.08.53%20PM.png)

## Summary
### Drawbacks
One of the main drawbacks of the webpage is that the search bars are case sensitive. Meaning everything in the table is entered in all lowercase so if a user were to accidentally make a letter uppercase or add an extra space or omit a space the table results would be inconclusive rendering the table blank. Continuing off the above example with New Jersey, as we know, there are results for "nj" but if I were to enter it as "NJ" I wouldn't get any output in the table.

![na.png](https://github.com/CristinaCod/UFOs/blob/main/resources/Screen%20Shot%202022-02-27%20at%207.05.52%20PM.png)

Additionally, unless a user really knows specifically what they're searching for it may be hard to use the table. For example if you don't know the specific city and state you're looking for the table may not be helpful and you're more likely to make a typo further hindering your results.Perhaps adding a closest match function would be beneficial if someone doesn't specifically know what they're looking for or how to spell it to make achieving results easier. 

### Recommendations
If the webpage were to be further refined I think it would be interesting for useres if an image was included in their search results. Obviously, not everyone has time to whip out their phone when they believe they're witnessing a UFO sighting but for the ones that do it would be beneficial to users to also see that image along with the information of the sighting.

Additionally, the database has two other search criteria of Duration and Comments which may be beneficial for users to add to the filter search bar if they were looking for something specific in these two categories.

Also, when looking at the webpage it's just a lot of text all in your face at once. We could possibly update the navbar and maybe make a drop down menu that includes more information on UFO sightings or a forum where people can comment their experiences as well. 
