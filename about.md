---
layout: page
title: About
---

## Project 
Here's some details about what this is about:

{{ site.description }}

We want to show links between pages, so you can check out [index.md](index.md) from here!

## Funders
Some info


## Team

{% for team_member in site.team_members %}
 - **Name:** {{ team_member.name }}, **role:** {{ team_member.role }}
{% endfor %}


## Cite us
Some info
