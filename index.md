---
layout: page
title: 
tagline: 試しに作ってみたよ
---
{% include JB/setup %}


## about

うに（uniq）です。こんにちわ。  
このページは、勉強がてら「Jekyll Bootstrap」で作ってみました。  
webデザインとか、html/css、UIなどについて書いてこうと思ってます。  
前のブログは、[http://uniq.heteml.jp/blog/](http://uniq.heteml.jp/blog/)。
<ul>
<li>なまえ：uniq（うに）</li>
<li>メール：info［at］uni-q.net</li>
<li><a href="http://uni-q.net">uni-q.net</a>（自己紹介とか）</li>
<li><a href="http://www.slideshare.net/yumi-uniq-ishizaki">slideshare</a>（社内LTだらけなの）</li>
<li><a href="https://github.com/uni-q">github</a>（このサイトのソースコードとかも）</li>
</ul>

-----

## Post


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




