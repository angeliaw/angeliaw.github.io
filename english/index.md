---
layout: home
---

<div class="index-content english">
    <div class="section">
        <ul class="artical-cate">
            <li><a href="/"><span>Blog</span></a></li>
            <li style="text-align:center"><a href="/training"><span>Training</span></a></li>
            <li class="on" style="text-align:right"><a href="/english"><span>English</span></a></li>
        </ul>

        <div class="cate-bar"><span id="cateBar"></span></div>

        <ul class="artical-list">
        {% for post in site.categories.english %}
            <li>
                <h3>
                    <a href="{{ post.url }}">{{ post.title }}</a>
                </h3>
                <div class="title-desc">{{ post.description }}</div>
            </li>
        {% endfor %}
        </ul>
    </div>
    <div class="aside">
    </div>
</div>
