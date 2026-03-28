---
layout: page
title: By Year
permalink: /years/
---

# Lessons by Year (1977-2025)

Every lesson from every shareholder letter, in chronological order. Each page contains 10-25 lessons with context, insight, and application.

| Year | Key Topics |
|------|-----------|
{% for year in (1977..2025) %}| [{{ year }}]({{ site.baseurl }}/lessons/lessons-{{ year }}) | |
{% endfor %}
