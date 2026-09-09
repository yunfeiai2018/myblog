<div class="banner">
    <h1>Oscar's blog</h1>
</div>
<div class="post-list">
    {% for post in site.posts %}
    <div class="post-item">
        <a href="/pg-blog/{{ post.url }}">{{ post.title }}</a>
    </div>
    {% endfor %}
</div>
