---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Welcome
---


<!-- FontAwesome CDN to load social media icons automatically -->
<script src="https://cloudflare.com" crossorigin="anonymous"></script>

<div style="display: flex; flex-wrap: wrap; gap: 40px; margin-top: 30px;">

  <!-- LEFT SIDEBAR: PHOTO, BIO, AND SOCIAL LINKS -->
  <div style="flex: 1; min-width: 260px; max-width: 280px; text-align: center;">
    
    <!-- Profile Image -->
    <img src="{{ site.baseurl }}/assets/my-photo.jpg" alt="Anish Mukherjee" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.08);">
    
    <!-- Title & Affiliation -->
    <h2 style="margin-top: 15px; margin-bottom: 5px; font-size: 1.5em;">Anish Mukherjee</h2>
    <p style="font-size: 0.95em; color: #555; margin-bottom: 15px; line-height: 1.4em;">
      Postdoctoral Researcher<br>
      <span style="color: #777;">Department of Statistics<br>University</span>
    </p>
    
    <hr style="border: 0; border-top: 1px solid #eee; margin: 15px 0;">
    
    <!-- Social & Contact Links (AcademicPages Style) -->
    <ul style="list-style: none; padding: 0; margin: 0; text-align: left; line-height: 2.2em; font-size: 0.95em;">
      <li><a href="mailto:anishm.space@gmail.com" style="color: #333; text-decoration: none;"><i class="fa-solid fa-envelope" style="width: 25px; color: #555;"></i> Email</a></li>
      <li><a href="https://scholar.google.com/citations?user=MR_fCsQAAAAJ" target="_blank" style="color: #333; text-decoration: none;"><i class="fa-solid fa-graduation-cap" style="width: 25px; color: #555;"></i> Google Scholar</a></li>
      <li><a href="https://github.com/anishspace/" target="_blank" style="color: #333; text-decoration: none;"><i class="fa-brands fa-github" style="width: 25px; color: #555;"></i> GitHub</a></li>
      <li><a href="https://www.linkedin.com/in/primestardust/" target="_blank" style="color: #333; text-decoration: none;"><i class="fa-brands fa-linkedin" style="width: 25px; color: #555;"></i> LinkedIn</a></li>
    </ul>
    
  </div>

  <!-- RIGHT COLUMN: MAIN CONTENT & BIOGRAPHY -->
  <div style="flex: 2; min-width: 320px;">
    <h1 style="margin-top: 0;">Biography</h1>
    <p>I am a data scientist specializing in the development of statistical methodologies for complex data. I am currently a Postdoctoral Research Assistant in the Faculty of Economics at the Università della Svizzera italiana (USI) in Lugano, Switzerland, working with [Stefano Peluso](https://publires.unicatt.it/en/persons/stefano-peluso/) and [Antonietta Mira](http://usi.to/exz). I earned my Ph.D. in Biostatistics from the University of Louisville under the supervision of  [Jeremy Gaskins](https://profiles.louisville.edu/jeremy.gaskins). My research spans spatio-temporal modeling, statistical genomics, and stochastic systems, with a particular focus on Bayesian approaches for analyzing high-dimensional and dependent data.

    My methodological contributions include the development of models for zero-inflated correlated count data, frameworks for identifying heterogeneity and outliers in longitudinal outcomes, Bayesian models for longitudinal microbiome data, and nonparametric Bayesian methods based on stochastic differential equations to study infectious disease transmission and gene regulation.  Beyond methodology, I have collaborated on several application-focused projects in public health, including research on sports medicine, maternal health, wastewater-based epidemiology, and environment.
    </p>
    
    <h3>Research Interests</h3>
    <ul>
      <li>Bayesian Methods</li>
      <li>Spatio-temporal Models</li>
      <li>Computational Biology</li>
      <li>Dynamical Systems</li>
    </ul>
  </div>

</div>
