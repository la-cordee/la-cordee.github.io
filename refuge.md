# Quoi de neuf sur le **Refuge** ?

{% for post in site.posts %}
  {% if post.tags contains 'Refuge' %}
    {{ post }}
  {% endif %}
{% endfor %}
