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



<!-- About Renmin -->

<br>
<h1 class="team-section" style="text-align:center; text-decoration:underline;">
	PRINCIPAL INVESTIGATOR
</h1>
<br>

<div class="team-grid">

	<div class="team-member">
		
		<img src="/images/RPretell_3.JPG" alt="Renmin Pretell">

		<!-- Text on the right of the headshot -->
		<div class="team-text">
		
			<h1 style="margin:0;">
				Renmin Pretell, PhD
			</h1>
			<br>
		
			<h2>
				Education
			</h2>
			
			<ul>
				<li>PhD, University of California, Davis, CA, 2022</li>
				<li>MS, University of California, Davis, CA, 2019</li>
				<li>BS <em>(Summa Cum Laude)</em>, Universidad Nacional de Ingeniería (UNI), Peru, 2012</li>
			</ul>
		
		</div>

		<!-- Text below the headshot -->
		<div class="team-bio">

			<h2>
				Employment history
			</h2>
			
			<ul>
				<li><em>08/2023 – Present</em> &nbsp;&nbsp;&nbsp;&nbsp;Assistant Professor, University of Nevada, Reno, NV</li>
				<li><em>10/2022 – 07/2023</em> &nbsp;&nbsp;Postdoctoral Scholar, University of California, Los Angeles, CA</li>
				<li><em>09/2017 – 09/2022</em> &nbsp;&nbsp;Graduate Student Researcher, University of California, Davis, CA</li>			
				<li><em>09/2015 – 08/2017</em> &nbsp;&nbsp;Project Engineer, Golder Associates, Denver, CO</li>
				<li><em>01/2013 – 08/2015</em> &nbsp;&nbsp;Staff Engineer, Golder Associates, Peru</li>
<!--				<li><em>01/2010 – 04/2012</em> &nbsp;&nbsp;Research Assistant, CISMID, Peru</li> -->
			</ul>

			<h2>
				Honors and awards
			</h2>

			<ul>
				<li>2025 International Research Seed Funding Competition, CTBUH, 2025</li>
				<li>ExCEEd Teaching Fellow, ASCE, 2025</li>
				<li>DesignSafe Dataset Award, NHERI, 2024</li>
				<li>Earthquake Spectra Outstanding Reviewer, EERI, 2023</li>
				<li>Building Future Faculty, NCSU, 2022</li>
				<li>Haley & Aldrich Diversity and Equity essay contest winner, 2021</li>
				<li>Patrick C. Lucia Geotechnical Engineering Scholarship, 2019</li>
				<li>Excellence Rating on thesis defense, UNI, 2014</li>
				<li>Top Student 2012-I, UNI, Rank: 1/120, 2012</li>
				<li>Best Research Project 2012, UNI, 2012</li>
				<li>Santiago Antúnez de Mayolo Scholarship, UNI, 2010</li>
			</ul>
		</div>
	</div>

</div>




<!-- Renmin's students -->

<br>
<h1 class="team-section" style="text-align:center; text-decoration:underline;"> GRADUATE RESEARCH ASSISTANTS </h1>
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
				Seismic site response, V_S profile uncertainty</p>
			
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
