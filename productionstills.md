---
layout: page
subtitle: Los Angeles-Based Actor, Musician, Singer, and Dancer
images:
  - image_path: ../img/headshots/IMG_5983.jpg
  - image_path: ../img/headshots/IMG_5973.jpg
  - image_path: ../img/headshots/d389cf_751e4e31dd764fcc84a1d01e261266fe~mv2_d_5472_3648_s_4_2.jpg
  - image_path: ../img/headshots/IMG_0738.JPG
  - image_path: ../img/headshots/IMG_2388.JPG
  - image_path: ../img/headshots/IMG_2619.JPG
  - image_path: ../img/headshots/IMG_2643.JPG
  - image_path: ../img/headshots/IMG_6155.PNG
  - image_path: ../img/headshots/IMG_7566.JPG
---

<ul class="photo-gallery">
  {% for image in page.images %}
    <a data-fancybox="gallery" href="{{ image.image_path }}">
      <img style="width:100%; padding-bottom:5px;" src="{{ image.image_path }}">
    </a>
  {% endfor %}
</ul>

<!-- 1. Add latest jQuery and fancybox files -->
<script src="//code.jquery.com/jquery-3.3.1.min.js"></script>
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fancyapps/fancybox@3.5.2/dist/jquery.fancybox.min.css" />
<script src="https://cdn.jsdelivr.net/gh/fancyapps/fancybox@3.5.2/dist/jquery.fancybox.min.js"></script>
