---
layout: story
title: Analysis
permalink: /story/
---

   <div class="story-text">
	   <h2>
	      What we can learn from patents data.
	   </h2>
	   
	   <h3>
	      Part 1. The Big Picture.
	   </h3>
	   The first map below illustrates the locations of everyone whom was listed as an inventor in a patent whose application was filed in 2013. It does not come as much of a surprise that inventors are spread out all around the world, with some higher-density centers. These centers are the usual suspects :   
   </div>
   
   <div class="story-figure">
      {% include All_2013.html %}
   </div>
   
   <div class="story-text">
   
       Note that after 2013, the diminishing number of inventors is mainly due to the delay between applying for a patent and obtaining it, which can take a few years. We us as date the patent application date, but the data is not included in the PatentsView database until the patent is accepted. 
       
       This next map shows the same map as above, but as a timeline between 1990 and 2016.
      
   </div>
   
   {% include image.html file="/assets/All.gif" title="World View" caption="Timelapse of the distribution of inventors in the world for the period 1990-2016."%}
   
   <div class="story-text">
   
      The graphs shown below...
      
   </div>
   
   {% include image.html file="/assets/tsplot.png" title="Time Series data" caption="Evolution of the (top) total number of patent applications for each year in the period 1990-2016 and their breakdown by patent type (second from top) total number of individuals listed as inventors in the patent applications for each year (third from top) total number of individuals listed as inventors in the patent applications by the top 10 US vs Non-US assignees, ranked by the number of patent applications in the given year (fourth from top) total number of patents cited in the patent applications of each year (bottom) total number of individuals listed as assignees for each year"%}
   
   
   <div class="story-text">
   
       ...
      
   </div>
   
   {% include image.html file="/assets/Asia_All.gif" title="Zoom on Asia." caption="Timelapse of the distribution of inventors in Asia for the period 1990-2016."%}
   
   {% include image.html file="/assets/Europe_All.gif" title="Zoom on Europe." caption="Timelapse of the distribution of inventors in Europe for the period 1990-2016."%}
   
   {% include image.html file="/assets/US_All.gif" title="Zoom on the US." caption="Timelapse of the distribution of inventors in the US for the period 1990-2016."%}
   
   <div class="story-text">
   
       ...
      
   </div> 
   
   <div style="height:300px; overflow-x: scroll; overflow-y: scroll; ">
      <caption> <b>Top 10 Us Assignees for each year</b></caption>
      {% include top_us_table.html %} 
   </div>
   
   {% include image.html file="/assets/top10_us.gif" title="Top US Assignees." caption="Timelapse of the distribution of inventors in the world for the 10 largest US-based assignees, ranked by the number of patent applications in the given year." %} 
   
   <div class="story-text">
   
       ...
      
   </div>
   
   {% include image.html file="/assets/top10_nonus.gif" title="Top Non-US Assignees." caption="Timelapse of the distribution of inventors in the world for the 10 largest Non-US-based assignees, ranked by the number of patent applications in the given year." %}
   
   <div style="height:300px; overflow-x: scroll; overflow-y: scroll; ">
      <caption> <b>Top 10 Non-Us Assignees for each year</b></caption>
      {% include top_nonus_table.html %}
   </div>
   
   
