---
layout : layout
---

<div class="post">
    <h1>Posts</h1>
    <ul id="archive">
        {% for post in site.posts limit: 14 %}
		    <li>
			    <a href="{{ post.url }}">{{ post.title }}</a>
			    <span class="date">{{ post.date | date: "%d %B, %Y" }}</span>
                {% if post.has_summary %}<p>{{ post.summary }}</p>{% endif %}
		    </li>
        {% endfor %}
    </ul>
</div>