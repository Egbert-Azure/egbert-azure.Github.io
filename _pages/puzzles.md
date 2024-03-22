---
layout: page
title: Puzzles
permalink: /puzzles/
image: '/images/puzzle.jpg'
tags: [weekly-puzzles, game-of-the-week]
---
<div style="text-align: left; font-size: smaller;">
Photo by <a href="https://unsplash.com/@edge2edgemedia?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Edge2Edge Media</a> on <a href="https://unsplash.com/photos/black-puzzle-piece-on-white-paper-x21KgBfOd_4?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
</div>  

{% assign puzzle_years = "" | split: "" %}

{% for puzzle in site.puzzles %}
  {% assign year = puzzle.date | date: "%Y" %}
  {% unless puzzle_years contains year %}
    {% assign puzzle_years = puzzle_years | push: year %}
  {% endunless %}
{% endfor %}

{% assign sorted_years = puzzle_years | sort: 'year' | reverse %}

{% for year in sorted_years %}
   **{{ year }}**
  
  {% assign puzzles_for_year = site.puzzles | where: 'date', year %}
  {% assign sorted_puzzles_for_year = puzzles_for_year | sort: 'date' | reverse %}
  
  {% for puzzle in sorted_puzzles_for_year %}
  - **{{ puzzle.title }}** -  {{ puzzle.description }} - [Link]({{ puzzle.url | relative_url }})
  {% endfor %}
{% endfor %}