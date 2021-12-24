---
title: Home
layout: base.njk
---

# hello world



## Success Criteria

<ul>
{%- for sc in collections.sc -%}
  <li><a href="{{ sc.url }}">{{ sc.data.title }}</a></li>
{%- endfor -%}
</ul>
