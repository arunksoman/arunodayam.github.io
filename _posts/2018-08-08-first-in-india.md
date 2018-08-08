---
layout: post
title: ഇന്ത്യയിൽ ആദ്യം
date: 2018-08-08 10:07:39 -0700
category: Vedic_Mathematics
img: /static/IMG/maths2.jpeg
color: deep-purple
theme_color: "#673ab7"
tags: 
- India
- In first
---

<ul>
{% for i in site.data.first_indian_digital %}
<ol>{{ forloop.index }}. {{ i.ques }}</ol><br />
{{ i.ans }}
{% endfor %}
</ul>
