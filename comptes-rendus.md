{{ posts.categories | inspect }}

{% for post in site.posts.categories."comptes-rendus" %}
# [{{ post.title }}]({{ post.url }})
{{ post.content }}
{% endfor %}
