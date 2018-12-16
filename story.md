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
	   <br>
	   The map below illustrates the locations of everyone whom was listed as an inventor in a patent whose application was filed in 2013. It does not come as much of a surprise that inventors are spread out quite unevenly around the world, with a noteworthy sparsity in developping regions like Latin America, Africa, the Middle East, and Central Asia, but also quite a few high-density centers. Among the latter are the usual suspects : in the United-States, Southern California and the North-East Coast have among the highest concentration of inventors in the world. In Europe, Germany seems to be leading the pack while in Asia, that role is taken on by Japan.
   </div>
   
   <div class="story-figure">
      <figure>
      {% include All_2013.html %}
      <figcaption> <b>2013 Heat Map.</b> Map illustrating the distribution of individuals listed as inventors in patent applications filed in 2013. </figcaption>
      </figure>
   </div>
   
   <div class="story-text">
   	   If you zoom in the map on North America, you'll notice that while on the US West Coast, inventors are packed very densily around a few cities - namely, Seattle and San José-San Francisco - it's a completely different story across the Atlantic : high numbers of inventors seem to be spread somewhat evenly across all of Germany, Switzerland, the Netherlands, Belgium, The United Kingdom, and across many other European cities. In Asia, the contrast is even more stark between Japan, South Korea, and Taiwan on one hand, and China, where only Shanghai and Hong Kong have any significant concentration of inventors, on the other.
   	   
   	   <br><br><h4>
   	      A Historical Perspective : 1990-2016
   	   </h4>
   	   
   	   While these disparities may seem massive, looking at historical data, from 1990 until 2016, offers a different perspective. This next map pictures the same frame as above, but illustrates the evolution of the density of inventors on this timeline as a timelapse. It should be noted that the chronology illustrated in this following graphs, as well as in all the other graphs in this article, is based on the dates at which the patent applications were filed, instead of the dates at which the patents were granted. The reasoning behind this choice is that at the time of the patent application, the innovation supporting it already exists, and what we want to paint here is a picture of innovation. This does however have as a consequence that after 2013, we obverse a rapidly diminishing number of patents and inventors. This is due to the long delays that can exist between the moment of filing a patent application and obtaining it, a delay of often a few years, and the fact that the PatentsView database only incorporates patents once they have been formally accepted. 
      
   </div>
   
   {% include image.html file="/assets/All.gif" title="World View" caption="Timelapse of the distribution of inventors in the world for the period 1990-2016."%}   
   
   <div class="story-text">
   What is perharps not so obvious when looking at the timelapse on this scale is the particular dynamics of the evolution of the distribution of inventors in different regions of the world. To better discern what is going on in Asia, Europe, and North America during this timeframe, we take a look at the maps which follow.
   </div>
   
   {% include image.html file="/assets/Asia_All.gif" title="Zoom on Asia." caption="Timelapse of the distribution of inventors in Asia for the period 1990-2016."%}
   
   <div class="story-text">
   Most notably in South Korea and in Taiwan, at the turn of the new millenium, the number of innovators grows from a moderate size up to the same scale as Tokyo, Japan. This coincides perfectly with the democratization occuring in South Korea at that time.
   </div>
   
   {% include image.html file="/assets/Europe_All.gif" title="Zoom on Europe." caption="Timelapse of the distribution of inventors in Europe for the period 1990-2016."%}
   
   <div class="story-text">
   What is most striking about Europe is that the region does not exhibit any significant change during the period in question. Some places - namely Paris and Munich - do seem to grow faster than other European countries but in general inventors remain mostly spread out accross the continent. One interesting fact to note is that the reunification of Germany does seem to lead to a steady growth in the number of inventors in the East after 1990.
   
   </div>
   
   {% include image.html file="/assets/US_All.gif" title="Zoom on the US." caption="Timelapse of the distribution of inventors in the US for the period 1990-2016."%}
   
   <div class="story-text">
   As for the US, while at the start of the 1990's, the distribution of innovators closely resembles that of Europe - with the notable exception of the Mountain States - from 2000 onwards the density of inventors in a number of cities grow remarkably : New York, Boston, Austin, Houston, Seattle, Portland, San Francisco, Los Angeles, to name a few.
   
   <br><br><h4>
      A Quantitative Perspective
   </h4>
   While these maps paint vivid picture of how innovation has evolved throught time in different places, we take a look at the numbers behind these maps before being drawing definitive conclusions. From the first graph below we can see spectacular growth in the raw number of patent applications that are filed each year in the period under scrutiny. The number of utility patent applications in particular experiences a growth of 150% between 1990 and 2013. What also stands out from this graph is the almost constant proportion of patent types. 'Other Patents' include plant patents, defensive publications, and statutory invention registrations.
   
   <br><br>
   
   While the growth in the number of patents is staggering, from the second graph shown below we learn that the increase in the number of inventors listed in patent applications has grown even more : from 1990 to 2013, a more than 160% increase. So while most all research fields today require always more specialization, an ever growing number of innovators are required in practice to actually innovate. Contrast this conclusion with the information seen on the bottom-most graph, which illustrates the number of individuals listed as assignees in patent applications during each year under consideration. While the number grows until the start of the 2000's, it actually starts shrinking after this point. 
   
   <br><br>
   
   The initial growth in individuals as inventors, we suspect, can be attributed to the Dot-com bubble. in the late 1990's to early 2000's, a lot of capital was flowing to people whom inventors perceived as being technological visionnaries. After these flows starting drying up, the number of individuals as assignees also started coming back down. While there are still around 1500 patent applications every year filed by individuals, this completely pales in comparison to the number of innovations made by people that are part of teams. In fact, in the third graph from the top, we see that the number of innovators that are part of the top 10 US-based and Non-US-based companies or organizations (ranked by number of patent applications in each year) represent at any given time around 20 times the number of solo innovators.
   
   <br><br> 

   Finally, when we look at the total number of patents which are cited in patent applications in each year, we can definitively say that what a typical patent holder today is one that is part of a large network and which is supported in their innovations by many other large networks of innovations.

   </div>

   {% include image.html file="/assets/tsplot.png" title="Time Series data" caption="Evolution of the (top) total number of patent applications for each year in the period 1990-2016 and their breakdown by patent type (second from top) total number of individuals listed as inventors in the patent applications for each year (third from top) total number of individuals listed as inventors in the patent applications by the top 10 US vs Non-US assignees, ranked by the number of patent applications in the given year (fourth from top) total number of patents cited in the patent applications of each year (bottom) total number of individuals listed as assignees for each year"%}
   
   <div class="story-text">
   
   In the table below, you can see the list of the top 10 US-based assignees for each year. The accompanying graph then shows the density of the inventors listed in the patent applications by those assignees.
   
   </div>
   
   <div style="height:300px; overflow-x: scroll; overflow-y: scroll; font-weight: 20">
      <caption> <b>Top 10 Us Assignees for each year</b></caption>
      {% include top_us_table.html %} 
   </div>
   
   {% include image.html file="/assets/top10_us.gif" title="Top US Assignees." caption="Timelapse of the distribution of inventors in the world for the 10 largest US-based assignees, ranked by the number of patent applications in the given year." %} 
   
   <div class="story-text">
   
       What is interesting here is the density of inventors from US-based assignees in India. While there are close to none in the early 1990's,
      
   </div>
   
   <div style="height:300px; overflow-x: scroll; overflow-y: scroll; font-weight: 20">
      <caption> <b>Top 10 Non-Us Assignees for each year</b></caption>
      {% include top_nonus_table.html %}
   </div>
   
   {% include image.html file="/assets/top10_nonus.gif" title="Top Non-US Assignees." caption="Timelapse of the distribution of inventors in the world for the 10 largest Non-US-based assignees, ranked by patent applications in the given year." %}   
   
   <div class="story-text">
   
       ...
      
   </div>
   
   {% include image.html file="/assets/tsplot_assignees.png" title="Inventors for Top Assignees." caption=" Evolution in the number of inventors cited in the patent applications for some of the top US and Non-US Assignees, ranked by the number of patent applications."%}
   
   <div class="story-text">
   
       ...
      
   </div>

   <div class="story-figure">
      <figure>
      {% include facebook.html %}
      <figcaption> <b>Facebook 2013 Display Screen Patent.</b> Map illustrating the distribution of individuals listed as inventors in the patent application (Layer 0), and the distribution of the inventors in the patents cited by patent application (Layer 1), etc.. </figcaption>
      </figure>
   </div>
   
   <div class="story-text">
   
       ...
      
   </div>

   <div class="story-figure">
      <figure>
      {% include tencent.html %}
      <figcaption> <b>Tencent 2013 Display Screen Patent.</b> Map illustrating the distribution of individuals listed as inventors in the patent application (Layer 0), and the distribution of the inventors in the patents cited by patent application (Layer 1), etc.. </figcaption>
      </figure>
   </div>
