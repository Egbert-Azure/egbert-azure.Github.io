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

## Tournament List

{% for tournament in site.tournaments %}
### {{ tournament.title }}
{% for game in tournament.games %}
- [**{{ game.name }}**]({{ game.url | relative_url }})
{% endfor %}
{% endfor %}

or this

## 2021 Electronic Knights Championship Semi-Final Section: 21ENs01

- Start Date: 3/1/23
- End Date: 9/1/25

| Game | Link |
|------|------|
{% for game_number in (1..2) %}
| Game {{ game_number }} | [Link to Game {{ game_number }}](/games/game_{{ game_number }}) |
{% endfor %}

