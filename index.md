{% for session in site.sessions %}
 * [{{ session.title }}]( {{ session.url | relative_url }})
{% endfor %}
