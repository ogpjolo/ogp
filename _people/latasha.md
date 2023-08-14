---
title: Lenus, Latasha
permalink: /people/latasha
description: "Lenus, Latasha - Serious Title"
id: latasha
name: Lenus, Latasha
joinDate: 1970-01-01
function: eng
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: My family is my life, and everything else comes second as far as what’s
  important to me.
linkedinId: latasha

---

{%- assign staff = site.data.people | find: "id", "latasha" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}