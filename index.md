---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<nav style="display:none;">
  <ul>
    <li>Wedding</li>
  </ul>
</nav>

{% for moment in site.data.moments %}
  {% include relationship_moment.html moment=moment %}
{% endfor %}