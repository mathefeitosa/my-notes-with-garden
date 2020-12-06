---
layout: post
title: Todas as notas
permalink: /lista/
content-type: eg
---

<style>
.category-content a {
    text-decoration: none;
    color: #4183c4;
}

.category-content a:hover {
    text-decoration: underline;
    color: #4183c4;
}
</style>

<main>
		{%- for note in site.notes -%}
                <li id="category-content" style="padding-bottom: 0.6em; list-style: none;"><a href="{{note.url}}">{{ note.title }}</a></li>
    	{%- endfor -%}
    <br/>
    <br/>
</main>
