# IPERS Benefit Payments and Payees by County Project

### February 16, 2020

**Today's Progress:** I adjusted the map to use the Mercator projection, moved the legend to the bottom and added a label, and I am looking at adding a toggle button to potentially add interactivity. The toggle would re-color the map to visually show the number of payees instead of the amount of money. 

**Thoughts:** I would have to restructure some things like the color scale to make the interactivity work, but I think it would provide a nice challenge in reformatting and reusing code with new data piped in. I haven't worked with interactivity or transitions in a D3 project yet, and this could be a good opportunity to learn.

**Link(s) to work:**
1. [IPERS Benefit Payments and Payees by County (WIP)](https://codepen.io/legendoflilac/pen/KKwLypE)
2. [IPERS Data PDF](https://www.ipers.org/sites/default/files/SAFR-2019%20final.pdf)
3. [Mercator Example](https://riptutorial.com/d3-js/example/27989/mercator-projections)

### February 9, 2020

**Today's Progress:** Using the same template as the 100 Days of Code log to write about my progress on my personal choropleth map. Today I worked on implementing a legend, which was a bit trickier than the one I did for the example project because the numbers needed formatted some in order to be human-readable. However, the implementation was largely the same--make rects and a scale/axis for the legend, get each section to be a different fill color, and place the tick values as needed. 

**Thoughts:** I'm thinking I'll need to change the projection of the map to a Mercator view to make it look better with my horizontal legend. Not looking forward to having to play with the scale and such again to make that work...

**Link(s) to work:**
1. [IPERS Benefit Payments and Payees by County (WIP)](https://codepen.io/legendoflilac/pen/KKwLypE)
2. [IPERS Data PDF](https://www.ipers.org/sites/default/files/SAFR-2019%20final.pdf)
