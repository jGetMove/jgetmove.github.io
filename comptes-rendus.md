{% for post in site.posts %}
{% if post.categories contains "comptes-rendus" %}
# [{{ post.title }}]({{ post.url }})
{{ post.content }}
{% endif %}
{% endfor %}
