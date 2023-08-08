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

# new header

{% for tournament in site.tournaments %}
- [**{{ tournament.title }}**]({{ tournament.url | relative_url }}) - {{ tournament.section }} - {{ tournament.game }}
{% endfor %}


[Link to Game {{ page.game }}](/{{ page.section }}/game_{{ page.game }}.md)

## 2021 Electronic Knights Championship Semi-Final Section: 21ENs04

- Start Date: 3/1/23
- End Date: 9/1/25

| Game | Link |
|------|------|
{% for game_number in (1..2) %}
| Game {{ game_number }} | [Link to Game {{ game_number }}]({{ '/tournaments/game_' | append: game_number | relative_url }}) |
{% endfor %}




