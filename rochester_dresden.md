---
layout: story
permalink: /rochester_dresden/
---

   <div class="story-text">
	   <h3>
	      Rochester University and Dresden University.
	   </h3>
	   <h4>
	      <A class="page-link" href="{{ "/story" | relative_url }}#anchor-list">Back to list</A>
	   </h4>
	   <br>
	   We compare a patent from an American university with that of a European university. The interest in doing so lies in the considerable number of patents originating from European and American institutions. We thus chose universities with a similar ranking, according to the <a class="page-link" href="https://www.topuniversities.com/university-rankings/world-university-rankings/2018">QS world universities ranking</a>, namely Rochester university (in New-York city) and Technische Universitaet Dresden (in Germany). 
      <br><br>
      These two universities, at a similar time period, both proposed a patent for chemically-engineered molecules aimed at therapeutical effects : the Rochester university patented molecule is designed to inhibit the activity of some proteins involved in disorders, whereas the school from Dresden proposed a molecule with antimicrobial activity. The American patent application (<a class="page-link" href="https://patents.google.com/patent/US9814704B2/">US9814704B2</a>) was filed in 2016, followed by the European patent (<a class="page-link" href="https://patents.google.com/patent/US9969830B2/">US9969830B2</a>) whose application was filed one year later. Both patent applications were recently granted in 2017 and 2018, respectively. 
      <br><br>
      The maps displaying the networks of the inventors of the cited patents provide some interesting information : the number of layers illustrated for the University of Dresden's network had to be higher than that of Rochester University's, to better observe the significant increase in the number of inventors in their cited patents at these following layers. Thus, at <b>layer 3</b>, Rochester university has a network as large as Dresden's network in <b>layer 5</b>. This points to a faster expansion of the patents support network for Rochester than for Dresden. We can as well observe that the patent proposed by Rochester university cites patents whose inventors are located in two main incubators, that are already well-defined in <b>layer 1</b> : Europe and East Coast of US. As we peel back the layers, the number of inventors in those two centers keeps growing. As for the patent by Dresden university, it has a network of inventors that come from a more disperse set of  countries, at least until <b>layer 3</b>. It is only has of <b>layer 4</b> that the locations of the cited patents' inventors start being more concentrated. In the end, whatever the origin of the patent, in this case at least, three main geographical centers stand out : the US East coast, Central Europe and Japan.
      <br><br>
      What is then surprising is that the similarity between the two networks is almost non-existent until <b>layer 3</b>, and that even then it is only 11%.
      <br><br>
      The comparison could be extended to Universities from Africa and Asia, the two remaining continents, though for that, less recent patents should be considered, to ensure their extraction from the database.
   </div>
 
   <div class="story-figure">
      <figure>
      {% include rochester.html %}
      <figcaption> <b>Rochester University Patent</b> Map illustrating the distribution of individuals listed as inventors in the patent application (Layer 0), and the distribution of the inventors in the patents cited by patent application (Layer 1), etc.. </figcaption>
      </figure>
   </div>
   
   <div class="story-text">
   </div>

   <div class="story-figure">
      <figure>
      {% include dresden.html %}
      <figcaption> <b>Dresden University Patent.</b> Map illustrating the distribution of individuals listed as inventors in the patent application (Layer 0), and the distribution of the inventors in the patents cited by patent application (Layer 1), etc.. </figcaption>
      </figure>
      
      
   <div class="story-text">
   
   <div style="height:500px; font-weight: 20; width:200px; ">
      <caption> <b>Similarities Table</b></caption>
      {% include rochester_dresden_sim.html %} 
   </div> 
    
   </div>
