---
layout: default
title: 鹽行國中重劃區觀測站
description: 聚焦台南市永康區「鹽行國中重劃區」，整理人口密度、土地使用與周邊設施等城市觀測資料。
image: /assets/img/OG/thumbnail.jpg
---

## 最新公告
- [鹽行國中重劃區觀測站｜平台定位與內容架構說明（2026）](/vision/)

---

## 最新文章

{% for post in site.posts limit:3 %}
<article>
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt | strip_html | truncatewords: 40 }}</p>
</article>
{% endfor %}

---

## 🔎 微觀｜近期紀錄

{% assign micro = site.categories.micro | sort: "date" | reverse %}
<ul>
{% for post in micro limit:3 %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

---

## 🔭 宏觀｜近期紀錄

{% assign macro = site.categories.macro | sort: "date" | reverse %}
<ul>
{% for post in macro limit:3 %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

---

## 🗣️ 鹽論｜近期出現

{% assign salt = site.categories.salt | sort: "date" | reverse %}
<ul>
{% for post in salt limit:3 %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

---

## 相關平台

本站不定期於多個社群平台更新，內容以觀測紀錄為主，不進行商業合作或代言：

- <a rel="me" href="https://www.facebook.com/yanhangwatch">Facebook｜鹽行國中重劃區觀測站</a>
- <a rel="me" href="https://www.instagram.com/yanhangwatch/">Instagram｜yanhangwatch</a>
- <a rel="me" href="https://www.threads.net/@yanhangwatch">Threads｜yanhangwatch</a>
- <a rel="me" href="https://www.youtube.com/@yanhangwatch">YouTube｜yanhangwatch</a>

---

> 本站內容整理自公開資料與實地觀察，部分圖像與資料出處為政府公開資訊，經整理重製使用，僅供資訊紀錄與研究參考，不構成投資、購屋或任何形式之建議，亦不代表任何機關立場。實際情況請以政府機關公告與正式文件為準。
