---
title: Liang, Yuanruo
permalink: /people/yuanruo
description: "Liang, Yuanruo - Serious Title"
id: yuanruo
name: Liang, Yuanruo
joinDate: 2019-01-07
function: eng
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: There is no doubt that it is around the family and the home that all the
  greatest virtues… are created, strengthened and maintained.
linkedinId: yuanruo

---

{%- assign staff = site.data.people | find: "id", "yuanruo" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}