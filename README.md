# Title: Crop-Production

## Purpose: 
The question I wanted to ask was, “Would agricultural use of fertilizers and pesticides enhance the production rate of crops that are moderate to highly reliant on nutrients and pesticide control?”
The answer I was able to discover thanks to the narrative visualization is, “Yes it does, but there’s a limit. The narrative visualization conveys that agricultural use of fertilizers and pesticides enhances the production rate of crops, but there is a limit to how much better these agricultural chemical additives can improve crop output. Exceeding that level does not result in a significant rise in the yield rate.” 


## Demo: https://public.tableau.com/app/profile/chris.park4883/viz/CropProductionwithAgriculturalFertilizersandPesticides/Dashboard
To run:
```
1. clone the repository or download zip
2. open ./index.html to see the the site! 
```

## Narrative Structure: 
The narrative visualization follows the interactive slideshow structure. As the author, I direct the path through a slideshow, and let the reader drill down into some details or investigate some tangent during each slide.
The narrative visualization has 4 interactive slideshows that give the reader the opportunity to drill down in a particular slide. Readers can advance between slides by scrolling up and down. 
It best conveys the messaging to the reader in order from “Crop Production,” “Chemical Additives Usage,” “World Map,” and “Crop Yield.” “Crop Production” scatter plot lets the readers interact with the chart by hovering over the circles to see the countries.  “Chemical Additives Usage” bubble chart lets the readers interact with the chart by hovering over the bubbles to see the country names and chemical additives usage from 2002 to 2018. The readers can also drag the bubbles around if they choose to compare the bubble size difference with other country bubbles. “World Map” lets the readers interact with the map by highlighting the nations they hover. “Crop Yield” scatter plot lets the readers interact with the chart by hovering over the circles to see the countries.


## Visual Structure: 
The narrative visualization makes it easy for the readers to understand each scene. The first scene acts like a title page to introduce to the readers what the narrative visualization is going to explore. The background picture depicts crop production to support the title page scene. The readers have the option to click on the “Explore” button to start understanding the message.
The viewers can navigate through scenes either by scrolling down and up between scenes in order or clicking on the buttons of the navigation bar to skip between scenes. The navigation bar is part of a template for visual consistency that highlights the title of the scenes for the viewers. The bold texts on top of each scene are the titles of the graph that they represent. Some scenes that have captions in smaller texts or greyed out are captions to convey the underlying message to the readers. The captions further explore the connection between scenes.
The axes of scatter plots are consistent with their ticks, svg size / length, and start and end values. The consistent axes urge the importance of the circle size. The color of economic groups are consistent throughout the scatter plots and bubble graphs. The color consistencies connect the data together for the readers.
Readers tend to focus on the center of their screen, so in every scene, the message and the graphs are centered because they are important to the messaging.


## Annotations: 
The annotation for  “Crop Production” scatter graph is the dashed line with an arrow pointing in a positive slope and the text, “Countries with more chemical additives produced more crops.” The arrow supports the messaging that nations that use more chemical additives yield more crop production, as explained in the text. The mouse over hover circles show a text of the country. The color scheme distinguishes the nations by their 4 different income groups. The circle size annotation shows the scale of production quantity of each nation.
The “Chemical Additives Usage” chart allows the readers to move around the bubbles to wherever they want to compare the size of other bubbles.  The mouse over hover circles show a text of the country. The color scheme distinguishes the nations by their 4 different income groups. The circle size annotation shows the scale of fertilizer and pesticide usage of each nation.
The annotation for the “World Map” map is the text, “Larger countries produce more crops.” As I have discovered that countries with higher crop production have more arable land, the annotation helps the reader understand the message that the land size of the nation might have a significant factor to crop production besides fertilizer and pesticide usage. 
The annotation for the “Crop Yield” scatter graph is the text, “Countries yield similar hectograms of crops per hectare. Chemical additives have a limited benefit to crop production.” It supports the message that there is a limit to how much better these agricultural chemical additives can improve crop output. Exceeding that level does not result in a significant rise in the yield rate.


## Parameters: 
For both the scatter plots, “Crop Production” and “Crop Yield” the circles’ values representation of each nation is the parameter. The x,y axes with their ticks, svg size / length, and start and end values are consistent in both of these plots. The circles share the same position on the plots. The reader can navigate between the two scatter plots by clicking on the scatter plot’s name in the navigation bar on the top. Thus, as those parameters change the scene state, it'll cause other parameters to change the scene states. If the production vs yield parameter changes state, then that's going to cause the parameter to change state.
The parameters for “Crop Production” scatter plot, “Chemical Additives Usage” chart and “World Map” map are the presence of axes. Because it’s difficult to compare the chemical additives usage in the scatter plot, excluding the axes will enable the readers to see the difference in chemical additives usage among nations. It’s also difficult to compare the crop production among nations, so excluding the axes will enable the readers to see the difference in crop production in a map. As the parameter changes the scene state, it’ll cause other parameters to change the scene states.


## Triggers: 
The narrative visualization starts with a title page. It gives the reader the option to click on the “Explore” button to start understanding the message. The button triggers a slide down to the first scene “Crop Production.” The navigation bar keeps track of which scenes the readers are at, so it’ll underline and change text to the scene it’s at. The automatic scroll down by pressing the button is an affordance to the reader to scroll up or down in order. The changes happening in the navigation bar is an affordance to the reader that they can hop between scenes out of order.
The scatter plots and the bubble chart have triggers that allow readers to know which countries the data indicate. The mouse over hover circles show a text of the country. In addition, the bubble chart also shows the average fertilizer and pesticide usage in tonnes. In the map, the reader can trigger highlighting the countries by hovering the mouse over it.
On the bottom right corner, there’s a button that triggers the narrative visualization to scroll all the way up to the home page. The upward arrow is the affordance to communicate to the user what its intent is. 
