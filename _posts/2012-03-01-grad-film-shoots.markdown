---
title: Grad Film Shoots
layout: post
categories: 35mm
album:
- title: "The Boxer"
  src: "https://c2.staticflickr.com/8/7616/27700033762_184795a720"
  alt: 
excerpt:
---
{% for photo in page.album %}
  {% assign image = page.album[0] %}{% include print_album_image.html %}
{% endfor %}