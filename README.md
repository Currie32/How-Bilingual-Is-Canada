How Bilingual Is Canada?

Summary

This data visualization should help viewers understand where and how may Canadians speak English, French, or neither of the two official languages of Canada. Using the map and adjacent menu, viewers can understand the languages spoken in each city (hover over each city to see a numerical breakdown of each type of speaker). Using the graph and its menu and legend, viewers can see how provinces and territories differ from each other in terms of languages (hover over each bar to see the percentage or population values).

Design

Map: 
A map was always essential to this data visualization. I wanted viewers to be able to see and understand where and how many Canadians speak English, French, or neither. Having a map that provided provincial and territorial boundaries was also important, as it helps viewers to better understand Canada’s geography. The size of the dots (cities) reflect the population, but the scale is a square root function, which makes it easier to see smaller cities and the larger ones do not become too big. Opacity was lowered to 0.7 to help viewers see clusters of cities, such as near Toronto and Vancouver. Light blue was chosen for the colour of the map as it is easy on the eyes, and red was chosen for the dots as it provides good contrast. Functionality such as zooming and dragging was incorporated to help viewers see areas of greater density, such as southern Ontario.

Map Menu:
I wanted there to be a way for viewers to change the information on the map. I thought this would provide some interesting interactivity. Originally, I had a button of ‘Either English or French,’ but I removed it as I thought it did not provide a great deal of new information. I chose the green hues, as they mix reasonably well with the map and the rest of the colours chosen. The darker green was created to remind viewers which button they had chosen, and the medium green indicates which button the user is hovering over, plus I like it when buttons do that.

Graph:
I thought it would also be important for people to understand which languages Canadians typically speak in each province. Presenting this information in percentages and using a stacked bar chart provides good comparison across provinces and territories. The x-axis labels are on an angle to make them more legible and help them to fit on the screen. The y-axis only has ticks every 20% as I thought that was enough (every 10% was a bit crowded). The legend helps viewers understand the chart, and the black outline around the coloured squared was done by accident, but I like it. The colours were chosen to provide decent contrast between each other, and I thought they went well with the map’s and menu’s colours. 

Second iteration:
The original graph was informative, but limited information could be learned from it, given it lacked interactivity. I wanted people to be able to play with it, so I used the legend as a sorting tool. I thought this would work best because I wouldn’t need to add another menu, and it had all the information I needed. Using underlining for hovering, and bolding for the selected language, this should provide enough of a reference for the viewer. I thought it would be neat to sort by population and population percentage for each language option. For consistency I wanted to keep the menu formatting the same as the map legend, plus this should make it more obvious to the viewer that they are both menus. I chose to use symbols rather than numbers to save space and I think it looks good.

Pop-ups:
I wanted viewers to be able to understand more about the map and graph, but I didn’t want to crowd the screen with too much information. I thought using these pop-ups (or tooltips) provided a good solution. For the map pop-up, I chose to present all of the information, rather than just the information selected from the menu; ex when ‘Bilingual’ is selected, the pop-up shows all the information and not just the Bilingual information. Also for the map pop-up, I thought opacity of 0.9 looked more pleasing than if the value was set to 1, and was easier to read than lower values. The graph pop-up has a fixed location in the top right as it does not interfere with any other information on the screen.

Second iteration:
For the graph’s pop-up, I changed the background colour to a light blue and the province font colour to a dark purple. I wanted to add more colour to the data visualization and this should provide a subtle improvement.

Header:
I wanted to keep the title and description short and simple. I think that together they provide enough information to help the viewer understand what the entire data visualization is about. The description is in italics as it looks better than in the standard font-style. The disclaimer in the top-right tells the viewers where I got my data from. Some might be curious as to why the population of cities differs from their actual numbers, this explains the difference. 

Second Iteration:
Increased the font size of the title and description. 

Layout:
I wanted everything to be visible on my screen at once (I apologize if things don’t look quite as nice on your screen if it is of a different size). Originally, I wasn’t sure if this would be possible as I did not think the map and graph would be able to sit side-by-side. However, once I tried it, it worked and looked pretty good. I put the map on the left as I think it is a more interesting visual and since we read from left to right, I thought people should see it first. 

Second Iteration:
I added tips below the map and graph to make it more obvious to users how they can interact with the data visualization. I added commas to numbers to increase readability.

Third Iteration:
Increased the font size of most elements to increase readability.

Colour Palette:
The colours that were chosen are meant to be rather neutral and easy on the eyes. I like blues and greens, and I think these shades go reasonably well together.

Feedback


1. CtrlAltDel, from Udacity forum:
I've lived most of my life in US states that border Canada and I've always wondered abut the distribution of the French speaking population, so this visualization is fascinating to me. This is definitely explanatory, with a great opening narrative. It is pretty clear that English is the most widely spoken language and that the French speaking population is primarily concentrated in Quebec. Here are some things to consider:
	•	Since the focus is on the distribution of the French speaking population it might make sense to use a horizontal bar graph where the y-axis is ordered by % French.
	•	The populations on the map are a little hard to see, because they are small. It might help to rearrange the graphic so that the map is larger overall. The map and the bar plot don't need to be side by side, stacking them may help give space to increase the map size.
	•	Consider using a color-blind friendly pallette, the currrent pallette may be problematic for readers that have common types of colorblindness.
Thanks for sharing this!

How I incorporated this feedback:
-I added interactivity to the graph, where people could sort by languages and see the population as well as the percentage of the population that speaks each language.
-The map already had the ability for zooming and dragging. I added ‘tips’ at the bottom of the map and graph so that people would know they could use the map just like Google Maps, hover over cities and bars on the graph to reveal more information.

2. Matt, a friend I showed the data vis to:
-“Is your legend centred?”
-He didn’t realize that he could use the map like Google Maps.

How I incorporated this feedback:
-I centred the legend.
-Another reason why I added the tips below the map and graph.

3. Dad, I showed the data vis to him:
-Squinted heavily at times.
-“It would be easier to read those numbers (from the map’s pop-ups) if they had commas.”

How I incorporated this feedback:
-I made most the font bigger.
-I added commas to numbers for easier readability.

4. Haylea, a friend I showed the data vis to:
-“Why are the provinces in that order (on the graph)?”
-“Maybe you should add some colour to the graph pop-up.”

How I incorporated this feedback:
-Added interactivity to the graph, the ability to sort by language, and see both population and population percentages.
-Added colour to the graph’s pop-up.

Resources
https://discussions.udacity.com/
http://bl.ocks.org/
https://groups.google.com/
http://stackoverflow.com
https://github.com/d3/d3/blob/master/API.md#number-formats-d3-format
http://www.w3schools.com
http://www.d3noob.org
http://htmlcolorcodes.com/
https://css-tricks.com/
http://www.colorhunt.co
https://coderwall.com

