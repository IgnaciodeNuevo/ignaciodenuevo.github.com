---
layout: list
title: 'Resources'
wrapper_class: resources-wrapper
---

<h1 class="main__title">Resources for Web Developers</h1>

<p class="main__text">List of resources to learn Frontend Web Design & Development curated by me, that I enjoyed reading, watching, listening to or using.</p>

<p class="main__title">TL; DR</p>

<section class="articles-list">
        <h2 id="books">Books</h2>
        {% for resource in site.data.books %}
            <article class="article">
                <a class="article__item" href="{{ resource.url }}"  target="_blank" rel="noopener noreferrer">
                    <h3 class="article__subtitle">{{ resource.name }}</h3>
                </a>
            </article>
        {% endfor %}
        <h2 id="newsletters">Newsletters</h2>
        {% for resource in site.data.newsletters %}
            <article class="article">
                <a class="article__item" href="{{ resource.url }}"  target="_blank" rel="noopener noreferrer">
                    <h3 class="article__subtitle">{{ resource.name }}</h3>
                </a>
            </article>
        {% endfor %}
        <h2 id="podcasts">Podcasts</h2>
        {% for resource in site.data.podcasts %}
            <article class="article">
                <a class="article__item" href="{{ resource.url }}"  target="_blank" rel="noopener noreferrer">
                    <h3 class="article__subtitle">{{ resource.name }}</h3>
                </a>
            </article>
        {% endfor %}
        <h2>RSS Feeds</h2>
        <article class="article">
            <a class="article__item" href="/feedly.opml">
                <h3 class="article__subtitle">RSS Feeds</h3>
            </a>
        </article>
        <h2>Slack Channels</h2>
        {% for resource in site.data.slacks %}
            <article class="article">
                <a class="article__item" href="{{ resource.url }}"  target="_blank" rel="noopener noreferrer">
                    <h3 class="article__subtitle">{{ resource.name }}</h3>
                </a>
            </article>
        {% endfor %}
        <h2>Webs of Resources</h2>
        {% for resource in site.data.resources %}
            <article class="article">
                <a class="article__item" href="{{ resource.url }}"  target="_blank" rel="noopener noreferrer">
                    <h3 class="article__subtitle">{{ resource.name }}</h3>
                </a>
            </article>
        {% endfor %}
</section>
