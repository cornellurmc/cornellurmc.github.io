---
layout: post
title: 'Gallery'
permalink: /gallery/
---

{% assign image_files = site.static_files | where: "gallery_image", true %}
{% for myimage in image_files %}
{: .gallery-image}
![image]({{ myimage.path }})
{% endfor %}
