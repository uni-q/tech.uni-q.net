---
layout: page
title: 
tagline: こんにちわ。<a href="http://uni-q.net">うに（uniq）</a>です。<br>本職はwebとかのデザイナーです。<br>webデザインとか、html/css、UIなどについて書いてこうと思ってます。
---
{% include JB/setup %}

### POST
<ul class="post-list">
    <!-- array limit:20 で最新20件
    https://github.com/Shopify/liquid/wiki/Liquid-for-Designers -->
    {% for post in site.posts array limit:20 %}
  <li>
    <a href="{{ BASE_PATH }}{{ post.url }}">
      <span class="post-list-category label {{ post.category }}">{{ post.category }}</span>
      <span class="post-list-date">{{ post.date | date: "%Y-%m-%d" }}</span>
      <div class="post-list-title">{{ post.title }}</div>
      <div class="post-list-tag">
        <ul class="inline-list">
          {% assign tags_list = post.tags %}  
          {% include custom/tags_list %}
        </ul>
      </div>
    </a>
  </li>
    {% endfor %}
</ul>
<div class="right">
  <a href="/archive.html" class="button">もっと読む</a>
</div>



