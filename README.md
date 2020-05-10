# banana-project

[Source for Inspiration](https://de.wikipedia.org/wiki/Kühlschifffahrt)
<p align="middle">
  <img src="resources/banana_graph.png" width="40%" />
</p>

## Demos
[R Data Visualization](https://amawest.github.io/banana-project/R_Banana_Project/docs/)

[Homeless](https://amawest.github.io/banana-project/R_Banana_Project/docs/homeless)

[Python Line Chart Visualization](https://clarkdatalabs.github.io/banana-project/Python_Banana_Project/docs/linechart/)

[Python Line Chart(improved) Visualization](https://clarkdatalabs.github.io/banana-project/Python_Banana_Project/docs/linechart-improved/)

[Python Animation Visualization](https://clarkdatalabs.github.io/banana-project/Python_Banana_Project/docs/animation/)

## Context
The most environmentally-friendly way of transporting certain foods intercontinentally is through the use of reefers. A reefer, or a refrigerated ship used for overseas transport of perishable goods, constitute the main source of transport for the banana trade. It was the invention of the refrigerated reefer ship that first brought Jamaican bananas to the English in 1897. Before then, bananas could only be shipped relatively short distances. This graph takes a look at the banana exports by various countries between 1994 - 2005. Data is derived from the United States Food and Agriculture Organization (FAO).

## Explanation
The original graph is particularly misleading. For example, while the graph says 1994-2005, the graph itself actually starts in 1993. Looking at the boxes listed between 1993-1994, Ecuador has just over 3 million banana exports; on the other hand, the banana exports for 1993 were actually only 2.5 million. These dynamics are better captured in a line plot than can not be portrayed in a 3-dimensional bar graph. 

Secondly, country levels in the back of the plot may be veiled by other country data, which could be confusing. 

Thirdly, the color is coded by year instead of by country. Typical practice would be to denote countries with different colors.

Finally, the use of bananas as a background image, while topical, contributes to visual overload and makes it hard to immediately understand what’s going on.

Glancing at the line graphs (full tutorials in both Python and R included), one can get the same information in a more easily digestible format. With a 2-dimensional line chart no country is shrouded, and the dynamics between years is better portrayed than in a box plot. Scrolling over the graph gives helpful information in regards to year, country, and export value. 
