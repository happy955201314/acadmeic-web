---
layout: about
title: about
permalink: /
subtitle: <i class="far fa-envelope"></i> r08921a28@ntu.edu.tw / chiwei955201314@gmail.com

profile:
  align: right
  image: me.png
  image_circular: false # crops the image to make it circular
  address: >
    <a href="assets/pdf/cv.pdf" class="float-left"><i class="fa fa-download"></i> Resume/CV</a>

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

Welcome! I am <b>Chi-Wei Chen</b>, deeply enthusiastic about the realms of <b>hardware security</b> and <b>teaching</b>. I earned my <b>Bachelor's degree</b> in Computer Science from the <b>National Tsing Hua University</b>, under the expert guidance of <a href="https://logoslab.github.io/"><b>Prof. Ren-Song Tsay</b></a>. Following that, I embarked on a research adventure as a research assistant at Academia Sinica, collaborating closely with <a href="https://homepage.iis.sinica.edu.tw/pages/janeliu/contact_en.html"><b>Prof. Jane Liu</b></a> and <a href="https://homepage.iis.sinica.edu.tw/~kmchung/"><b>Prof. Kai-Min Chung</b></a>. 

My academic pursuits continued with the attainment of a <b>Master's degree</b> in Electrical Engineering, specializing in cybersecurity track, at <b>National Taiwan University</b>. During this phase, I had the privilege of being mentored by <a href="https://homepage.ntu.edu.tw/~sykuo/"><b>Prof. Sy-Yen Kuo</b></a>. Presently, I am actively shaping my plans to embark on a <b>Ph.D.</b> journey within the field of <b>hardware security</b>, fueled by an unwavering dedication to advancing knowledge and innovation.

<h3 id="research">Research</h3>
My research interests lie primarily and widely in the field of security, with a specific focus on hardware security. I am particularly passionate about investigating hardware Trojans, side-channel attacks, and embedded security. I aspire to leverage my software skills to verify and address hardware security issues.
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

<h3 id="others">Other Internships</h3>
I also possess experience in mechanical engineering and law, further diversifying my skill set and expertise.
<div class="others">
  {% for entry in site.data.others %}
    {% include cv/experience.html %}
  {% endfor %}
</div>



