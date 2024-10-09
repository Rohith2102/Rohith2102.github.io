---
layout: default
title: "Home"
---

<div class="home-content">
  <div class="left-column">
    <img src="{{ '/assets/images/my-profile-img.DNG' | relative_url }}" alt="{{ site.author.name }}" class="profile-image">
    <div class="social-links">
      <a href="mailto:{{ site.author.email }}">
        <i class="fas fa-envelope"></i> Email
      </a>
      <a href="https://github.com/{{ site.author.github }}" target="_blank">
        <i class="fab fa-github"></i> GitHub
      </a>
      <a href="https://linkedin.com/in/{{ site.author.linkedin }}" target="_blank">
        <i class="fab fa-linkedin"></i> LinkedIn
      </a>
      <!-- Add more social links as needed -->
    </div>
  </div>
  <div class="right-column">
    <h1>About Me</h1>
    <p>
      <!-- Write your details here -->
      Welcome to my personal website! I am a [Your Profession], passionate about [Your Interests].
      Here you can find more about my work, projects, and interests.
    </p>
  </div>
</div>
