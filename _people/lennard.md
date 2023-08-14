---
title: Lim, Fa Ping Lennard
permalink: /people/lennard
description: "Lim, Fa Ping Lennard - Serious Title"
id: lennard
name: Lim, Fa Ping Lennard
joinDate: 1970-01-01
function: pm
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: Family is not defined by our genes, it is built and maintained through love.
linkedinId: lennard

---

{%- assign staff = site.data.people | find: "id", "lennard" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.pm %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}