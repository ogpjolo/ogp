---
title: Tan, Geraldine
permalink: /people/geraldine
description: "Tan, Geraldine - Serious Title"
id: geraldine
name: Tan, Geraldine
joinDate: 1970-01-01
function: ops
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: Family gives you the roots to stand tall and strong.
linkedinId: geraldine

---

{%- assign staff = site.data.people | find: "id", "geraldine" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.ops %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}