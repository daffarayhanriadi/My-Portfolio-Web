---
layout: page
title: About
permalink: /about/
weight: 4
---

# **About Me** 

Hi I am **{{ site.author.name }}** :wave:,<br><br>
Bachelor of Computer Science at the Software Engineering Department, Faculty of Informatics, Telkom Institute of Technology, has experience in working on Machine Learning projects.<br><br>
- I also AI Enthusiasm

{% include elements/button.html link="https://drive.google.com/drive/folders/1ZbwkoS3jNR8ZtMOoRGqOYrTGMVX7G9Nk?usp=sharing" text="Download CV" %}

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Design & Prototyping Skills" source=site.data.other-skills %}
{% include about/skills.html title="Language Skills" source=site.data.languange-skills %}
</div>

## <span class="material-symbols-rounded">school</span> Education
<div class="timeline-body bg-themed">
    <div class="timeline-item">
        <div class="content">
          <h2>Telkom Insitute of Technology, Indonesia</h2>
          <h6 class="date">2020 - 2024</h6>
          <p>Bachelor of Computer Science at Software Engineering Department, Faculty of Informatics, as Graduate in Academics 2024 with a GPA of 3.89 out of 4.0</p>
        </div>
      </div>
</div>

## <span class="material-symbols-rounded">work</span> Working Experience
<div class="row">
{% include about/timeline.html %}
</div>


## <span class="material-symbols-rounded">integration_instructions</span> Tech Contribution
<div class="timeline-body bg-themed">
    {% for item in site.data.experience %}
      <div class="timeline-item">
        <div class="content">
          <h2>{{ item.title }}</h2>
          <h6 class="date">{{ item.year}}</h6>
          <p>{{ item.description }}</p>
        </div>
      </div>
    {% endfor %}
</div>

<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Rounded:opsz,wght,FILL,GRAD@48,400,0,200" />
