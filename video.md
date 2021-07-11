---
layout: page
subtitle: Los Angeles-Based Actor, Musician, Singer, and Dancer
youtube_ids:
  - id: 8fepsY3vGZs
  - id: mkhBsmNZnWg
  - id: HI3GoZlD6rk
  - id: RotGlXa6EUs
  - id: CLHxChiSaag
  - id: 7K9HalQEyD8
---

{% for youtube_id in page.youtube_ids %}
  {% include youtubePlayer.html id=youtube_id.id %}
{% endfor %}

<!-- 1. Add latest jQuery and fancybox files -->
<script src="//code.jquery.com/jquery-3.3.1.min.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fancyapps/fancybox@3.5.2/dist/jquery.fancybox.min.css" />
<script src="https://cdn.jsdelivr.net/gh/fancyapps/fancybox@3.5.2/dist/jquery.fancybox.min.js"></script>
