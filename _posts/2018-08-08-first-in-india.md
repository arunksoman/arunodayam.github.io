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
rtyv the following
{% for i in site.data.first_indian_digital %}
<div class="w3-panel w3-pale-blue w3-leftbar w3-border-blue">
{{ forloop.index }}. {{ i.ques }}
</div>
{{ i.ans }}
{% endfor %}
