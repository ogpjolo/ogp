---
title: Sng, Kenneth
permalink: /people/kenneth
description: "Sng, Kenneth - Serious Title"
id: kenneth
name: Sng, Kenneth
joinDate: 1970-01-01
function: pm
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: I didn’t give you the gift of life, but life gave me the gift of you.
linkedinId: kenneth

---

{%- assign staff = site.data.people | find: "id", "kenneth" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.pm %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}