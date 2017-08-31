---
title: Grad Film Shoots
layout: post
categories: 35mm
album:
- title: "The Boxer"
  src: "https://c2.staticflickr.com/8/7616/27700033762_184795a720"
  alt: 
- title: "The 'Is Land'"
  src: "https://farm5.staticflickr.com/4409/36470856680_7b7a3bc1e5"
  alt: "The 'Is Land', a floating island"
excerpt:
---
{% for image in page.album %}
  {% include print_album_image.html %}
{% endfor %}