---
layout: page
title: 
tagline: こんにちわ。<a href="http://uni-q.net">うに（uniq）</a>です。<br>本職はwebとかのデザイナーです。<br>webデザインとか、html/css、UIなどについて書いてこうと思ってます。
---
{% include JB/setup %}

### POST
<table class="twelve">
  <tbody>
    {% for post in site.posts array limit:20 %}
    <!-- array limit:20 で最新20件
    https://github.com/Shopify/liquid/wiki/Liquid-for-Designers -->
    <tr>
      <td>{{ post.date | date: "%Y-%m-%d" }}</td>
      <td><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>
<!-- {{ post.category }} -->
      </td>
    </tr>
    {% endfor %}
    <tr>
      <td colspan="2"><a href="/archive.html">もっと読む</a></td>
    </tr>
  </tbody>
</table>




