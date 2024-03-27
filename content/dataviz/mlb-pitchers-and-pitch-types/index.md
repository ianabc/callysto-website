---
title: MLB pitchers and pitch types
date: 2021-04-14
---
<h2>Can MLB pitching statistics be used to visualize differences in pitch types?</h2>

<p>Grades 6-12</p>
<p><a href="https://www.mlb.com/" target="_blank" rel="noopener">Major League Baseball</a> (MLB) teams can have up to 13 pitchers on their roster during the regular season, and four to six of those are usually starting pitchers. Our goal is to use MLB data to see if there are numerical differences between different types of pitches and pitchers.</p>
<p>Specifically, we wondered if we could look at MLB pitching statistics to visualize the differences in the types of pitches thrown by two successful starting pitchers, <a href="https://www.mlb.com/player/yu-darvish-506433" target="_blank" rel="noopener">Yu Darvish</a> and <a href="https://www.mlb.com/player/jon-lester-452657" target="_blank" rel="noopener">Jon Lester</a>.</p>
<p>As background, MLB pitchers will specialize in different <a href="https://www.mlb.com/glossary/pitch-types" target="_blank" rel="noopener">types of pitches</a> thrown (e.g. fastball, slider, curveball, etc.). These pitch types are achieved in part by the different speeds at which the baseball is thrown, and the rate of spin (“spin rate”) of the baseball.</p>
<h4>To answer our question we:</h4>
<ul>
<li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Used data from a </span><a href="https://github.com/palewire/baseball-notebooks" target="_blank" rel="noopener"><span style="font-weight: 400;">GitHub user</span></a><span style="font-weight: 400;"> who gathered pitching data for the 2012-20 baseball seasons from the website </span><a href="https://www.baseball-reference.com/" target="_blank" rel="noopener"><span style="font-weight: 400;">baseball-reference.com</span></a><span style="font-weight: 400;">.</span></li>
<li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">Created scatter plot graphs — </span><span style="font-weight: 400;">a type of data visualization that plots points as the relationship between two variables (or sets of data) using </span><a style="font-family: system-ui, &#39;---apple-system&#39;, BlinkMacSystemFont, &#39;Segoe UI&#39;, Roboto, Oxygen, Ubuntu, Cantarell, &#39;Open Sans&#39;, &#39;Helvetica Neue&#39;, sans-serif;" href="https://www.mathsisfun.com/data/cartesian-coordinates.html" target="_blank" rel="noopener">Cartesian coordinates</a><span style="font-weight: 400;">.</span></li>
</ul>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="ttps://callysto.github.io/data-files/data-viz-of-the-week/baseball/visualizations/DarvishPitches.html" width="100%" height="600" scrolling="no" seamless="seamless"></iframe></p>

<p><span style="font-weight: 400;">In the first plot, we can see that Yu Darvish has thrown 10 different pitch types.&nbsp; These vary with respect to both speed and spin rate, with the fastest pitch (two seam and four seam fastball types) reaching 98.8 miles per hour (MPH), and the highest spin rate for a pitch (change-up type) reaching 3,042 revolutions per minute (RPM).</span></p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-files/data-viz-of-the-week/baseball/visualizations/LesterPitches.html" width="100%" height="600" scrolling="no" seamless="seamless"></iframe></p>
<p>In the second plot, we can see that Jon Lester has thrown five different pitch types. He doesn’t throw quite as hard as Yu Darvish, with his four-seam fastball pitch type reaching 96.1 MPH. The maximum spin rate achieved by a Jon Lester pitch is 3,482 RPM. This is higher than any of Yu Darvish’s pitches, but seems to be abnormal and may be an <a href="https://www.itl.nist.gov/div898/handbook/prc/section1/prc16.htm" target="_blank" rel="noopener">outlier</a>.</p>

<h2><b>Reflect on what you see</b></h2>
<p><span style="font-weight: 400;">Look and interact with the scatter plot graphs above. When you mouse-over the scatter plots, you’ll notice more information appears.</span></p>
<h4><b>Think about the following questions:</b></h4>
<ul>
<li style="font-weight: 400;" aria-level="1"><span style="font-weight: 400;">What do you notice about the scatter plot graphs?</span></li>
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
<p>Go to our <a href="http://bit.ly/dataviz-baseball" target="_blank" rel="noopener">walk-through</a><span style="font-weight: 400;">&nbsp;(in Jupyter notebook format) to see how we used the data science process to create the line graph. (This process included formulating the question, gathering the data, analyzing the data with code, and creating the visualizations.)</span></p>