---
title: Lai, Jing Yi
permalink: /people/jingyi
description: "Lai, Jing Yi - Serious Title"
id: jingyi
name: Lai, Jing Yi
joinDate: 1970-01-01
function: eng
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: Being part of a family means smiling for photos.
linkedinId: jingyi

---

{%- assign staff = site.data.people | find: "id", "jingyi" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}