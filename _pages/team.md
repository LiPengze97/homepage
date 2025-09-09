---
layout: single
title: "Our Team"
permalink: /team/
classes: wide
author_profile: false   # ← 这一行关闭作者栏
sidebar: false          # ← 可选，彻底禁掉 sidebar 容器
---

<!-- Inline styles to beautify the cards (works out-of-the-box).
     If you prefer, move this block into /assets/css/custom.css -->
<style>
.team-grid{
  display:grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 1.25rem;
  margin: 1rem 0 2rem;
}
.team-card{
  background: var(--mm-surface, #fff);
  border: 1px solid rgba(0,0,0,.06);
  border-radius: 14px;
  padding: 1rem;
  text-align: center;
  box-shadow: 0 4px 16px rgba(0,0,0,.05);
  transition: transform .18s ease, box-shadow .18s ease;
}
.team-card:hover{
  transform: translateY(-2px);
  box-shadow: 0 10px 24px rgba(0,0,0,.08);
}
.team-card img{
  width: 120px;
  height: 120px;
  object-fit: cover;
  border-radius: 50%;
  border: 3px solid rgba(0,0,0,.06);
  background: #f7f7f7;
}
.team-card h4{
  margin: .6rem 0 .25rem;
  font-weight: 700;
}
.team-card p{
  margin: .2rem 0;
}
.section-title{
  margin-top: 1.75rem;
  margin-bottom: .75rem;
  border-left: 4px solid var(--mm-accent, #2a7ae2);
  padding-left: .5rem;
}
</style>

{% assign desired_order = "Principal Investigator|Faculty Member|Program Coordinator|Member|Alumni" | split: "|" %}
{% assign grouped = site.data.team | group_by: "group" %}

{% for name in desired_order %}
  {% assign bucket = grouped | where: "name", name | first %}
  {% if bucket and bucket.items.size > 0 %}
  <h2 class="section-title">{{ name }}</h2>
  <div class="team-grid">
    {% for person in bucket.items %}
    <div class="team-card">
      <img src="{{ person.image }}" alt="{{ person.name }}">
      <h4>{{ person.name }}</h4>
      <p><em>{{ person.role }}</em></p>
      {% if person.description %}<p>{{ person.description }}</p>{% endif %}
    </div>
    {% endfor %}
  </div>
  {% endif %}
{% endfor %}

*If you’re part of the team and would like your info updated, please contact the li.pengze@mayo.edu.*
