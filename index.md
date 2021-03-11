---
layout: default
lesson-example: "https://carpentries.github.io/lesson-example/"
title: "Learning how to build websites with Jekyll"
---

## Description
{{ site.description }}

{%  assign lead = site.team_members | where:"role", "project lead" | first %}
The project is led by {{ lead.name }}.

[See our full team](about)

If you want to know more, you can check [the about page](about.md).

See some [examples of our work]({{ page.lesson-example }}).
