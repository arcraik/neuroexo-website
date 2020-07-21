---
layout: page
title: Research Blog
---       
{%- if site.posts.size > 0 -%}
    <ul class="post-list">
      {%- for post in site.posts -%}
    <hr>
      <li style="overflow: auto;">
        {%- if post.author -%}
          {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
          <span class="post-meta">{{ post.date | date: date_format }} • {{ post.author | escape }}</span>
        {%- else -%}
          {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
          <span class="post-meta">{{ post.date | date: date_format }}</span>
        {%- endif -%}


        <h3>
        {%- if post.link -%}
          <a class="post-link" href="{{ post.link }}">
            {{ post.title | escape }}
          </a>          
        {%- else -%}
          {{ post.title | escape }}
        {%- endif -%}
        </h3>

        {%- if site.show_excerpts -%}
          {{ post.excerpt }}
        {%- endif -%}
      </li>
      {%- endfor -%}
    </ul>
{%- endif -%}
