---
layout: page
title: 
tagline: 試しに作ってみたよ
---
{% include JB/setup %}

## Post

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


## Profile

【なまえ】いしざきうに / uniq / unico  
（読み方は「うにきゅう」とか「うにこ」）

【しごと】萌え絵描きweb屋さん  
【メール】info［at］uni-q.net  


<ul>
<li><a href="http://pic.uni-q.net">pic.uni-q.net</a>（お絵描き、同人）</li>
<li><a href="http://uniq.hatenablog.com/">はてなブログ</a>（日記）</li>
</ul>

<ul>
        <li><a href="http://twitter.com/uniq">Twitter</a></li>
        <li><a href="http://www.slideshare.net/yumi-uniq-ishizaki">slideshare</a>（社内LTだらけなの）</li>
        <li><a href="https://github.com/uni-q">github</a>（このサイトのソースコードとかも）</li>
</ul>


## about

勉強がてら、「Jekyll Bootstrap」で作ってみた。
まだDesignの途中。。。

[http://uniq.heteml.jp/blog/](http://uniq.heteml.jp/blog/)から
引っ越してみました。



