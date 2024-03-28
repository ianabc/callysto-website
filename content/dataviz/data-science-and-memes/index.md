---
title: Data science and memes
date: 2020-12-02
---
<h2> Have you ever wondered what meme data looks like?</h2>
<p>We answered that question by looking at a dataset based on data from the "<a href="https://twitter.com/dog_rates" target="_blank" rel="noopener">WeRateDogs</a>" Twitter account. The dataset was created by <a href="https://www.sfu.ca/computing/people/faculty/gregbaker.html" target="_blank" rel="noopener">Greg Baker</a>, a Computing Science instructor at Simon Fraser University in British Columbia (BC). Greg's inspiration for the dataset came from an <a href="http://dhmontgomery.com/2017/03/dogrates/" target="_blank" rel="noopener">article</a> written by journalist David Montgomery.</p>
<p><a href="https://twitter.com/dog_rates/status/1295405819840749568"><img loading="lazy" decoding="async" class="alignright size-full wp-image-4145" src="weratedogs-1.png" alt="" width="481" height="471" srcset="weratedogs-1.png 481w, weratedogs-1.png 300w" sizes="(max-width: 481px) 100vw, 481px"></a></p>
<p>WeRateDogs shares and scores funny dog pictures. Usually the dogs end up with a score above 10/10 (take a look at the <a href="https://twitter.com/dog_rates/status/1295405819840749568" target="_blank" rel="noopener">example WeRateDogs tweet</a> to the right). This account is also credited for creating meme language you may know, like "doggo" and "pupper."</p>
<p><span style="color: #993366;"><strong>We wanted to figure out if the scores given to dog pictures on WeRateDogs were increasing over time.</strong> </span></p>
<p>To do this, we created a scatterplot using the dataset.</p>
<ul>
<li>The <span style="color: #ff0000;">red line</span> in the scatterplot is the line of best fit. It shows us how the scores changed over time.</li>
<li>The <span style="color: #0000ff;">blue dots<span style="color: #333333;"> in the scatterplot</span> <span style="color: #333333;">represent tweets with a dog rating (like the WeRateDogs tweet above).</span></span></li>
</ul>

<iframe loading="lazy" id="igraph" style="border: none;" src="https://callysto.github.io/data-viz-of-the-week/dog-rating-inflation/best-fit.html" width="100%" height="600" scrolling="no" seamless="seamless"></iframe>

<p><span style="font-size: 10pt;"><i data-stringify-type="italic">Data source: WeRateDogs Twitter account. Dataset creator: Greg Baker, Computing Science instructor, Simon Fraser University. OLS means "Ordinary Least Squares" which is a method for creating lines of best fit.</i></span></p>

<p><!-- wp:heading --></p>
<h2>Reflect on what you see</h2>
<p><!-- /wp:heading --> <!-- wp:paragraph --></p>
<p>Look and interact with the data visualization above. When you mouse-over the scatterplot, you’ll notice more information appears.</p>
<p><!-- /wp:paragraph --> <!-- wp:heading {"level":4} --></p>
<h4>Think about the following questions:</h4>
<p><!-- /wp:heading --> <!-- wp:list --></p>
<ul>
<li>What do you notice about the scatterplot?</li>
<li>What do you wonder about the data?</li>
</ul>
<p><!-- /wp:list --> <!-- wp:heading {"level":4} --></p>
<h4>Use the fill-in-the-blank prompts to summarize your thoughts:</h4>
<p><!-- /wp:heading --> <!-- wp:list --></p>
<ul>
<li><em>“I used to think_______”</em></li>
<li><em>“Now I think_______”</em></li>
<li><em>“I wish I knew more about_______”</em></li>
<li><em>“This data visualization reminds me of_______”</em></li>
</ul>
<p><!-- /wp:list --> <!-- wp:heading --></p>
<h2>Learn how we visualized the data</h2>
<p><!-- /wp:heading --> <!-- wp:paragraph --></p>
<p><a href="https://hub.callysto.ca/jupyter/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fcallysto%2Fdata-viz-of-the-week&amp;branch=main&amp;subPath=dog-rating-inflation/weratedogs-bestfit.ipynb&amp;depth=1" target="_blank" rel="noreferrer noopener">Go to our walk-through</a> (in Jupyter notebook format) to see how we used the data science process (formulating a question, gathering the data, analyzing the data with code, and creating the visualizations) to create the scatterplot.</p>