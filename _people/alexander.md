---
title: Lee, Alexander
permalink: /people/alexander
description: "Lee, Alexander - Serious Title"
id: alexander
name: Lee, Alexander
joinDate: 15/06/2020
function: eng
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: Family is family.
linkedinId: alexander

---

{%- assign staff = site.data.people | find: "id", "alexander" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.eng %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}