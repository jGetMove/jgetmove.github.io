{% for post in site.posts %}
{{ variable | inspect }}
{% if post.categories contains "comptes-rendus" %}
# [{{ post.title }}]({{ post.url }}
{{ post.content }}
{% endif %}
{% endfor %}
