---
title: Ravisankar
subtitle: Jack of many stacks, master of some. Forever debugging life’s edge cases.
layout: layouts/base.njk
---


## Notes

Random access thoughts

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>





