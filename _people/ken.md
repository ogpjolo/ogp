---
title: Lee, Ken
permalink: /people/ken
description: "Lee, Ken - Serious Title"
id: ken
name: Lee, Ken
joinDate: 27/02/2023
function: eng
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: Family and friendships are two of the greatest facilitators of happiness.
linkedinId: ken

---

{%- assign staff = site.data.people | find: "id", "ken" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}