---
layout: page
title: By Year
description: "Browse all 1,091 lessons from Warren Buffett's 49 Berkshire Hathaway shareholder letters (1977-2025) in chronological order. Each year contains 10-25 business and investing lessons."
permalink: /years/
---

# Lessons by Year (1977-2025)

Every lesson from every shareholder letter, in chronological order. Each page contains 10-25 lessons with context, insight, and application.

| Year | Key Topics |
|------|-----------|
{% for year in (1977..2025) %}| [{{ year }}]({{ site.baseurl }}/lessons/lessons-{{ year }}) | |
{% endfor %}
