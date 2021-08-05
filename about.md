---
title: About
---

This is a static web template for GitHub Page.

* GitHub Account Public Information (cbkadal):<br>
  [https://api.github.com/users/cbkadal/events/public](https://api.github.com/users/cbkadal/events/public)
* {% for ii in site.navbarlinks %}{% if ii.navbar == "GitHub" %}<a
  href="{{ ii.link | relative_url }}">{{ ii.navbar }}</a>{% endif %}{% endfor %}
* {% for ii in site.navbarlinks %}{% if ii.navbar == "GitHub Page" %}<a
  href="{{ ii.link | relative_url }}">{{ ii.navbar }}</a>{% endif %}{% endfor %}

