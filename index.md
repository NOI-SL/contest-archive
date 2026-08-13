---
layout: default
title: null
---

# NOI Sri Lanka — Contest Archive

Archive of contests held by the National Olympiad in Informatics Sri Lanka.

<p class="stats"><strong>{{ site.data.stats.contests }}</strong> contests · <strong>{{ site.problems | size }}</strong> problems</p>

{%- assign years = site.problems | group_by: "year" | sort: "name" | reverse -%}
{%- for yg in years -%}
{%- assign items = yg.items | sort: "sortkey" %}
<h2 id="y{{ yg.name }}">{{ yg.name }}</h2>
{%- assign lastround = "" -%}
{%- for p in items -%}
{%- if p.round != lastround %}
{%- unless forloop.first %}
</ul>
{%- endunless %}
<h3>{{ p.round }}</h3>
<ul>
{%- assign lastround = p.round -%}
{%- endif %}
<li><a href="{{ p.url | relative_url }}">{{ p.title }}</a></li>
{%- if forloop.last %}
</ul>
{%- endif -%}
{%- endfor -%}
{%- endfor %}
