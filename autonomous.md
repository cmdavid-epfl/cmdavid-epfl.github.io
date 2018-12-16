---
layout: story
permalink: /autonomous/
---

   <div class="story-text">
	   <h3>
	      Autonomous Navigation Technology.
	   </h3>
	   <h4>
	      <A class="page-link" href="{{ "/story" | relative_url }}#anchor-list">Back to list</A>
	   </h4>
	   <br>
	   In this section, we compare patents related to Autonomous Navigation Technology for two privately owned companies, the German carmaker Volkswagen AG (patent <a class="page-link" href="https://patents.google.com/patent/US6151539A/">US6151539A</a>) and the German conglomerate Siemens AG (patent <a class="page-link" href="https://patents.google.com/patent/US5793934A/">US5793934</a>), with that of the United States Navy (patent <a class="page-link" href="https://patents.google.com/patent/US5111401A/">US5111401</a>).

       <br><br>
	   The patent applications reveal that the U.S. Navy filed its patent in May of 1990 whereas Volkswagen and Siemens filed theirs in November of 1998 and June of 1995 respectively. Hence, in this case is it seems that the navy was at the forefront in the development of new technology, as has been seen for other innovations such as the GPS and the development of drones.
      <br><br>
 	  When exploring the various layers of the maps below, we observe from the <b>layer 1</b> cited patent inventors that the US Navy solely cites patents from the US and Japan, whereas the two German companies have a broader base of citations. This is in line what we would expect, as the U.S. Navy were earlier out with their patent. Furthermore, it would be expected for the US Navy to have a relatively stronger connection to national research facilities and other national organizations, as opposed to that of the two privately own companies.
 	  
 	  <br><br>
 	  Finally, from the similarities table at the bottom of the page, we see that while Volkswagen's and Siemens' networks are very similar to each other (more than 68% at the 3rd layer), the US Navy's network is quite distinct, at least up until 3rd layer.
   </div>
 
   <div class="story-figure">
      <figure>
      {% include vw.html %}
      <figcaption> <b>Volkswagen AG Patent.</b> Map illustrating the distribution of individuals listed as inventors in the patent application (Layer 0), and the distribution of the inventors in the patents cited by patent application (Layer 1), etc.. </figcaption>
      </figure>
   </div>
   
   <div class="story-text">
   
   </div>

   <div class="story-figure">
      <figure>
      {% include siemens.html %}
      <figcaption> <b>Siemens AG Patent.</b> Map illustrating the distribution of individuals listed as inventors in the patent application (Layer 0), and the distribution of the inventors in the patents cited by patent application (Layer 1), etc.. </figcaption>
      </figure>
      
      
   <div class="story-text">
   
    
   </div>
   
   <div class="story-figure">
      <figure>
      {% include navy.html %}
      <figcaption> <b>US Secretary of Navy Patent.</b> Map illustrating the distribution of individuals listed as inventors in the patent application (Layer 0), and the distribution of the inventors in the patents cited by patent application (Layer 1), etc.. </figcaption>
      </figure>
      
      
   <div class="story-text">
   
    
    
   <br><br>
   <div style="height:500px; font-weight: 20; width:200px; float:left; padding-right:20px; ">
      <caption> <b>Siemens - Volkswagen</b></caption>
      {% include vw_siemens_sim.html %} 
   </div> 
   
   <div style="height:500px; font-weight: 20; width:200px; float:left; padding-right: 20px; ">
      <caption> <b> Siemens - US Navy</b></caption>
      {% include siemens_navy_sim.html %} 
   </div> 

   <div style="height:500px; font-weight: 20; width:200px; float:left; padding-right: 20px; ">
      <caption> <b>Volkswagen - US Navy</b></caption>
      {% include vw_navy_sim.html %} 
   </div> 

   </div>
   

