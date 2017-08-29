---
title: 	Secret Garden Party 2010
layout:	post
album:	["https://farm5.staticflickr.com/4409/36470856680_7b7a3bc1e5_c.jpg"]
excerpt: 
---
{% for photo in page.album %}
  ![]({{ photo }})
{% endfor %}