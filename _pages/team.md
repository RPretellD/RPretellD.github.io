---
<!-- layout: single -->
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
  align-items: start;
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

/* ===== Group pictures ===== */
.group-photos {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
  margin-top: 40px;
}

.group-photos img {
  width: 100%;
  height: auto;
  display: block;
  border-radius: 0;
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

<h1 class="team-section" style="text-align:center; text-decoration:underline;"> TEAM </h1>
<br>

<!-- <h1 class="doctoral students section" style="text-align:left; font-style:italic;">Doctoral students</h1>
<br> -->

<div class="team-grid">

	<div class="team-member">
		<img src="/images/SantoshKatuwal.jpeg" alt="Santosh Katuwal">
	
		<div class="team-text">
	
			<h1 style="margin:0;"> Santosh Katuwal </h1>
			<br>
			
			<p><strong>Research areas<br></strong>
				Seismic site response, ground motion modeling</p>

			<p><strong>Degree objective:&nbsp;&nbsp;&nbsp;</strong>
				PhD (expected: 2027)</p>
			
			<p>
			Santosh completed his Master’s degree at Purbanchal University, where he graduated in first position and received 
			two Gold Medals for securing the top rank. At UNR, he was awarded the Nevada DRIVE Graduate Research Assistantship. Santosh 
			works on integrating theoretical approaches and computational analysis to better understand site effects. His long-term goal 
			is to develop tools and models that connect seismic data with engineering applications to support communities in reducing seismic risk.
			</p>
	  
		</div>
    </div>

	<div class="team-member">
		<img src="/images/DominikBrozowski.jpg" alt="Dominik Brozowski">
	
		<div class="team-text">
	
			<h1 style="margin:0;"> Dominik Brozowski </h1>
			<br>
			
			<p><strong>Research areas<br></strong>
				Soil liquefaction, numerical modeling</p>

			<p><strong>Degree objective:&nbsp;&nbsp;&nbsp;</strong>
				PhD (expected: 2030)</p>
			
			<p>
			Dominik is a third-year civil engineering student at UNR, graduating early with a Bachelor’s degree
			in May 2026. Dominik will continue his studies working towards a PhD in Geotechnical Engineering. He has internship 
			experience at Nevada Department of Transportation with concrete and soils lab work, contractor quality control, and 
			retaining wall design. Dominik’s research interests include numerical modeling, program implementation into models 
			and structural materials.
			</p>
	  
		</div>
    </div>

	<div class="team-member">
		<img src="/images/MuhsinAcar.jpg" alt="Muhsin Acar">
	
		<div class="team-text">
	
			<h1 style="margin:0;"> Muhsin Acar </h1>
			<br>
			
			<p><strong>Research areas<br></strong>
				Soil liquefaction, numerical modeling</p>

			<p><strong>Degree objective:&nbsp;&nbsp;&nbsp;</strong>
				PhD (expected: 2029)</p>
			
			<p>
			Muhsin earned his Bachelor’s degree in Civil Engineering from Firat University in Türkiye, where he ranked first 
			in the Faculty of Engineering. He also holds a Master’s degree in Geotechnical Engineering from the University of 
			Illinois at Urbana-Champaign. His master’s research focused on the numerical simulation of the dynamic response 
			of concrete-faced rockfill dams. Prior to joining UNR, Muhsin served for over seven 
			years as a Staff Engineer at the State Hydraulic Works of Türkiye. His research interests include soil liquefaction, 
			non-linear dynamic analyses and the integration of advanced numerical modeling with field instrumentation to enhance 
			the seismic resilience of critical infrastructure.
			</p>
	  
		</div>
    </div>
	
</div>

<!-- <h1 class="master students section" style="text-align:left; font-style:italic;">Master students</h1>
<br> -->

<div class="team-grid">

	<div class="team-member">
		<img src="/images/Carlos.jpg" alt="Carlos Fernandez">
	
		<div class="team-text">
	
			<h1 style="margin:0;"> Carlos Fernández Portal </h1>
			<br>
			
			<p><strong>Research areas<br></strong>
				Seismic site response, V<sub>S</sub> profile uncertainty</p>
			
			<p><strong>Degree objective:&nbsp;&nbsp;&nbsp;</strong>
				MS (expected: 2026)</p>
				
			<p>
			Carlos earned his Bachelor’s degree in Civil Engineering from the National University of Engineering in Lima, Peru. 
			Before UNR, Carlos worked as a Research Assistant at CISMID (Peru). Carlos’ research interests include geotechnical earthquake 
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
				MS (expected: 2026)</p>
				
			<p>
			Cesar holds a BS in civil engineering from the National University of Engineering in Peru. Before joining UNR,
			Cesar spent three years with WSP at the Lima office working in tailings dam projects. 
			Cesar’s research interests include mine tailings and soil spatial variability. 
			</p>
	  
		</div>
    </div>
</div>
	
<!-- 
<br>
<h1 class="undergrad students section" style="text-align:left; font-style:italic;">Undergraduate students</h1>

	<div class="team-member">
		<img src="/images/name.jpg" alt="Name">
	
		<div class="team-text">
	
			<h1 style="margin:0;"> Name </h1>
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
	
</div> -->

<hr>

<br>
<h1 class="team-section" style="text-align:center; text-decoration:underline;"> GROUP PICTURES </h1>
<br>

<figure style="margin: 0 auto 0.5rem auto; max-width: 900px;">

	<img src="/images/GroupPic_SK_birthday_2025_12_22.jpg" alt="Research group photo" 
		style="width:100%; height:auto; border-radius:6px; display:block; margin:0 auto;">

	<figcaption style="font-size:0.95em; color:#555; text-align:center; max-width:900px; margin:0 auto; margin-top:0.5rem; ">
	
		Celebrating Santosh’s birthday. December, 2025.
		<br>
		<em>
			From left to right: Alejandro, Cesar, Dominik, Santosh, Safal, and Carlos. Behind the camera: Renmin. 
		</em>
		<br>
	
	</figcaption>
</figure>
<br>

<figure style="margin: 0 auto 0.5rem auto; max-width: 900px;">

	<img src="/images/GroupPic_Thanksgiving_2025_11_26.jpg" alt="Research group photo" 
		style="width:100%; height:auto; border-radius:6px; display:block; margin:0 auto;">

	<figcaption style="font-size:0.95em; color:#555; text-align:center; max-width:900px; margin:0 auto; margin-top:0.5rem; ">
	
		Thanksgiving dinner. November, 2025.
		<br>
		<em>
			From left to right: Santosh, Cesar, Carlos, and Renmin.
		</em>
		<br>
	
	</figcaption>
</figure>
