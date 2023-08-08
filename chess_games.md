---
layout: page
title: Chess Games Replay
permalink: "/tournaments/"
date: 2023-08-06
---
## here list of games

{% for tournament in site.tournaments %}
- [**{{ tournament.title }}**]({{ tournament.url | relative_url }})
{% endfor %}
