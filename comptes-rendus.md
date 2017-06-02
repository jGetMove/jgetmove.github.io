{{ site.categories | inspect }}

{% for post in site.categories.comptes-rendus %}
# [{{ post.title }}]({{ post.url }})
{{ post.content }}
{% endfor %}
