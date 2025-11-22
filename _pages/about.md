---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
/* Wider sidebar so name fits */
.sidebar {
  width: 280px !important;
}
@media (min-width: 64em) {
  .sidebar {
    width: 320px !important;
  }
  
  /* Reduce gap between sidebar and content */
  .page {
    width: calc(100% - 350px) !important;
    padding-left: 350px !important;
  }
}
/* Remove extra top padding/margin from content */
.page__content {
  padding-top: 0 !important;
  margin-top: 0 !important;
}
/* Move content up to align with top of sidebar */
.page__inner-wrap {
  margin-top: 0 !important;
  padding-top: 0 !important;
}
/* Remove top margin from first paragraph */
.page__content p:first-child {
  margin-top: 0 !important;
}
/* Target main content wrapper */
#main {
  padding-top: 0 !important;
  margin-top: 0 !important;
}
/* Target article element if present */
article {
  padding-top: 0 !important;
  margin-top: 0 !important;
}
</style>

I am an AI Scientist at Samsung SDS Research America, Mountain View, where I work on building AI tools for enterprise data.
