---
layout: single
permalink: /
title: ""
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
.minimal-home {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  padding: 80px 20px;
  max-width: 500px;
  margin: 0 auto;
  min-height: 70vh;
}

.profile-image {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 25px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
}

.name {
  font-size: 2em;
  font-weight: 600;
  color: #333;
  margin: 10px 0 8px 0;
}

.title-company {
  font-size: 1.1em;
  color: #666;
  margin: 5px 0;
  line-height: 1.5;
}

.location {
  font-size: 1em;
  color: #888;
  margin: 15px 0;
}

.social-links {
  display: flex;
  gap: 20px;
  justify-content: center;
  margin: 20px 0;
  flex-wrap: wrap;
}

.social-links a {
  color: #0066cc;
  text-decoration: none;
  font-size: 0.95em;
  display: flex;
  align-items: center;
  gap: 5px;
  transition: color 0.2s;
}

.social-links a:hover {
  color: #0052a3;
}

@media (max-width: 768px) {
  .profile-image {
    width: 130px;
    height: 130px;
  }
  
  .name {
    font-size: 1.7em;
  }
  
  .social-links {
    flex-direction: column;
    gap: 12px;
  }
}
</style>

<div class="minimal-home">
  <img src="/images/Davoud.png" alt="Davoud Ataee Tarzanagh" class="profile-image">
  
  <h1 class="name">Davoud Ataee Tarzanagh</h1>
  
  <p class="title-company">
    AI Scientist<br>
    Samsung SDS Research America
  </p>
  
  <p class="location">📍 Mountain View, CA</p>
  
  <div class="social-links">
    <a href="https://www.linkedin.com/in/YOUR-LINKEDIN" target="_blank">
      🔗 LinkedIn
    </a>
    <a href="https://github.com/Tarzanagh" target="_blank">
      💻 Github
    </a>
    <a href="https://scholar.google.com/citations?user=YOUR-SCHOLAR-ID" target="_blank">
      🎓 Google Scholar
    </a>
  </div>
</div>
