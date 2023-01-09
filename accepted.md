---
title: Accepted Papers
layout: default
weight: 5
---

<h1>{{ site.data.conference.short_name }} {{ site.data.conference.year }} Accepted Papers</h1>

{%- if site.data.accepted_papers -%}
<ul>
	{%- for paper in site.data.accepted_papers -%}
	<li> <b>{{paper.PaperTitle}}</b> <br>{{paper.AuthorNames | remove: "*"}}</li>
	<br>
	{%- endfor -%}
</ul>
{%- endif -%}
