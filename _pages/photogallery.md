---
layout: splash
permalink: /photogallery/
hidden: true
author_profile: true
header:
  overlay_image: /gallery/headerimg.jpg
  overlay_filter: linear-gradient(rgba(255, 0, 0, 0.5), rgba(0, 255, 255, 0.5))
excerpt: "Photo gallery."


gallery:
  - image_path: /gallery/IMG_4489.jpg
    alt: "Ice castle"

  - image_path: /gallery/IMG_4476.jpg
    alt: "Ice castle"

  - image_path: /gallery/IMG_4479.jpg
    alt: "Ice castle"
---

{% include base_path %}


{% include gallery %}


<figure class="two-column">
  <a>
    <img src="/gallery/IMG_4489.jpg" alt="Ice castle 1">
  </a>
  <a>
    <img src="/gallery/IMG_4489.jpg" alt="Ice castle 2">
  </a>
  <figcaption>Ice castles.</figcaption>
</figure>
