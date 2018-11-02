---
layout: page
images:
  - image_path: ../img/headshots/NL-070_hiRez.jpg
  - image_path: ../img/headshots/NL-002.jpg
  - image_path: ../img/headshots/NL-010.jpg
  - image_path: ../img/headshots/NL-037.jpg
  - image_path: ../img/headshots/NL-059.jpg
  - image_path: ../img/headshots/NL-096_hiRez.jpg
---

<ul class="photo-gallery">
  {% for image in page.images %}
    <a data-fancybox="gallery" href="{{ image.image_path }}">
      <img style="width:300px;" src="{{ image.image_path }}">
    </a>
  {% endfor %}
</ul>

<!-- 1. Add latest jQuery and fancybox files -->
<script src="//code.jquery.com/jquery-3.3.1.min.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fancyapps/fancybox@3.5.2/dist/jquery.fancybox.min.css" />
<script src="https://cdn.jsdelivr.net/gh/fancyapps/fancybox@3.5.2/dist/jquery.fancybox.min.js"></script>
