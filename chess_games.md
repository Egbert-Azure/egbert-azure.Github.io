---
layout: page
title: Chess Games Replay
permalink: "/Games_Replay/"
date: 2023-08-06
---
## here list of games

wip

{% for tournament in site.tournaments %}
- [**{{ tournament.title }}**]({{ tournament.url | relative_url }})
{% endfor %}

## 2021 Electronic Knights Championship Semi-Final Section: 21ENs03

- Start Date: 3/1/23
- End Date: 9/1/25

| Game | Link |
|------|------|
{% for game_number in (1..2) %}
| Game {{ game_number }} | [Link to Game {{ game_number }}]({{ '/tournaments/' | relative_url }}{{ game_number }}/game_{{ game_number }}.md) |
{% endfor %}

## 2021 Electronic Knights Championship Semi-Final Section: 21ENs03
## slugify function

- Start Date: 3/1/23
- End Date: 9/1/25

| Game | Link |
|------|------|
{% for game_number in (1..2) %}
| Game {{ game_number }} | [Link to Game {{ game_number }}]({{ '/tournaments/' | relative_url }}{{ tournament.title | slugify }}/{{ game_number }}/game_{{ game_number }}.md) |
{% endfor %}



