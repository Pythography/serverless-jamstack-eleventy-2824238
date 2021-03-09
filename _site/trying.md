---
title: JAMstack with Eleventy is Awesome!
date: Created
tags:
- home
- about
- posts
---
# {{title}}

**Date:** {{page.date.toUTCString()}} 
<ul>
{% for item in tags %}
<li>{{item}}</li>
</ul>