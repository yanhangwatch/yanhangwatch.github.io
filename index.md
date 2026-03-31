---
layout: default
description: 廣告之外的另一種視角：獨立整理台南永康鹽行國中重劃區的環境、產業設施與都市發展，透過公開資料與實地觀察記錄地方變化。
image: /assets/img/OG/thumbnail.webp
---

![台南市永康區鹽行國中重劃區衛星影像圖](/assets/img/OG/thumbnail.webp)

# 鹽行國中重劃區觀測站

鹽行國中重劃區觀測站(yanhangwatch)，是一個聚焦於**台南市永康區鹽行國中重劃區**的獨立觀測平台，提供廣告之外的另一種資訊視角。透過整理公開資料與實地紀錄，記錄城市發展、產業設施與生活空間之間的實際樣貌。

本站關注的不是單一事件，而是資訊如何被留下、被忽略，或逐漸消失。

---

## 我在觀測什麼

- **🔎 微觀**：以實地拍攝、地圖定位與公開資料，記錄重劃區周邊設施的位置、規模與日常運作情形。
- **🔭 宏觀**：透過人口密度、土地使用分區等大尺度資料，解析本區在台南都市結構中的定位。
- **🗣️ 鹽論**：整理關於資訊透明、制度風險與公共知情權的觀測筆記。
- **🔙 時間檔案**：帶領讀者回顧過去，盼能跨越時間維度，找回散落在網路邊陲的故事。

---

## 最新公告

- [進度追蹤：目前已完成項目一覽（2026.02）](/status/2026-02/)
- [觀測指南：平台定位與內容架構說明（2026）](/vision/) 

---

## 官網最新文章

{% if site.posts.size > 0 %}
  {% for post in site.posts limit:3 %}
<article style="margin-bottom:1.5em;">
  <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
  <p>{{ post.excerpt | strip_html | truncate: 150 }}</p>
</article>
  {% endfor %}
{% else %}
<p style="color:#888;">目前尚無公開觀測紀錄，首波資料整理中。</p>
{% endif %}

---

### 🔎 微觀｜近期紀錄

{% assign micro = site.categories.micro %}
<ul>
{% if micro.size > 0 %}
  {% for post in micro limit:3 %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small style="color:#999;">({{ post.date | date: "%m/%d" }})</small></li>
  {% endfor %}
{% else %}
  <li style="color:#888; list-style:none;">Coming soon</li>
{% endif %}
</ul>

### 🔭 宏觀｜近期紀錄

{% assign macro = site.categories.macro %}
<ul>
{% if macro.size > 0 %}
  {% for post in macro limit:3 %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small style="color:#999;">({{ post.date | date: "%m/%d" }})</small></li>
  {% endfor %}
{% else %}
  <li style="color:#888; list-style:none;">Coming soon</li>
{% endif %}
</ul>

### 🗣️ 鹽論｜近期出現

{% assign salt = site.categories.salt %}
<ul>
{% if salt.size > 0 %}
  {% for post in salt limit:3 %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small style="color:#999;">({{ post.date | date: "%m/%d" }})</small></li>
  {% endfor %}
{% else %}
  <li style="color:#888; list-style:none;">Coming soon</li>
{% endif %}
</ul>

---

## 相關平台

本站不定期於多個社群平台更新，內容以觀測紀錄為主，不進行商業合作或代言：
- <a href="https://www.facebook.com/yanhangwatch" target="_blank">Facebook</a>
- <a href="https://www.instagram.com/yanhangwatch" target="_blank">Instagram</a>
- <a href="https://www.threads.net/@yanhangwatch" target="_blank">Threads</a>
- <a href="https://www.youtube.com/@yanhangwatch" target="_blank">YouTube</a>

---

> 本站內容整理自公開資料與實地觀察，部分圖像與資料出處為政府公開資訊，經整理重製使用，僅供資訊紀錄與研究參考，不構成投資、購屋或任何形式之建議，亦不代表任何機關立場。實際情況請以政府機關公告與正式文件為準。
