---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Welcome
---


<!-- FontAwesome CDN to load social media icons automatically -->
<link rel="stylesheet" href="https://cloudflare.com">

<div style="display: flex; flex-wrap: wrap; gap: 40px; margin-top: 30px;">

  <!-- LEFT SIDEBAR: PHOTO, BIO, AND SOCIAL LINKS -->
  <div style="flex: 1; min-width: 260px; max-width: 280px; text-align: center;">
    
    <!-- Profile Image -->
    <img src="{{ site.baseurl }}/assets/my-photo.jpg" alt="Your Name" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 10px rgba(0,0,0,0.08);">
    
    <!-- Title & Affiliation -->
    <h2 style="margin-top: 15px; margin-bottom: 5px; font-size: 1.5em;">Your Name</h2>
    <p style="font-size: 0.95em; color: #555; margin-bottom: 15px; line-height: 1.4em;">
      Ph.D. Candidate<br>
      <span style="color: #777;">Department of Computer Science<br>University Name</span>
    </p>
    
    <hr style="border: 0; border-top: 1px solid #eee; margin: 15px 0;">
    
    <!-- Social & Contact Links (AcademicPages Style) -->
    <ul style="list-style: none; padding: 0; margin: 0; text-align: left; line-height: 2.2em; font-size: 0.95em;">
      <li><a href="mailto:your.email@university.edu" style="color: #333; text-decoration: none;"><i class="fa-solid fa-envelope" style="width: 25px; color: #555;"></i> Email</a></li>
      <li><a href="https://google.com" target="_blank" style="color: #333; text-decoration: none;"><i class="fa-solid fa-graduation-cap" style="width: 25px; color: #555;"></i> Google Scholar</a></li>
      <li><a href="https://github.com" target="_blank" style="color: #333; text-decoration: none;"><i class="fa-brands fa-github" style="width: 25px; color: #555;"></i> GitHub</a></li>
      <li><a href="https://twitter.com" target="_blank" style="color: #333; text-decoration: none;"><i class="fa-brands fa-x-twitter" style="width: 25px; color: #555;"></i> Twitter / X</a></li>
      <li><a href="https://linkedin.com" target="_blank" style="color: #333; text-decoration: none;"><i class="fa-brands fa-linkedin" style="width: 25px; color: #555;"></i> LinkedIn</a></li>
    </ul>
    
  </div>

  <!-- RIGHT COLUMN: MAIN CONTENT & BIOGRAPHY -->
  <div style="flex: 2; min-width: 320px;">
    <h1 style="margin-top: 0;">Biography</h1>
    <p>Introduce yourself here. Talk about your core research problem, your advisors, and what you aim to solve. This layout perfectly replicates the academic sidebar look while maintaining the blazing fast load times of your minimalist setup.</p>
    
    <h3>Research Interests</h3>
    <ul>
      <li>Machine Learning & Optimization</li>
      <li>Distributed Data Networks</li>
    </ul>
  </div>

</div>
