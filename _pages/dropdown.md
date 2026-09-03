<style>
:root {
  --global-theme-color: #00779A !important;
  --global-hover-color: #00779A !important;
}
html[data-theme="dark"] {
  --global-theme-color: #00779A !important;
  --global-hover-color: #00779A !important;
}
.navbar {
  background-color: #0d1b2a !important;
}
.navbar .navbar-brand,
.navbar .nav-link {
  color: #ffffff !important;
}
.navbar .nav-link:hover {
  color: #00779A !important;
}
</style>
---
layout: page
title: submenus
nav: false
nav_order: 8
dropdown: true
children:
  - title: bookshelf
    permalink: /books/
  - title: divider
  - title: blog
    permalink: /blog/
---
