# Kubiblog

Blog o všetkom

{% for post in site.posts %}

- [ {{ post.date | date: "%Y-%m-%d" }} - {{ post.title }} ]({{ post.url }})

{% endfor %}
