---
title: Soh, Yi Zhi Zeke
permalink: /people/zeke
description: "Soh, Yi Zhi Zeke - Serious Title"
id: zeke
name: Soh, Yi Zhi Zeke
joinDate: 1970-01-01
function: eng
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: This is my family. I found it all on my own. It’s little, and broken, but
  still good. Yeah. Still good.
linkedinId: zeke

---

{%- assign staff = site.data.people | find: "id", "zeke" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}