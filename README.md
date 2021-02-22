# Amber Flevaris - Portfolio

## About Me
Hi there! My name is Amber Flevaris (she/her). I'm a Pittsburgh native, studying in the Masters of Public Management part-time program at Heinz College. In addition to school part-time, I have worked full time at CMU in University Advancement for the last five years. My background is in arts and education fundraising (including a bachelor of science in sports, arts, and entertainment management from Point Park University), all in the Pittsburgh region. My ultimate goal is to run an arts non-profit in the city. I live in the Highland Park neighborhood with my husband, where we have spent most of the pandemic doing puzzles, watching Jeopardy, and rewatching every Pixar movie.  

## What I hope to learn
My work here at the university involves a lot of donor-related data, and I have found myself struggling to be able to convey it all visually. What excites me the most is learning how to master storytelling without explicitly telling the audience through words. I also hope to take all I've learned into future jobs, adding to my skillset. This is also my first time coding my own webpage (unless you count finangling the layout for my MySpace page in 2006!), which is exciting and another important experience. 

## Portfolio

Visualizing Government Debt: 

<iframe src="https://data.oecd.org/chart/6gPh" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/6gPh" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2018</a></iframe>




Using Flourish, I was able to manipulate the above data to create the following visualization: 


<div class="flourish-embed flourish-chart" data-src="visualisation/5282925"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

<div class="flourish-embed flourish-scatter" data-src="visualisation/5283261"><script src="https://public.flourish.studio/resources/embed.js"></script></div>



What makes the dot plot unique from the other two charts is its ability to compare all of the countries over time, emphasizing the story that overall, all country's debt percentage related to GDP has grown over the years. In particular, Japan has shown a significant rise from the mid-1990s to today.  The audience is able to look at the story using their own tools, watching the data change over time or picking a specific year to analyze. Using the playthrough function, the reader can see the story happening before their own eyes without much explanation from the create. Highlighted are the US and Canada to show a comparison from Western countries that the audience may be more familiar with. The media has emphasized the high debt that the US has, which lends the reader to see how steep Japan has grown their debt in regards to percentage of GDP. The first graph does a good job at showing that Japan and the other countries in 2018, the second graph shows the progression of each of country over the years, but only the third graph shows both of those attibutes together. In both the first and third visualizations, I used color to emphasize the appropriate points (Japan, USA, Canada) and gray for the other data points. 

## Homework 3 and 4: Critique by Design 

![alt text](https://github.com/aflevaris/flevaris-portfolio/blob/main/EuRmJ6sXcAQIuXs.jpg)
Link to visualization: https://twitter.com/dave_andersen/status/1362054094563737601 

This visualization was found in a tweet by a CMU professor in reply to the Allegheny County Health Department. The county has done an excellent job at tracking COVID-19 data, as well as sharing the full data set with the public. This visualization in particular, however, could use some adjustments to make it less confusing and provide a clearer story: the virus peaked in December 2020, but is trending downward to the levels we saw in early fall. 

In my updating of this visualization, I wanted to show the comparison between the daily totals and the 7 day average, as well as the impact that time of year. It clearly shows a high spike right after the holidays and things beginning to go down into January and as vaccines have started. It was important for me to show the relationship between the daily totals and 7 day average to get a sense of the trends of the data over a short period of time. However, hospitalizations still felt important as well for the overall story. 

Thinking about how I wanted to do a comparison and look at the relationship, my initial thoughts were shifting to a scatter plot, vertical bar chart, or cleaning about the line chart. If I kept it a line chart, I would want to remove the right Y axis, the many horizontal and vertical background lines, and the formatting of the dates. I also want to add in a source and better describe that the Y axis represents cases. It’s also misleading for the ICU bed line chart to begin at zero, making it seem like no ICU beds in Allegheny County were used until October 23, which is incorrect. Their use of color was difficult to interpret, given that the red of the daily case numbers stands out, but the pink and purple are difficult to see clearly underneath. This graph needs to be more spread out – though I suspect they wanted to show the dramatic December increase as best they could. 

At first glance, the chart does a good job of showing a large spoke in December and that they are tracking multiple points. The title helped show that the points were cases and hospitalizations and I liked that they gave a legend. What made this graph difficult to read was trying to decipher the different colors and what each line means. The fonts are small and the lines’ colors and lack of bold make them hard to follow in the long run other than a general shape of the graph. I also was thrown off by the double Y axis on each side and the “graph paper” background, which made following the lines even more difficult. There is also no source on this graph, which is an important piece to include. 

Mock-ups: 
 
 Graph 1 - 
 ![alt text](https://github.com/aflevaris/flevaris-portfolio/blob/main/COVID1.JPG)
 
 Graph 2 - 
 ![alt text](https://github.com/aflevaris/flevaris-portfolio/blob/main/COVID2.JPG)
 

The two people I asked to review my two mock-ups both gave excellent feedback. My husband’s immediate reactions were to read the title, look at the graph, and then check the legend to see what each line meant. He felt that the colors were a little difficult to read in the first graph in the beginning of October, but then were clearer to distinguish towards the peak. My friend felt similar to this, understanding what the chart represented and felt a broad audience could interpret that it was showing COVID-19 data for Allegheny County. They both felt that the second graph, including the bar charts with a line chart, were the most aesthetically pleasing and easy to interpret. They liked the colors, legend placement, and that I included the source data. My husband suggested changing the 7 day average to hospitalizations and getting rid of the ICU numbers, which he felt looked pretty stagnant and didn’t add much to story. My friend thought the graph could be improved by changing the dates at the bottom to months, with tick marks for each week. I liked both of their ideas and decided to incorporate them into my final solution. 

In the final using Tableau, I also made the colors less loud than the Infogram mock-up. Below is the final result, comparing daily cases with hospitalizations. 

Final: 

 ![alt text](https://github.com/aflevaris/flevaris-portfolio/blob/main/COVID3.png)
