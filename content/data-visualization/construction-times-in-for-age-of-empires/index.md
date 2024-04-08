---
title: Construction times in Age of Empires
date: 2023-03-24
---
<h2>How long does it take to build different monuments, from different eras, in Age of Empires?</h2>

<p>Grades 6-12</p>
<p><a href="https://www.ageofempires.com/" target="_blank" rel="noopener"><em>Age of Empires</em></a>, a series of historical, real-time strategy video games, was originally released in 1997. Part of the game focuses on building historically significant monuments from around the world, in collaboration with others.</p>
<p>In building these historical monuments, players can experience what it must have been like to construct actual ancient architecture. Their characters advance through succeeding civilizations by building these structures. To construct these monuments, players must take into consideration how long they take to build (“time units”), as well as the type and amount of resources (wood, stone, gold, etc) needed to build the structures.</p>
<p>Players can advance through four main ages: Dark, Feudal, Castle and Imperial, each with a unique set of structures to build. The more the player advances, the more structures they have to build, and the more complex those structures become.</p>
<p>This game setup made us wonder: what is the average time taken to build a structure in each of the four ages?</p>
<h4>To answer our question we:</h4>
<ul>
<li style="font-weight: 400;" aria-level="1">Gathered data from an “API” (an application programming interface) — a mechanism that allows users to extract data from a database and parse it into a table (a “dataframe”) using Python and Jupyter notebooks.</li>
<li style="font-weight: 400;" aria-level="1">Created a box plot graph — a type of data visualization that shows the minimum, maximum, sample median, and the first and third quartiles of the data.</li>
</ul>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-viz-of-the-week/age-of-empires-ii/visualizations/box_build_time_per_age_with_wonder.html" width="100%" height="600" scrolling="no" seamless="seamless"></iframe></p>

<p>In the first plot, it looks like there is one data point for a structure called “Wonder” that distorts (or, to use statistical language, “skews”) the data. This data point increases the average time to build structures in the Imperial age.</p>
<p>If we remove the “Wonder” data point, we have a clearer view of how long the other structures take to build in each of the four ages.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-viz-of-the-week/age-of-empires-ii/visualizations/box_build_time_per_age_without_wonder.html" width="100%" height="600" scrolling="no" seamless="seamless"></iframe></p>
<p>We can now see the median build time for structures across all ages is comparable (between 35-45 time units). A data point like the “Wonder” is known in statistics as an “outlier”, that is, a data point that differs significantly from other data points in the set of observations.</p>

<h2><b>Reflect on what you see</b></h2>
<p>Look and interact with the box plots above. When you hover your mouse over the plots, you’ll notice more information appears. You can also use the legend to make plots appear and disappear.</p>
<h4><b>Think about the following questions:</b></h4>
<ul>
<li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">What do you notice about the box plot graphs?</span></li>
<li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">What do you wonder about the data?</span></li>
</ul>
<h4><b>Use the fill-in-the-blank prompts to summarize your thoughts:</b></h4>
<ul>
<li aria-level="1"><i>“I used to think_______”</i></li>
<li aria-level="1"><i>“Now I think_______”</i></li>
<li aria-level="1"><i>“I wish I knew more about_______”</i></li>
<li aria-level="1"><i>“These data visualizations remind me of _______”</i></li>
</ul>
<h2><b>Learn how we visualized the data</b></h2>
<p>Go to our <a href="http://bit.ly/dataviz-aoeii" target="_blank" rel="noopener">walk-through</a><span style="font-weight: 400;">&nbsp;(in Jupyter notebook format) to see how we used the data science process to create the line graph. (This process included formulating the question, gathering the data, analyzing the data with code, and creating the visualizations.)</span></p>