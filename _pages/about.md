---
layout: about
title: about
permalink: /
subtitle: <i class="far fa-envelope"></i> r08921a28@ntu.edu.tw | chiwei955201314@gmail.com

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
Welcome! <a href="#"><b>Chi-Wei Chen</b></a> received his Master's degree in Electrical Engineering, specializing in the cybersecurity track, at National Taiwan University, advised by <a href="https://homepage.ntu.edu.tw/~sykuo/">Prof. Sy-Yen Kuo</a>. Before that, Chi-Wei earned his Bachelor's degree in the Computer Science Department from National Tsing Hua University, advised by <a href="https://logoslab.github.io/">Prof. Ren-Song Tsay</a>. Additionally, he was a research assistant at Academia Sinica, collaborating closely with <a href="https://homepage.iis.sinica.edu.tw/pages/janeliu/contact_en.html">Prof. Jane Liu</a> and <a href="https://homepage.iis.sinica.edu.tw/~kmchung/">Prof. Kai-Min Chung</a>.

His research interests primarily span the field of security, with a specific focus on hardware security. He is particularly passionate about investigating hardware Trojans, side-channel attacks, and embedded security. He aspires to leverage his software skills to address hardware security issues.

<h3 id="research">Research</h3>
Due to my background in both Computer Science (CS) and Electrical Engineering (EE), I possess relevant experience in both software and hardware. The following outlines my research experience:
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



