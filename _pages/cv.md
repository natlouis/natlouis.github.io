---
layout: default   # or “none”, whatever you prefer
permalink: /cv/
title: CV
nav: true
nav_order: 5
---

{% assign pdf = "/assets/pdf/natlouis_cv.pdf" | relative_url %}

<!-- automatic redirect -->
<script>window.location.replace("{{ pdf }}");</script>

<p>If you are not redirected automatically, <a href="{{ pdf }}">click here</a>
to open my CV.</p>
