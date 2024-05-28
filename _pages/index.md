---
layout: page
title: Home
id: home
permalink: /
---

# Welcome! 🌱

## Erwachen Purpose
[[Game Purpose]]
[[Game Roots]]
[[Erwachen Ages]]

## Character Creation
[[Character Creation Process]]
[[Playbooks]]
[[Races]]

## Moves and Dice
[[A guide to rolling]]
[[Moves]]
[[Effect]]
[[Position]]
## Combat
[[Combat]]
[[Formidability]]
## Equipment
[[Equipment Points]]
[[Equipment acquisition]]
## The Spark
[[The Spark]]
[[Move-components]]
[[Magic-effects]]
## The GM
[[Phases]]
[[Calm Phase]]
[[Quest Phase]]
[[Survival Phase]]
[[OpFormidability]]
[[Setting Position and Effect]]

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  Take a look at <span style="font-weight: bold">[[Your first note]]</span> to get started on your exploration.
</p>

This digital garden template is free, open-source, and [available on GitHub here](https://github.com/maximevaillancourt/digital-garden-jekyll-template).

The easiest way to get started is to read this [step-by-step guide explaining how to set this up from scratch](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll).

<strong>Recently updated notes</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 5 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ site.baseurl }}{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
