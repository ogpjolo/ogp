---
title: Lau, Kar Rui
permalink: /people/karrui
description: "Lau, Kar Rui - Serious Title"
id: karrui
name: Lau, Kar Rui
joinDate: 2020-03-02
function: eng
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: Family is not an important thing. It’s everything.
linkedinId: karrui

---

{%- assign staff = site.data.people | find: "id", "karrui" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}