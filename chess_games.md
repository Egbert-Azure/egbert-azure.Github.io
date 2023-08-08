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
