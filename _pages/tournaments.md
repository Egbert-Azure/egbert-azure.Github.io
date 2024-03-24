---
layout: page
title: Tournaments
permalink: "/tournaments/"
date: 2023-08-06
image: '/images/tournament.jpg'
tags: [chess, USCF, ICCF, tournament]
---
<div style="text-align: left; font-size: smaller;">
Photo by <a href="https://unsplash.com/@eugenechystiakov?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Eugene Chystiakov</a> on <a href="https://unsplash.com/photos/chess-pieces-on-chess-board-sRRhKMeCeXY?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>
</div>

<br>
  
Welcome to my world of competitive chess! In this section, you will find updates and results from various chess tournaments I have participated in. 

The tournament page has a collection of annotated games from **Electronic Knights 2021** tournament. I also participate in **Electronic Knights 2023 Championship** and the **Electronic Knights 2024 Championship**.

In USCF tournaments, you play one game with each opponent for six games, 3 with White and 3 with Black.

# US Correspondence Chess:

## Electronic Knights

### 2021 Electronic Knights Finals 
[Crosstable 21ENf01](https://www.iccf.com/event?id=104617)

Electronic Knights moved to ICCF Server, but played under USCF rules and rankings.

### 2021 Electronic Knights Championship Semi-Final Section: 21ENs03

- Start Date: 3/1/23
- End Date: 9/1/25
- Prelim Score: 5.5

**Section result: 5 wins, 1 loss**

### 2021 Electronic Knights Championship Semi-Final Section: 21ENs04

- Start Date: 3/1/23
- End Date: 9/1/25
- Prelim Score: 4.5
  
**Section result so far: 1 win, 3 draws, 1 loss, 1 running**

### 2021 Electronic Knights Championship - Preliminary Round: 21EN15 
- Egbert Schroeer rating: 1933
- Start Date: x/x/xx
- End Date: 9/1/25

**Section result:**

### 2021 Electronic Knights Championship - Preliminary Round: 21EN09 
- Egbert Schroeer rating: unrated
- Start Date: x/x/xx
- End Date: 9/1/25

**Section result:**

## Annotated Games for Replay by year and section

{% assign sorted_tournaments = site.tournaments | sort: 'title' | sort: 'section' %}
{% assign current_section = "" %}

{% if sorted_tournaments.size > 0 %}
## Section: {{ sorted_tournaments[0].section }}
{% endif %}

{% for tournament in sorted_tournaments %}
{% if current_section != tournament.section %}
{% assign current_section = tournament.section %}
{% if current_section != "" and tournament != sorted_tournaments[0] %}
## Section: {{ current_section }}
{% endif %}
{% endif %}

- **{{ tournament.title }}** - Section: {{ tournament.section }} - Opponent: {{ tournament.name }} - [Link]({{ tournament.url | relative_url }})

{% endfor %}



## 2021 Victor Palciauskas ICCF Tournament

[Crosstable](https://www.iccf.com/event?id=93278)

**Result: 6 wins, 0 loss**

## ICCF tournament & friendly matches

| Name                                               | Start Date | Status   | Link |
|----------------------------------------------------|------------|----------|------|
| Champions League 2024 C2 Board 4                   | 2/25/2024 | Running  | [Link](https://www.iccf.com/event?id=102157) |
| Veterans World Cup 13 Semi-Final 9                 | 6/15/2023 | Running  | [Link](https://www.iccf.com/event?id=105050) |
| Netherlands - USA Friendly Match 2023 Board 28     | 11/21/2023 | Running  | [Link](https://www.iccf.com/event?id=104112) |
| VWC14, ICCF Veterans World Cup 14 pr. 25           | 9/1/2023   | Running  | [Link](https://www.iccf.com/event?id=102886) |
| VWC14, ICCF Veterans World Cup 14 pr. 56           | 9/1/2023   | Running  | [Link](https://www.iccf.com/event?id=102917) |
| ICCF Veterans World Cup 13 Semi-Final 9            | 6/15/2023  | Running  | [Link](https://www.iccf.com/event?id=102157) |
| Switzerland - USA 2023 Board 20                    | 4/14/2023  | Running  | [Link](https://www.iccf.com/event?id=101708) |
| Hungary - USA Friendly Match 2022 Board 18         | 12/26/2022 | Finished | [Link](https://www.iccf.com/event?id=100532) |
| Germany - USA Friendly Match 2022 Board 83         | 10/12/2022 | Finished | [Link](https://www.iccf.com/event?id=99816) |
| WS/CCE/A/30                                       | 9/29/2022  | Finished  | [Link](https://www.iccf.com/event?id=99566) |
| Finland - USA Friendly Match 2022 Board 18         | 7/26/2022  | Finished | [Link](https://www.iccf.com/event?id=98691) |
| Peace Open "Amici sumus" Group 28                  | 5/1/2022   | Finished | [Link](https://www.iccf.com/event?id=97909) |
| Peace Open "Amici sumus" Group 29                  | 5/1/2022   | Finished  | [Link](https://www.iccf.com/event?id=97910) |
| WZ Individual Championship Preliminaries Group 36  | 1/5/2022   | Finished | [Link](https://www.iccf.com/event?id=96436) |
| WZ Individual Championship Preliminaries Group 34  | 11/30/2021 | Finished | [Link](https://www.iccf.com/event?id=96017) |
| WZ Individual Championship Preliminaries Group 35  | 11/30/2021 | Finished | [Link](https://www.iccf.com/event?id=96146) |
| CUB - USA 2 Board 74                              | 11/29/2021 | Finished | [Link](https://www.iccf.com/event?id=95989) |
| Champions League 2021 C9 Board 2                  | 11/1/2021  | Finished | [Link](https://www.iccf.com/event?id=95550) |
| WZ Individual Championship Preliminaries Group 32  | 9/30/2021  | Finished | [Link](https://www.iccf.com/event?id=95086) |
| ICCF Veterans World Cup 13 pr 58                  | 9/1/2021   | Finished | [Link](https://www.iccf.com/event?id=94823) |
| Peru - USA friendly match 2021 Board 38            | 6/4/2021   | Finished | [Link](https://www.iccf.com/event?id=93232) |

