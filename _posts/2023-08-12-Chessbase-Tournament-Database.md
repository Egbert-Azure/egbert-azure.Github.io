---
layout: post
title: Creating a ChessBase Tournament Database for Correspondence Chess
categories: [chess, correspondence chess, ChessBase, game management]
excerpt: Learn how to efficiently create and manage a ChessBase tournament database for correspondence chess, track your games, and generate a comprehensive crosstable.
tags: [ChessBase, correspondence chess, game tracking, crosstable, USCF, tutorial]
date: 2023-08-12 00:00:00 -0700
---
Upcoming Friday will be no blog, so it is today, Saturday and happy Chess Week to you all.

So, whats up today? I recently boldly decided to participate in the 2023 Electronic Knights Championship. With pairings happening swiftly, I realized it was the ideal moment to share my practical approach to effortlessly creating a crosstable using a ChessBase tournament database. I guide you through effectively managing your correspondence chess games and generating a comprehensive crosstable.

Correspondence chess demands strategic depth and meticulous planning. Without an official USCF game archive, players often take the responsibility of documenting their games.

**Creating the Crosstable**

While this doesn't sound like a big deal, this is - again - one of ChessBase's hidden and poorly documented features.
Before you pull out your hair, here is the short "How to" version: For a practical example, let's create my upcoming tournament database with crosstable.
In this tournament, you play one game with each opponent for six games, 3 with White and 3 with Black. As indicated, you must send your first move as White to your opponents.

- Player #1 sends first move to players 2, 4, 6
- Player #2 sends first move to players 3, 5, 7
- Player #3 sends first move to players 1, 4, 6
- Player #4 sends first move to players 2, 5, 7
- Player #5 sends first move to players 1, 3, 6
- Player #6 sends first move to players 2, 4, 7
- Player #7 sends first move to players 1, 3, 5

> **Note:** For privacy reasons, I have removed the email aliases

| # | Name              | US Chess ID# | Rating | 1 | 2 | 3 | 4 | 5 | 6 | 7 | Total |
|---|-------------------|--------------|--------|---|---|---|---|---|---|---|-------|
| 1 | Marc Siegel       | 11041680     | 2098   |   |   |   |   |   |   |   |       |
| 2 | Egbert Schroeer   | 30088451     | 2008   |   |   |   |   |   |   |   |       |
| 3 | John O'Brien      | 12455289     | 1973   |   |   |   |   |   |   |   |       |
| 4 | Patrick A. Walsh  | 12617017     | 1962   |   |   |   |   |   |   |   |       |
| 5 | Tom Castle        | 12810546     | 1399   |   |   |   |   |   |   |   |       |
| 6 | Joshua Miller     | 31219806     | UNR    |   |   |   |   |   |   |   |       |
| 7 | Eric Moskow       | 31368678     | UNR    |   |   |   |   |   |   |   |       |


To get started, follow these quick steps:

1. Create a new database in ChessBase.
2. Open the database and click on "File."
3. Select "Tournament Template."
4. Enter the number of players and their names.

<p align="center">
<img src="../jpg/Screenshot 2023-08-11 173513-1.jpg" alt="Crosstable" width="400">
</p>

<ol start="5">
<li>Provide the tournament details, such as "USCF 23EN11 - 2023 Electronic Knights."</li>

<li>Don't forget to check the box at *Corr. Chess*</li>
</ol>

And - eh voila - with hitting the **Crosstable** icon and

![Crosstable](<../jpg/Screenshot 2023-08-11 203010.jpg>)

Here we have our database and this nice crosstable in ChessBase:

<p align="center">
<img src="../jpg/Screenshot 2023-08-11 202542.jpg" alt="Crosstable" width="400">
</p>

Now one of the great features is that if you have the player database installed, all players in **Metadatabase** get automatically assigned. Those in ChessBase own **Correspondence** database, unfortunately not.

And another excellent function with one click, you get the table to the clipboard in ASCII format. Like this, with one click.

## USCF 23EN11 - 2023 Electronic Knights 2023

|   | Name              | Rating | 1 | 2 | 3 | 4 | 5 | 6 | 7 | Total |
|---|-------------------|--------|---|---|---|---|---|---|---|-------|
| 1 | Siegel, Marc      | 2098   | * |   |   |   |   |   |   | 0.0/0 |
| 2 | Schroeer, Egbert  | 2008   |   | * |   |   |   |   |   | 0.0/0 |
| 3 | O'Brien, John     | 1973   |   |   | * |   |   |   |   | 0.0/0 |
| 4 | Walsh, Patrick A. | 1962   |   |   |   | * |   |   |   | 0.0/0 |
| 5 | Castle, Tom       | 1399   |   |   |   |   | * |   |   | 0.0/0 |
| 6 | Moscow, Eric      | xxxx   |   |   |   |   |   | * |   | 0.0/0 |
| 7 | Miller, Joshua    | xxxx   |   |   |   |   |   |   | * | 0.0/0 |

And with the players identified you can check them and prepare yourself to play against your oponents.
> **Note:** I have updated the [Road to ELO 200](https://egbert-azure.github.io/the-road-to-elo-2000/) blog with some more details and guidance. Check it out

> **Note:** [Subscribe to receive updates](https://follow.it/senior-chess-improver?leanpub)



