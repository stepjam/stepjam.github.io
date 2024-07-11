---
layout: page
title: group
permalink: /group/
description: The Robot Learning Lab members.
nav: false
nav_order: 1
display_categories: [PI, research]
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
  <h2 class="category">Research Scientists</h2>
  <div class="grid">
  {% for person in site.data.people.ResearchScientists %}
    <div class="grid-sizer"></div>
    <div class="grid-item">
      <a href="{{ person.website }}" target="_blank">
        <div class="card hoverable">
          <img src="{{ person.image | relative_url }}" alt="{{ person.name }}">
          <div class="card-body">
            <h2 class="card-title text-lowercase">{{ person.name }}</h2>
            <p class="card-text">{{ person.role }}</p>
          </div>
        </div>
      </a>
    </div>
  {% endfor %}
  </div>
  
  <h2 class="category">Research Engineers</h2>
  <div class="grid">
  {% for person in site.data.people.ResearchEngineers %}
    <div class="grid-sizer"></div>
    <div class="grid-item">
      <a href="{{ person.website }}" target="_blank">
        <div class="card hoverable">
          <img src="{{ person.image | relative_url }}" alt="{{ person.name }}">
          <div class="card-body">
            <h2 class="card-title text-lowercase">{{ person.name }}</h2>
            <p class="card-text">{{ person.role }}</p>
          </div>
        </div>
      </a>
    </div>
  {% endfor %}
  </div>
  

</div>

