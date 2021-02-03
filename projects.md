---
layout: page
title: Projects
permalink: /projects/
---
  
    

{% for post in site.categories.projects %}
# [{{ post.proj-title }}]({{ post.proj-url }})  
<img src="{{post.proj-img}}" width="1000"/>  
{{ post.proj-authors }}  
**_{{ post.proj-publication }}_**  
[pdf]({{ post.proj-pdf }})
  
    
{% endfor %}
