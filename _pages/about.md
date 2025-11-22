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
/* Reset and ensure proper centering */
.page {
  width: 100%;
  margin: 0;
  padding: 0;
}

.page__content {
  max-width: 100% !important;
  margin: 0 !important;
  padding: 0 !important;
}

.minimal-home {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 80px 20px;
  max-width: 600px;
  margin: 0 auto;
  min-height: 70vh;
}

.profile-image {
  width: 150px;
  height: 150px;
  border-radius: 50%;
  object-fit: cover;
  margin: 0 auto 25px auto;
  box-shadow: 0 4px 12px rgba(0,0,0,0.15);
  display: block;
}

.name {
  font-size: 2em;
  font-weight: 600;
  color: #333;
  margin: 10px 0 15px 0;
  text-align: center;
}

.title-company {
  font-size: 1.1em;
  color: #666;
  margin: 5px 0;
  line-height: 1.6;
  text-align: center;
}

.location {
  font-size: 1em;
  color: #888;
  margin: 20px 0;
  text-align: center;
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 5px;
}

.social-links {
  display: flex;
  gap: 25px;
  justify-content: center;
  align-items: center;
  margin: 25px 0;
  flex-wrap: wrap;
}

.social-links a {
  color: #0066cc;
  text-decoration: none;
  font-size: 0.95em;
  display: inline-flex;
  align-items: center;
  gap: 5px;
  transition: color 0.2s;
  white-space: nowrap;
}

.social-links a:hover {
  color: #0052a3;
}

@media (max-width: 768px) {
  .minimal-home {
    padding: 60px 20px;
  }
  
  .profile-image {
    width: 130px;
    height: 130px;
  }
  
  .name {
    font-size: 1.7em;
  }
  
  .social-links {
    flex-direction: column;
    gap: 15px;
  }
}
</style>

<div class="minimal-home">
  <img src="/images/profile.png" alt="Davoud Ataee Tarzanagh" class="profile-image">
  
  <h1 class="name">Davoud Ataee Tarzanagh</h1>
  
  <p class="title-company">
    AI Scientist<br>
    Samsung SDS Research America
  </p>
  
  <p class="location">
    📍 Mountain View, CA
  </p>
  
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
