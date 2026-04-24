---
layout: page
title: 文章分类
permalink: /categories
---

<!-- 定义导航跳转的目标 ID -->
<h2 id="IT技术">💻 IT技术</h2>
<ul>
  {% for post in site.categories["IT技术"] %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>

<hr>

<h2 id="养鱼日常">🐠 养鱼日常</h2>
<ul>
  {% for post in site.categories["养鱼日常"] %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>

<hr>

<h2 id="生活记录">📝 生活记录</h2>
<ul>
  {% for post in site.categories["生活记录"] %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>
