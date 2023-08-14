---
title: Tan, Wei Seng
permalink: /people/weiseng2
description: "Tan, Wei Seng - Serious Title"
id: weiseng2
name: Tan, Wei Seng
joinDate: 22/02/2021
function: eng
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: The only rock I know that stays steady, the only institution I know that
  works, is the family.
linkedinId: weiseng2

---

{%- assign staff = site.data.people | find: "id", "weiseng2" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}