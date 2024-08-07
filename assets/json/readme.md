# Generated JSON Data

I can generate json data using liquid at build time using front matter on top of a json file:

```json
---
layout: none
---

{
    "posts": [ {%for post in site.posts%}
        "{{post.title}}"{% unless forloop.last %},{% endunless -%}
    {%endfor%}
    ]
}
```