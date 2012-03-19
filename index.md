---
layout : layout
---

<div class="post">
    <div>
	    <h2>Welcome to the Ardent Team Blog</h2>
	    <p>Here we talk about some of the work we are doing, the good, the bad and the awesome! As well as trying to help out our fellow developers in the community. </p>
    </div>

    <h2>Posts</h2>
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