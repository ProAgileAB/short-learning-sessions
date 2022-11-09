# short-learning-sessions

{% for session in site.sessions %}
[{{ session.title }}]( {{ session.url | relative_url }})
{% endfor %}

[homepage](https://proagileab.github.io/short-learning-sessions/)
