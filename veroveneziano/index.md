---
layout: page
title: "#veroVeneziano"
image: /assets/img/seo/masstourists-opg-facebook.png
---

{%- if site.posts.size > 0 -%}
  <ul class="post-list">
    {%- for post in site.posts -%}
    <li>
      <a class="post-link" href="{{ post.url | relative_url }}">
        <img src="{{ post.image }}" alt="post thumbnail">
      </a>
      {%- if site.show_excerpts -%}
        {{ post.excerpt }}
      {%- endif -%}
    </li>
    {%- endfor -%}
  </ul>


{%- endif -%}
