---
title: COVID-19 and log scales
date: 2020-11-26
---
<h2> Have you ever wondered how you can use data to learn about the growth of COVID-19 cases?</h2>
<p>We answered that question by looking at how long it takes for reported COVID-19 cases to double in Canada. We did this by plotting them using a logarithmic or “log” scale on a line graph.</p>
<p>We created two log scale graphs:</p>
<ul>
<li>Daily reported cases of COVID-19 in Canada</li>
<li>COVID-19 fatalities in Canada</li>
</ul>
<h3>What’s a log scale?</h3>
<p>Log scales allow us to identify when&nbsp;<a href="https://www.dictionary.com/browse/exponential-growth" target="_blank" rel="noreferrer noopener">exponential growth</a>&nbsp;is happening, even if we don’t see that right away in our data. To see if there’s exponential growth, we tell the log scale what to do using math. In our case, we wanted to see how many days it took for COVID-19 cases in Canada to double.</p>
<h3>What do the blue bars and red lines mean?</h3>
<p>There are two plots in these visualizations: a bar plot and line plot.</p>
<ul>
<li>Blue bars&nbsp;(left-hand “y-axis”): this is a bar plot that shows the number of daily reported cases. To create this plot, we used data from the&nbsp;<a href="https://systems.jhu.edu/" target="_blank" rel="noreferrer noopener">Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE).</a></li>
<li>Red line:&nbsp;this is our log-scale line plot that we created by doing some math. It matches up with the red numbers on the right-hand side of the graph.&nbsp;It shows us how many days it takes for COVID-19 cases to double.&nbsp;We made this happen by telling our log scale to take the data from the JHU CSSE and count it using a base-2 log scale. This means we count in factors of 2, and the y-axis values represent the exponent values. For example, a y-axis value of 5 means 2^5 = 32 confirmed cases.</li>
</ul>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-viz-of-the-week/covid-19-visualizations/reported_Canada_.html" width="100%" height="600" scrolling="no" seamless="seamless"></iframe></p>
<p class="has-text-align-center"><em>Data source:&nbsp;<a href="https://systems.jhu.edu/" target="_blank" rel="noreferrer noopener">Johns Hopkins University Center for Systems Science and Engineering</a></em></p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-viz-of-the-week/covid-19-visualizations/fatal_Canada_.html" width="100%" height="600" scrolling="no" seamless="seamless"></iframe></p>
<p class="has-text-align-center"><em>Data source:&nbsp;<a href="https://systems.jhu.edu/" target="_blank" rel="noreferrer noopener">Johns Hopkins University Center for Systems Science and Engineering</a></em></p>
<h2>Reflect on what you see</h2>
<p>Look and interact with the data visualizations above. When you mouse-over the visualizations, you’ll notice more information appears.</p>
<p>Think about the following questions:</p>
<ul>
<li>What do you notice about the blue bar plot?</li>
<li>What do you notice about the red line plot?</li>
<li>What do you wonder about the data?</li>
<li>Can you use the plot to identify on what dates the number of cases doubled?</li>
</ul>
<p>Use the fill-in-the-blank prompts to summarize your thoughts:</p>
<ul>
<li><em>“I used to think_______”</em></li>
<li><em>“Now I think_______”</em></li>
<li><em>“I wish I knew more about_______”</em></li>
<li><em>“These data visualizations remind me of_______”</em></li>
</ul>
<h2>Learn how we visualized the data</h2>
<p><a href="https://tinyurl.com/yxfqdkjb" target="_blank" rel="noreferrer noopener">Go to our walk-through</a>&nbsp;(in Jupyter notebook format) to see how we used the data science process (formulating a question, gathering the data, analyzing the data with code, and creating the visualizations) to create these visualizations. In the notebook, you can also explore similar visualizations for several countries affected by COVID-19.</p>
<h2>Teacher resource</h2>
<p>To learn more about how to use Callysto learning resources (Jupyter notebooks) in your classroom, visit our&nbsp;<a href="https://bit.ly/callystostarterkit">getting started</a>&nbsp;page.</p>