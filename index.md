---
layout: default
---

<ul>
    {% for post in paginator.posts %}
      <li>
          <h2><a href="{{ post.url | prepend: site.baseurl | replace: '//', '/' }}">{{ post.title }}</a></h2>
          <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date_to_string }}</time>
          <p>{{ post.content | strip_html | truncatewords:50 }}</p>
      </li>
    {% endfor %}
</ul>
© 2021 GitHub, Inc.
# Quick Links

Google drive link for AAPS and ML : 
[AAPS and ML](https://tinyurl.com/4da4enw9)

Onedrive link for AAPS and ML : 
[AAPS and ML](https://tinyurl.com/d2h3jyyc)


