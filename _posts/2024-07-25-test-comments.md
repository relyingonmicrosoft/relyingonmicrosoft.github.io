---
layout: post
title: "Troubleshooting Comments"
date: 2024-07-26
comments: true
---

This is a test post to troubleshoot automatic comment inclusion.

{% raw %}
{% if page.comments != false %}
  Comments should appear below this line.
  {% include utterances_comments.html %}
{% endif %}
{% endraw %}
