---
title: Samdarshi, Amit
permalink: /people/amit
description: "Samdarshi, Amit - Serious Title"
id: amit
name: Samdarshi, Amit
joinDate: 1970-01-01
function: pm
jobTitle: Serious Title
curProducts: currentProducts
pastProducts: pastProducts
accomplishments: ""
quote: A happy family is but an earlier heaven.
linkedinId: amit

---

{%- assign staff = site.data.people | find: "id", "amit" -%}
{% include staff_heading.html staff=staff color=site.colors.function-colors.pm %}

<p>I joined since {{page.joinDate}} and I am currently working on {{page.curProducts}}.</p>

<p>Products I worked on before include {{page.pastProducts}}</p>

<p>Three things I've done recently which I'm proud of are...</p>
{{page.accomplishments}}