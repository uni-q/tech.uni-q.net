---
layout: page
title: 
tagline: 試しに作ってみたよ
---
{% include JB/setup %}


## about

勉強がてら「Jekyll Bootstrap」で作ってみた。色々修正中。  
修正履歴は<a href="https://github.com/uni-q">github</a>に。

[http://uniq.heteml.jp/blog/](http://uniq.heteml.jp/blog/)から
引っ越してみました。

-----

## Post


<table class="twelve">
  <tbody>
    {% for post in site.posts %}
    <tr>
      <td>{{ post.date | date: "%Y-%m-%d" }}</td>
      <td><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></td>
    </tr>
    {% endfor %}
  </tbody>
</table>

-----

## Profile

【なまえ】Yumi Ishizaki  
【メール】info［at］uni-q.net  

<ul>
<li><a href="http://uni-q.net">uni-q.net</a>（自己紹介とか）</li>
<li><a href="http://www.slideshare.net/yumi-uniq-ishizaki">slideshare</a>（社内LTだらけなの）</li>
<li><a href="https://github.com/uni-q">github</a>（このサイトのソースコードとかも）</li>
</ul>



