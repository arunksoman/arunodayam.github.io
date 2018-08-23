---
layout: post
title: "കേരളം ക്വിസ്: ഭാഗം 1"
date: 2018-08-12 16:15:39 -0700
category: Keralam
img: /static/IMG/Kerala.jpg
color: deep-purple
theme_color: "#673ab7"
tags: 
- India
- In first
---

{% for i in site.data.Keralam-part1 %}
<div class="w3-panel w3-pale-blue w3-leftbar w3-border-blue">
<p>{{ forloop.index }}. {{ i.ques }}</p>
</div>
<button onclick="myFunction('Demo{{ forloop.index }}')" class="w3-button w3-block w3-left-align w3-green">
ഉത്തരം</button>

<div id="Demo{{ forloop.index }}" class="w3-hide w3-container">
  <p>{{ i.ans }}</p>
</div>
{% endfor %}
