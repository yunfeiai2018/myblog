<div class="banner">
    <h1>Oscar's blog</h1>
</div>
<div class="post-list">
    {% for post in site.posts %}
    <div class="post-item">
        <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        <span class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</span>
    </div>
    {% endfor %}
</div>
