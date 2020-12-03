---
layout: page
title: Blog
---
<a href="https://www.poetryfoundation.org/poems/45723/theres-a-certain-slant-of-light-320"><img src = "https://user-images.githubusercontent.com/45428531/100492602-ce3d9900-30fb-11eb-9ebe-2f4b26d9bca1.jpg"></a>
{% for post in site.posts %}
  * {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
