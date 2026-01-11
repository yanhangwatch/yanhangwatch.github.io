---
layout: default
title: 鹽行國中重劃區觀測站
description: 聚焦台南市永康區「鹽行國中重劃區」，以公開資料與實地觀測，記錄都市發展、產業設施與生活空間的結構關係。
image: /assets/img/OG/thumbnail.jpg
---

# 鹽行國中重劃區觀測站

鹽行國中重劃區觀測站，是一個聚焦於**台南市永康區鹽行國中重劃區**（正式名稱為**台南市永康區新設鹽行國中暨附近地區區段徵收**，簡稱**台南鹽行重劃區**）的獨立觀測平台，整理公開資料與實地紀錄，記錄城市發展、產業設施與生活空間之間的實際樣貌。

本站關注的不是單一事件，而是資訊如何被留下、被忽略，或逐漸消失。

---

## 我在觀測什麼

本觀測站內容分為三個主軸，作為可回顧、可對照的長期紀錄：

- **🔎 微觀**  
  以實地拍攝、地圖定位與公開資料，記錄重劃區周邊設施的位置、規模與日常運作情形。

- **🔭 宏觀**  
  從人口密度、土地使用分區、行政區界線等資料，理解鹽行國中重劃區在台南都市結構中的位置與角色。

- **🗣️ 鹽論**  
  討論資訊如何被呈現、被省略，或被過度簡化，協助讀者建立判斷基礎。

---

## 最新公告
- [鹽行國中重劃區觀測站｜平台定位與內容架構說明（2026）](/vision/)

## 最新文章
{% for post in site.posts limit:3 %}
<article>
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt | strip_html | truncatewords: 40 }}</p>
</article>
{% endfor %}

### 🔎 微觀｜近期紀錄
{% assign micro = site.categories.micro %}
<ul>
{% if micro %}
  {% for post in micro limit:3 %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small style="color: #999;">({{ post.date | date: "%m/%d" }})</small></li>
  {% endfor %}
{% else %}
  <li style="color: #888; list-style: none;">Coming soon</li>
{% endif %}
</ul>

### 🔭 宏觀｜近期紀錄
{% assign macro = site.categories.macro %}
<ul>
{% if macro %}
  {% for post in macro limit:3 %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small style="color: #999;">({{ post.date | date: "%m/%d" }})</small></li>
  {% endfor %}
{% else %}
  <li style="color: #888; list-style: none;">Coming soon</li>
{% endif %}
</ul>

### 🗣️ 鹽論｜近期出現
{% assign salt = site.categories.salt %}
<ul>
{% if salt %}
  {% for post in salt limit:3 %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small style="color: #999;">({{ post.date | date: "%m/%d" }})</small></li>
  {% endfor %}
{% else %}
  <li style="color: #888; list-style: none;">Coming soon</li>
{% endif %}
</ul>

---

## 相關平台

本站不定期於多個社群平台更新，內容以觀測紀錄為主，不進行商業合作或代言：

- <a rel="me" href="https://www.facebook.com/yanhangwatch">Facebook｜鹽行國中重劃區觀測站</a>
- <a rel="me" href="https://www.instagram.com/yanhangwatch/">Instagram｜yanhangwatch</a>
- <a rel="me" href="https://www.threads.net/@yanhangwatch">Threads｜yanhangwatch</a>
- <a rel="me" href="https://www.youtube.com/@yanhangwatch">YouTube｜yanhangwatch</a>


> 本站內容整理自公開資料與實地觀察，部分圖像與資料出處為政府公開資訊，經整理重製使用，僅供資訊紀錄與研究參考，不構成投資、購屋或任何形式之建議，亦不代表任何機關立場。實際情況請以政府機關公告與正式文件為準。
