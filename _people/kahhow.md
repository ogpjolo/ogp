---
title: Lee, Kahhow
permalink: /people/kahhow
description: "Lee, Kahhow - Serious Title"
id: kahhow
name: Lee, Kahhow
joinDate: 1970-01-01
function: ops
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: It’s all about the quality of life and finding a happy balance between
  work and friends and family.
linkedinId: kahhow

---

{%- assign staff = site.data.people | find: "id", "kahhow" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.ops %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}