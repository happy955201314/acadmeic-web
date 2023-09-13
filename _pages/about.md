---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Graduate student | Department of Electrical Engineering ,NTU</a>.

profile:
  align: right
  image: me2.jpg
  image_circular: false # crops the image to make it circular
  address: >
    <a href="assets/pdf/cv.pdf" class="float-left"><i class="fa fa-download"></i> Resume/CV</a>

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

Welcome! I am <b>Chi-Wei Chen</b>, deeply enthusiastic about the realms of computer science and electrical engineering. I proudly earned my Bachelor's degree in Computer Science from the esteemed National Tsing Hua University, guided by the expertise of Prof. Ren-Song Tsay. Following this, I furthered my academic journey by achieving a Master's degree in Electrical Engineering, specializing in the cybersecurity track at National Taiwan University, under the mentorship of Prof. Sy-Yen Kuo. Presently, I am actively formulating my plans to embark on a Ph.D. journey within the field of security, driven by my unwavering passion for pushing the boundaries of knowledge and innovation.

<h3 id="research">Research</h3>
My research interests lie primarily in the field of security, with a specific focus on hardware security. I am particularly passionate about investigating hardware Trojans, side-channel attacks, and embedded security. I aspire to leverage my software skills to verify and address hardware security issues.
<div class="research publications">
  {% for entry in site.data.research %}
      {% include cv/experience.html %}                
  {% endfor %}
</div>

<h3 id="teaching">Teaching</h3>
I have a strong passion for teaching and enjoy collaborative brainstorming with my peers. As a result, I actively seek opportunities to serve as a teaching assistant. Here is a list of the teaching assistant positions I have held thus far:
<div class="teaching">
  {% for entry in site.data.teaching %}
      {% include cv/experience.html %}                
  {% endfor %}
</div>



