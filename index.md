{% for session in site.sessions %}
 * [{{ session.title }}]( {{ session.url | relative_url }})
{% endfor %}


Send pull requests on our [github page](https://github.com/ProAgileAB/short-learning-sessions)
