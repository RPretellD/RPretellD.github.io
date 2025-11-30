---
layout: single
permalink: /team/
author_profile: false
---

<style>
/* ===== Team page layout ===== */
.team-grid {
  display: flex;
  flex-direction: column;
  gap: 60px; /* vertical space between people */
}

/* Grid: photo left, short intro right, long content spans full width below */
.team-member {
  display: grid;
  grid-template-columns: 250px 1fr;
  grid-template-areas:
    "photo intro"
    "full  full";
  column-gap: 30px;
  row-gap: 10px;
  align-items: center;
}

.team-member img {
  grid-area: photo;
  width: 250px;
  height: auto;
  border-radius: 0;
  display: block;
}

.team-text {         /* short intro next to the photo */
  grid-area: intro;
  max-width: 900px;
}

.team-bio {          /* long stuff: spans under photo + intro, full width */
  grid-area: full;
}

/* Mobile */
@media (max-width: 720px) {
  .team-member {
    grid-template-columns: 1fr;
    grid-template-areas:
      "photo"
      "intro"
      "full";
  }
  .team-member img { width: 200px; }
}
</style>


<!-- Renmin's students -->

<br>
<h1 class="team-section" style="text-align:center; text-decoration:underline;"> TEAM </h1>
<br>

<div class="team-grid">

	<div class="team-member">
		<img src="/images/SantoshKatuwal.jpeg" alt="Santosh Katuwal">
	
		<div class="team-text">
	
			<h1 style="margin:0;"> Santosh Katuwal </h1>
			<br>
			
			<p><strong>Research areas<br></strong>
				Seismic site response, ground motion modeling</p>

			<p><strong>Degree objective:&nbsp;&nbsp;&nbsp;</strong>
				PhD (expected: May 2027)</p>
			
			<p>
			Santosh completed his master’s degree at Purbanchal University, where he graduated in first position and received 
			two Gold Medals for securing the top rank. At UNR, he was awarded the Nevada DRIVE Graduate Research Assistantship. Santosh 
			works on integrating theoretical approaches and computational analysis to better understand site effects. His long-term goal 
			is to develop tools and models that connect seismic data with engineering applications to support communities in reducing seismic risk.
			</p>
	  
		</div>
    </div>


	<div class="team-member">
		<img src="/images/Carlos.jpg" alt="Carlos Fernandez">
	
		<div class="team-text">
	
			<h1 style="margin:0;"> Carlos Fernández Portal </h1>
			<br>
			
			<p><strong>Research areas<br></strong>
				Seismic site response, V<sub>S</sub> profile uncertainty</p>
			
			<p><strong>Degree objective:&nbsp;&nbsp;&nbsp;</strong>
				MS (expected: Dec. 2026)</p>
				
			<p>
			Carlos earned his Bachelor’s degree in Civil Engineering from the National University of Engineering in Lima, Peru. 
			Before UNR, Carlos worked as a Research Assistant at CISMID (Peru). Carlos' research interests include geotechnical earthquake 
			engineering, dynamic soil behavior, and programming applications in Python for data analysis.
			</p>
	  
		</div>
    </div>


	<div class="team-member">
		<img src="/images/Cesar.jpeg" alt="Cesar Sanchez">
	
		<div class="team-text">
	
			<h1 style="margin:0;"> Cesar Manuel Sanchez Ore </h1>
			<br>
			
			<p><strong>Research areas<br></strong>
				Soil spatial variability, tailings</p>
			
			<p><strong>Degree objective:&nbsp;&nbsp;&nbsp;</strong>
				MS (expected: Dec. 2026)</p>
				
			<p>
			Cesar holds a BS in civil engineering from the National University of Engineering in Peru. Before joining UNR,
			Cesar spent three years with WSP at the Lima office working in tailings dam projects. 
			Cesar's research interests include mine tailings and soil's spatial variability. 
			</p>
	  
		</div>
    </div>

</div>
