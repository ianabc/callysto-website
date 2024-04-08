---
title: Food prices in Canada
date: 2023-08-03
---
<h2>How has consumer product pricing changed in 2022?</h2>

<p>Grades 6 - 12</p>
<p>According to recent headlines (e.g. this <a href="https://www.cbc.ca/news/business/food-prices-inflation-groceries-1.6499640" target="_blank" rel="noopener">CBC</a> article), grocery prices in Canada are soaring. Is there any correlation between this surge in food prices and the Covid-19 pandemic?</p>
<p>In this exercise, we investigated the monthly average retail price of common grocery store products in Canada from 2017 to 2022. We also analyzed provincial grocery price trends.</p>
<h4>To answer our question we:</h4>
<ul>
<li style="font-weight: 400;" aria-level="1">Used monthly average retail price data (2017-2022) for selected products across the country * from&nbsp;<a href="https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810000101" target="_blank" rel="noopener">Statistics Canada</a></li>
<li style="font-weight: 400;" aria-level="1">Used historical product price data (1995-2022) for Canada, also from <a href="https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=1810000101" target="_blank" rel="noopener">Statistics Canada</a></li>
<li style="font-weight: 400;" aria-level="1">Created a series of line graphs</li>
</ul>
<p><em>* Note: The prices for Northwest Territories, Nunavut, and Yukon were not found in the Statistics Canada dataset.</em></p>
<p>First, we plotted the prices of different products over recent years in each Canadian province. In this interactive plot (below), you can select specific products from the dropdown menu. You can also toggle the province and territory names to turn on/off the respective data graphs.</p>
<p>Notice that the plot for each product is “normalized,” which means that the prices are shown relative to the Canadian average. For example, the average price of two litres of apple juice in Canada was $2.80 in January 2017. We divided the price of apple juice in each month by 2.8 to rescale them. The rescaling set the price index (normalized price) for Canadian average in January 2017 to 1.0. Now, we can easily compare data points on the plots to this price index.</p>
<p>For instance, the apple juice price index in Alberta in June 2017 was 1.1. This means the price was 10% higher (1.1/1.0 x 100%) than the Canadian average in January 2017. We can easily calculate the actual price by multiplying the price indices by the same factor of 2.8. The actual price of apple juice in Alberta in June 2017 was $2.8 x 1.1 = $3.08.</p>
<p>Note that rescaling the data points does not change the shape of our plots, it just makes it easier for us to compare the different data points.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-viz-of-the-week/price-comparison-Canada/visualizations/fig2-NormalizedPricesOverTime.html" width="100%" height="600" scrolling="no" seamless="seamless"></iframe></p>
<p>In this line graph visualization, you can see that while the price of two litres of apple juice in Alberta has increased steadily (~ 20%) since 2017, the price of oranges has increased by almost 80%. Try clicking on the province names to focus on the province of interest.</p>
</div>
	</div>
</div>
<div class="fl-module fl-module-rich-text fl-node-qa1zkpj268rs" data-node="qa1zkpj268rs">
	<div class="fl-module-content fl-node-content">
		<div class="fl-rich-text">
	<p>Next, we plotted the current prices (as of May 2022) of different products on a regional map. This plot allows you to visualize variations in price across geographical regions.</p>
<p><iframe loading="lazy" id="igraph" class="post-img-shadow" style="border: none;" src="https://callysto.github.io/data-files/data-viz-of-the-week/price-comparison-Canada/visualizations/fig4-prices-choropleth.html" width="100%" height="750" scrolling="no" seamless="seamless"></iframe></p>
<p>As you can see, the lowest prices for two litres of apple juice are in Ontario, and the highest prices are in the adjacent province of Quebec. The lowest price for a kilogram of beef sirloin is in Newfoundland and Labrador, and the highest is in Quebec. There is not much variation in the price of a kilogram of beef sirloin across the prairie provinces.</p>
<p>Overall, we observed a fixed pattern in the change in prices for seasonal products, such as apples, pears, and cabbages. In May 2022, the price of most grocery store products increased substantially across Canada. While this price hike affected some provinces more than others, the overall trend was a general increase in prices across all Canadian provinces.</p>
<p>What do you notice in this data visualization? Can you think of some factors contributing to this price hike?</p>
</div>
	</div>
</div>
</div>
</div>
	</div>

<div class="fl-col-group fl-node-qb7r6p3sztdi" data-node="qb7r6p3sztdi">
			<div class="fl-col fl-node-c97ob03fwlxm" data-node="c97ob03fwlxm">
	<div class="fl-col-content fl-node-content"><div class="fl-module fl-module-rich-text fl-node-3idmcfe2xn58" data-node="3idmcfe2xn58">
	<div class="fl-module-content fl-node-content">
		<div class="fl-rich-text">
	<h2><b>Reflect on what you see</b></h2>
<p>Look and interact with the data visualizations above. When you hover your mouse over the plots, you’ll notice that more information appears. You can also use the legend to make plots appear and disappear.</p>
<p><strong>Think about the following questions.</strong></p>
<ul>
<li>What do you notice about these graphs?</li>
<li>What do you wonder about the data?</li>
</ul>
<h4><b>Use the fill-in-the-blank prompts to summarize your thoughts.</b></h4>
<ul>
<li aria-level="1">“I used to think _______”</li>
<li aria-level="1">“Now I think _______”</li>
<li aria-level="1">“I wish I knew more about _______”</li>
<li aria-level="1">“These data visualizations remind me of _______”</li>
<li aria-level="1">"I really like _______”</li>
</ul>
<h2><b>Learn how we visualized the data</b></h2>
<p>Go to our <a href="https://bit.ly/dataviz-foodprices" target="_blank" rel="noopener">walk-through</a> (in Jupyter notebook format) to see how the data science process was applied to creating these graphs from formulating a question, gathering the data, and analyzing the data with code to creating the graph.</p>
</div>
	</div>
</div>
</div>
</div>
	</div>
		</div>
	</div>
</div>
</div>