---
layout: page
title: Weekly Puzzles and Game of the Week
permalink: "/Puzzle/"
tags: [weekly-puzzles, chess, game-of-the-week]
categories: [puzzles, chess]
comments: false
---


<div style="text-align: left;">
<img src="../assets/images/art/weekly.jpeg" alt="image" width="25%">
</div>

{% assign puzzle_years = "" | split: "" %}

{% for puzzle in site.puzzles %}
  {% assign year = puzzle.date | date: "%Y" %}
  {% unless puzzle_years contains year %}
    {% assign puzzle_years = puzzle_years | push: year %}
  {% endunless %}
{% endfor %}

{% for year in puzzle_years %}
   **{{ year }}**
  
  {% assign puzzles_for_year = site.puzzles | where: 'date', year %}
  {% assign sorted_puzzles_for_year = puzzles_for_year | sort: 'title' %}
  
  {% for puzzle in sorted_puzzles_for_year %}
  - **{{ puzzle.title }}** -  {{ puzzle.description }} - [Link]({{ puzzle.url | relative_url }})
  {% endfor %}
{% endfor %}

{% assign sorted_tournaments = site.tournaments | sort: 'title' | sort: 'section' %}

