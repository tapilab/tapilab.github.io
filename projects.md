---
layout: page
title: Projects
header: Projects
group: navigation
---
{% include JB/setup %}

{% for category in site.category_list %}
<h2 id="{{ category.name }}-ref">{{ category.name }}</h2>
<img align="right" width="300px" src="assets/{{ category.image }}"/>
{{ category.description }}
#### Publications
  <ul class="posts">
    {% for post in site.posts %}
    {% if post.category contains category.name %}
      <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>, {{ post.venue }} </li>
    {% endif %}
    {% endfor %}
</ul>
<hr/>
{% endfor %}

