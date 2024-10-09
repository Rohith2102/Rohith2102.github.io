---
layout: default
title: "Home"
---

<h1 class="page-title">Home</h1>

<div class="home-content">
  <div class="left-column">
    <img src="{{ '/assets/images/myprofile-img.DNG' | relative_url }}" alt="{{ site.author.name }}" class="profile-image">

    <h2 class="author-name">{{ site.author.name }}</h2>

    <div class="icon-links">
      <div class="icon-link">
        <i class="fas fa-map-marker-alt"></i>
        <span>{{ site.author.location }}</span>
      </div>
      <div class="icon-link">
        <i class="fas fa-university"></i>
        <span>{{ site.author.university }}</span>
      </div>
      <div class="icon-link">
        <a href="https://linkedin.com/in/{{ site.author.linkedin }}" target="_blank">
          <i class="fab fa-linkedin"></i> LinkedIn
        </a>
      </div>
      <div class="icon-link">
        <a href="https://github.com/{{ site.author.github }}" target="_blank">
          <i class="fab fa-github"></i> GitHub
        </a>
      </div>
      <div class="icon-link">
        <a href="mailto:{{ site.author.email }}">
          <i class="fas fa-envelope"></i> Email
        </a>
      </div>
    </div>
  </div>

  <div class="right-column">
    <!-- Other content goes here -->
    <h2>About Me</h2>
    <p>
      <!-- Write your details here -->
      Welcome to my personal website! I am a [Your Profession], passionate about [Your Interests]. 
      Here you can find more about my work, projects, and interests.
    </p>
  </div>
</div>
