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

## List of Games

{% for tournament in site.tournaments %}
### {{ tournament.title }}

- Start Date: {{ tournament.start_date }}
- End Date: {{ tournament.end_date }}

| Game | Link |
|------|------|
{% for game_number in (1..2) %}
| Game {{ game_number }} | [Link to Game {{ game_number }}]({{ tournament.url | relative_url }}game_{{ game_number }}.md) |
{% endfor %}
{% endfor %}



