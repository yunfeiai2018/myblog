{% for post in site.posts %}
    <li class="post-item">
        <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        <span class="post-date">{{ post.date | date: "%Y-%m-%d" }}</span>
    </li>
{% endfor %}
