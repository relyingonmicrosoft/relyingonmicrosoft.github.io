---
layout: post
title: "Test Comments"
date: 2024-07-25
comments: true
---

This is a test post to troubleshoot automatic comment inclusion.

{% if page.comments != false %}
Comments should appear below this line.
{% include utterances_comments.html %}
{% endif %}
